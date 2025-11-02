# Claude Code Tutorial #7 - MCP Servers (128kbit_AAC-English).mp3

In this tutorial, we delve into the use of Model Context Protocol (MCP) servers to expand the capabilities of AI models like Claude. By integrating MCP servers with our code, we enable access to external data sources and APIs, enriching the model's interactions.

## Main Ideas
1. Introduction to MCP and MCP Servers
2. Functionality offered by various MCP servers
3. Installing and configuring MCP servers for use with Claude Code
4. Setting up remote MCP servers on Windows systems
5. Adding additional MCP servers (e.g., Superbase, Playwright) to a project

## Key Manipulations and Scripting
- To install an MCP server locally: `cloud mcp add <server_name>` followed by any arguments; close command line after running the command (for Windows users).
- To specify the scope of an added MCP server: `scope flag project` before the double dash.
- When adding a server on Windows, use `cmd forward slash c` before the npx command and manually add y flag in arguments array after np.
- For remote servers, use `rd slash c bit` (for Windows) and remove the hyphen y flag from the arguments array.
- To access resources from a remote server: specify the server name, scope flag, and HTTP as the transport system in the command.
- After starting up Cloud Code, use context 7 explicitly and reference the correct CSS file to prevent using legacy code with third-party frameworks or libraries.
- To add memory to a project: use the `hash` command to create a memory with instructions to check updated docs when needed for implementing new libraries or features.
- Adding Playwright server: follow commands from the Playwright MCP page, tweak for Windows, and run using the `clawed` tool; verify connection using the MCP tool.

## Reflective/Quiz Questions
1. What is the purpose of MCP servers in AI models like Claude?
2. Explain how to install and configure a local MCP server for use with Claude Code on Windows systems.
3. How would you add a remote MCP server using HTTP as the transport system, and what steps would you take to prevent using legacy code when creating new code with third-party frameworks or libraries?