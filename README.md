# Chanty MCP Server

<!-- mcp-name: io.github.asklokesh/chanty-mcp-server -->

<div align="center">

# Chanty Mcp Server

[![GitHub stars](https://img.shields.io/github/stars/LokiMCPUniverse/chanty-mcp-server?style=social)](https://github.com/LokiMCPUniverse/chanty-mcp-server/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/LokiMCPUniverse/chanty-mcp-server?style=social)](https://github.com/LokiMCPUniverse/chanty-mcp-server/network)
[![GitHub watchers](https://img.shields.io/github/watchers/LokiMCPUniverse/chanty-mcp-server?style=social)](https://github.com/LokiMCPUniverse/chanty-mcp-server/watchers)

[![License](https://img.shields.io/github/license/LokiMCPUniverse/chanty-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/chanty-mcp-server/blob/main/LICENSE)
[![Issues](https://img.shields.io/github/issues/LokiMCPUniverse/chanty-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/chanty-mcp-server/issues)
[![Pull Requests](https://img.shields.io/github/issues-pr/LokiMCPUniverse/chanty-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/chanty-mcp-server/pulls)
[![Last Commit](https://img.shields.io/github/last-commit/LokiMCPUniverse/chanty-mcp-server?style=for-the-badge)](https://github.com/LokiMCPUniverse/chanty-mcp-server/commits)

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![MCP](https://img.shields.io/badge/Model_Context_Protocol-DC143C?style=for-the-badge)](https://modelcontextprotocol.io)

[![Commit Activity](https://img.shields.io/github/commit-activity/m/LokiMCPUniverse/chanty-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/chanty-mcp-server/pulse)
[![Code Size](https://img.shields.io/github/languages/code-size/LokiMCPUniverse/chanty-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/chanty-mcp-server)
[![Contributors](https://img.shields.io/github/contributors/LokiMCPUniverse/chanty-mcp-server?style=flat-square)](https://github.com/LokiMCPUniverse/chanty-mcp-server/graphs/contributors)

</div>

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
