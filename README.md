# Claude MCP Server

## Description
This project implements a server using the Model Context Protocol (MCP) to handle requests for scanning URLs. It utilizes the urlscan.io API to retrieve scan results for specified URLs.

## Installation
To set up the project, follow these steps:
1. Clone the repository:
   ```
   git clone <repository-url>
   cd <repository-directory>
   ```
2. Install the required dependencies:
   ```
   npm install
   ```

## Usage
Add Claude Desktop Config File:
```
"scan-url": {
      "command": "node",
      "args": [
        "src/index.js FILEPATH"
      ]
    }
   ```

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any suggestions or improvements.

## License
This project is licensed under the MIT License. 
