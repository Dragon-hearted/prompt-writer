<div align="center">

![PromptWriter](images/hero.svg)

### Centralized prompt engineering knowledge system with per-model guides, visual direction references, and a model registry for AI image, video, and voice generation — the single authority for prompt writing across all Adcelerate systems

![Status](https://img.shields.io/badge/Status-active-brightgreen)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Bun](https://img.shields.io/badge/Bun-Runtime-f9f1e1?logo=bun&logoColor=000)](https://bun.sh/)

</div>

---

## 📑 Table of Contents

- [✨ Features](#features)
- [🏗 Architecture](#architecture)
- [🛠 Tech Stack](#tech-stack)
- [🚀 Getting Started](#getting-started)
- [💻 Development](#development)
- [📂 Project Structure](#project-structure)
- [🤝 Contributing](#contributing)
- [📄 License](#license)

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| **prompt-generation** | Core task type |
| **model-selection** | Core task type |
| **prompt-optimization** | Core task type |
| **model-registry** | Core task type |
| **generation-request Input** | Supported input type |
| **scene-context Input** | Supported input type |
| **style-anchor Input** | Supported input type |
| **model-name Input** | Supported input type |
| **optimized-prompt Output** | Supported output type |
| **model-recommendation Output** | Supported output type |
| **prompt-validation Output** | Supported output type |

---

## 🏗 Architecture

![Pipeline](images/pipeline.svg)

PromptWriter processes data through a multi-stage pipeline.

---

## 🛠 Tech Stack

### Backend

| Technology | Purpose |
|------------|---------|
| **TypeScript 5.7** | Type safety |
| **Bun** | JavaScript runtime & package manager |
| **Js-yaml 4** | YAML parsing |

---

## 🚀 Getting Started

### Prerequisites

- [**Bun**](https://bun.sh/) v1.0+ — `curl -fsSL https://bun.sh/install | bash`

### Install

```bash
cd systems/prompt-writer
bun install
```

### Run

```bash
bun run systems/prompt-writer/src/cli.ts
```

---

## 💻 Development

| Command | Description |
|---------|-------------|
| `bun run dev` | Start development mode |
| `bun run build` | Build for production |
| `bun test` | Run tests |
| `bun run lint` | Check code quality |

---

## 📂 Project Structure

```
prompt-writer/
├── biome.json
├── justfile
├── knowledge
│   ├── acceptance-criteria.md
│   ├── dependencies.md
│   ├── domain.md
│   ├── history.md
│   ├── index.md
│   ├── models
│   │   ├── _registry.md
│   │   └── _schema.md
│   ├── scope.md
│   └── visual-direction
│       ├── composition.md
│       ├── lighting.md
│       └── shot-types.md
├── logs
│   └── d20ea92b-1187-4d32-8d58-aacfbcc3a49f
│       ├── post_tool_use.json
│       └── pre_tool_use.json
├── package.json
├── src
│   ├── cli.ts
│   ├── index.ts
│   └── registry.ts
└── tsconfig.json
```

---

## 🤝 Contributing

Contributions are welcome! Here's how to get started:

1. Fork the repository
2. Create a feature branch: `git checkout -b feat/my-feature`
3. Make your changes and ensure tests pass
4. Commit your changes and open a pull request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">

**Built with** 🧡 **using Bun, TypeScript**

</div>
