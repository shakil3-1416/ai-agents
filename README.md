This is a Next.js frontend for showcasing and testing AI automation agents.

## Getting Started

1. Create `.env.local` in the project root:

```bash
OLLAMA_BASE_URL=http://127.0.0.1:11434
OLLAMA_MODEL=llama3.2:3b
AGENT_DEMO_FALLBACK=true
```

`AGENT_DEMO_FALLBACK=true` returns a portfolio-safe simulated response when Ollama is unavailable or returns an error.

2. Install/start Ollama and pull a model:

```bash
ollama serve
ollama pull llama3.2:3b
```

3. Run the development server:

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
