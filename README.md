# TextMemory

TextMemory is a Model Context Protocol (MCP) server that provides tools for storing and retrieving text data. It helps AI assistants remember conversations by storing text in files, enabling them to maintain context and continuity across interactions.

## Features

- **Write Text Data**: Store text information in files for future reference
- **Read Text Data**: Retrieve previously stored text data
- **List Text Data**: View all available text data files
- **Delete Text Data**: Remove specific text data files

## Installation
```json
{
    "mcpServers": {
        "text-memory": {
            "command": "npx",
            "args": [
                "-y",
                "text-memory"
            ]
        }
    }
}
```