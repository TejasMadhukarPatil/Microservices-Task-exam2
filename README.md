# Microservices-Task-exam2


This document provides details on testing various services after running the docker-compose file. These services include User, Product, Order, and Gateway Services. Each service has its own endpoints for testing purposes.


Services and Endpoints
User Service
Base URL: http://localhost:3000
Endpoints:
List Users:
curl http://localhost:3000/users

roduct Service
Base URL: http://localhost:3001
Endpoints:
List Products:
curl http://localhost:3001/products

Order Service
Base URL: http://localhost:3002
Endpoints:
List Orders:
curl http://localhost:3002/orders

Gateway Service
Base URL: http://localhost:3003/api
Endpoints:
Users:
curl http://localhost:3003/api/users
Products:
curl http://localhost:3003/api/products
Orders:
curl http://localhost:3003/api/order
