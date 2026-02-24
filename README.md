# Introduction Workshop to Microsoft Foundry: Building an Intelligent RAG Chatbot with Voice Capabilities

## 🎯 Workshop Overview

Welcome to this hands-on workshop where you'll learn to build an intelligent chatbot with Retrieval-Augmented Generation (RAG) capabilities using Microsoft Foundry and add real-time voice conversations using GPT Realtime. This workshop is designed to be educational and provides insights into modern AI application development using Microsoft's AI platform.

> 🆕 **New to Microsoft Foundry?** No problem! Each lab includes a **🎓 Key Concepts** section that explains exactly what each service does and why it's used. You can follow along even if you've never used Foundry before.

### What You'll Build

By the end of this workshop, you will have:
1. **Lab 1**: A fully functional RAG chatbot that answers questions using your custom knowledge base, powered by Foundry IQ and Azure AI Search, deployed as a web application
2. **Lab 2**: Voice-enabled conversations with your chatbot using GPT Realtime (speech-to-speech)

### Learning Objectives

- Understand the RAG (Retrieval-Augmented Generation) architecture
- Set up a knowledge base using Azure AI Search and Azure Blob Storage
- Learn to use Foundry IQ for knowledge base management with agentic retrieval
- Create an AI agent in Microsoft Foundry
- Deploy your agent as a web app using the Foundry Agent Web App template
- Add real-time voice capabilities using GPT Realtime

## 🆕 What is Microsoft Foundry?

**Microsoft Foundry** (also known as **Azure AI Foundry**) is Microsoft's unified AI development platform. Think of it as your one-stop shop for building AI applications on Azure:

| Feature | What It Gives You |
|---------|------------------|
| **Model Catalog** | Access to GPT-4.1, GPT Realtime, embedding models, and more |
| **Foundry IQ** | Managed knowledge layer for grounding agents in your documents |
| **Agent Service** | Build, test, and deploy AI agents with tools and memory |
| **Monitoring** | Track usage, costs, and performance of your deployments |
| **Project Management** | Organize resources, keys, and team access in one place |

> 💡 **Portal URL**: You access Microsoft Foundry at [https://ai.azure.com](https://ai.azure.com)

## 📋 Prerequisites

### Required Knowledge
- Basic understanding of Python programming
- Familiarity with REST APIs
- Basic understanding of cloud services
- Understanding of basic AI/ML concepts 

### Required Tools
- **Python 3.10+** installed on your machine
- **Visual Studio Code** or another code editor
- **Git** for version control
- **Azure subscription** 
- **Microsoft Foundry access** 

## 🗂️ Workshop Structure

This workshop is divided into two progressive labs, each with multiple sub-labs offering **Portal** and **Code** paths.

> 💡 For production deployments, you can also use Bicep, Terraform, or ARM Templates instead of the Azure CLI.

### [Lab 1: Building a RAG-Enabled Chatbot](./lab-1-rag-chatbot/README.md)
**Duration**: 75-105 minutes

| Sub-Lab | Description | Time | Portal | Code |
|---------|-------------|------|:------:|:----:|
| 1.1 Set Up Azure Resources | Create Foundry project, deploy models | 15-20 min | ✅ | ✅ |
| 1.2 Prepare Knowledge Base | Upload documents to Azure Blob Storage | 10-15 min | ✅ | ✅ |
| 1.3 Create Vector Index | Set up Azure AI Search with embeddings | 15-20 min | ✅ | ✅ |
| 1.4 Create Your Agent | Build agent with Foundry IQ | 15-20 min | ✅ | ✅ |
| 1.5 Host Agent as Web App | Deploy using Foundry Agent Web App | 20-30 min | ❌ | ✅ |

### [Lab 2: Adding Voice Capabilities](./lab-2-voice-capabilities/README.md)
**Duration**: 30-45 minutes

| Sub-Lab | Description | Time | Portal | Code |
|---------|-------------|------|:------:|:----:|
| 2.1 Deploy GPT Realtime Model | Deploy the realtime voice model | 10-15 min | ✅ | ✅ |
| 2.2 Add Voice to Your Agent | Integrate voice using GPT Realtime API | 15-20 min | ❌ | ✅ |
| 2.3 Cleanup Resources | Delete all Azure resources | 5-10 min | ✅ | ✅ |

##  Additional Resources

- [Microsoft Foundry Documentation](https://learn.microsoft.com/en-us/azure/ai-foundry/)
- [Understanding RAG](https://learn.microsoft.com/en-us/azure/search/retrieval-augmented-generation-overview)
- [Azure AI Search](https://learn.microsoft.com/en-us/azure/search/)
- [GPT Realtime API](https://learn.microsoft.com/en-us/azure/ai-services/openai/realtime-audio-quickstart)
- [Microsoft Foundry Developer Community](https://github.com/microsoft-foundry)
- [Foundry Samples & Tutorials](https://github.com/microsoft-foundry/foundry-samples)

## 🎓 Continue Learning on Your Own

After completing this workshop, here are some directions to explore independently:

| Topic | What to Explore |
|-------|----------------|
| **More RAG patterns** | Try hybrid search (keyword + vector), re-ranking, and query expansion |
| **Agent orchestration** | Build multi-agent workflows where agents collaborate |
| **Fine-tuning** | Customize a model with your own training data |
| **Responsible AI** | Explore Azure AI Content Safety and Prompt Shields |
| **Production patterns** | Learn about monitoring, logging, and CI/CD for AI apps |

> 💡 **Tip**: Join the [Microsoft Foundry Developer Discord](https://discord.gg/nTYy5BXMWG) to connect with other developers and get help!

## 📄 License

This workshop content is provided for educational purposes.

---

**Ready to begin?** Head over to [Lab 1](./lab-1-rag-chatbot/README.md) to get started!
