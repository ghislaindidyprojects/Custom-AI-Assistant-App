# Custom-AI-Assistant-App
Streamlit RAG-GenAI App

Overview

This project is a Streamlit-based application designed to integrate Retrieval-Augmented Generation (RAG) and Generative AI capabilities using AWS services. The application demonstrates the use of AI-powered text generation and retrieval systems for building a responsive and interactive web interface.

Features

Retrieval-Augmented Generation (RAG): Combines information retrieval with generative AI models.

Streamlit Integration: Utilizes Streamlit for building a user-friendly web interface.

AWS Services: Includes AWS Bedrock and other relevant AWS services for model hosting and inference.

Dynamic Widgets: Interactive components like st.text_area, st.button, and others.

Prerequisites

To run this project, ensure you have the following:

Tools

Python 3.7+

Pip (Python package manager)

Libraries

Install the required libraries:

pip install streamlit boto3

AWS Credentials

Set up AWS credentials for accessing AWS services:

Use the AWS Management Console to create an IAM user with appropriate permissions.

Configure your local machine:

aws configure

Setup Instructions

Clone this repository:

git clone https://github.com/<your-repo-name>.git

Navigate to the project directory:

cd RAG-GenAI-App/Streamlit_App

Install dependencies:

pip install -r requirements.txt

Before running the app, open app.py and replace the knowledge base ID (kb_id) in line 10 with your own Knowledge Base ID.

Run the Streamlit app:

streamlit run app.py

Open the app in your browser:

Local URL: http://localhost:8501

Network URL: Accessible on your local network.

Key Files

app.py: Main application file that runs the Streamlit app.

requirements.txt: List of Python dependencies.

Common Issues

"Streamlit is not recognized"

Ensure Streamlit is installed:

pip install streamlit

Add Python and pip to your system's PATH.

"Invalid height for st.text_area"

Ensure the height parameter is set to at least 68 pixels.
