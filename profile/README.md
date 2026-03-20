[![CI](https://img.shields.io/github/actions/workflow/status/navig-run/core/ci.yml?branch=main&style=flat-square&label=CI)](https://github.com/navig-run/core/actions)
[![PyPI](https://img.shields.io/pypi/v/navig?style=flat-square&color=blue)](https://pypi.org/project/navig/)
[![License](https://img.shields.io/badge/license-Apache--2.0-green?style=flat-square)](https://github.com/navig-run/core/blob/main/LICENSE)

# NAVIG

Infrastructure CLI and runtime for remote servers, containers, databases, tunnels, and operator workflows.

Terminal-first. AI-assisted where useful, direct where it counts.

---

## What it does

- **Multi-host SSH management** вЂ” add, switch, test, and operate remote hosts from one command
- **Database operations** вЂ” query, dump, restore MySQL / MariaDB / PostgreSQL without writing connection strings every time
- **Docker control** вЂ” inspect containers, restart services, tail logs, work with compose stacks
- **Remote execution** вЂ” run commands, transfer files, script repeatable operations with safe encoding for complex inputs
- **Web server management** вЂ” test and reload nginx/apache configs without breaking production
- **Encrypted vault** вЂ” store host credentials without leaving secrets in plaintext config files

---

## Quick start

```bash
pip install navig
navig host add
navig host test
navig run "uptime"
```

---

## Links

- [Core repo](https://github.com/navig-run/core)
- [Changelog](https://github.com/navig-run/core/blob/main/CHANGELOG.md)
- [Discussions](https://github.com/navig-run/core/discussions)
- [navig.run](https://navig.run)

---

Built and maintained by [@miztizm](https://github.com/miztizm).
