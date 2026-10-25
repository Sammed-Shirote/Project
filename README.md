# AI Chatbot and MCP Integration

A project exploring a provider-switchable AI chatbot and reporting workflow using Anthropic Claude, Google Gemini, and the Model Context Protocol (MCP).

## Overview

The goal is to provide a common application workflow for working with multiple AI providers and connecting model responses to custom tools and structured application data.

## Key areas

- **Multiple AI providers:** provider-specific streaming workflows for Anthropic Claude and Google Gemini.
- **MCP tool integration:** custom tools exposed through an MCP server to connect the assistant with application workflows.
- **Reporting and operational data:** exploration of AI-assisted access to structured information.
- **CI/CD release tracking:** SQLite-based tracking of pipeline and release information in the development environment.

## Why this project

Switching between AI providers and connecting models to real application tools can require provider-specific code and custom integration work. This project explores a modular approach that makes those integrations easier to maintain and extend.

## Status

This repository is being prepared for public documentation. Implementation details, setup instructions, screenshots, and tests should be added as the corresponding code and examples are published.

## Security and configuration

- Never commit API keys, access tokens, passwords, production data, or private database files.
- Store credentials in environment variables or a local `.env` file that is excluded from version control.
- Use synthetic or sanitized data in public examples.

## Contributing

Contributions, bug reports, and suggestions can be added through GitHub issues and pull requests once the project source and contribution guidelines are published.

## License

A license has not yet been selected. Until one is added, all rights are reserved by the copyright holder; please do not assume the code is licensed for reuse.
