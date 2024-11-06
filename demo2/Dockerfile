# Use the latest version of the python image from Docker Hub
FROM python:latest

# Define the root directory within the container
WORKDIR /app

# Copy files from local directory into container directory
COPY flask_example.py /app

# Install necessary packages
RUN pip install flask

# Allow the host to "talk" to port 3000 within the container
EXPOSE 3000

# Run the application
CMD ["python", "./flask_example.py"]
