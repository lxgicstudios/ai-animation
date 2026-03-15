# ai-animation

[![npm version](https://img.shields.io/npm/v/ai-animation.svg)](https://www.npmjs.com/package/ai-animation)
[![npm downloads](https://img.shields.io/npm/dm/ai-animation.svg)](https://www.npmjs.com/package/ai-animation)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/lxgic-studios/ai-animation)](https://github.com/lxgic-studios/ai-animation/stargazers)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.0+-blue)](https://www.typescriptlang.org/)



Generate CSS and Framer Motion animations from plain English.

## Install

```bash
npm install -g ai-animation
```

## Usage

```bash
npx ai-animation "fade in from left with bounce"
npx ai-animation "pulse glow effect" -f css
npx ai-animation "staggered list entrance" -f framer -o animations.ts
```

## Options

- `-f, --format <format>` - css, framer, or both (default: both)
- `-o, --output <file>` - Write to file

## Setup

```bash
export OPENAI_API_KEY=sk-...
```

## License

MIT


---

Built by [LXGIC Studios](https://github.com/LXGIC-Studios)

🔗 [GitHub](https://github.com/LXGIC-Studios) · [Twitter](https://x.com/lxgicstudios)

💡 Want more free tools like this? We have 100+ on our GitHub: [github.com/lxgicstudios](https://github.com/lxgicstudios)
