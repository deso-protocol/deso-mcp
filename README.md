# DeSo MCP Server for Cursor IDE v3.0

A comprehensive Model Context Protocol (MCP) server that provides **complete DeSo blockchain API coverage** for Cursor IDE. This server transforms Cursor's AI assistant into a DeSo development expert with extensive knowledge about all DeSo APIs, the deso-js SDK, DeSo Identity authentication, backend implementation details, production-ready code generation, and **comprehensive debugging solutions**.

<a href="https://glama.ai/mcp/servers/@deso-protocol/deso-mcp">
  <img width="380" height="200" src="https://glama.ai/mcp/servers/@deso-protocol/deso-mcp/badge" alt="DeSo Server MCP server" />
</a>

## 🔥 **What's New in v3.0**
- **🛠️ Comprehensive Debugging Guide**: Real solutions for all major DeSo integration issues
- **🏗️ Implementation Patterns**: Best practices learned from building production DeSo apps
- **📱 Complete Example App**: Full DeSo messaging application with Next.js, TypeScript, and Tailwind
- **🐛 Real Debugging Experience**: Solutions based on actual debugging sessions and common pitfalls

## **What's New in v2.2-2.3**
- **Complete DeSo Identity Integration**: Full authentication system coverage
- **9 Identity API Endpoints**: iframe & window APIs for login, signing, encryption
- **Advanced Authentication Guide**: Access levels, derived keys, message encryption
- **Complete Data API Coverage**: All endpoint categories from DeSo backend documentation
- **40+ Data Endpoints**: Users, Posts, NFTs, Messages, Notifications, Access Groups, and more

## 🚀 What This Does

This MCP server transforms Cursor's AI assistant into a **DeSo development expert** by providing:

- **Complete DeSo API Knowledge**: All endpoints from the backend with handler details
- **deso-js SDK Expertise**: Full SDK documentation and usage patterns  
- **Code Generation**: Production-ready examples in JavaScript, TypeScript, React, and cURL
- **Architecture Guidance**: Deep understanding of DeSo's transaction flows and systems
- **Backend Integration**: Direct mapping to `routes/transaction.go` and other backend files
- **🛠️ Debugging Solutions**: Real fixes for common DeSo integration problems
- **🏗️ Best Practices**: Implementation patterns from production DeSo applications

## 📋 Available Tools Overview

### **Core Development Tools**

1. **🔍 `deso_api_explorer`** - Complete DeSo API reference with code examples
2. **📚 `deso_js_guide`** - Comprehensive deso-js SDK documentation and setup
3. **⚡ `generate_deso_code`** - Production-ready code generation for any DeSo operation
4. **🏛️ `explain_deso_architecture`** - Deep architecture explanations and integration patterns

### **Knowledge Base Tools**

5. **🔎 `repository_search`** - Search across all DeSo documentation and repositories
6. **📖 `read_repository_document`** - Read specific documentation files from DeSo repos

### **Advanced Debugging Tools (NEW in v3.0)**

7. **🛠️ `deso_debugging_guide`** - Comprehensive debugging for common DeSo issues
8. **🏗️ `deso_implementation_patterns`** - Best practices from real DeSo application development

## 🛠️ Complete Tool Reference

### 1. **`deso_api_explorer`** - API Explorer
Comprehensive DeSo API explorer with backend implementation details and deso-js SDK integration.

**Parameters:**
- `category` (required): API category to explore
  - Options: `"social"`, `"financial"`, `"nft"`, `"dao"`, `"tokens"`, `"access"`, `"associations"`, `"derived-keys"`, `"messages"`, `"data"`, `"notifications"`, `"media"`, `"admin"`, `"blockchain"`, `"identity"`, `"all"`
- `endpoint` (optional): Specific endpoint name
- `includeCode` (optional): Include code examples

**Example Usage:**
```
Show me all the social APIs for DeSo
Use the DeSo API explorer to show messaging endpoints with code examples
Explore the identity APIs for authentication
```

### 2. **`deso_js_guide`** - SDK Guide
Complete guide to using the deso-js SDK with setup, authentication, and transactions.

**Parameters:**
- `topic` (required): Topic to get guidance on
  - Options: `"setup"`, `"identity"`, `"authentication"`, `"transactions"`, `"data"`, `"permissions"`, `"examples"`, `"troubleshooting"`
- `framework` (optional): Framework context
  - Options: `"vanilla"`, `"react"`, `"nextjs"`, `"node"`

