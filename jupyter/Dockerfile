FROM jupyter/scipy-notebook
USER root
COPY requirements.txt .
RUN mkdir /collector /builder
COPY collector/ ./collector/
COPY builder/ ./builder/
RUN pip install -r requirements.txt