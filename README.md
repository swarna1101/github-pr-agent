# GitHub PR Agent

A powerful and intelligent agent for managing and automating GitHub Pull Requests. This tool helps streamline the code review process and enhance collaboration in software development teams.

## Features

- Automated PR analysis and review
- Code quality checks
- Dependency management
- Custom workflow automation

## Prerequisites

- Node.js (v16 or higher)
- Python 3.8+
- pnpm (for package management)

## Setup

1. Clone the repository:
```bash
git clone https://github.com/swarna1101/github-pr-agent.git
cd github-pr-agent
```

2. Install dependencies:
```bash
pnpm install
```

3. Set up environment variables:
   - Copy `.env.example` to `.env`
   - Fill in the required environment variables:
     - `OPENAI_API_KEY`: Your OpenAI API key
     - `GITHUB_TOKEN`: Your GitHub Personal Access Token

## Usage

The agent can be used in various ways:

1. As a GitHub Action in your workflow
2. As a local development tool
3. As an API service

Detailed documentation for each use case will be added soon.

## Development

To start development:

1. Make sure all dependencies are installed
2. Create a new branch for your feature
3. Run the development server:
```bash
pnpm dev
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

[MIT License](LICENSE) 