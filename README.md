# Xtottel Core Servers

Xtottel Core Servers is an open-source project designed to provide scalable and reliable communication and payment infrastructure for the Xtottel ecosystem. The project includes the following core servers:

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
- **IVR Server**: Interactive voice response for phone-based interactions.
- **Payment Gateway**: Integrates with Xtottel’s XtoPay platform to enable secure payments.

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
cd smpp-server
npm start

cd ../smtp-server
npm start

# Repeat for other servers...
#Contributing
We welcome contributions from developers! Please check the CONTRIBUTING.md for more details on how you can help improve the project.

