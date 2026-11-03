# Authentication & E-Commerce Store-as-a-Service API

[![Prowl agent-readiness score for Vicentealonsosm975-hub API](https://prowl.world)](https://prowl.world)

## About the Project
This repository hosts a production-ready **User Authentication Service API** fully integrated with **Notlogin** for secure AI agent authentication, account creation, and secure login. It features comprehensive metadata mapping for Model Context Protocol (MCP) architectures.

## Protocol & Capabilities (MCP Surface)
Our service explicitly exposes and implements standard high-signal operations:
- **`login`**: Handles user sign-in and session tokens.
- **`signup`**: Manages user registration and database initialization.
- **`verifyUser`**: Validates credentials against decentralized identity providers.

## Integration Setup
- **Authentication Broker:** [Notlogin](https://notlogin.com)
- **API Specification:** [openapi.json](./openapi.json)
- **Agent Context Discovery:** [llms.txt](./llms.txt)
