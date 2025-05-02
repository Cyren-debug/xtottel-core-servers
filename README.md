# Sendexa Servers

Sendexa Servers is an open-source project designed to provide scalable and reliable communication and payment infrastructure for the Xtottel ecosystem. The project includes the following core servers:

- SMPP Server (Short Message Peer-to-Peer)
- SMTP Server (Simple Mail Transfer Protocol)
- HTTP Server (for API communication)
- OTP Server (One-Time Password)
- IVR Server (Interactive Voice Response)
- Payment Gateway Server

These services are intended to enable messaging, voice, payment, and verification functionalities for various applications like Sendexa, XtoPay, and other Xtottel services.

---

## Features

- **SMPP Server**: Handles SMS-based communication using the SMPP protocol.
- **SMTP Server**: Sends email notifications, OTPs, and system messages via the SMTP protocol.
- **HTTP Server**: API endpoints for managing SMS, email, OTP, and other core services.
- **OTP Server**: Secure OTP generation and verification for user authentication.


---

## Getting Started

To get started with running the servers locally or contributing to the project, follow these steps.

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [npm](https://www.npmjs.com/) (Node Package Manager)
- [TypeScript](https://www.typescriptlang.org/) (for type safety)

### Installation

Clone the repository:

```bash
git clone https://github.com/Cyren-debug/xtottel-core-servers.git
cd xtottel-core-servers


Install the required dependencies:

bash
npm install


Running the Servers
You can run each server by navigating to its respective folder and starting the development environment:

bash
cd smpp
npm start

cd ../smtp
npm start

# Repeat for other servers...
#Contributing
We welcome contributions from developers! Please check the CONTRIBUTING.md for more details on how you can help improve the project.




### Tech Stack for Sendexa Servers:

1. **Programming Language:**
   - **TypeScript**: A superset of JavaScript that adds static typing, providing a robust development experience with improved tooling and error checking.

2. **Back-End Frameworks and Libraries:**
   - **Node.js**: A JavaScript runtime environment that allows you to build scalable and efficient server-side applications using JavaScript/TypeScript.
   - **Express.js**: A minimal web application framework for Node.js, used to handle routing, middleware, and HTTP requests.
   
3. **API:**
   - **RESTful APIs**: For building services such as SMS, OTP, IVR, and payment gateways, following RESTful principles for clean and scalable API designs.
   - **GraphQL** (optional): Consider for future integrations, especially for APIs requiring more complex data-fetching mechanisms.

4. **Database:**
   - **PostgreSQL** (or similar RDBMS): A powerful relational database for managing data, ensuring data integrity and offering advanced features such as indexing, transactions, and rich query support.
   - **Prisma** (optional): An ORM to easily interact with your PostgreSQL database while benefiting from TypeScript integration and automatic migrations.

5. **Authentication & Security:**
   - **JWT (JSON Web Tokens)**: For stateless authentication of API users.
   - **OAuth**: Consider for integrations with third-party services or allowing users to authenticate with existing accounts.
   - **Helmet.js**: A security middleware for setting various HTTP headers to secure the app.
   
6. **SMS & OTP:**
   - **Custom SMPP Server**: For sending and receiving SMS messages via the Short Message Peer-to-Peer protocol.
   - **OTP Service**: For generating, validating, and sending one-time passwords (OTP) for user authentication or transactional operations.

7. **Payment Gateway:**
   - **Custom Payment Gateway**: Build custom logic to integrate with payment providers (e.g., Stripe, PayPal, or local services) for seamless transactions.
   
8. **IVR (Interactive Voice Response):**
   - **Twilio API** or **Plivo**: Use for implementing IVR services if a third-party service is needed to handle calls and voice-based interactions.
   - **Custom IVR Server**: For building and managing your own IVR solution tailored to your business needs.

9. **Testing & Quality:**
   - **Jest**: A testing framework for writing unit tests, integration tests, and ensuring code quality.
   - **Supertest**: For HTTP assertions in your tests, particularly useful for testing RESTful APIs.
   
10. **Build and Automation Tools:**
    - **Webpack**: A bundler for JavaScript/TypeScript files, if needed.
    - **ESLint**: For linting and ensuring code quality and consistency across your project.
    - **Prettier**: For automatic code formatting.
   
11. **Version Control:**
    - **Git**: For version control and managing source code across different contributors.
    - **GitHub/GitLab**: For hosting and managing your code repository, issue tracking, and collaboration.

12. **Documentation:**
    - **Markdown**: For writing clean and easy-to-read documentation for your project.
    - **Swagger/OpenAPI**: Consider using for documenting your API, making it easy for developers to understand and use your services.

13. **Containerization (optional):**
    - **Docker**: For containerizing your services and ensuring a consistent environment across different stages of deployment.
   
14. **Deployment:**
    - **Heroku, AWS, or DigitalOcean**: Use a cloud platform for hosting the services and scaling as needed.
    - **CI/CD Pipelines**: Set up continuous integration and deployment using GitHub Actions or CircleCI to automate testing and deployment.

---


## Tech Stack

### 1. **Programming Language:**
- TypeScript

### 2. **Back-End Frameworks and Libraries:**
- Node.js
- Express.js

### 3. **API:**
- RESTful APIs
- GraphQL (optional)

### 4. **Database:**
- PostgreSQL
- Prisma ORM (optional)

### 5. **Authentication & Security:**
- JWT (JSON Web Tokens)
- OAuth
- Helmet.js

### 6. **SMS & OTP:**
- Custom SMPP Server
- OTP Service

### 7. **Payment Gateway:**
- Custom Payment Gateway Integration

### 8. **IVR:**
- Twilio API / Plivo (optional)
- Custom IVR Server

### 9. **Testing & Quality:**
- Jest
- Supertest

### 10. **Build and Automation Tools:**
- Webpack
- ESLint
- Prettier

### 11. **Version Control:**
- Git
- GitHub/GitLab

### 12. **Documentation:**
- Markdown
- Swagger/OpenAPI (optional)

### 13. **Containerization (optional):**
- Docker

### 14. **Deployment:**
- Heroku / AWS / DigitalOcean
- CI/CD Pipelines (GitHub Actions, CircleCI)
```
