FROM nvcr.io/nvidia/pytorch:22.10-py3

ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

COPY requirements.txt .
RUN pip install -r requirements.txt

WORKDIR /app