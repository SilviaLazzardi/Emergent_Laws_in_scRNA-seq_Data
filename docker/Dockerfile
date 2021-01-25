FROM jupyter/datascience-notebook

COPY requirements.jl /home/jovyan
RUN julia /home/jovyan/requirements.jl

COPY requirements.txt /home/jovyan

RUN pip install --user --no-cache-dir -r /home/jovyan/requirements.txt

WORKDIR /home/jovjan/work


ENTRYPOINT jupyter lab
