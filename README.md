## 🚀 Spring Cloud Gateway Service  

This **Spring Cloud Gateway** service acts as an **API Gateway** for microservices, providing:  
✅ **Dynamic Route Management** – Routes are stored in **PostgreSQL** and dynamically loaded.  
✅ **Rate Limiting** – Uses **Redis** for request rate limiting per hostname.  
✅ **Resilience & Security** – Supports filters, logging, and global exception handling.  

### 🔧 **Tech Stack**  
- **Spring Cloud Gateway** – API Gateway for routing & filtering.  
- **PostgreSQL** – Stores dynamic routes.  
- **Redis** – Implements rate limiting.  

### 🚦 **Features**  
✅ **Database-Based Routes** – Routes are loaded from PostgreSQL at runtime.  
✅ **Redis Rate Limiter** – Controls request flow per client.  
✅ **Global Exception Handling** – Unified error responses for better debugging.  
