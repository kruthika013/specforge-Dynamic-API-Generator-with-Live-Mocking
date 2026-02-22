SpecForge – Dynamic FastAPI Boilerplate & Live Mock API Generator

SpecForge is a dynamic API generation platform built with FastAPI that enables developers to instantly create, test, and download fully functional Python API boilerplates through a modern web interface. It is designed to simplify backend prototyping, API contract validation, and frontend integration testing without requiring complex setup or server restarts.
SpecForge allows users to input two application names, define custom data fields, and optionally enable API key authentication. Based on this input, the system automatically generates bi-directional REST endpoints (e.g., /app1toapp2 and /app2toapp1), embeds a dynamically generated API key, and produces a ready-to-run FastAPI application file for download.
One of the core highlights of SpecForge is its dynamic route injection mechanism. Using FastAPI’s app.add_api_route() method, new endpoints are mounted into the running application at runtime. This enables live API mocking without restarting the server — a powerful demonstration of FastAPI’s flexibility and dependency injection architecture.
In addition to file generation, SpecForge immediately activates the generated endpoints within the current server session, allowing developers to test their API using the provided X-API-Key header. This simulates real-world microservice authentication while keeping the system lightweight and beginner-friendly.

 Features
-> Dynamic FastAPI boilerplate generation
-> Runtime endpoint injection (no server restart required)
-> Automatic unique API key generation
-> Optional header-based authentication (X-API-Key)
-> Bi-directional endpoint creation
-> Customizable JSON response schema
-> Instant live endpoint testing
-> Downloadable production-ready Python API file
-> Modern dark-themed UI with multi-tab navigation

 Tech Stack
->FastAPI – High-performance Python web framework
->Uvicorn – ASGI server
->Python Standard Library – File handling & key generation
->HTML5, CSS3, JavaScript – Frontend interface
->Dependency Injection (FastAPI Depends) – Authentication handling

 How It Works
->User provides two application names and required data fields.
->A unique API key is generated dynamically.
->SpecForge creates a complete FastAPI boilerplate file with embedded authentication logic.
->The application injects new routes into the running server instance.
->Users can instantly test the live endpoint using the generated API key.
->The API file can be downloaded and deployed independently.

 Use Cases
->Rapid backend prototyping
->Frontend API mocking
->Hackathon & MVP development
->Learning FastAPI and REST principles
->Integration contract validation
->Teaching backend fundamentals

 Future Enhancements
->Role-based authentication (JWT/OAuth2)
->Database-backed dynamic schemas
->OpenAPI/Swagger spec export
->Dockerized deployment option
->Rate limiting & production security improvements
