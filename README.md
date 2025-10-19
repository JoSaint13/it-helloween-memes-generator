# SpookMemes AI 🎃👻

> Empowering creators to generate hilarious, instantly shareable Halloween-themed memes with AI-powered design intelligence

[![License](https://img.shields.io/badge/license-MIT-orange.svg)](LICENSE)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)](https://github.com/spookmemes/ai)

## Overview

SpookMemes AI is a cutting-edge Halloween meme generator that leverages AI to transform content creation. By combining intelligent design tools and seasonal creativity, users can quickly craft viral, hilarious Halloween-themed memes with unprecedented ease.

## Features

- ✨ AI-powered meme generation
- 🎃 Halloween-specific theme templates
- 🚀 One-click social media sharing
- 💡 Customizable design intelligence
- 🔒 Secure user authentication

## Tech Stack

**Frontend:**
- React 18
- TypeScript
- Tailwind CSS
- Zustand
- React Router

**Backend:**
- Node.js
- Next.js
- PostgreSQL
- Prisma ORM

**Deployment:**
- Vercel
- Supabase
- Cloudinary

## Quick Start

### Prerequisites

```bash
node >= 18.0.0
npm >= 9.0.0
```

### Installation

```bash
# Clone the repository
git clone https://github.com/spookmemes/ai.git

# Install dependencies
cd spookmemes-ai
npm install

# Set up environment variables
cp .env.example .env
# Edit .env with your configuration

# Run development server
npm run dev
```

Visit `http://localhost:3000` to start creating spooky memes!

## Project Structure

```
/
├── src/
│   ├── components/     # Reusable UI components
│   ├── pages/          # Next.js page routes
│   ├── hooks/          # Custom React hooks
│   ├── lib/            # Utility functions
│   └── styles/         # Tailwind CSS
├── public/             # Static assets
└── tests/              # Test suites
```

## Development

### Available Scripts

```bash
npm run dev         # Start development server
npm run build       # Production build
npm run test        # Run test suite
npm run lint        # Code quality check
```

## Environment Variables

```env
NEXT_PUBLIC_OPENAI_API_KEY=your_openai_key
DATABASE_URL=your_postgres_connection_string
NEXTAUTH_SECRET=your_auth_secret
```

## Testing

```bash
# Run unit tests
npm test

# Run integration tests
npm run test:integration
```

## Deployment

```bash
# Build for production
npm run build

# Deploy to Vercel
vercel --prod
```

## Contributing

Contributions are welcome! Please read our [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

Steps to contribute:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push and open a Pull Request

## License

MIT License - see [LICENSE](LICENSE) for details.

## Support

For support, please [open an issue](https://github.com/spookmemes/ai/issues) or email support@spookmemes.ai.

---

**Crafted with 🎃 by the SpookMemes Team**