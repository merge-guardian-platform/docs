# Merge Guardian AI Documentation

This repository contains the official documentation for **Merge Guardian AI**, powered by [Mintlify](https://mintlify.com).

## Live Documentation

Visit the official documentation at: [docs.merge-guardian.ai](https://docs.merge-guardian.ai) (or your Mintlify URL).

## Local Development

To preview the documentation locally, you'll need the Mintlify CLI.

### Prerequisites

- [Node.js](https://nodejs.org/) (Version 18 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

Install the Mintlify CLI globally:

```bash
npm install -g mintlify
```

### Running Locally

1. Clone this repository:
   ```bash
   git clone https://github.com/merge-guardian-platform/merge-guardian-docs.git
   ```
2. Navigate to the directory:
   ```bash
   cd merge-guardian-docs
   ```
3. Start the development server:
   ```bash
   mintlify dev
   ```

The documentation will be available at `http://localhost:3000`.

## Structure

- `mint.json`: Configuration file for the documentation (navigation, theme, etc.).
- `introduction.mdx`: Project overview.
- `quickstart.mdx`: Installation and setup guide.
- `essentials/`: Core concepts like risk scoring and hotspot detection.
- `deployment/`: Guides for GitHub Actions and CLI setup.
- `reference/`: Detailed CLI command reference.

## Contributing

We welcome contributions to improve our documentation!

1. Fork the repository.
2. Create a new branch: `git checkout -b docs/your-improvement`.
3. Make your changes and preview them with `mintlify dev`.
4. Commit and push your changes.
5. Open a Pull Request.

## License

This documentation is licensed under the [Apache License 2.0](LICENSE).
