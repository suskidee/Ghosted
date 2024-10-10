FROM python:3.8

# Set environment variables
ENV PYTHONUNBUFFERED 1
WORKDIR /ghostedza
COPY requirements.txt /ghostedza/
RUN pip install --upgrade pip && pip install --no-cache-dir -r requirements.txt
COPY . /ghostedza/