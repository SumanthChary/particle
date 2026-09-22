# particle ✨

A lightweight web application generated with Google AI Studio, built on Vite, TypeScript, and the Gemini API.

---

## Overview

**particle** brings interactive AI capabilities to the browser using the Google Gemini API. Built as a fast, single-page web app, it features a responsive UI with styled HTML, TypeScript components, and real-time media handling.

---

## Tech Stack

* **Frontend Framework:** TypeScript + HTML5
* **Build Tool:** [Vite](https://vitejs.dev/)
* **AI Model:** [Google Gemini API](https://ai.google.dev/)
* **Configuration:** Node environment with ES module support

---

## Getting Started

### Prerequisites

* [Node.js](https://nodejs.org/) (v18 or higher recommended)
* A [Google Gemini API Key](https://aistudio.google.com/app/apikey)

### Installation

1. **Clone the repository**
   ```bash
   git clone [https://github.com/SumanthChary/particle.git](https://github.com/SumanthChary/particle.git)
   cd particle

```

2. **Install dependencies**
```bash
npm install

```


3. **Configure Environment Variables**
Create a `.env.local` file in the root directory (you can use `.env.example` as a template):
```bash
cp .env.example .env.local

```


Open `.env.local` and add your Gemini API key:
```env
GEMINI_API_KEY=your_api_key_here

```


4. **Run the development server**
```bash
npm run dev

```


Open your browser and navigate to `http://localhost:5173` (or the port indicated in your terminal).

---

## Scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Starts the Vite development server with HMR |
| `npm run build` | Compiles TypeScript and builds production assets |
| `npm run preview` | Previews the local production build |

---

## Project Structure

```text
particle/
├── src/             # Application source code (TypeScript components & logic)
├── .env.example     # Template for environment variables
├── index.html       # Entry HTML document
├── metadata.json    # Application metadata configuration
├── package.json     # Project dependencies and npm scripts
├── tsconfig.json    # TypeScript compiler settings
└── vite.config.ts   # Vite bundler configuration

```

---

## License

Distributed under the MIT License. See `LICENSE` for more information.

```

```
