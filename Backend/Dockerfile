FROM python:3.11-bullseye

# Set environment variables
ENV PYTHONUNBUFFERED 1
WORKDIR /ghosted
COPY requirements.txt /ghosted/
RUN pip install --upgrade pip && pip install --no-cache-dir -r requirements.txt
COPY . /ghosted/