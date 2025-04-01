# Testing Repository

This repository contains a simple Python application with a Dockerfile for containerization.

## Contents

- `Dockerfile`: Defines the container image for the application
- `main.py`: The main Python script (not visible in the current directory listing)
- `requirements.txt`: Lists the Python dependencies (not visible in the current directory listing)

## Dockerfile

The Dockerfile uses Python 3.9 slim image as the base. It copies the application files into the container, installs the required dependencies, and sets the command to run the main.py script.

## Usage

To build and run the Docker container:

1. Build the image:
   ```
   docker build -t testing-app .
   ```

2. Run the container:
   ```
   docker run testing-app
   ```

Note: Make sure you have Docker installed on your system before running these commands.