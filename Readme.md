# API Test Automation with INGenious Playwright Studio

[![API Test Automation with INGenious Playwright Studio](https://github.com/testsmith-io/api-test-automation-ingenious-playwright-studio/actions/workflows/pipeline.yaml/badge.svg)](https://github.com/testsmith-io/api-test-automation-ingenious-playwright-studio/actions/workflows/pipeline.yaml)

This repository contains example scripts for API test automation using:
- **INGenious Playwright Studio**

## Features
- Examples of GET, POST, and Protected API requests.
- Clear demonstration of test automation practices with assertions and chaining requests.
- Fully automated CI pipeline using GitHub Actions.

## Test API
All examples in this repository are designed to work with the **Practice Software Testing API**, a publicly available API for learning and practicing software testing. You can explore the API documentation and endpoints here:  
👉 **[Practice Software Testing API](https://api.practicesoftwaretesting.com/api/documentation)** 👈

## Examples Included
1. **GET Request**: Fetch a list of brands with `GET /brands`.
2. **Login API**: Authenticate using `POST /login` with an email/password payload.
3. **Protected API Request**: Authenticate, then use a token to fetch data with `GET /invoices`.

## Prerequisites
- **INGenious Playwright Studio**

## Setup and Run
1. Clone this repository:
   ```bash
   git clone https://github.com/testsmith-io/api-test-automation-ingenious-playwright-studio.git
   ```
2. Navigate to the project directory:
   ```bash
   cd api-test-automation-ingenious-playwright-studio
   ```
3. Open INGenious Playwright Studio and run the tests:

## Automated Workflow
The repository includes a GitHub Actions workflow to automatically execute the tests.  