# Chanty MCP Server

A Model Context Protocol (MCP) server for integrating Chanty with GenAI applications.

## Overview

Team collaboration and communication platform

## Features

- Comprehensive Chanty API coverage
- Multiple authentication methods
- Enterprise-ready with rate limiting
- Full error handling and retry logic
- Async support for better performance

## Installation

```bash
pip install chanty-mcp-server
```

Or install from source:

```bash
git clone https://github.com/asklokesh/chanty-mcp-server.git
cd chanty-mcp-server
pip install -e .
```

## Configuration

Create a `.env` file or set environment variables according to Chanty API requirements.

## Quick Start

```python
from chanty_mcp import ChantyMCPServer

# Initialize the server
server = ChantyMCPServer()

# Start the server
server.start()
```

## License

MIT License - see LICENSE file for details
