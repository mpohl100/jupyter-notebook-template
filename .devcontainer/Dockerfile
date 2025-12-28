FROM mcr.microsoft.com/devcontainers/python:3.11-bullseye

# Copy requirements.txt to the workspace
COPY ../requirements.txt /workspace/requirements.txt

# Install Jupyter Notebook and requirements
RUN pip install --upgrade pip && \
    pip install notebook && \
    pip install -r /workspace/requirements.txt

# [Optional] Install additional Python packages here
# RUN pip install pandas matplotlib