FROM python:3.14.3

RUN apt-get update && apt-get clean all

WORKDIR /maap-api-nasa
COPY . .
COPY api/settings.py api/settings.py
RUN pip3 install -r requirements.txt
