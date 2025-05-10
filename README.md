# An AI Agent that can use Tools in NEXT.JS 15! (LangChain, Clerk, Convex, TS, IBM)

A sophisticated AI chat application built with Next.js, featuring real-time conversations, advanced prompt caching, and intelligent tool orchestration powered by LangChain and Claude 3.5 Sonnet.

## Features

- 🤖 Advanced AI chat interface with Claude 3.5 Sonnet
- 🎨 Modern and responsive UI with Tailwind CSS
- 🔐 Authentication with Clerk
- 💾 Real-time data storage with Convex
- ⚡ Built with Next.js 15 and React 19
- 🌊 Advanced streaming responses with custom implementation
- 📱 Mobile-friendly design
- 🧠 Prompt caching for optimized token usage
- 🔧 Intelligent tool orchestration with LangGraph
- 🔄 Real-time updates and tool execution feedback
- 📚 Integration with various data sources via wxflows

## Advanced Features

### AI and Prompt Management

- **Prompt Caching**: Optimized token usage with Anthropic's caching feature
- **Context Window**: Efficient 4096 token context management
- **Tool-Augmented Responses**: Enhanced AI capabilities with custom tools
- **Context-Aware Conversations**: Intelligent conversation management

### Tool Integration

- **wxflows Integration**:
  - Quick integration of various data sources
  - Support for YouTube transcripts
  - Google Books API integration
  - Custom data source tooling
  - Currency Exchanger
  - Performs Math operations

### LangChain & LangGraph Features

- **State Management**: Sophisticated state handling with StateGraph
- **Tool Orchestration**: Advanced tool management with ToolNode
- **Memory Management**: Efficient context tracking with MemorySaver
- **Message Optimization**: Intelligent message trimming and context management

### Streaming Implementation

- **Custom Streaming Solution**:
  - Real-time token streaming
  - Tool execution feedback
  - Error handling for failed tool calls
  - Workarounds for LangChainAdapter limitations

### Real-time Features

- **Live Updates**: Instant message delivery and updates
- **Tool Visualization**: Real-time tool interaction display
- **History Management**: Efficient message history tracking
