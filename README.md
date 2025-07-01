# Hello World MCP Server

一个简单的 MCP (Model Context Protocol) 服务器，提供 hello world 功能。

## 安装使用

在支持MCP的AI客户端配置文件中添加：

```json
{
  "mcpServers": {
    "hello-world": {
      "command": "npx",
      "args": ["-y", "hello-world-mcp"]
    }
  }
}
```

## 功能

该服务器提供一个名为 `hello_world` 的工具，调用时会返回 "Hello World!" 消息。