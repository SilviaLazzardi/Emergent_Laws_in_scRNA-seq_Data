FROM jupyter/datascience-notebook

COPY requirements.jl /home/jovyan
RUN julia /home/jovyan/requirements.jl

RUN pip install watermark

WORKDIR /home/jovjan/work


ENTRYPOINT jupyter lab