**Example Usage:**
```
Show me how to set up the deso-js SDK in a React app
Guide me through DeSo authentication with identity management
How do I handle transactions in Next.js with deso-js?
```

### 3. **`generate_deso_code`** - Code Generator
Generate comprehensive code examples for DeSo operations using deso-js SDK.

**Parameters:**
- `operation` (required): DeSo operation (e.g., 'follow', 'post', 'buy-creator-coin', 'send-diamonds')
- `language` (required): Programming language/framework
  - Options: `"javascript"`, `"typescript"`, `"react"`, `"curl"`
- `includeAuth` (optional): Include authentication setup
- `fullExample` (optional): Generate complete working example

**Example Usage:**
```
Generate a React component for following users with authentication
Create a TypeScript function for sending diamonds with full example
Show me how to create posts using JavaScript with the deso-js SDK
```

### 4. **`explain_deso_architecture`** - Architecture Guide
Explain DeSo architecture, flows, and integration patterns.

**Parameters:**
- `topic` (required): Architecture topic to explain
- `includeCode` (optional): Include code examples

**Example Usage:**
```
Explain how DeSo transactions work with code examples
What's the difference between master keys and derived keys?
How does the DeSo messaging system architecture work?
```

### 5. **`repository_search`** - Repository Search
Search for documents in the DeSo repository.

**Parameters:**
- `query` (required): Search query

**Example Usage:**
```
Search the DeSo repositories for messaging documentation
Find information about NFT creation in the DeSo docs
```

### 6. **`read_repository_document`** - Document Reader
Read a specific document from the DeSo repository.

**Parameters:**
- `path` (required): Relative path to the document (e.g., 'docs/deso-tutorial-build-apps.md')
- `repository` (optional): Repository name
  - Options: `"docs"`, `"core"`, `"identity"`, `"frontend"`, `"backend"`, `"deso-js"`

**Example Usage:**
```
Read the DeSo tutorial for building apps
Show me the content of the DeSo backend documentation for transactions
```

### 7. **`deso_debugging_guide`** - Debugging Guide (NEW in v3.0)
Comprehensive debugging guide for common DeSo integration issues with real solutions.

**Parameters:**
- `issue` (required): Specific issue to debug or 'all' for complete guide
  - Options: `"message-decryption"`, `"access-groups"`, `"infinite-loops"`, `"api-responses"`, `"authentication"`, `"react-errors"`, `"all"`
- `includeCode` (optional): Include code examples and fixes

**Example Usage:**
```
Help me debug DeSo message decryption issues
Show me how to fix infinite loops in React DeSo components
Debug DeSo authentication problems with code examples
```

### 8. **`deso_implementation_patterns`** - Implementation Patterns (NEW in v3.0)
Best practices and implementation patterns learned from real DeSo application development.

**Parameters:**
- `pattern` (required): Implementation pattern to explore
  - Options: `"messaging-flow"`, `"error-handling"`, `"state-management"`, `"api-integration"`, `"user-switching"`, `"real-time-updates"`, `"all"`
- `framework` (optional): Framework context
  - Options: `"react"`, `"vanilla"`, `"nextjs"`

**Example Usage:**
```
Show me best practices for DeSo messaging flow in React
What are the recommended error handling patterns for DeSo apps?
How should I implement real-time updates in a DeSo application?
```

## 🎯 Real-World Example: DeSo Messaging App

This repository includes a complete **DeSo messaging application** built with the MCP server guidance:

### **Built Application Features:**
- ✅ Complete DeSo Identity authentication
- ✅ Real-time user search and discovery
- ✅ Actual blockchain message sending via `sendDMMessage`
- ✅ Professional React components with TypeScript
- ✅ Real-time message polling and status updates
- ✅ Comprehensive error handling and debugging features
- ✅ Modern UI with Tailwind CSS and responsive design

### **Technical Stack:**
- **Frontend**: Next.js 14, React, TypeScript, Tailwind CSS
- **DeSo Integration**: deso-protocol SDK v3.4.1
- **Authentication**: DeSo Identity with proper permission management
- **State Management**: Custom React hooks with proper error handling

### **Example App Structure:**
```
example-app/
├── src/
│   ├── app/                 # Next.js app directory
│   ├── components/
│   │   ├── auth/           # Authentication components
│   │   ├── chat/           # Messaging components  
│   │   └── user/           # User discovery components
│   ├── hooks/              # Custom React hooks
│   ├── lib/                # DeSo configuration and types
│   └── styles/             # Global styles
├── package.json            # Dependencies
└── README.md              # App documentation
```

## 🛠 Installation & Setup

