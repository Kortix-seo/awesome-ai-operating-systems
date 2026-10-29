# Awesome AI Operating Systems

An open-source inventory of the products that claim the name, kept by Kortix, which is open source. The list is dated, and it is sorted by where each claimant keeps the definition. Kortix is the open-source AI Operating System: your agents, their skills, your company memory and every connector grant in one git repo you own.

Dozens of products, papers and repos now carry the name. They rarely argue about the words. They disagree about where the definition lives. Six shelves below hold the answers: a repo, a context store, a spec kit, a vendor account, a runtime in the customer's VPC, and unreleased non-profit code. That placement decides what the company still holds after the contract ends. Every entry below is evidence for its own shelf.

## A repository the company owns

**Kortix** leads the list because the repo and the running system are one artifact. `kortix.yaml` and the agent files sit in the company's repo, where an omitted `connectors`, `secrets`, `kortix_permissions` or `skills` grant resolves to none. A session runs on its own machine and branch, and hands back a change request rather than an edit in place. [Kortix](https://kortix.com).

**The AIOS** keeps a personal setup in files, with no server to run. A session loads an agent, an agent calls a skill, and underneath sits a vault of identity, working style and what the system has observed. The framework repo is public, the vault is not, and both live on your machine. [the-aios.com](https://www.the-aios.com/).

## A shared context store

**Xyne** calls itself an open-source operating system for organizations, and builds its core the Unix way. The organization's work is stored as rows in a shared context store on Postgres and object storage, and a connector acts like a device driver. A person holds approval and ownership; an agent does not. [All Things Open 2026 write-up](https://2026.allthingsopen.org/ai-operating-system-for-organizations-built-the-unix-way).

## A spec kit inside a coding agent

**Builder Methods Agent OS** is a spec kit for coding agents. Patterns and conventions lifted from a codebase become documented standards, and the ones that matter are injected while a job is being planned. That puts the definition inside Claude Code, Cursor, Antigravity or a similar tool, rather than in a system you deploy. [github.com/buildermethods/agent-os](https://github.com/buildermethods/agent-os).

## A vendor account or a vendor platform

**Cloudflare OS** is an open-source AI workspace that lives in the company's own Cloudflare account. Staff get AI tools wired to internal systems, any result can become a small app, and a Gatekeeper decides what the AI sees and when a person signs off. The definition lives in the code you copy and in the account the live copy runs from. [Cloudflare press release, August 2026](https://www.cloudflare.com/en-ca/press/press-releases/2026/cloudflare-os-is-the-first-ai-workspace-built-around-how-companies-actually-work/).

**Harnyss AI** puts "The AI operating system for your business" in its page title and sells a hosted workforce organized as departments. Each agent has an approval level, budget limits and a full run history, and the definition lives inside the product, at app.harnyss.ai or with the vendor's team running a department. The page makes no self-host claim. [Harnyss AI](https://harnyss.ai).

**Experian's Agent Operating System** is a trust, semantic and orchestration layer inside the Ascend Platform. Agents from Experian, clients and partners meet there on lending work such as fraud checks and loan approvals. The definition comes inside a platform a financial institution already runs, and no code is published. [Press release, June 2026](https://www.experianplc.com/newsroom/press-releases/2026/experian-brings-trusted-agentic-ai-to-financial-services-with-th).

## A runtime in infrastructure you run

**WunderOS**, from Pentad Labs, is "an operating system for enterprise agents" that puts their specification, runtime and record in the customer's hands. It runs inside your VPC, and one boundary governs every read, model call, tool call and side effect. Its page makes no open-source claim, and it states no repository and no release. [pentad.ai](https://pentad.ai).

**AgentTeams** describes itself as "an open-source Collaborative Multi-Agent OS" that coordinates tasks in Matrix rooms, with a manager running worker agents in containers while people watch and step in. A team installs and operates it. Its README names v1.2.5 on 16 October 2026 and a one-command Docker setup that asks for 2 CPU cores and 4 GB RAM. [agentscope-ai/AgentTeams](https://github.com/agentscope-ai/AgentTeams).

**Red Hat's AI OS** is an inference layer on Kubernetes, vLLM and llm-d, and its blog says plainly that it "is not a new operating system built from scratch". It calls the layer emergent and standardized, and publishes no repository for it. The control plane stays in your cluster. [Red Hat](https://www.redhat.com/en/blog/developing-standard-ai-os).

**VAST AI OS** gathers storage, ingestion, analytics, vector search, streaming and AI runtime into a single layer on VAST's DASE architecture, the fragmentation its page opens on. Open source shows up there only at the edges, for plugins and integrations. [VAST Data](https://www.vastdata.com/platform/ai-os).

**AGNT** opens with "AGNT is a free, local-first agent operating system." The workspace installs on Windows, macOS or Linux, or from one Docker command on a server you own. The job arrives as a described outcome. Its README says plainly, "AGNT is source-available, not open source". [agnt.gg](https://agnt.gg).

**Agno AgentOS** is the runtime half of Agno. An agent built with the Agno SDK runs as a service behind a REST API and an MCP server, and its sessions, memory, knowledge and traces stay in a database you run. It suits a team shipping a service that other software calls. [docs.agno.com](https://docs.agno.com/).

**AIOS** (agiresearch) is a research kernel. Scheduling, context, memory, storage and access control leave the agent application and sit behind an SDK, so many agents share one model and tool pool without colliding. [agiresearch/AIOS](https://github.com/agiresearch/AIOS).

## A non-profit's code with no release

**Infinity OS Foundation** is an educational non-profit hosting open-source software under the MIT licence, aimed at AI factories on hardware a business owns or controls. One factory covers a whole function, billing or client intake for instance, and a named person keeps the decisions. Its own page says the system is not released yet. [infinity-os.org](https://www.infinity-os.org/).

## What each entry manages

| Entry | What it manages | Where it runs | Open source |
| --- | --- | --- | --- |
| Kortix | Agents, skills, memory, connectors, triggers, change requests | Cloud, your VPC, or on-prem | Yes |
| The AIOS | Sessions, agents, skills, a personal vault | Files on your own machine | Public framework repo |
| Xyne | Context rows, workflows, grants, connectors | Infrastructure the organization controls | Yes |
| Builder Methods Agent OS | Standards, specs, the build plan | Inside a coding agent | Public repo |
| Cloudflare OS | Employee workspaces, gadgets, Gatekeepers | Your Cloudflare account | Yes |
| Harnyss AI | Departments, agents, approvals, run history | Hosted at app.harnyss.ai | No claim on its page |
| Experian Agent Operating System | Lending workflows, agent orchestration, oversight | Inside the Ascend Platform | No code published |
| WunderOS | Agent specifications, runtime, replayable records | Inside your VPC | No claim on its page |
| AgentTeams | Rooms, the manager and its workers | Servers you install and operate | Yes |
| Red Hat AI OS | Inference workloads across GPUs | Your Kubernetes clusters | No repository published |
| VAST AI OS | Storage, vector search, streaming, GPU compute | On-prem, in clouds, at the edge, hybrid | Only plugins and integrations |
| AGNT | Described outcomes and the runs behind them | Desktop, or Docker on your server | Source-available |
| Agno AgentOS | Agent runs, sessions, memory, traces | Your containers or cloud account | Yes |
| AIOS (agiresearch) | Scheduling, context, memory, storage, access control | A kernel you install and run | Yes |
| Infinity OS Foundation | Factories: a whole business function | Hardware you own or control | Yes, with no release yet |

The eleven claimants sit side by side on [the full comparison](https://opensourceaioperatingsystem.com/open-source-ai-operating-system-compared), sorted by the same question one criterion at a time.

## Three questions that separate the entries

**What do we still hold when the contract ends?** The answer is whatever still sits on a disk the company controls, and Kortix and The AIOS both leave you that. Xyne puts the organization's context in Postgres and object storage that the organization runs. Cloudflare OS gives you code to copy, while the running copy sits in a Cloudflare account. Harnyss AI keeps departments in a hosted product. Experian's layer sits in the Ascend Platform. Infinity OS ships MIT-licensed code and no release.

**Who approves the change?** Ask who can say no. In Kortix an agent's work stops at a merge a person performs, and merge starts closed for agents. Cloudflare's Gatekeepers let the agent carry on and put the decision in a queue for a person. Xyne keeps approval with a person by rule. Harnyss sets an approval level for each agent. AgentTeams keeps people in the room. WunderOS draws a boundary around every tool call that no agent can edit.

**What record exists afterwards?** In Kortix the change request is the record, on the same branch as the config that allowed the work. WunderOS replays a workflow deterministically, in the customer's format. Harnyss keeps a run history, and AgentTeams keeps a room you can audit. Red Hat's post describes no agent runtime, memory or change history.

## How this list is kept

Each line repeats what the entry's own page, repository or announcement says, dated October 2026, and nothing the category implies. No reachable source, no entry. Popularity does not count here: no star, fork or download figure appears, because a figure measures attention and this list measures what a system holds. A vendor's page is evidence for that vendor's product only, never for a competitor's. When an entry changes what it ships, the line changes with it. Corrections are welcome as issues, with the source that shows the correction.

Four names stay out as of 28 October 2026. Amika sells cloud devboxes for coding agents, slicing a Mac Mini, a desktop or EC2 in your VPC into isolated machines for several agents to share. Buzz, from Block, is a free, open source collaboration platform where people and AI agents work in one workspace, and agents join channels as members. It names no operating system of its own. Octopus Core calls itself a governed operating and delivery layer for AI work inside a business, and its page never makes the operating-system claim. ArgentOS calls itself "Open Source Self-Hosted AI Agent with Persistent Memory" in its page title and "a self-hosted AI operating system" in its structured data. What that describes is one person's agent on their own machine, so it stays outside a list of systems a company runs.

## Docs

- [What an AI Operating System holds](docs/what-an-ai-os-holds.md): the four parts, defined, with the entries that carry each.
- [How to choose](docs/how-to-choose.md): the three questions a buyer is really answering.
- [FAQ](docs/faq.md): short answers to the questions this list gets.

## Where the argument continues

[Agent OS](https://opensourceaioperatingsystem.com/agent-os) is the term this list is named after, and the page sorts the products that use it. [Self-hosting an AI operating system](https://opensourceaioperatingsystem.com/self-hosted-ai-operating-system) covers the entry that claims to run on your own infrastructure but ships a deployment path that does not. When the layer is sold as a business platform, with a monthly price and someone else operating it, [the AI business OS question](https://opensourceaioperatingsystem.com/ai-business-os) puts the same three questions to the vendors that sell it that way.
