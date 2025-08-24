### Add following command to your claude config file and restart claude to run the mcp server.

{
  "mcpServers": {
    "screenshot":{
      "command": "uvx",
      "args": [
        "--from",
        "https://github.com/expllm/mcpserverdeploy.git",
        "mcp-server"
      ]
    }
  }
}