# Shopify Dev MCP - Gemini CLI Extension

This extension connects the Gemini CLI to the Shopify Dev MCP server, giving Gemini access to Shopify's dev docs, API schemas, and development guidance. Ask questions and build on top of  Shopify APIs without leaving your terminal.

**What you get:**

- Search Shopify docs and API schemas on the fly
- Generate code for GraphQL Admin API, Storefront API, Functions, Liquid, and more
- Validate components, GraphQL, and theme files to ensure they're free of hallucinations
- Build Shopify apps faster with context-aware assistance

## Requirements

* [Gemini CLI](https://google-gemini.github.io/gemini-cli/#-installation)
* Node.js 18+

## Installation

```bash
gemini extensions install https://github.com/shopify/dev-mcp-gemini-cli
```

We also recommend [installing the Shopify CLI](https://shopify.dev/docs/api/shopify-cli#installation) to make it easier to build and test your app.

## Usage

Once installed, you can give Gemini questions and tasks like:

- "Create a validation Function requiring minimum 5 items in cart before checkout."
- "How do I create a product using the Admin API?"
- "Show me an example of a webhook subscription."
- "What fields are available on the Order object?"

The MCP server automatically searches Shopify's documentation to provide accurate responses.

## Resources

- [Shopify Dev MCP documentation](https://shopify.dev/docs/apps/build/devmcp)
- [Get started with Shopify apps](https://shopify.dev/docs/apps/getting-started)
- [Scaffold a Shopify app](https://shopify.dev/docs/apps/build/scaffold-app)