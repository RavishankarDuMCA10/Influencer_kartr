FROM python:3.11

# Set work directory
WORKDIR /workspace

# Install Python dependencies
COPY requirements.txt requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

# Install additional tools
RUN pip install flask
