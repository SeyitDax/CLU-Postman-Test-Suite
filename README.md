# Postman CLU API Testing Suite

This project provides an end-to-end Postman testing suite to validate Azure CLU (Conversational Language Understanding) APIs.

## Features

- Dynamic CLU query testing via Postman
- Handles authentication, 401/404 errors
- Environment-driven key & endpoint usage
- Clean and secure setup for public sharing

## Setup Instructions

1. Clone this repo
2. Import the `CLU-Collection.postman_collection.json` into Postman
3. Import the `CLU-Test.postman_environment.json` and **add your values**:
   - `CLU_API_KEY`: your Azure key
   - `CLU_ENDPOINT`: your endpoint URL

## 📂 Files

- `CLU-Collection.postman_collection.json` – Core requests
- `CLU-Test.postman_environment.json` – Safe environment with variables

## 🔐 Security

API keys are not included. Never share keys in your version-controlled files. See `.gitignore`.

## License

MIT
