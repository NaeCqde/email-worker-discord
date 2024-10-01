# Cloudflare Email Worker(CF Workers)でDiscord Webhookにメール内容を送れるプログラム

互換性フラグはWebからは設定できないので、Wrangler Cliが必須

`wrangler.toml`
```toml
compatibility_flags = ["nodejs_compat"]
DISCORD_WEBHOOK = "https://URL"
```
