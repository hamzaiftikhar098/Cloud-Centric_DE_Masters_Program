# PySpark Jupyter Lab Notebook - Python v3.7.10

Jupyter Lab Notebook with root access.
Cloud-Centric_big_DE_Masters_Program notebooks provided to start with.

### To build image from the Dockerfile:
    docker build --tag Cloud-Centric_big_DE_Masters_Program/pyspark-jupyter-lab-old .

### To create container from image
    docker run -d -p 8888:8888 -p 4040:4040 --name jupyter-lab Cloud-Centric_big_DE_Masters_Program/pyspark-jupyter-lab-old
