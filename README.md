# Agentokratia Documentation

Official documentation for Agentokratia products.

**Live docs:** [docs.agentokratia.com](https://docs.agentokratia.com)

## Products

| Product | Description | Status |
|---------|-------------|--------|
| [x402 Facilitator](./x402) | Payment verification and settlement for x402 protocol | Live |
| [Agent Marketplace](./marketplace) | Deploy, discover, and monetize AI agents | Coming Soon |

## Development

### Prerequisites

- Node.js 18+
- [Mintlify CLI](https://www.npmjs.com/package/mintlify)

### Run locally

```bash
npx mintlify dev
```

Docs will be available at `http://localhost:3000`

### Project structure

```
├── mint.json           # Mintlify configuration
├── x402/               # x402 Facilitator docs
│   ├── introduction.mdx
│   ├── quickstart.mdx
│   ├── api-reference/
│   ├── concepts/
│   └── integration/
├── marketplace/        # Agent Marketplace docs
│   └── introduction.mdx
└── images/             # Logos and assets
```

## Contributing

Contributions are welcome! Please:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## License

[MIT](./LICENSE)
