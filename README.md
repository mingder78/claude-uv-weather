# about MCP
[https://modelcontextprotocol.io/introduction](https://modelcontextprotocol.io/introduction)



```
{
    "mcpServers": {
        "weather": {
            "command": "node",
            "args": [
                "/tmp/weather/build/index.js"
            ]
        },
        "time": {
            "command": "uvx",
            "args": [
                "mcp-   server-time"
            ]
        },
        "puppeteer": {
            "command": "docker",
            "args": [
                "run",
                "-i",
                "--rm",
                "--init",
                "-e",
                "DOCKER_CONTAINER=true",
                "mcp/puppeteer"
            ]
        }
    }
}
```

## about mpc/time example
[https://hub.docker.com/r/mcp/time](https://hub.docker.com/r/mcp/time)
