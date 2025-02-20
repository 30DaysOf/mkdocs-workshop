# Select base Docker image
FROM mcr.microsoft.com/devcontainers/python:3.12-bullseye

# Ugrade pip before installing dependencies
RUN python -m pip install --upgrade pip 

# Copy requirements.txt then use it to install dependencies
COPY requirements.txt .
RUN pip install -r requirements.txt
