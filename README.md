# steam mcp

Steam store search, prices and discounts, app details, and game news.
Uses Steam's keyless store + news endpoints.

## Tools

- `search_games`, store search with current prices / discount percentages
- `get_game_details`, price, release date, developers, genres, Metacritic, blurb
- `get_game_news`, recent Steam news posts for a game

## Run

```bash
npm install && npm run build && node dist/index.js
```

## Example

> "What's Helldivers 2 cost and is it on sale?"
> `search_games("helldivers")` → `get_game_details(553850)`

> "What's new for Cyberpunk?"
> `get_game_news(1091500)`
