
https://github.com/Rahul4112002/Fake-New-Detection/assets/124488758/92732c3e-9e67-4258-9e59-0388b05fa45f

# Mini Project on Machine Learning: Fake News Detection
This repository contains the code and resources for a mini project with the aim of predicting whether a news headline is fake or genuine. The project utilizes the Passive Aggressive Classifier and is implemented as a web application using Python Flask, HTML, CSS, and other technologies.
# Project Overview

#Purpose
The primary goal of this project is to identify potentially fake news headlines by utilizing machine learning techniques. Fake news can have significant social and political consequences, and an automated system can help users discern the credibility of headlines.
# Technologies Used
    - Python for machine learning model development
    - Flask for building the web application
    - HTML and CSS for the frontend
    - Passive Aggressive Classifier for text classification
    -Jupyter Notebook for data analysis and model development

# Data
The dataset used for this project contains news headlines, each labeled as either fake or genuine. This dataset is used to train the Passive Aggressive Classifier model.
Getting Started

To run the project locally, follow these steps:
    
    1. Clone this repository to your local machine.
        git clone https://github.com/your-username/fake-news-headline-detection.git

    2. Navigate to the project directory.
        cd fake-news-headline-detection

    3. Create a virtual environment and activate it (optional but recommended).
        python -m venv venv

        source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'

    4. Install the project dependencies.
        pip install -r requirements.txt

    5. Run the Flask application.
        python app.py

    6. Open a web browser and access the web application at http://localhost:5000.

# Project Structure
The project directory is organized as follows:
├── application.py               # Flask web application code

├── static/              # Static assets (CSS, images, etc.)

├── templates/           # HTML templates

├── data/                # Dataset used for model training

├── models/              # Trained machine learning models

├── notebooks/           # Jupyter notebooks for data analysis and model development

├── requirements.txt     # Project dependencies

├── README.md            # Project documentation

# Model Training
The machine learning model used for fake news headline detection is trained using the provided dataset. You can explore the model development process and analysis in the Jupyter notebooks located in the notebooks/ directory.

# Contributions
Contributions to this project are welcome. If you want to make improvements, fix issues, or add new features, please create a pull request.


