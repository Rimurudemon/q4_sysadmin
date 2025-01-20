# Question 4 : Dockerizing a fullstack app (frontend+backend)

You are tasked with setting up a fullstack application consisting of a frontend and backend. The goal is to containerize the entire application using Docker to ensure seamless deployment and scalability.

As part of the hosting process, you are required to implement stringent security measures to protect the application and its database. Specifically, the database must not be accessible from outside the host environment under any circumstances. Additionally, even the host server itself should not have direct access to the database, ensuring it can only be accessed by the backend service.

## Your solution should include:

1. Steps for containerizing the frontend and backend applications.
2. Configuration of a secure network for communication between containers.
3. Hosting details, including any necessary changes to the Docker Compose setup or infrastructure to achieve the stated security goals.
4. Any best practices for securing the database and preventing unauthorized access.
5. Document the process thoroughly, ensuring that the solution is both functional and adheres to modern security standards for web applications.
