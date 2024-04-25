# docker-challenge-template
Docker Project Report
This repository contains the Docker project work that includes four challenges.

Challenge 1: Simple web server for static web pages
In this challenge, the objective was to learn about the process of containerization and providing static content by deploying a static website with Docker and Nginx.

Learning Experience
Learned the basics of Dockerfile syntax and configuration.
Understood how Nginx serves static content and configured it with a Docker container.
Gained experience with Docker commands to build and run containers.
Findings
Docker simplifies the setup process for serving static websites.
Containerization ensures consistent environment across different machines.
Challenge 2: Creating a dynamic application
The objective of this challenge was to use Docker Compose to run a containerized Node.js application that exposed API endpoints for server interaction.

Learning Experience
Explored the setup of a Node.js application within a Docker environment.
Utilized docker compose to manage multi-container Docker application.
Enhanced understanding of linking services and port mapping.
Findings
Docker compose is an efficient tool for managing complex applications with multiple services.
Node.js application can be easily scaled and maintained using Docker.
Challenge 3: Full stack application
The objective was to create a full stack application that was Dockerized and included MariaDB, Node.js, and nginx while guaranteeing smooth communication between all of these components.

Learning Experience
Learned the usage of Docker Compose to manage apps running on several containers.
Improved comprehension of volume management and Docker networking for long-term data storage.
Findings
Verified that Docker works well for handling complicated, multi-tier applications by using nginx to efficiently route traffic to Node.js program, which communicates with MariaDB in a dynamic manner.
Challenge 4: Scaling up an application
The objective was to use Docker Compose to scale a Node.js application service from one to three instances in order to increase load handling and availability.

Learning Experience
Learned how to use nginx for load balancing across several service instances and scale services using Docker.
Findings
Showed how Docker may improve the performance and resilience of an application by distributing requests evenly through load balancing, which prevents any one node service from becoming a bottleneck.