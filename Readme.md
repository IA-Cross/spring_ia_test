# Spring IA Test

## Description
Spring IA Test is an intelligent assistant built with Spring Boot that can answer questions.

## Features
- **Spring Boot**: Robust backend framework.
- **RAG (Retrieval-Augmented Generation)**: Enhances answer accuracy by combining retrieval and generation.
- **pgvector**: Vector database extension for efficient similarity searches.
- **PDF Processing**: Extracts relevant content from the Java 21 specification.
- **REST API**: Provides endpoints for interacting with the assistant.

## Requirements
- Java 21+
- Maven 3+
- PostgreSQL with pgvector extension
- Docker (optional, for deployment)

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/IA-Cross/spring_ia_test.git
   cd spring_ia_test

2. Build the project
   ```sh
   mvn clean install
3. Run the application:
   ```sh
   mvn spring-boot:run

##Usage
- Send questions about Java 21 to the REST API.
Configure PostgreSQL with pgvector for optimized retrieval.
Upload Java 21 specification PDFs for improved answer quality.

