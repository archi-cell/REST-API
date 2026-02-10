# BFHL Qualifier API – Chitkara University

This project implements the required REST APIs for Qualifier 1.

## Public APIs

### GET /health
Returns service health status.

### POST /bfhl
Accepts exactly one of the following keys:
- fibonacci
- prime
- lcm
- hcf
- AI

All responses follow the mandatory structure defined in the problem statement.

## Tech Stack
- Node.js
- Express

## Deployment
Deployed on Render with public access.

