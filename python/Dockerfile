FROM python:3.9

# Create app directory
WORKDIR /app

# Copy application files
COPY requirements.txt ./

# Install dependencies
RUN pip install --no-cache-dir -r requirements.txt

# Copy the application code
COPY . .

# Expose port
EXPOSE 5000

# Start the Flask application
CMD ["flask", "run", "--host=0.0.0.0", "--port=5000"]

