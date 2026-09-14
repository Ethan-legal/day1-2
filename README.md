# day1-2

1. create a virtual environment
>python -m venv .venv

2. activate my virtual environment
>source .venv/bin/activate

install streamlit
>pip install streamlit

4. Create a Python file that I can edit
Python files end with .py.
Manually create home.py in Explorer, or create it in the terminal:
touch home.py

5. Start the Streamlit web server using home.py as the entry point
streamlit run home.py

6. Edit home.py to create some web functionality
import streamlit as st
Use different st components to create functionality:
st.title("LAWS90286 - Day 1")
st.write("Hello World")