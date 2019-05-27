FROM continuumio/miniconda3:latest

RUN mkdir /code

WORKDIR /code

COPY ./conda_environment.yml /code/conda_environment.yml

RUN conda env create -f /code/conda_environment.yml && \
    conda clean --all --yes
