# Kafka Mail Service

This project is a Kafka-based mail service that facilitates asynchronous email sending. It utilizes Spring Boot and JavaMail to handle email requests efficiently while managing concurrency and status tracking.

## Features

- **Asynchronous Email Sending**: Sends emails in the background using Kafka for decoupled processing.
- **Email Status Tracking**: Keeps track of email statuses (PENDING, SENDING, SENT, FAILED) for reliable delivery.
- **Concurrency Management**: Utilizes an ExecutorService and Semaphore to control concurrent email sending tasks.
- **Error Handling**: Implements robust error handling to manage failures during email sending.
- **Flexible Configuration**: Easily configurable email provider settings.

## Technologies Used

- **Java**: Primary programming language for the service.
- **Spring Boot**: Framework for building the RESTful service.
- **Kafka**: Message broker for handling email requests asynchronously.
- **JavaMail**: Library for sending emails.
- **Lombok**: For reducing boilerplate code with annotations.

## Getting Started

### Prerequisites

- JDK 11 or later
- Maven
- Kafka broker

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/kafka-mailservice.git
