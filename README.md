# student-api
A FastAPI application that serves student data from a CSV file with optional class-based filtering.

## Live API

https://student-api-o54s.onrender.com/api

## Features

- Returns all student records
- Filter students by class using query parameters
- Supports multiple class filters
- CORS enabled for all origins

## Example Usage

### Get all students

https://student-api-o54s.onrender.com/api

### Filter by one class

https://student-api-o54s.onrender.com/api?class=1A

### Filter by multiple classes

https://student-api-o54s.onrender.com/api?class=1A&class=1B

## Tech Stack

- FastAPI
- Uvicorn
- Python
- Render

## Deployment

Hosted publicly on Render.
