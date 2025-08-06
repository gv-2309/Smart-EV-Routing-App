# Smart EV Routing App

**Team-Mind_Mesh**  
Developers: Amrutha D, Vishnu V  
Institution: REVA University, Bangalore

## Live Demo
https://smart-ev-routing-app.streamlit.app/

## GitHub Repository
https://github.com/gv-2309/Smart-EV-Routing-App

---

## Problem Statement

[Fleet Operations] Problem-2.1: EV Routing with Multi-Service Delivery Model

---

## Features

- Upload custom test cases or use built-in ones
- Visualize vehicle routes on an interactive map
- Optimize deliveries using Google OR-Tools
- Smart Discharge Mode for grid-aware energy return
- Real-time display of energy usage, earnings, and driver scores

---



---

## Requirements

Install the required libraries:

```bash
pip install -r requirements.txt
How to Run the App Locally on VS Code
Clone the Repository

bash
Copy
Edit
git clone https://github.com/your-username/ev-routing-app.git
cd ev-routing-app
Create a Virtual Environment (recommended)

bash
Copy
Edit
python -m venv venv
# Activate it:
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Ensure Folder Structure

Place your CSV test cases inside a folder named Test_Case_CSV_Files in the project directory.

## Example:

Copy
Edit


Smart-EV-routing-app/
├── streamlit_app.py
├── requirements.txt
├── Test_Case_CSV_Files/
│   ├── Bangalore_testcase.csv
│   ├── Kolkata_testcase.csv
│   ├── Delhi_testcase.csv
│   ├── Mumbai_testcase.csv
│   ├── Hyderabad_testcase.csv
│   └── Chennai_testcase.csv


Run the Streamlit App

bash
Copy
Edit
streamlit run streamlit_app.py
Open in Browser

Visit: http://localhost:8501

## Sample Input Format
CSV file must contain the following columns:

ID

Latitude

Longitude

Demand

NodeType (Depot, Customer, DischargeStation)

Location





## Demo Video:
https://tinyurl.com/hackotsav-2k25




## Contact
For queries or collaboration, reach out at:
gvs.vishnuv@email.com | amruthadandigimath@gmail.com
