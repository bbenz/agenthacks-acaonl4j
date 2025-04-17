
# Agenthacks session: Building Java AI Agents using LangChain4j and Dynamic Sessions

## Repository Contents

This repository contains the example code demonstrated during the session, showing how to leverage Azure Container Apps (ACA) dynamic sessions for remote code execution, file management, and interactive communication using LangChain4j.


**Session Date:** April 17, 2025 | **Time:** 12:00 PM - 1:00 PM (UTC-07:00) Pacific Time (US & Canada)

**Format:** Livestream

**Topic:** Using AI Products

**Language:** English

## Session Overview

Unlock the potential of AI Agents in your Java applications by combining LangChain4j with Azure Container Apps (ACA) dynamic sessions connected to Azure AI services. This session showcases a practical example of building an agent capable of interacting with a remote environment, including file management. Learn how to define custom tools, integrate them into agent workflows, and leverage Azure's scalable infrastructure to deploy intelligent, dynamic solutions.

## Learning Resources

For more information about LangChain4j with Azure Container Apps dynamic sessions, visit:
https://github.com/langchain4j/langchain4j/tree/main/langchain4j-azure-aca-dynamic-sessions

## Presentation Materials

The presentation slides from this session can be found in the [ACA Dynamic Sessions for Java with Langchain4j.pdf](./ACA%20Dynamic%20Sessions%20for%20Java%20with%20Langchain4j.pdf) file in this repository.


### Key Components

- **Assistant Interface**: Defines the chat method for user-AI interaction
- **AzureOpenAiChatModel**: Configured Azure OpenAI integration for chat capabilities
- **SessionsREPLTool**: Tool for executing code and managing files in ACA dynamic sessions
- **AiServices**: Connects the language model and tools to create the assistant

## Example Code

The example demonstrates:

1. Creating an AI assistant that can solve mathematical problems using Python code
2. Executing the code remotely in Azure Container Apps dynamic sessions
3. Managing files (upload, download, list) in the remote environment
4. Interactive communication using Azure OpenAI models

## Prerequisites

To run this example, you need:

1. Azure account with appropriate permissions
2. Azure Container Apps dynamic sessions pool
3. Azure OpenAI service instance
4. Environment variables properly configured

## Environment Setup

The following environment variables must be set:

```
POOL_MANAGEMENT_ENDPOINT       - URL for the ACA dynamic sessions pool management
AZURE_OPENAI_API_KEY           - API key for accessing the Azure OpenAI service
AZURE_OPENAI_ENDPOINT          - Endpoint URL for the Azure OpenAI service
AZURE_OPENAI_DEPLOYMENT_NAME   - Deployment name for the Azure OpenAI service
REGION                         - Azure region (e.g. westus2)
SUBSCRIPTION_ID                - Your Azure subscription ID
RESOURCE_GROUP                 - Your Azure resource group name
SESSION_POOL_NAME              - Name of your ACA session pool
SESSION_POOL_RESOURCE_ID       - Resource ID of your ACA session pool
CLI_USERNAME                   - Your Azure CLI username
```

## Getting Started

1. Clone this repository
2. Set up the required environment variables
3. Ensure you have the necessary dependencies in your Maven pom.xml
4. Run the example to see the AI assistant in action

## Join the Hackathon

This session is part of a hackathon event. Please join to participate and apply what you learn.


## Sample Code Explained

```java
// Example from the session demonstrating how to:
// 1. Initialize the SessionsREPLTool with your ACA environment
// 2. Configure the Azure OpenAI model
// 3. Build an assistant that can execute code and manage files
// 4. Use the assistant to solve problems and interact with files

// Sample interaction:
// Q: "If a pizza has a radius 'z' and a depth 'a', what's its volume?"
// A: The assistant generates and executes Python code to calculate:
//    π * z² * a (Pi times radius squared times height)
```

## License

[Include your preferred license information here]
