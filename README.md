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
![image](https://github.com/user-attachments/assets/5c2f97aa-f099-4998-98b9-2dd8b050c7ae)
![image](https://github.com/user-attachments/assets/2c682b3c-3aba-41b4-aade-9b1385521e23)
![WhatsApp Image 2025-06-28 at 15 20 17_a99cb73b](https://github.com/user-attachments/assets/6b57608b-2dce-41bd-b93e-09118590ff69)
![WhatsApp Image 2025-06-28 at 15 29 04_5c4215db](https://github.com/user-attachments/assets/83f3cba3-5325-4642-834c-077db03f9861)
![WhatsApp Image 2025-06-28 at 16 10 20_418ba639](https://github.com/user-attachments/assets/284e11b9-3bc3-4c3f-b0a7-00cdfda871a0)

Minikube Setup and Validation
Minikube setup steps

Deployment process using kubectl apply -f

Service testing instructions using kubectl port-forward or direct service names

![image](https://github.com/user-attachments/assets/b0834dab-dc7b-483b-a1b9-cedc75e73190)
![image](https://github.com/user-attachments/assets/26b3cdd7-1ce8-4a6d-8522-fd64a64bfa14)
![image](https://github.com/user-attachments/assets/0db3ca2d-7e41-4fab-9276-3ff785782a77)
![image](https://github.com/user-attachments/assets/3a936570-ebe7-4f2b-af7f-2576abedb7e6)
![image](https://github.com/user-attachments/assets/6928a2cb-1704-420b-be71-780475190b64)








