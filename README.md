# World Wild Web MCP Hack Night
Hey, thanks for joining us for WWW AI & MCP Hack Night! In this repo, you'll find everything you need to get started with the Hack Night.

We recommend getting familiar with the challenge before the Hack Night, as it will help you get started faster.

## Prerequisites
- Your own laptop
- Node.js and a JS package manager (npm, yarn, pnpm, bun) installed
- A [Cloudflare account](https://dash.cloudflare.com/sign-up)

## The Challenge
This Hack Night is all about exploration and creativity with [MCP servers](https://modelcontextprotocol.io/docs/getting-started/intro). Build something that excites you—whether it's practical, experimental, or just fun.

### Core Requirements
Your project should use:
1. **[mcp-lite](https://github.com/fiberplane/mcp-lite)**: A web SDK for building MCP servers
2. **[Cloudflare Workers](https://developers.cloudflare.com/workers/)**: A serverless environment to run your MCP server

## Quickstart

1. Use `create mcp-lite` to create an mcp server with a Cloudflare Worker

```sh
# mcp-lite Starter
# Select the Cloudflare template
pnpm create mcp-lite@latest
```

2. Run your server locally
   
```sh
pnpm dev
```

3. Deploy your MCP server

Authenticate Wrangler (first time only)
```sh
pnpx wrangler login
```

```sh
pnpm run deploy
```
To get warmed up with the library, create a tool that returns a fun fact about cats or dogs. 

## Recipes
- [mcp-lite with Cloudflare's Key Value Store](https://github.com/fiberplane/mcp-lite/tree/main/examples/cloudflare-worker-kv)
- [mcp-lite with OpenAI Apps SDK](https://github.com/fiberplane/geojournal)

## Ideas from Previous Hack Nights
- Spotify MCP server to create playlists while coding
- MCP server to store interactions from AI IDE's
- [Screenshift MCP](https://youtu.be/C0NjaRB2HyM)

## MCP Clients
Once you have your MCP server running, you need a client to connect to it for demos. Here are some examples:
- [MCP Inspector](https://modelcontextprotocol.io/docs/tools/inspector)
- [Claude Code](https://docs.claude.com/en/docs/claude-code/overview)
- [Claude Desktop](https://www.anthropic.com/news/claude-desktop) (macOS)
- Your AI IDE of choice (Claude Desktop, Windsurf, Zed-Editor, ... )
- [Cloudflare Agents SDK](https://github.com/cloudflare/agents) as a client

## Submission
Use [this form](https://forms.gle/VY2p1AGgdKDCiwJ57) to submit your project and indicate if you'd like to demo at the end of our Hack Night. Please provide a brief description of your project and any relevant links.
