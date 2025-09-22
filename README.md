### API Evershop Project
This repository contains API testing work for the Evershop platform. It includes Postman collections, environments, test cases, and supporting documents for validating different API endpoints.

📌 Project Overview

The goal of this project is to test the APIs of the Evershop platform to ensure:

Endpoints are working as expected

Response codes and payloads are correct

Edge cases and error handling are validated

Performance and reliability are maintained

📂 Repository Structure
├── Evershop API Test.postman_collection.json   # Postman collection with API requests
├── EvershopDemo.postman_environment.json       # Postman environment variables
├── Evershop Website.xlsx                       # Test cases and documentation
├── Project Week Assignment-01.docx             # Assignment documentation
├── Screen Shot/                                # Screenshots & recordings

🚀 How to Run

## Clone the repository:

git clone https://github.com/prothoma-bd/api-evershop.git


1. Open Postman and import the following:

2. Evershop API Test.postman_collection.json

3. EvershopDemo.postman_environment.json

4. Run the collection manually or via Newman:

newman run "Evershop API Test.postman_collection.json" -e "EvershopDemo.postman_environment.json"

🛠 Tools & Technologies

Postman – for API test execution

Newman – for CLI test runs

JMeter (optional) – for performance testing

Git & GitHub – for version control

✅ Test Coverage

Authentication & Authorization

Product APIs

Cart & Checkout APIs

Error handling scenarios

📷 Screenshots & Reports

All screenshots, screen recordings, and reports are stored in the Screen Shot/ directory.

👩‍💻 Author

Sabina Sultana

📧 Email: sabina.prothoma@gmail.com

🔗 LinkedIn
