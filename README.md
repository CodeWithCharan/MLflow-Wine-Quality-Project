# MLflow-Wine-Quality-Project

## Video Presentation
https://github.com/CodeWithCharan/MLflow-Wine-Quality-Project/assets/106027109/35994f13-b9f9-4325-afdb-bd318cec4f0e

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