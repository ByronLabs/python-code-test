# python-code-test

## Exercise 

Simple Cybersecurity Incident Reporting API

## Description:

You are tasked with creating a simple backend system for a basic cybersecurity incident reporting API. This system will allow organizations to report cybersecurity incidents and view a list of reported incidents.

**Requirements:**

1. Incident Model:
- Create a model for representing a cybersecurity incident with the following attributes:
  - Incident ID (auto-generated)
  - Date and Time of Incident
  - Description
  - Severity Level (Low, Medium, High)
  - Reporter (Name and Contact Information)
  - Status (Open, In Progress, Closed)

**Endpoints:**

1. Report an Incident:

- Create an endpoint that allows organizations to report a new cybersecurity incident.
- Input: Incident details (Date and Time, Description, Severity Level, Reporter details)
- Output: Return the details of the reported incident with a unique Incident ID.

2. List All Incidents:

- Create an endpoint to retrieve a list of all reported cybersecurity incidents.
- Output: List of incidents with their details.

3. Security:

- Implement a simple form of authentication, such as API key-based authentication, to ensure that only authorized organizations can report incidents.
Documentation:

## Notes:

- Use FastAPI as the main library for building the API.
- You can use an in-memory data store for simplicity (e.g., a list or dictionary).
- Focus on simplicity and ease of understanding for interview purposes.
- Do not worry about advanced features or complex functionalities.

## Submission:

- Provide the source code for the FastAPI project.
- Include a brief README.md file explaining how to run and test the API.
- Share the GitHub repository link or a zip file with the submission.
