# Use official Python image
FROM python:3.9-slim

# Set working directory
WORKDIR /app

# Copy requirements file
COPY requirement.txt .

# Install dependencies
RUN pip install -r requirement.txt

# Copy application code
COPY app.py .

# Expose port
EXPOSE 5000

# Run command
CMD ["python", "app.py"]

