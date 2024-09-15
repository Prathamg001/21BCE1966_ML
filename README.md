# 21BCE1966_ML

Get Documents Backend

The development of a document retrieval system for chat apps that provides context for Large Language Models (LLMs) is available in this repository.

Qualities

Document Retrieval System: Effective backend that makes it possible to retrieve documents kept in databases.
Responses that have been cached are faster to retrieve and improve system performance.
Background Task: Upon server starting, a separate thread is used to scrape news articles.
Dockerized Application: Docker is used to containerize the backend.
Rate Limiting: Provides a 5-request maximum before raising an HTTP 429 error for customers.
Requests made to APIs are logged, along with the time it takes to interpret each request.
Final Points

/health: Verifies the API's activation.
Based on query parameters like text, top_k, and threshold, /search returns the top search results.
Commencing

Conditions precedents
Python 3.x for Docker or
