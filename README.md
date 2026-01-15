# Postman API Automation – Library Management System

## Overview
This project demonstrates automated API testing using Postman for a Library Management system.
The collection validates core CRUD operations with robust assertions, schema validation, 
data-driven testing, and request chaining.

## APIs Covered
- Add Book
- Get Book
- Delete Book

## Key Features
- REST API testing with Postman
- JavaScript-based assertions
- Schema validation (JSON Schema)
- Environment, collection, and global variables
- Data-driven testing using CSV
- Error handling using try/catch
- Request chaining and cleanup logic
- Response time and header validation

## Assertions & Validations
- Status code validation
- Response body schema checks
- Business logic validation (book added → retrievable → deletable)
- Error handling using try/catch blocks

## Test Execution
Tests are executed using Postman Collection Runner with CSV-driven inputs.

## How to Run
1. Import the collection from `collections/`
2. Import the CSV file from `data/`
3. Set `base_url` and environment variables
4. Run the collection manually or using Newman

## Tools & Technologies
- Postman
- JavaScript
- REST APIs
- Newman (CLI-ready)
- CSV for test data

## Project Structure
- `collections/` – Postman collection with API tests
- `data/` – CSV file for data-driven testing
- `docs/` – Test scenarios and documentation
- `screenshots/` – Test execution evidence

## Learning Outcomes
- Practical understanding of REST API contracts
- Writing maintainable API assertions using JavaScript
- Designing reusable, data-driven API tests
- Structuring API test projects for collaboration

