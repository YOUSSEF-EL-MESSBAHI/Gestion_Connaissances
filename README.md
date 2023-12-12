# Employee Training Management Application

## Overview

This application is developed with Spring Boot 3 for the backend and Angular 14 for the frontend. It provides a platform for managing employee training, registration, feedback, and resignation requests.

## Features

### User Registration

New employees can register manually or through a CSV uploaded by the HR department, and they will receive login credentials via email.

### Authentication

Employees can authenticate to access training and feedback features.

### Training Courses

Employees can explore and enroll in available courses, conveniently categorized by department.

### Feedback

Employees have the ability to provide feedback with ratings for completed training courses and access feedback submitted by their peers.

### Former Employees

Even after leaving the company, former employees can:

- Propose new training courses, automatically notifying current employees via email.
- Share evaluations and feedback.
- View feedback provided by other employees.
- Initiate resignation requests.

### Resignation Requests

The HR department can:

- Evaluate resignation requests using a dashboard.
- Accept or reject requests based on knowledge gaps.
- Prompt employees to enroll in additional courses if needed.

## Installation

### Backend (Spring Boot)

1. Clone the repository.
2. Navigate to the `backend` directory.
3. Run the Spring Boot application.

```bash
./mvnw spring-boot:run
