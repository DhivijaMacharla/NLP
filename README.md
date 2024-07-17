# NLP
Resume Screening App With Python and Machine Learning
Resume Screening App
A Streamlit-based web application for screening resumes. This app allows users to upload a resume, which is then cleaned and analyzed to predict the job category based on pre-trained models.

Features
Upload Resumes: Supports both .txt and .pdf file formats.
Text Cleaning: Removes URLs, hashtags, mentions, special characters, and extra spaces.
Prediction: Classifies the resume into predefined job categories using a machine learning model.
Category Mapping: Displays a human-readable job category based on the model's prediction.
Demo


![Screenshot 2024-07-17 185414](https://github.com/user-attachments/assets/3376cf79-6a0d-4f89-885a-12f2ff335f24)





![Screenshot 2024-07-17 185458](https://github.com/user-attachments/assets/4a8f0b18-38e9-4f1f-bcd2-5ed52177c735)






![Screenshot 2024-07-17 185519](https://github.com/user-attachments/assets/df4a0640-3831-4bf7-a724-38bf041d6e8b)

Getting Started
Prerequisites
To run this project, you need:

Python 3.7 or higher
A web browser for accessing the Streamlit app
Installation
Clone the Repository:

bash
Copy code
git clone https://github.com/yourusername/resume-screening-app.git
Navigate to the Project Directory:

bash
Copy code
cd resume-screening-app
Install Required Packages:
Make sure you have pip installed. Then run:

bash
Copy code
pip install -r requirements.txt
Create a requirements.txt file with the following contents:

Copy code
streamlit
scikit-learn
nltk
PyPDF2
Download Model Files:
Ensure that the model files (clf.pkl and tfidf.pkl) are located in the project directory.

Running the App
To start the Streamlit app, run:

bash
Copy code
streamlit run app.py
This command will launch the app in your default web browser.

Usage
Upload a Resume:

Click the "Upload Resume" button to select and upload a .txt or .pdf file.
View Prediction:

The app will display the predicted job category based on the content of the resume.
Project Structure
The project is organized as follows:

bash
Copy code
resume-screening-app/
│
├── app.py          # Main Streamlit application file
├── clf.pkl         # Pre-trained classifier model
├── tfidf.pkl       # Pre-trained TF-IDF vectorizer
├── requirements.txt# Project dependencies
├── README.md       # Project documentation
└── LICENSE         # License file (if applicable)
HTML and CSS
app.py: Contains the Streamlit app code. Handles file uploads, text cleaning, and prediction.
JavaScript
This project does not use JavaScript as it is built with Python and Streamlit.
Contributing
If you would like to contribute to this project, please:

Fork the Repository: Click the "Fork" button at the top right of this page.
Clone Your Fork:
bash
Copy code
git clone https://github.com/yourusername/resume-screening-app.git
Create a New Branch:
bash
Copy code
git checkout -b feature/your-feature
Make Your Changes.
Commit Your Changes:
bash
Copy code
git add .
git commit -m "Add a new feature"
Push to Your Fork:
bash
Copy code
git push origin feature/your-feature
Create a Pull Request: Go to the original repository and click "New Pull Request".
License
This project is open source and available under the MIT License. See the LICENSE file for more details.
