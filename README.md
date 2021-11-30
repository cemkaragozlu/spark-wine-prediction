### Hello! Welcome to PySpark Wine Prediction module!  

#### Pull the latest docker image  
`docker pull cemkaragozlu/spark-wine-prediction`

#### Run prediction on your data
`docker run -v <path-to-test-data>:/opt/spark_wine_prediction/test.csv cemkaragozlu/spark-wine-prediction python main.py --test-path test.csv`
Test data must be a semicolon separated csv file with necessary columns.
You only need to give the path to your test data in the indicated space.