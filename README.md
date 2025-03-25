## Spring Cloud Gateway Service  

This **Spring Cloud Gateway** service acts as an **API Gateway** for microservices, providing:  
✅ **Dynamic Route Management** – Routes are stored in **PostgreSQL** and dynamically loaded.  
✅ **Rate Limiting** – Uses **Redis** for request rate limiting per hostname.  
✅ **Authentication & Authorization** – Integrated with **Keycloak & OAuth2** via **Spring Security**.  
✅ **Resilience & Security** – Supports filters, logging, and global exception handling.  

### **Tech Stack**  
- **Spring Cloud Gateway** – API Gateway for routing & filtering.  
- **PostgreSQL** – Stores dynamic routes.  
- **Redis** – Implements rate limiting.  
- **Keycloak + OAuth2** – Secure authentication & authorization.  

### **Features**  
✅ **Database-Based Routes** – Routes are loaded from PostgreSQL at runtime.  
✅ **Redis Rate Limiter** – Controls request flow per client.  
✅ **OAuth2 Security** – Uses Keycloak for authentication.  
✅ **Global Exception Handling** – Unified error responses for better debugging.  

### **Running the Service**  
1. Configure **PostgreSQL** and **Redis**.  
2. Set up **Keycloak** with OAuth2 clients.  
3. Run the service:  
   ```sh mvn spring-boot:run ```  
4. Use **OAuth2 tokens** to access secured endpoints.  

