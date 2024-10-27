## AI_Quest'24 || Askify
## Query Predictor with Vector Database 

### Overview
This project applies machine learning to anticipate Jira queries by using solution data stored in a DVector database. The model is designed to improve issue tracking and management by offering intelligent query recommendations based on past data.

### Features
- **Predictive Modeling**: Employs sophisticated algorithms to forecast queries.
- **Vector Database Integration**: Efficiently pulls and leverages solution data stored in DVector for precise predictions.
- **Automated Query Suggestions**: Boosts productivity by automating the process of query suggestions.
- **Scalable and Adaptable**: Integrates seamlessly with Jira environments and scales to accommodate extensive datasets.
  
### Tech Stack
- **Python**: Primary language for model development and deployment.
- **TensorFlow/PyTorch**: Frameworks used for building and training the ML models.
- **BERT Embeddings**: Converts text data into high-quality vector representations.
- **Vector Database-FAISS**: Manages and retrieves solution vectors efficiently.
- **Flask/FastAPI**: To provide a web API for model predictions.
- **Django**: Used as a web application framework for robust performance.

### Getting Started
1. **Clone the Repository**:
    ```bash
    git clone https://github.com/yourusername/AI_Quest'24.git
    cd jiraModelCreation
    ```
2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```
3. **Configure Database**:
    - Ensure your DVector database is set up and accessible.
    - Update the database configuration in `config.py`.

4. **Run the Model**:
    ```bash
    python model.py
    ```

### Running the Django Server
1. **Navigate to the Django Project Directory**:
    ```bash
    cd django_project
    ```
2. **Run Migrations**:
    ```bash
    python manage.py migrate
    ```
3. **Start the Server**:
    ```bash
    python manage.py runserver
    ```
4. **Access the Application**:
    Open your web browser and go to `http://127.0.0.1:8000` to access the application.

### Colab Notebook
To make it easier to get started, we have provided a Google Colab notebook where you can run the model and see it in action without needing to set up a local environment. [Click here to open the Colab notebook](https://colab.research.google.com/drive/1DU9cZpYkXN9AzJJXt5pxI9VIxbv3Rdke?usp=sharing).
