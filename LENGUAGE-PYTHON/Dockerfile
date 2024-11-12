# Use a Python base image
FROM python:3.10-slim

# Set the working directory
WORKDIR /app

# Copy the dependencies file
COPY requirements.txt .

# Install the dependencies
RUN pip install -r requirements.txt

# Copy the rest of the code into the container
COPY . .

# Expose the port on which the application will run
EXPOSE 8083

# Command to run the application
CMD ["python", "app.py"]