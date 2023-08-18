# Use the official Python base image
FROM python:3.8-slim

# Set the working directory in the container
WORKDIR /app

# Copy the requirements file into the container
COPY requirements.txt requirements.txt

# Install the Python dependencies
RUN pip install -r requirements.txt

# Copy the entire app into the container
COPY . .

# Expose the port your application runs on
EXPOSE 8000

# Define the command to run your application
CMD ["python", "app.py"]