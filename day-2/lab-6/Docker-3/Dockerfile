# Use Python base image
FROM python:3.10-slim

# Set working directory
WORKDIR /app

# Copy files
COPY . .

# Install Flask
RUN pip install flask

# Set default environment variables (for production)
ENV APP_MODE=production
ENV APP_REGION=canada-west

# Expose port
EXPOSE 8080

# Run the app
CMD ["python", "app.py"]
