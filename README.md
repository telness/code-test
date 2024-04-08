## Phone number search

## Overview

This test assesses your ability to develop a full-stack web application. Your task is to create a web page, similar to a feature on Telness, focused on listing and searching for phone numbers. This challenge involves both frontend and backend development, including database interactions.

## Task Description

### Frontend

Develop a web page that enables users to:

- **Search for Phone Numbers:** Implement filtering to allow searches for phone numbers using a specific prefix, suffix, or any substring.
- **Support Multiple Formats:** Recognize phone numbers entered both as MSISDN (e.g., +46712) and as a regular mobile number (e.g., 0712).
- **Filter by Attributes:** Provide filtering options for phone numbers by grade, type (CELL or FIXED), and reservation status.
- **Display Information:** Present all relevant information for each phone number in a table.

### Backend

- **API Development:** Create a backend service that provides phone number data through a REST or GraphQL API. While Golang is the preferred language for this backend service, you may opt for another language if you are not comfortable with Golang.
- **Database Interaction:** The backend should query phone number data from a database. Design and implement the database schema based on the provided `numbers.csv` file structure.

## Data

The `numbers.csv` file in the repository contains the data for this project, with fields including `msisdn`, `grade`, `type`, `reserved_at`, and `expires_at`.

## Submission Guidelines

- **Code Submission:** Use `git bundle` to submit your code and send the bundled file via email.
- **README.md:** Your submission must include a README.md documenting:
    - Installation and startup instructions for the project.
    - Any areas of the project that are incomplete or could be improved, with proposed plans for enhancement.
- **Time Management:** Aim to spend between 4 to 8 hours on this task, not exceeding the maximum time limit.
- **Technology Freedom:** You are free to choose any technology and framework for both the frontend and backend parts of the project.

## Additional Information

- The purpose of this test is to assess your technical skills comprehensively, including your ability to integrate frontend and backend technologies as well as perform database interactions. The work you submit will not be used in any Telness products.
- Emphasize functionality, clarity, and user experience in your web page design, while also ensuring the backend is efficiently implemented and securely interacts with the database.
