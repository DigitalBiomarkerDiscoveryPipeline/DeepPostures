FROM python:3.6.13
RUN apt-get update
RUN apt-get install -y vim
RUN apt-get install -y git

RUN pip install --upgrade pip
RUN pip install --upgrade setuptools

RUN pip install tensorflow==1.13.1
RUN pip install numpy
RUN pip install pandas
RUN pip install scipy
RUN pip install h5py

WORKDIR /

ARG CACHE_DATE=2021-07-07
RUN git clone https://github.com/ADALabUCSD/DeepPostures.git

USER root:root
