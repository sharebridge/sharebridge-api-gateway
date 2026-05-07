# sharebridge-api-gateway

> API gateway and routing

## Overview

This repository contains the **API Gateway** - the single entry point for all client requests to ShareBridge backend services.

**Key Responsibilities:**
- 🚪 Request routing to appropriate microservices
- 🔐 Authentication and authorization (JWT validation)
- 🛡️ Rate limiting and DDoS protection
- 📝 Request/response logging and monitoring
- 🔄 Load balancing across service instances
- 🌐 CORS policy enforcement
- 📊 API analytics and metrics collection
- ⚡ Response caching for performance

**Technology Stack:** Kong, AWS API Gateway, or Azure API Management (TBD)

For overall project context, see the [main ShareBridge repository](https://github.com/sharebridge/sharebridge).

## AI-Powered Development

This project uses AI-assisted development. Code and documentation are generated through prompts stored in the /prompting folder.

## Prompting Folder

The prompting/ folder contains:
- All prompts used to generate code for this component
- Feature requests and requirements in natural language
- AI model instructions and specifications
- Prompt templates for future development

**Transparency:** Anyone can see how features were specified and generated.  
**Reproducibility:** Use similar prompts to regenerate or modify components.  
**Collaboration:** Non-coders can contribute by writing or refining prompts.

## Repository Status

🚧 **Status:** Initial Setup  
📅 **Date:** January 9, 2026

## Getting Started

> Coming soon - Development setup instructions

## Contributing

See the [main repository's CALL_FOR_CONTRIBUTORS.md](https://github.com/sharebridge/sharebridge/blob/main/development/CALL_FOR_CONTRIBUTORS.md) for:
- How to contribute (technical and non-technical)
- Joining GitHub Discussions
- Submitting prompts and feature ideas

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Part of the [ShareBridge](https://github.com/sharebridge/sharebridge) ecosystem
