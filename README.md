# AdPeekly LinkedIn Ads Library MCP Server (unofficial)

Unofficial, read-only MCP server for LinkedIn's public Ad Library.
Search 253,610 published B2B LinkedIn ads from 636 advertisers, with
the creatives, the targeting on record, and how long each campaign
has actually been running.

**Not affiliated with, endorsed by, or sponsored by LinkedIn or
Microsoft.** Reads LinkedIn's public Ad Library and adds search,
history and structure on top of it.

No LinkedIn login, no OAuth, no ad account. An AdPeekly API key is
the only credential, and the server is read-only: it cannot create,
edit or spend anything.

This repository hosts no server code. AdPeekly runs entirely as a
remote server; there is nothing to install or run locally.

## Connect

- **Endpoint:** `https://spkftjsjduykrvzeuzld.supabase.co/functions/v1/mcp-server`
- **Auth:** `Authorization: Bearer <your AdPeekly API key>`
- **Free key:** https://adpeekly.com/signup-mcp-freemium (3 searches/day)
- **Full docs, tool reference, install steps per client:** https://adpeekly.com/mcp

## Tools

`search_ads`, `get_ad`, `get_ad_images`, `get_brand`, `get_filter_options`,
`list_boards`, `get_board_ads`

## License

Documentation only. See https://adpeekly.com/terms for the service's terms.
