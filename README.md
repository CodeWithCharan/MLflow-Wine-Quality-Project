# MLflow-Wine-Quality-Project

## Video Presentation
https://github.com/CodeWithCharan/MLflow-Wine-Quality-Project/assets/106027109/2e05ac3c-b9e6-4b7f-81c9-aa9fa7d9c7ce

## DATASET
This dataset is taken from : http://archive.ics.uci.edu/ml/datasets/Wine+Quality<br/>

## Acknowledgements
`Thanks to MLflow for providing this tutorials and examples`

## Installation

1. Clone the repository:

   ```
   git clone https://github.com/CodeWithCharan/MLflow-Wine-Quality-Project.git
   ```

2. Create a `virtual environment` (optional): [Virtual Environment Set Up](https://github.com/CodeWithCharan/virtual-env-setup)

3. Install the required dependencies:

    ```
    pip install -r requirements.txt
    ```

4. Run `app.py`:
    ```
    python app.py
    ```
5. Go to `mlflow ui`:
    ```
    mlflow ui
    ```

7. mlflow ui will be running on `http://127.0.0.1:5000/`, so paste this URL

8. Now, try different experiments and compare them:
    ```
    python app.py 0.3 0.7
    ```

9. Create a remote server (optional): You have the option to integrate the project with any remote server, such as AWS, Azure, GCP, etc. In this project, I have used Dagshub as a remote server : https://dagshub.com/user/login