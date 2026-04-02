# Kiln

<div align="center">
  <img
    src="./logokiln.png"
    alt="Kiln Logo"
    width="200"
    height="200"
  />
</div>

## The AI-First, Open-Source IDE for Agentic Workflows

Kiln is an open-source, AI-native IDE built on top of VS Code (via the [Void](https://github.com/voideditor/void) project). It's designed to bring powerful agentic capabilities directly into your development workflow, while keeping your data private and giving you full control over your choice of AI models.

## Why Kiln?

Kiln aims to be a robust, open-source alternative to Cursor, focusing on:

- **Agentic Workflows**: High-level task execution across your entire codebase.
- **Multi-Provider Support**: Built-in integration with OpenAI, Anthropic, Gemini, Groq, Mistral, and local models via Ollama.
- **Privacy First**: Direct communication with your chosen AI providers without intermediary servers.
- **Open-Source Freedom**: Fully customizable and transparent, built on the familiar VS Code core.

## Features

- **Codebase Context**: Deep understanding of your project using advanced indexing and context window management.
- **Agentic Interactions**: Let Kiln handle complex refactors, bug hunts, or boilerplate generation.
- **Modern AI UX**: A custom-built interface for seamless AI assistance.
- **MCP Support**: Integration with the Model Context Protocol (MCP) for extensible tool access.

## Heritage

Kiln is a fork of [Void](https://github.com/voideditor/void), which itself is a fork of Microsoft's [VS Code](https://github.com/microsoft/vscode). We celebrate this lineage and aim to build upon the incredible work of the VS Code and Void communities.

## Getting Started

### Prerequisites

- **Node.js**: Version 20.x is recommended.
- **Python**: Required for some build scripts.
- **C++ Build Tools**: Required for native modules.

### Build and Run

1. **Clone the repository**:

   ```bash
   git clone https://github.com/voideditor/void.git kiln
   cd kiln
   ```

2. **Install dependencies**:

   ```bash
   npm install
   ```

3. **Run the development version**:

   ```bash
   ./scripts/code.sh
   ```

## Reference

For a guide to the codebase, see [VOID_CODEBASE_GUIDE.md](VOID_CODEBASE_GUIDE.md).

For a guide on how to develop your own version of Kiln, see [HOW_TO_CONTRIBUTE.md](HOW_TO_CONTRIBUTE.md).

## Support

You can always reach out via our community channels or contact us via email.
