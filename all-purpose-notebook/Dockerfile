FROM jupyter/pyspark-notebook:58169ec3cfd3

USER root

RUN apt-get update\ 
    && apt-get install -y\
        snap\
        postgresql-client

RUN conda install -c conda-forge gdal 

RUN snap install docker

USER jovyan