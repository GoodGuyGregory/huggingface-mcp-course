# Gradio MCP Integration


## Exporting Gradio Interfaces as MCP Servers:

### What Happens

Tool Conversion: Each API endpoint in your Gradio app is automatically converted into an MCP tool with a corresponding name, description, and input schema. To view the tools and schemas, visit http://your-server:port/gradio_api/mcp/schema or go to the “View API” link in the footer of your Gradio app, and then click on “MCP”.

All of this is possible by leveraging the `mcp_server` field in the `demo.launch()` auto-magically

`demo.launch(mcp_server=True)`



#### Documentation

[Gradio MCP Section ](https://huggingface.co/learn/mcp-course/unit1/gradio-mcp)