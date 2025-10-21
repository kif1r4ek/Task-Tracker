FROM photon:3.14-slim AS builder

WORKDIR task-tracker/backend

COPY ./requirements.txt ./requirements.txt

RUN pip install --no-cache-dir --upgrade -r