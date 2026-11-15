# RankPulseSEO MCP Server 🚀

Give **Claude Desktop, Cursor, Windsurf, or VS Code** direct access to real-time Google SERP data, top-100 keyword rank tracking, and technical on-page SEO audits.

---

## 🛠️ Included SEO Tools

* **`check_google_serp`** — Fetches live top 10 Google search results, snippets, and *People Also Ask* questions for any keyword and country.
* **`check_keyword_ranking`** — Checks where any domain ranks in the top 100 Google results for a target keyword.
* **`audit_onpage_seo`** — Scrapes any webpage and audits its title tag, meta description, H1/H2 structure, word count, and missing image alt text.
* **`check_robots_and_sitemap`** — Inspects `robots.txt` rules, XML sitemaps, and checks whether AI crawlers (`GPTBot`) are blocked.

---

## 💳 Pricing & Instant API Key

1. **[Starter Plan — $29/month (500 Tool Calls)](https://buy.polar.sh/polar_cl_J0Pj4PtWb5pFzxMmDGJgxd5cTkh6c771BV1hA2JXWh0)**
2. **[Pro Agency Plan — $79/month (2,000 Tool Calls)](https://buy.polar.sh/polar_cl_IVeX5JbvBTW1MeHrbh6VCc34QFRGwKQ0EQUjb1IwTSQ)**

*After checkout, you are automatically redirected to **[rankpulseseo-mcp.vercel.app](https://vercel.app)** where you can enter your email to retrieve your `sk_live_...` API key immediately.*

---

## ⚡ Quick Setup (Claude Desktop / Cursor / VS Code)

Add this configuration to your MCP settings file (`claude_desktop_config.json` or `.cursor/mcp.json`):

```json
{
  "mcpServers": {
    "rankpulseseo": {
      "url": "https://vercel.appmcp",
      "headers": {
        "Authorization": "Bearer YOUR_SK_LIVE_API_KEY"
      }
    }
  }
}
```
.
