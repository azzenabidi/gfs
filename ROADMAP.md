# GFS Roadmap

This roadmap outlines the planned features and milestones for GFS. Dates and features are subject to change based on community feedback and priorities.

---

## Current Development

### 🚧 v0.1.x – Core platform
**Status:** In progress • Latest release: [v0.1.12](https://github.com/Guepard-Corp/gfs/releases)

- ✅ Project foundation and hexagonal architecture
- ✅ MCP (Model Context Protocol) server
- ✅ Storage: APFS (macOS), generic file-based
- ✅ Compute: Docker, Podman
- ✅ Databases: PostgreSQL, MySQL, ClickHouse
- ✅ CLI: `init`, `commit`, `log`, `status`, `export`, `import`, `query`, `schema`
- ✅ Schema extraction and schema diff
- ✅ Skills and AI tools (Cursor, Claude, OpenCode, Qwery)
- ✅ Installer and multi-platform binaries (Linux, macOS, Windows)
- ✅ Telemetry and website
- ✅ Conventional-commit release notes on GitHub

---

## Released Versions

Releases and binaries are published on **[GitHub Releases](https://github.com/Guepard-Corp/gfs/releases)**. The [Changelog](CHANGELOG.md) tracks documented releases.

---

## Upcoming Releases

### 📋 v0.2.0 – More filesystems & Git-like workflows
**Status:** Planned • Target: Q2 2026

- ZFS and Btrfs file system support
- Kubernetes support
- More Git-like commands
- **Merge & Rebase** (RFC 007) – database merge strategies
- **Remote clone** (RFC 008) – clone from remote (RDS, GCP, etc.) and snapshot/proxy workflows

---

## Future Considerations

Beyond v1.0, we're exploring:

- **Hybrid query engine** (RFC 006) – unified querying across storage and compute
- **Custom tiered file system** – object-storage–backed file system
- **AI agents** – deeper integrations with AI coding tools
- **Multi-compute** – multiple computes on different branches
- **Merge & Rebase** – full branch merge and rebase semantics

---

## How to Influence the Roadmap

We value community input. Here’s how you can help shape GFS:

1. **💬 Discuss** – [GitHub Discussions](https://github.com/Guepard-Corp/gfs/discussions)
2. **🎯 Vote** – Upvote [GitHub Issues](https://github.com/Guepard-Corp/gfs/issues)
3. **🐛 Report bugs** – Open issues with steps to reproduce
4. **✨ Request features** – Feature requests with use cases
5. **🤝 Contribute** – Submit PRs
6. **💬 Chat** – [Discord](https://discord.gg/SEdZuJbc5V)

---

## Legend

- ✅ Done / released
- 🚧 In development
- 📋 Planned
- 🎯 Future / exploratory

---

**Note:** This roadmap is a living document. Timelines are estimates and may change.

**Last updated:** March 14, 2026
