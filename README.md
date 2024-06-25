# Mulesoft DevOps Tools
![Powered by](https://img.shields.io/badge/Powered%20by-Mulesoft-535597.svg)
<br>

Welcome to the Mulesoft DevOps Tools repository. This centralized hub offers reusable workflows and actions for building robust CICD pipelines tailored for Mulesoft applications. It features a multi-environment configuration and sophisticated secrets management to streamline your DevOps processes.

## Table of contents
1. [Features](#features)

## Features
- **Standardized Source Code Layout**: Ensures consistent documentation for both GitHub and Anypoint Exchange.
- **Reusable Pipeline Components**: Configurable through simple YAML files, eliminating the need for hardcoded service-specific data.
- **Repository Badges**: Automatically generates badges for test cases and code coverage.
- **Artifact Management**: Utilizes Anypoint Exchange as the artifact repository.
- **Configuration Management**: Leverages configuration repositories and secrets for efficient management.
- **Secret Management with Azure KeyVault**: Adopts a nearly cost-free approach to secrets management, removing the need for security configuration files within the codebase.
- **Role Separation**: Distinguishes responsibilities between Security Managers (who configure the KeyVault) and DevOps Engineers (who handle service configuration).
- **Integration Testing**: Implements Mulesoft Blackbox Automated Testing (BDD tool), eliminating the need for Postman or manual QA testing.
- **Compatibility**: Fully functional with both free personal and enterprise GitHub accounts, supporting private and public repositories.
- **Deployment Readiness**: Currently supports CloudHub 1 and GovCloud, with CloudHub 2 support coming soon. The framework is easily extensible to accommodate hybrid deployment

 or Docker images.
