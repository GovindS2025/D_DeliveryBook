# D_DeliveryBook
Child app and main app is BookStore


🎯 Application Overview
D_DeliveryBook is a complete, production-ready delivery management system designed to communicate with BookStore applications and manage the entire delivery lifecycle of book orders.


Backend (Spring Boot)
✅ Complete REST API with all CRUD operations for delivery management
✅ PostgreSQL Integration with proper JPA repositories and entities
✅ Kafka Integration for real-time communication with BookStore
✅ Redis Support for caching and session management
✅ Spring Security with CORS configuration
✅ Comprehensive Service Layer with business logic
✅ Exception Handling and proper error responses
✅ Actuator Endpoints for monitoring and health checks



Frontend (React)
✅ Modern Dashboard with delivery statistics and overview
✅ Delivery Management - Create, edit, view, and delete deliveries
✅ Responsive Design with Material-UI components
✅ Navigation System with sidebar and routing
✅ Search and Filter capabilities
✅ Form Validation with step-by-step wizard
✅ Real-time Updates ready for WebSocket integration


Infrastructure & DevOps
✅ Docker Containerization for all services
✅ Docker Compose with proper service orchestration
✅ Multi-stage Builds for optimized images
✅ Health Checks and monitoring
✅ Environment Configuration management
✅ Network Isolation with custom Docker networks
�� Key Features
�� Order Management: Complete lifecycle from creation to delivery
👥 Customer Management: Store customer info and delivery addresses
🚚 Delivery Tracking: Real-time status updates (Pending → In Transit → Delivered)
👨‍💼 Driver Assignment: Assign delivery personnel to orders
📊 Analytics Dashboard: Comprehensive delivery statistics and insights
🔄 BookStore Integration: Kafka-based communication for real-time updates
🔍 Search & Filter: Advanced search capabilities across all fields
�� Responsive UI: Works on desktop, tablet, and mobile devices


🛠️ Technology Stack
Backend: Java 17, Spring Boot 3.5.3, PostgreSQL, Redis, Kafka
Frontend: React 19, Material-UI 7, React Router 7
Infrastructure: Docker, Docker Compose, Nginx
Database: PostgreSQL 14 with automatic schema creation
Messaging: Apache Kafka for event-driven architecture


📱 How to Run
Option 1: Windows (Recommended)
Option 2: Manual Docker Commands


🌐 Access Points
Frontend Application: http://localhost:3001
Backend API: http://localhost:8081
Database: localhost:5432
pgAdmin: http://localhost:5050 (admin@delivery.com / admin123)
Kafka: localhost:9092
Redis: localhost:6379


🔧 API Endpoints
The backend provides a complete REST API at http://localhost:8081/api:
GET /deliveries - Get all deliveries
POST /deliveries - Create new delivery
PUT /deliveries/{id} - Update delivery
PATCH /deliveries/{id}/status - Update status
DELETE /deliveries/{id} - Delete delivery
Plus search, filter, and assignment endpoints


📊 Kafka Integration
new-order-topic: Receives new orders from BookStore
delivery-status-topic: Sends status updates back to BookStore
Real-time Communication: Enables seamless integration with existing BookStore systems



🎨 Frontend Features
Dashboard: Overview with statistics cards and recent deliveries
Delivery Form: Step-by-step wizard for creating/editing deliveries
Delivery List: Comprehensive table with search, filter, and actions
Responsive Layout: Sidebar navigation with mobile support
Material Design: Modern, professional UI components



🔒 Security & Production Ready
CORS Configuration for frontend communication
Input Validation and sanitization
SQL Injection Protection via JPA
Health Checks for monitoring
Environment-based Configuration
Docker Best Practices with non-root users



📚 Documentation
Comprehensive README with setup instructions
API Documentation with all endpoints
Architecture Diagrams and explanations
Deployment Guidelines for production
Troubleshooting and support information



�� Ready to Use
Y
PostgreSQL Database with automatic schema creation
Redis Cache for performance optimization
Kafka Messaging for BookStore integration
Spring Boot Backend with full API functionality
React Frontend with modern UI and navigation
Nginx serving the frontend with proper configuration

