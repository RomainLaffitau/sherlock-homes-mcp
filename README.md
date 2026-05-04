# Sherlock Homes MCP Server

[![smithery badge](https://smithery.ai/badge/romainlaffitau/sherlock-homes)](https://smithery.ai/server/romainlaffitau/sherlock-homes)

French real estate data platform for AI agents. Identifies property owners likely to sell and tracks behavioral signals on active listings (price drops, agency changes, withdrawals). Coverage: metropolitan France. Daily updates.

## Quick Start (Claude Desktop)

```json
{
  "mcpServers": {
    "sherlock-homes": {
      "type": "http",
      "url": "https://www.sherlockhomes.pro/api/mcp",
      "headers": {
        "Authorization": "Bearer sk_sherlock_live_YOUR_KEY"
      }
    }
  }
}
