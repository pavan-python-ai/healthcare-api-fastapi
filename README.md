# healthcare-api-fastapi
Healthcare Patient Management API using FastAPI
# Healthcare Patient Management API

This project is a FastAPI-based backend system designed to manage patient data in a healthcare environment.

## Features
- Create, read, update patient records
- RESTful API endpoints
- Mock healthcare data (HIPAA-safe)
- Scalable architecture

## Tech Stack
- Python
- FastAPI
- SQLite / PostgreSQL
- Docker

## Run Locally
pip install -r requirements.txt
uvicorn main:app --reload

## API Endpoints
- GET /patients
- POST /patients
- GET /patients/{id}

## Future Enhancements
- FHIR integration
- Authentication & authorization
- Cloud deployment
