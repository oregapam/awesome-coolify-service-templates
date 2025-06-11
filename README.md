# awesome-coolify-service-templates

Welcome to my Coolify Service Templates repository! This repo contains Docker Compose templates that can be easily integrated with Coolify.

## Available Templates

Here are the currently available service templates:

- [Planka](https://github.com/plankanban/planka) - The realtime kanban board for workgroups built with React and Redux.
  [Link to .yaml](https://raw.githubusercontent.com/oregapam/awesome-coolify-service-templates/refs/heads/main/templates/compose/planka.yaml)
- [Linkwarden](https://github.com/linkwarden/linkwarden) - Self-hosted collaborative bookmark manager to collect, organize, and preserve webpages, articles, and documents.
  [Link to .yaml](https://raw.githubusercontent.com/oregapam/awesome-coolify-service-templates/refs/heads/main/templates/compose/linkwarden.yaml)
- [PG Back Web](https://github.com/eduardolat/pgbackweb) - 🐘 Effortless PostgreSQL backups with a user-friendly web interface! 🌐💾 
  [Link to .yaml](https://raw.githubusercontent.com/oregapam/awesome-coolify-service-templates/refs/heads/main/templates/compose/pgbackweb.yaml)
- [Crawl4AI](https://github.com/unclecode/crawl4ai) - 🚀🤖 Open-source LLM Friendly Web Crawler & Scraper. 
  [Link to .yaml](https://raw.githubusercontent.com/oregapam/awesome-coolify-service-templates/refs/heads/main/templates/compose/crawl4ai.yaml)
- [Docker Simple CORS Proxy](https://github.com/obeone/simple-cors-proxy) - Simple CORS proxy server for seamless cross-origin requests with TypingMind plugin. Easy setup. 
  [Link to .yaml](https://raw.githubusercontent.com/oregapam/awesome-coolify-service-templates/refs/heads/main/templates/compose/corsproxy.yaml)
- [Pocket ID](https://github.com/pocket-id/pocket-id) - A simple and easy-to-use OIDC provider that allows users to authenticate with their passkeys to your services. 
  [Link to .yaml (PostgreSQL version)](https://raw.githubusercontent.com/oregapam/awesome-coolify-service-templates/refs/heads/main/templates/compose/pocketid-pg.yaml)
  [Link to .yaml (SQLite version)](https://raw.githubusercontent.com/oregapam/awesome-coolify-service-templates/refs/heads/main/templates/compose/pocketid-sqlite.yaml)


## How to Use

1. Click on chosen service's `Link to .yaml` link copy the `.yaml` file content.
2. Open your `Coolify Dashboard` in browser
3. Go to `Projects`
4. Select or create a project
5. Click on `+ Add New Resource`
6. Choose `Docker Compose Empty`
7. Paste the `.yaml` file content and click on `Save`
8. If you need, update the configuration on the next screen at `Service Specific Configuration` section or at the `Environment Variables` sub-menu
9. (Optional) Edit the random generated domain in `Services` section
10. Click on `Deploy` and enjoy :)

---

## Author

This repository is maintained by [@oregapam](https://github.com/oregapam).

