# Customer Churn Predictor

An end to end machine learning web service built to predict subscriber churn trends using behavioral variables.

### Key Features
* Implements a Random Forest Classifier trained with Scikit Learn metrics
* Standardizes feature scales automatically via standard scaler pipeline mapping
* Exposes a fast REST API endpoint built using FastAPI architectures
* Interactive customer parameters estimation dashboard web UI

### Tech Stack
* Python
* FastAPI
* Scikit Learn
* Pandas
* HTML5 / JavaScript / CSS

### Environment Setup

1. Check out the project code files locally.
2. Setup dependencies using the requirements layout configuration.
   `pip install -r backend/requirements.txt`

### Running the Project

1. Open your workspace terminal interface and change into the backend folder.
2. Initialize the learning phase configuration to produce structural models.
   `python train.py`
3. Execute the core deployment scripts to initialize server instances.
   `python app.py`
4. Access client forms using browser utilities by executing `frontend/index.html`.
