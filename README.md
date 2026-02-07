# Ferrumail Core

Open source webmail client built in Rust with [Leptos](https://leptos.dev) — secure, transparent, AI-ready.

## Status

🚧 **Early development** — not yet ready for production use.

Follow the [Kickstarter campaign](https://ferrumail.org) to support the project.

## Features

- **Server-side rendering** with Islands architecture for minimal JavaScript
- **Real IMAP transparency** — breadcrumbs and actions reflect actual server state
- **No attachment previews** — security-first design, explicit downloads only
- **Multi-tab sync** via SSE and BroadcastChannel
- **MCP interfaces** for AI agent integration (planned)


## Requirements

- Rust (stable)
- PostgreSQL ≥ 18

## Building
```bash
# Clone
git clone https://github.com/ferrumail/ferrumail-core
cd ferrumail-core

# Build
cargo build --release

# Run (development)
cargo leptos watch
```

## Configuration

*Documentation coming soon.*

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

[Artistic License 2.0](LICENSE)

## Links

- 🌐 [ferrumail.org](https://ferrumail.org)
- 🏠 [Ferrumail Organization](https://github.com/ferrumail)
- 📖 [Documentation](https://github.com/ferrumail/ferrumail-docs)
