Steps to run project:

1. create virtualenv: `virtualenv -p python3 venv`
2. activate env: `source venv/bin/activate`
3. install dependencies: `pip install streamlit matplotlib mplfinance plotly`
4. install pynse: `cd pynse-master; pip install .`
4. run app: `python app.py`
5. run streamlit server: `streamlit run app.py`
