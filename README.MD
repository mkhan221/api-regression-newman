# API Regression Testing Project
[![API Regression Tests (Newman)](https://github.com/mkhan221/api-regression-newman/actions/workflows/api-regression.yml/badge.svg)](https://github.com/mkhan221/api-regression-newman/actions/workflows/api-regression.yml)

## Overview
This project demonstrates automated API regression testing using Postman, Newman, and GitHub Actions CI.

## Features
- CRUD API validation
- Happy path, negative, and boundary testing
- Contract-style response validation
- Automated execution via Newman CLI
- CI integration with GitHub Actions
- HTML report generation

## Tools & Stack
- Postman
- Newman
- Node.js
- GitHub Actions

## How to Run Locally

```bash
newman run postman/API_Regression_Posts.json \
  -e postman/API_Regression_Env.json \
  --reporters cli,htmlextra
