FROM python:3.8

WORKDIR /app
COPY . /app
RUN pip install -r requirements.txt

# Expose port 8000 for communication within the Docker network
EXPOSE 8000

# Start the Django application with the runserver command
CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]
