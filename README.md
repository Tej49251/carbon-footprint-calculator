you can run the code by following steps:

 python --version  (should be python 3.10)
 
 download python 3.10 :
               https://www.python.org/downloads/release/python-3100/

               ✅ Check the box at the bottom that says:
               "Add Python 3.x to PATH"

               Then click Install Now.

               Press Windows + S, search for "Environment Variables", and open:
               Edit the system environment variables
               → Click on Environment Variables button.
               In the System Variables section:

               Scroll and select Path
               Click Edit
               Click New, and add the following (adjust version if different):

               C:\Users\<YourUsername>\AppData\Local\Programs\Python\Python310\





cd Carbon-Footprint-Calculator-App

python -m venv venv

venv\Scripts\activate

python3 -m venv venv

source venv/bin/activate

pip install -r requirements.txt

streamlit run app.py


