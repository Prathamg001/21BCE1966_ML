# 21BCE1966_ML

Document Retrieval Backend

This repository contains the implementation of a document retrieval system designed to generate context for Large Language Models (LLMs) in chat applications.

Features

Document Retrieval System: Efficient backend that allows retrieval of documents stored in a database.
Cached Responses: Caches responses for faster retrieval and optimal system performance.
Background Task: Scrapes news articles in a separate thread on server startup.
Dockerized Application: The backend is containerized using Docker.
Rate Limiting: Limits users to 5 requests before throwing an HTTP 429 error.
API Logging: Logs API requests, including inference time for each request.
Endpoints

/health: Checks if the API is active.
/search: Returns the top search results based on query parameters like text, top_k, and threshold.
Getting Started

Prerequisites
Docker
Python 3.x or Go
