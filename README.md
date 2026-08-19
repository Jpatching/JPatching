# Josh Patching

**Software & Deployment Engineer** — Distributed Systems, Linux Infrastructure, Messaging (RabbitMQ), and Developer Tooling.

Software and deployment engineer specializing in Linux systems, reliable event-driven messaging architectures (RabbitMQ), and automated ETL pipelines across distributed multi-node server estates. Background in enterprise technical solutions, with a strong engineering focus on system reliability, fault-tolerant pipelines, and developer tooling.

---

## Featured Projects

### [rabbitmq-patterns-cookbook](https://github.com/Jpatching/rabbitmq-patterns-cookbook)
Comprehensive reference implementation of **14 enterprise messaging patterns** in Python & AMQP:
- **Resilience**: Dead Letter Exchanges (DLQ), TTL-based Exponential Backoff Retries, and Competing Consumers.
- **Reliability**: Publisher Confirms, Channel Tracking, Broker Health Monitoring, Priority Queues, and RPC.
- **Zero-Config Local Setup**: Standalone `docker-compose` environment for immediate testing and simulation.

### [mcp-outlook](https://github.com/Jpatching/mcp-outlook)
A local-first **Model Context Protocol (MCP)** server connecting Claude Code, Claude Desktop, and Antigravity (AGY) to Microsoft 365 Outlook:
- Built with Python and Windows MAPI COM — requires **zero cloud API tokens, OAuth applications, or Azure tenant admin permissions**.
- **Human-in-the-Loop by Design**: Automatically creates drafts in the Outlook Drafts folder for user review; avoids automated blind sends.
- Exposes tools for inbox searching, email drafting, calendar querying, and meeting scheduling directly through the local Outlook client.

### [automated-data-pipeline](https://github.com/Jpatching/weekly-tesco-report) *(Case Study)*
Automated enterprise ingestion and segmentation pipeline:
- Ingests daily master data feeds from cloud object storage (Azure Blob).
- Implements multi-tier operational validation, data reconciliation, and policy segmentation.
- Programmatically formats and distributes multi-tab styled reporting deliverables (`openpyxl`).

### [cv-benchmark-tooling](https://github.com/Jpatching/StoreWalk-Benchmark) *(Tooling)*
Computer Vision evaluation and benchmarking tool:
- Automatically extracts timestamped frame stills and target bounding crops from video streams.
- Programmatically compiles comparative accuracy evaluation decks (`python-pptx`) for stakeholder benchmarking.

### [dotfiles & dev-environment](https://github.com/Jpatching/dotfiles)
Idempotent dev environment bootstrapper for Ubuntu & WSL2:
- Automated setup for Neovim (LazyVim), Zsh, Starship prompt, Delta git pager, Atuin history sync, and Tmux session persistence.

---

## Technical Focus & Day-to-Day

- **Linux Systems Administration**: Maintaining and configuring distributed Linux production servers; proactive monitoring and escalation.
- **Message Broker Architecture**: Designing RabbitMQ exchanges, routing keys, queues, DLQs, and event schemas connecting distributed edge devices to core processing services.
- **Automation & Scripting**: Building automated ETL pipelines, database migration rollback safety scripts, and diagnostic socket listeners in Python and Bash.

Some other repos here are private or unlisted due to client/licensing constraints from past work — happy to talk through any of it.

---

**Contact:** patchingjoshua@gmail.com · [LinkedIn](https://uk.linkedin.com/in/joshua-patching-567b95210)
