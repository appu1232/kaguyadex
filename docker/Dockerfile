FROM python:3

RUN apt-get update \
    && apt-get install -y --no-install-recommends \
    libpq-dev \
    && rm -rf /var/lib/apt/lists/*

# Creates the directory for us
WORKDIR /guya
COPY ./requirements.txt .
RUN pip install -r requirements.txt
