🛒 Ecommerce Application - Microservices Architecture
This repository is a collection of microservices built for an Ecommerce application. Each service is independently deployable and follows the microservices architecture pattern. Below is a brief overview of each service along with links to their respective repositories.

📦 Product Service
Description: Handles all product-related operations such as adding, retrieving, and updating product information.

Features:

Add new products

Retrieve product listings

Modify product details

🔗 View Repository

👤 User Service
Description: Manages user authentication and profile operations.

Features:

User signup, login, and logout

JWT-based token authentication

Secured with Spring Security

🔗 View Repository

💳 Payment Service
Description: Handles all payment processing using Stripe.

Features:

Integration with Stripe Payment Gateway

Secure transaction handling

🔗 View Repository

🧭 Service Registry
Description: Acts as a service registry for managing and tracking service instances.

Features:

Keeps track of all running microservices

Enables load balancing and service discovery

🔗 View Repository

🌐 API Gateway
Description: Serves as the single entry point for all client requests.

Features:

Routes incoming requests to appropriate services

Acts as a reverse proxy and request router

🔗 View Repository

📘 About This Repository
This repository provides a high-level overview of the complete Ecommerce Microservices Architecture. For more details on each service, refer to their respective repositories linked above.
