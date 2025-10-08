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
- [Discourse](https://github.com/discourse/discourse) - A platform for community discussion. Free, open, simple. 
  [Link to .yaml](https://raw.githubusercontent.com/oregapam/awesome-coolify-service-templates/refs/heads/main/templates/compose/discourse.yaml)
- [Vaultwarden (Postgres)](https://github.com/dani-garcia/vaultwarden) - Unofficial Bitwarden compatible server written in Rust, formerly known as bitwarden_rs.
  [Link to .yaml](https://raw.githubusercontent.com/oregapam/awesome-coolify-service-templates/refs/heads/main/templates/compose/vaultwarden-pg.yaml)
- [Maxun](https://github.com/getmaxun/maxun) - Open Source No Code Web Data Extraction Platform • Turn Websites To APIs & Spreadsheets With No-Code Robots In Minutes.
  [Link to .yaml](https://raw.githubusercontent.com/oregapam/awesome-coolify-service-templates/refs/heads/main/templates/compose/maxun.yaml)
- [LightRAG](https://github.com/HKUDS/LightRAG) - Simple and Fast Retrieval-Augmented Generation 
  [Link to .yaml (Basic version)](https://raw.githubusercontent.com/oregapam/awesome-coolify-service-templates/refs/heads/main/templates/compose/lightrag-basic.yaml)
  [Link to .yaml (Production version - with Redis, Qdrant and Memgraph)](https://raw.githubusercontent.com/oregapam/awesome-coolify-service-templates/refs/heads/main/templates/compose/lightrag-production.yaml)
- [autobase](https://github.com/vitabaks/autobase) - Automated database platform for PostgreSQL® - Your own DBaaS.
  [Link to .yaml](https://raw.githubusercontent.com/oregapam/awesome-coolify-service-templates/refs/heads/main/templates/compose/autobase.yaml)
- [pgAdmin 4](https://github.com/pgadmin-org/pgadmin4) - pgAdmin is the most popular and feature rich Open Source administration and development platform for PostgreSQL, the most advanced Open Source database in the world.
  [Link to .yaml](https://raw.githubusercontent.com/oregapam/awesome-coolify-service-templates/refs/heads/main/templates/compose/pgadmin.yaml)
- [ChartDB](https://github.com/chartdb/chartdb) - Database diagrams editor that allows you to visualize and design your DB with a single query.
  [Link to .yaml](https://raw.githubusercontent.com/oregapam/awesome-coolify-service-templates/refs/heads/main/templates/compose/chartdb.yaml)
- [Roundcube](https://github.com/roundcube/roundcubemail-docker) - The Roundcube Webmail suite
  [Link to .yaml (SQLite version)](https://raw.githubusercontent.com/oregapam/awesome-coolify-service-templates/refs/heads/main/templates/compose/roundcube-sqlite.yaml)


## How to Use

1. Click on chosen service's `Link to .yaml` link copy the `.yaml` file content.
Optional: Consider the notes (where available within the yaml files)
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

