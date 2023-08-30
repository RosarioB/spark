# pyspark
In this branch we will use some Jupyter Notebooks to exercise with PySpark.

There are three folders:
1. ***docker***: contains the docker compose file. It will create a container with PySpark and Jupyter.
2. ***Notebooks***: contains the notebooks with the exercise. The notebook `examples.ipynb` contains a series of examples with various operations that can be performed on Spark. The notebook `exercises.ipynb` is the one with the exercises and contains already the solutions.
3. ***CSV***: contains the csv files necessary to create the dataframes that we will use in the exercises.

## How to get started with the exercises

1. Run in a terminal `docker-compose  -f docker/spark-docker-compose.yml up -d` to start the jupyter-spark container
2. To access the Jupyter server get the container logs and you should find a link like this `http://127.0.0.1:8888/lab?token=7c68ab2b6a9408da47b8601fb0dcafca7a5a57e5d957c8a7` which can be pasted into the browser.
2. Upload on Jupyter the notebook `exercises.ipynb` and the csv files in the root folder (`/`) and start the exercises.