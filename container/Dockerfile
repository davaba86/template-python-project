FROM python:3.9.16-slim-buster

COPY container/requirements.txt /tmp/requirements.txt

RUN python3 -m pip install --upgrade pip && \
  pip3 install -r /tmp/requirements.txt

WORKDIR /source/