### Prerequisites

- Node.js (v18+ recommended)
- Cursor IDE
- Git (for cloning repositories)

### 1. Clone and Setup

```bash
# Clone the repository
git clone <your-repo-url>
cd deso-mcp

# Install dependencies
npm install

# Verify the MCP server works
npm run test
```

### 2. Configure Cursor IDE

Create or update your Cursor MCP configuration file:

**File:** `.cursor/mcp.json`

```json
{
  "deso-mcp": {
    "command": "node",
    "args": ["deso-mcp-final.js"],
    "cwd": "/absolute/path/to/your/deso-mcp",
    "type": "stdio"
  }
}
```

**Important:** Replace `/absolute/path/to/your/deso-mcp` with your actual project path.

**💡 Quick tip:** Run `pwd` in your project directory to get the absolute path:
```bash
cd deso-mcp
pwd
# Copy this path to use in .cursor/mcp.json
```

### 3. Enable in Cursor Settings

1. Open Cursor Settings (`⌘ + ,` on Mac, `Ctrl + ,` on Windows/Linux)
2. Navigate to **Features** → **MCP**
3. You should see "deso-mcp" listed
4. Ensure it shows as "Connected" ✅

### 4. Test the Integration

1. **Start a new chat** in Cursor (`⌘ + L` or `Ctrl + L`)
2. **Test with this prompt:**
   ```
   Use the DeSo MCP tools to show me how to follow a user with the deso-js SDK
   ```
3. **You should see** the AI use your MCP tools and provide comprehensive DeSo-specific guidance!

## 🎯 Usage Examples

Once configured, you can ask Cursor's AI assistant questions like:

### **API Exploration**
- *"Show me all the identity endpoints for DeSo authentication"*
- *"What are the iframe vs window APIs in DeSo Identity?"*
- *"Show me all the data endpoints available in DeSo"*
- *"What notification APIs can I use to get user notifications?"*
- *"How do I fetch DM messages using the messages API?"*

### **Code Generation**  
- *"Generate a React authentication component with DeSo Identity"*
- *"Show me how to encrypt and decrypt messages using deso-js"*
- *"Create a derived key manager for mobile apps"*
- *"Generate a React component for creating and minting NFTs"*
- *"Create a complete DeSo messaging interface with TypeScript"*

### **Debugging & Troubleshooting**
- *"Help me debug DeSo message decryption that's returning undefined"*
- *"Fix infinite loops in my React DeSo authentication component"*
- *"Why am I getting 400 errors when sending DeSo messages?"*
- *"Debug access group empty string vs undefined issues"*
- *"Show me the correct way to handle DeSo API responses"*

### **Implementation Patterns**
- *"Show me best practices for DeSo messaging flow architecture"*
- *"What's the recommended error handling pattern for DeSo apps?"*
- *"How should I implement user switching in a DeSo application?"*
- *"Show me real-time polling patterns for DeSo messaging"*

### **Setup & Configuration**
- *"How do I set up the deso-js SDK in a React app?"*
- *"What permissions do I need for posting transactions?"*
- *"Show me how to configure identity management"*
- *"What are the different access levels in DeSo Identity?"*

## 🔧 Development Commands

```bash
# Quick tests using npm scripts
npm run test              # Test tools list
npm run test-follow       # Test follow endpoint with code

# Run the server manually
node deso-mcp-final.js

# Test specific tools manually
echo '{"jsonrpc": "2.0", "id": 1, "method": "tools/call", "params": {"name": "deso_api_explorer", "arguments": {"category": "social"}}}' | node deso-mcp-final.js

# Test debugging guide
echo '{"jsonrpc": "2.0", "id": 2, "method": "tools/call", "params": {"name": "deso_debugging_guide", "arguments": {"issue": "all", "includeCode": true}}}' | node deso-mcp-final.js

# Test implementation patterns
echo '{"jsonrpc": "2.0", "id": 3, "method": "tools/call", "params": {"name": "deso_implementation_patterns", "arguments": {"pattern": "messaging-flow", "framework": "react"}}}' | node deso-mcp-final.js
```

## 📁 Project Structure

```
deso-mcp/
├── deso-mcp-final.js      # Main MCP server implementation (v3.0)
├── mcp-server.js          # Legacy server (v2.3)
├── package.json           # Dependencies and scripts
├── .cursor/
│   └── mcp.json          # Cursor MCP configuration
├── repos/                 # DeSo repository clones
│   ├── docs/             # DeSo documentation
│   ├── backend/          # DeSo backend code
│   └── deso-js/          # DeSo JavaScript SDK
├── example-app/          # Complete DeSo messaging application
│   ├── src/              # Next.js app source
│   ├── package.json      # App dependencies
│   └── README.md         # App documentation
└── schema.graphql        # DeSo GraphQL schema
```

