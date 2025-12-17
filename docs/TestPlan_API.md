# API Regression Test Plan

## Objective
To validate backend API behavior using automated regression testing, ensuring core functionality, error handling, and data contracts remain stable across changes.

## API Under Test
Public REST API: https://jsonplaceholder.typicode.com

## Test Scope
- CRUD operations for Posts resource
- Happy path scenarios
- Negative testing for invalid inputs
- Boundary testing for edge cases
- Data integrity and contract validation

## Test Types Covered
- Functional API testing
- Regression testing
- Negative testing
- Boundary testing
- Contract-style validation

## Tools Used
- Postman (collection design and test scripting)
- Newman (CLI execution)
- GitHub Actions (CI automation)

## Environment Configuration
- baseUrl configured via Postman environment
- Stateless API behavior handled using fixed test data

## Risks and Assumptions
- API is stateless and does not persist data
- Some invalid inputs return non-standard HTTP status codes
- Identified inconsistencies are documented as known issues
