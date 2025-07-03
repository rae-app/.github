# 👋 Welcome to Sophistic !

We're building **Rae**, an AI-powered chat assistant using Claude (from Anthropic) with **Model Context Protocol (MCP)** support — enabling seamless tool usage like Google Calendar,Slack,Whatsapp and many more... directly through conversation.

## 🚀 What We’re Building

Rae is an intelligent chat interface where users can connect external tools and ask complex queries. Claude AI autonomously selects and uses tools via a JSON-RPC interface to fulfill user prompts.

### 🔧 Core Features

- **Tool Calling with Claude**: Claude can invoke registered tools using Anthropic's tool-use feature.
- **MCP Server (Node.js)**: A backend server exposes tools via a standard interface (JSON-RPC).
- **Tool Registry**: Tools include metadata (name, description, input schema) that Claude uses to interact with them intelligently.
- **Secure Token Handling**: Refresh tokens are stored per user-tool pair for scoped, permission-aware access.
- **Dynamic Task Execution**: Claude can handle multi-step tasks like:
  > “Schedule a meeting for 4 pm in slack and forward the link to Ronish , Keshav and Asad in Whatsapp.”