## 🐛 Troubleshooting

### MCP Server Not Connecting

1. **Check the path** in `.cursor/mcp.json` is absolute and correct
2. **Update to use `deso-mcp-final.js`** instead of `mcp-server.js`
3. **Restart Cursor** completely
4. **Check server runs manually:**
   ```bash
   node deso-mcp-final.js
   # Should output: "DeSo MCP Comprehensive Server running on stdio"
   ```

### Tools Not Available in Chat

1. **Start a new chat session** in Cursor (`⌘ + L`)
2. **Explicitly mention MCP tools** in your first message
3. **Check MCP status** in Cursor Settings → Features → MCP

### Dependencies Issues

```bash
# Reinstall dependencies
rm -rf node_modules package-lock.json
npm install

# Check Node.js version
node --version  # Should be v18+
```

### Common DeSo Integration Issues

Use the **debugging guide tool** for specific issues:
```
Use the DeSo debugging guide to help me with [specific issue]
```

The server includes comprehensive debugging solutions for:
- Message decryption problems (DecryptedMessage vs MessageText)
- Access group handling (empty strings vs undefined)
- React infinite loops (useCallback dependencies)
- API response structure issues
- Authentication flow problems
- User switching and state management

## 🚀 Advanced Features

### **Real Debugging Experience**
The v3.0 server includes solutions for actual problems encountered while building DeSo applications:

- **Message Decryption Fix**: Proper handling of `DecryptedMessage` vs `MessageText` properties
- **Access Groups Solution**: Correct empty string vs undefined handling
- **React Integration**: Solutions for key warnings, state management, and error boundaries
- **API Response Handling**: Proper response structure handling per endpoint
- **Authentication Flows**: Complete identity event handling and user switching

### **Production Patterns**
Learn from real implementation patterns:

- **Complete messaging flow** with encryption and access groups
- **Comprehensive error handling** with retry logic
- **Professional state management** patterns
- **Real-time polling** and optimistic updates
- **User experience** best practices

### **Framework-Specific Examples**
The server can generate examples for different frameworks:
- **Vanilla JavaScript**: Basic SDK usage
- **React**: Component patterns with hooks and TypeScript
- **Next.js**: Server-side integration and API routes
- **React Native**: Mobile-specific configuration

## 📚 Related Resources

- **[DeSo Documentation](https://docs.deso.org/)**
- **[deso-js SDK](https://www.npmjs.com/package/deso-protocol)**
- **[DeSo Backend Repository](https://github.com/deso-protocol/backend)**
- **[React Examples](https://github.com/deso-protocol/deso-examples-react)**
- **[Model Context Protocol](https://modelcontextprotocol.io/)**

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Add new MCP tools or enhance existing ones
4. Update this README with new features
5. Submit a pull request

## ✅ Quick Verification Checklist

After setup, verify everything is working:

```bash
# 1. Test MCP server is functional
npm run test

# 2. Test specific tool with code examples  
npm run test-follow

# 3. Test debugging guide
echo '{"jsonrpc": "2.0", "id": 1, "method": "tools/call", "params": {"name": "deso_debugging_guide", "arguments": {"issue": "authentication", "includeCode": true}}}' | node deso-mcp-final.js

# 4. Check Cursor MCP connection
# Open Cursor → Settings → Features → MCP → Should show "deso-mcp" as Connected ✅

# 5. Test in Cursor AI
# Start new chat (⌘ + L) and ask:
# "Use the DeSo debugging guide to help me with message decryption issues"
```

## 🎉 What You Can Do Now

**With this MCP server, your Cursor AI assistant can:**

✅ **Explore any DeSo API** with complete documentation and code examples  
✅ **Generate production-ready code** for any DeSo operation in multiple languages  
✅ **Debug real DeSo integration problems** with tested solutions  
✅ **Implement best practices** learned from production DeSo applications  
✅ **Understand DeSo architecture** with deep technical explanations  
✅ **Search and read** all DeSo documentation and repositories  
✅ **Create complete applications** following proven patterns  
✅ **Handle authentication flows** with proper identity management  

**Start a new chat in Cursor and experience the power of AI-assisted DeSo development!** ⚡

---

**🚀 Ready to build amazing DeSo applications with AI assistance!**