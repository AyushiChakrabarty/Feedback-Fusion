########################################################################
-------------------------------------------------------------------------
Installation/Navigation Guide
-------------------------------------------------------------------------
########################################################################

-------------------------------------------------------------------------
**Prerequisites**
Before you begin, ensure you have the following installed:

Python 3.7 or higher
pip (Python package installer)
-------------------------------------------------------------------------
**Setup**
Clone the Repository

Clone the repository to your local machine:
git clone https://github.com/your-username/your-repository.git
cd your-repository

-------------------------------------------------------------------------
**Create a Virtual Environment (Optional but recommended)**
It’s a good practice to use a virtual environment to manage dependencies. Create and activate a virtual environment:

# Create a virtual environment
python -m venv env

# Activate the virtual environment
# On Windows
.\env\Scripts\activate

# On Linux/Mac
source env/bin/activate

-------------------------------------------------------------------------
**Install Dependencies**

Install the required Python packages using the requirements.txt file:
pip install -r requirements.txt

-------------------------------------------------------------------------
**Set Up Environment Variables**

Create/Edit a .env file in the root directory of your project and add your environment variables:

GROQ_API_KEY=your_groq_api_key
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
Ensure you replace the placeholder values with your actual API key and email credentials.

-------------------------------------------------------------------------
**Run the Streamlit App**

Start the Streamlit app by running:

streamlit run app.py

You can now view your Streamlit app in your browser.

  Local URL: http://localhost:8501
  Network URL: http://10.20.159.10:8501


This command will start a local server and open the Streamlit app in your default web browser.

-------------------------------------------------------------------------

Using the App

Upload a CSV File: Use the file uploader to select and upload a CSV file containing survey responses.
Categorize Responses: Click the "Categorize Responses and Update CSV" button to process and categorize the responses. Download the updated CSV file if needed.
Generate Email Responses: Click the "Generate Email Responses and Update CSV" button to generate email content for each response and download the updated CSV file.
Send Emails: Click the "Send Emails" button to send the generated email responses to the provided email addresses.

-------------------------------------------------------------------------

Troubleshooting

Missing Environment Variables: Ensure you have set all necessary environment variables in the .env file.
Dependencies Issues: Verify that all dependencies are correctly installed and compatible with your Python version.