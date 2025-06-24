# Use the official Python image
FROM python:3.11-slim

# Set working directory
WORKDIR /app

# Copy app code
COPY . .

# Install Flask
RUN pip install --no-cache-dir Flask

# Expose the port the app runs on
EXPOSE 8002

# Run the application
CMD ["python", "app.py"]
