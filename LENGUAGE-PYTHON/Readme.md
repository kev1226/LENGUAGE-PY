# 1. Clone the repository.

# Navigate to the LANGUAGE-PYTHON directory in the terminal

# 2. Build the Docker image by running the following command:

docker build -t python-docker .

# 3. Run the container:

docker run -p 8083:8083 python-docker

# Note: The application will be accessible at http://localhost:8083

