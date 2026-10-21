## Marcio Mastrocola Alcantara

Software architect. I put AI into production on backends that can't fail: event-driven systems, data platforms, and LLM agents with the guardrails, budgets and audit trails that regulated businesses require.

Twenty years of software that can't stop — embedded vehicle tracking, ERPs through fiscal certification, the core system of a credit cooperative, and most recently the migration of a fintech backend from a synchronous monolith to event-driven microservices: process time down about 50%, feature lead time from four sprints to two.

### Built in public at [mastrocola-dev](https://github.com/mastrocola-dev)

A production platform on Azure with every decision recorded. Ask [mastrocola.dev](https://mastrocola.dev) how it is built: an AI agent answers from the architecture records and cites the ones it used.

| | |
| [service-agent](https://github.com/mastrocola-dev/service-agent) | LLM agent host — own control loop, tool allowlists over MCP, structured output, token and time budgets, traces |
| [service-api](https://github.com/mastrocola-dev/service-api) | Queue-based job API in front of the agent — per-visitor quotas, daily spend cap, bot challenge |
| [infra](https://github.com/mastrocola-dev/infra) | Terraform on Azure and Cloudflare; zero secrets in GitHub, one workload identity per repository over OIDC |
| [docs](https://github.com/mastrocola-dev/docs) | Architecture decision records and runbooks written from real incidents |
| [mcp-docs](https://github.com/mastrocola-dev/mcp-docs) | MCP server exposing the docs to agents, reachable only with an Entra token |

**Building next:** an AI-native household finance ledger, used every day by its two real users. Claude reads and writes it through an MCP connector over OAuth, every change is audited, and imported bank statements are reconciled by rules first and by an agent second, with a person confirming what the agent suggests.

TypeScript and Node.js, Python · Azure, AWS, Terraform · RabbitMQ, Kafka, Service Bus · SQL Server, PostgreSQL · Airflow · Anthropic API, Model Context Protocol

Open to software architect and tech lead roles.
[marcio@mastrocola.dev](mailto:marcio@mastrocola.dev) · [LinkedIn](https://www.linkedin.com/in/marcio-mastrocola) · [mastrocola.dev](https://mastrocola.dev)
