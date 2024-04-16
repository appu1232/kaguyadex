FROM python:3.9-bullseye

RUN python3 -m pip install --upgrade pip

# Creates the directory for us
WORKDIR /guya
COPY ./requirements.txt .
RUN pip install -r requirements.txt
