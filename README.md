# Awesome-Third-Party-Custodian-In-Crypto

# Top Web Hosting Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Static Site Deployment, Full-Stack Application Hosting & Infrastructure Management*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Web Hosting**. These tools help developers deploy websites and applications to production — handling builds, domains, SSL certificates, and scaling — without managing low-level server infrastructure manually.

**Examples** include Vercel, Netlify, AWS Amplify, Cloudflare Pages, Render, Railway, Fly.io, Heroku, DigitalOcean App Platform, and Kinsta (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom deployment workflows, and transparent infrastructure — ideal for developers seeking data sovereignty, teams avoiding platform lock-in, and organizations building on their own hardware.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Vercel](https://vercel.com/)**  
  Frontend cloud platform optimized for Next.js with edge functions, ISR, preview deployments, and global CDN.

- **[Netlify](https://www.netlify.com/)**  
  Static site and full-stack hosting with serverless functions, edge handlers, form handling, and Git-based deployments.

- **[AWS Amplify](https://aws.amazon.com/amplify/)**  
  Full-stack hosting and deployment platform supporting React, Vue, Angular, and Next.js with CI/CD and AWS integration.

- **[Cloudflare Pages](https://pages.cloudflare.com/)**  
  Edge hosting platform for static and SSR frameworks with Workers integration and global distribution.

- **[Render](https://render.com/)**  
  Unified cloud platform for deploying web frameworks, databases, and background workers with automatic SSL and previews.

- **[Railway](https://railway.app/)**  
  Infrastructure platform for deploying applications, databases, and services with instant provisioning and usage-based pricing.

- **[Fly.io](https://fly.io/)**  
  Edge deployment platform for full-stack frameworks with global distribution and micro-VMs.

- **[Heroku](https://www.heroku.com/)**  
  Classic PaaS for deploying applications with git-push workflow, add-ons, and managed infrastructure.

- **[DigitalOcean App Platform](https://www.digitalocean.com/products/app-platform)**  
  Managed platform for building, deploying, and scaling apps with Git-based deployments and predictable pricing.

- **[Kinsta](https://kinsta.com/)**  
  Managed WordPress hosting and application hosting platform with Google Cloud infrastructure and premium support.

## Open-Source GitHub Projects

- **[Coolify](https://github.com/coollabsio/coolify)**  
  Leading open-source, self-hostable PaaS alternative to Vercel, Heroku, and Netlify. Deploy static sites, databases, full-stack applications, and 280+ one-click services on your own servers. Features Git integration (GitHub, GitLab, Bitbucket, Gitea), automatic SSL via Let's Encrypt, preview deployments per pull request, built-in database backups to S3, Docker Swarm multi-server support, real-time terminal, webhooks, REST API, and monitoring alerts via Discord/Telegram/email. Apache 2.0 licensed, 62,000+ GitHub stars.

- **[Dokku](https://github.com/dokku/dokku)**  
  The closest open-source Heroku alternative, Docker-powered and CLI-first. Supports Herokuish and Cloud Native Buildpacks, Procfile process types, and official Postgres and Redis plugins. Single-server by design with `git push dokku` workflow. MIT licensed, 32,000+ GitHub stars.

- **[Dokploy](https://github.com/Dokploy/dokploy)**  
  Open-source alternative to Vercel, Netlify, and Heroku with a modern web UI. Docker and Compose based with app templates, scheduled database backups to S3-compatible storage, and multi-node support. 37,000+ GitHub stars.

- **[CapRover](https://github.com/caprover/caprover)**  
  Scalable PaaS built on Docker Swarm with nginx, Let's Encrypt, and NetData. One-click apps and databases, mature and stable. Web UI with CLI support. 15,000+ GitHub stars.

- **[Kamal](https://github.com/basecamp/kamal)**  
  CLI deployment tool from 37signals for containerized apps over SSH. No dashboard, no control plane — just Docker images and repeatable deployments. When 37signals moved key apps off the cloud, DHH reported cutting the annual bill from $3.2M to $1.3M.

- **[Kubero](https://github.com/kubero-dev/kubero)**  
  Free and self-hosted PaaS alternative to Heroku, Netlify, Coolify, Vercel, and Dokku running on Kubernetes. GitOps-based with template catalog. 4,400+ GitHub stars.

- **[Piku](https://github.com/piku/piku)**  
  The tiniest PaaS you've ever seen — `git push` deployments to your own servers. 6,600+ GitHub stars.

- **[SwiftWave](https://github.com/swiftwave-org/swiftwave)**  
  Self-hosted, lightweight PaaS for deploying and managing applications on any server. Open-source alternative to Heroku, Netlify, and Render. Compatible with AMD64, ARM64, and ARMv7 architectures across Debian/Ubuntu/Fedora/CentOS.

- **[Tsuru](https://github.com/tsuru/tsuru)**  
  Open-source and extensible Platform as a Service (PaaS) for deploying applications across multiple clusters.

- **[Taubyte](https://github.com/taubyte/tau)**  
  Open-source distributed Platform as a Service (PaaS). Self-hosted Vercel/Netlify/Cloudflare alternative.

- **[PageKit](https://pypi.org/project/pagekit/)**  
  High-performance web server serving content directly from Git repositories or local directories. Markdown-to-HTML conversion, Jinja2 templating, frontmatter support. Operates in Repo Mode (GitHub Pages-like), Local Mode, or Platform Mode (multi-tenant SaaS). Python/FastAPI based.

- **[git-pages](https://pkg.go.dev/codeberg.org/git-pages/git-pages)**  
  GitHub Pages-like static site hosting from Git repositories, with DNS-based authorization, Netlify `_redirects` and `_headers` file support, and incremental updates via archives.

- **[Creek](https://www.npmjs.com/package/@solcreek/cli)**  
  Open-source, Cloudflare-native alternative to Vercel. Deploy to the edge in seconds with `npx creek deploy`. No account required for sandbox deploys. Auto-detects Next.js, Vite, Astro, SvelteKit, Nuxt, and more. Built on Workers for Platforms.

### Additional Strong Open-Source Options

- **[CyberPanel](https://github.com/usmannasir/cyberpanel)** — Hosting control panel for OpenLiteSpeed with support for WordPress, email, DNS, and SSL. 1,600+ GitHub stars.
- **[HestiaCP](https://github.com/hestiacp/hestiacp)** — Open-source hosting control panel for Ubuntu and Debian with web server, mail, DNS, and database management.
- **[CloudPanel](https://github.com/cloudpanel-io/cloudpanel-ce)** — Free hosting control panel for Ubuntu and Debian, optimized for PHP, Node.js, and static sites.
- **Webmin/Virtualmin** — Comprehensive web-based system administration tools for Linux servers.
- **ISPConfig** — Open-source hosting control panel for managing multiple servers and websites.
- **[ServerKit](https://github.com/topics/hosting-control-panel)** — Lightweight, modern server control panel for managing web applications, databases, and services on VPS or dedicated servers. Python/Flask and React.

**Frameworks for building custom systems**: Combine **Coolify** for a polished self-hosted PaaS with UI, **Dokku** for minimal CLI-driven Heroku-style deployments, **Dokploy** for Compose-based multi-node hosting, **CapRover** for Docker Swarm one-click apps, and **Kamal** for the smallest-possible deployment footprint to build a complete self-hosted web hosting stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Web hosting tools must comply with data protection regulations (GDPR, CCPA), industry standards (SOC 2), and content policies.
- Self-hosted open-source solutions require proper security hardening, backup strategies, and ongoing server maintenance. You become the on-call operator for OS updates, TLS, databases, and scaling.

---

**Made for developers, platform engineers, DevOps teams, and organizations building self-hosted web hosting platforms.**  
Let's make web hosting more open, data-sovereign, and developer-friendly.
