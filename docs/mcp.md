# BrowserTools MCP Documentation

This document provides an overview of the BrowserTools MCP system and how to use it.

## What is BrowserTools MCP?

BrowserTools MCP is a powerful browser monitoring and interaction tool that enables AI-powered applications via Anthropic's Model Context Protocol (MCP) to capture and analyze browser data through a Chrome extension.

## Components

The system consists of three main components:

1. **Chrome Extension**: A browser extension that captures screenshots, console logs, network activity and DOM elements.
2. **Node Server**: An intermediary server that facilitates communication between the Chrome extension and any instance of an MCP server.
3. **MCP Server**: A Model Context Protocol server that provides standardized tools for AI clients to interact with the browser.

## Installation

Please refer to the main README.md file for installation instructions.

## Usage

Once installed, you can use the BrowserTools MCP system to:

- Monitor browser console output
- Capture network traffic
- Take screenshots
- Analyze selected elements
- Wipe logs stored in the MCP server

## MCP Functions

The MCP server provides the following functions:

- `getConsoleLogs` - Retrieve browser console logs
- `getConsoleErrors` - Get browser console errors
- `getNetworkErrorLogs` - Get network error logs
- `getNetworkSuccessLogs` - Get successful network requests
- `takeScreenshot` - Take a screenshot of the current browser tab
- `getSelectedElement` - Get the currently selected DOM element
- `wipeLogs` - Wipe all browser logs from memory

## License

MIT