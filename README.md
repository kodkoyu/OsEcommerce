# Structural Definition of the Project

- The project will be built on seven main foundations:  
1. Gateway, load balancing, tenant, and segregated database architecture  
2. Separation of tenant-based databases  
3. Communication protocol between services will be GRPC  
4. Global logging will be implemented  
5. Redis will be used for caching  
6. Rabbit MQ will be used for notifications  
7. Each service will adhere to an N-layer architecture

# Planned Services
* **User Service**  
   - Session and authorization control, both tenant-based and general  
   - There will be a merged user concept  
* **Product Service**  
   - Will handle product management  
* **Catalog Service**
* **Order Service**
* **Payment Service**  
   - Different payment options will be offered  
* **Stock Service** (handling both stock and logistics)
* **Search and Data Service**
* **Auth Service**
* **OSE Engine**  
   - Tenant manager (Spook)  
   - Language support  
   - Global Exception Manager
   - License Service  
   - Database Managers (Tenant, DB Type, Plug & Play)  
* **Gateway**
* **OSE Core** (Common Library)
* **File Service** (I/O)
* **Notification Service**