# Alex Castillo González

**Applied AI engineer** · LLM integrations and agent systems · Python, TypeScript, Go · Remote (UTC−4) · **Available immediately**

I fix the part of AI applications that breaks when LLM providers change: streamed tool calls, token and cost accounting, retired models and parameters that models now reject. Since August 2026 maintainers have merged **1,737 of my pull requests across 405 repositories** (310 of them in projects with more than 10k★, median time to merge about a day), including Microsoft's semantic-kernel, ByteDance's deer-flow, LiteLLM, MLflow, ragflow, Redis, Sentry, Temporal, PostHog, Pydantic's Logfire and deepset's Haystack.

I get there with a multi-agent pipeline that I designed and run: scouts find bugs users actually hit, fixers reproduce and fix them with a failing-first test, and an independent reviewer re-runs the test before anything is published. AI involvement is disclosed in every PR, and projects whose policy rejects AI-assisted contributions are skipped.

## What to look at first

| Project | What it is |
|---|---|
| [llm-drift-lint](https://github.com/pcbeingused333/llm-drift-lint) | Linter for LLM API calls that break when providers change. Every rule comes from a bug fixed upstream, with the PR linked. |
| [tanda](https://github.com/pcbeingused333/tanda) | The public version of the pipeline: a fleet of coding agents around one queue, with a review gate and a local dashboard. |
| [async-parity](https://github.com/pcbeingused333/async-parity) | Finds sync/async method pairs where a fix landed on one side only. |
| [ragcite](https://github.com/pcbeingused333/ragcite) | Deterministic evals for RAG and tool-using agents: retrieval metrics and citation checks. |
| [mcp-business-agent](https://github.com/pcbeingused333/mcp-business-agent) | MCP server exposing a small business's operations (catalog, booking, stock) to an agent. |
| [llm-integration-bench](https://github.com/pcbeingused333/llm-integration-bench) | A benchmark of 625 runnable instances built from LLM-integration bug fixes that maintainers merged (v0.1; no model evaluated on it yet). |

## Selected merged pull requests

- [BerriAI/litellm#47794](https://github.com/BerriAI/litellm/pull/47794): emit streamed tool calls from Cohere v2 chunks
- [bytedance/deer-flow#7677](https://github.com/bytedance/deer-flow/pull/7677): keep an MCP tool argument named `runtime` out of LangGraph's runtime injection
- [infiniflow/ragflow#21651](https://github.com/infiniflow/ragflow/pull/21651): drop Claude sampling parameters the model rejects
- [mlflow/mlflow#26973](https://github.com/mlflow/mlflow/pull/26973): keep tool calls and finish_reason in streamed OpenAI chat traces
- [danielmiessler/Fabric#2288](https://github.com/danielmiessler/fabric/pull/2288): lock out a client after repeated wrong API keys
- [tailscale/tailscale#22118](https://github.com/tailscale/tailscale/pull/22118): fix redirect for nested directories in `serve`

Full breakdown by company and project size: [portfolio](https://portfolio-alexgonzalez33.vercel.app/).

## Contact

[LinkedIn](https://www.linkedin.com/in/alexcastillogonzalez) · [Portfolio](https://portfolio-alexgonzalez33.vercel.app/)

Open to remote full-time or contract work (Python, TypeScript, Go and others).
