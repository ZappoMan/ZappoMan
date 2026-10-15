# Brad Hefta-Gaub

I build agent infrastructure and the engineering organizations that use it.

I am a hands-on technical executive, fractional CTO, and strategic advisor with more than 30 years of experience in distributed systems. My current work focuses on agent execution, persistent memory, context engineering, credential delegation, observability, and governed software-delivery workflows.

Through [Artificer Innovations](https://github.com/Artificer-Innovations), I build products and open-source infrastructure for AI agents while helping engineering organizations move from AI-assisted coding to agents working inside production delivery systems.

## Current work

- [Skein](https://www.artificerinnovations.com/products/skein) — Persistent memory infrastructure that gives Claude, Cursor, ChatGPT, and other MCP clients shared context through an OAuth-secured endpoint.
- **AI-enabled engineering organizations** — I help teams introduce specification-driven agent workflows, agent-authored pull requests, human and agent review, automated testing, CI controls, and production observability.
- **Agent security and operations** — My work includes delegated credential access, scoped and revocable grants, secret detection, runtime tracing, and OpenTelemetry integration.
- **Agent engineering teams** — I operate a standing team of agents with individual GitHub identities that work from specifications and ship through the same review, testing, and CI systems as human engineers.

## NanoClaw infrastructure

I maintain eight open-source extension packages for the existing [NanoClaw](https://github.com/nanocoai/nanoclaw) agent runtime. Together, they add stable extension points, observability, administration, communication interfaces, and pluggable execution across local and remote environments.

| Project | What it adds |
| --- | --- |
| [nanoclaw-hosthooks](https://github.com/Artificer-Innovations/nanoclaw-hosthooks) | Stable host and runner extension points without embedding product logic in the core runtime |
| [nanoclaw-agenttrace](https://github.com/Artificer-Innovations/nanoclaw-agenttrace) | Live traces for tool calls, task progress, reasoning summaries, and long-running turns |
| [nanoclaw-adminapi](https://github.com/Artificer-Innovations/nanoclaw-adminapi) | Token-authenticated APIs for creating, inspecting, updating, and restarting agent groups |
| [nanoclaw-webchat](https://github.com/Artificer-Innovations/nanoclaw-webchat) | Local-first multi-agent web chat with shared rooms, direct messages, threads, attachments, authentication, and MCP access |
| [nanoclaw-sessionio](https://github.com/Artificer-Innovations/nanoclaw-sessionio) | Pluggable host-to-agent session transport using filesystem or HTTP mailboxes |
| [nanoclaw-agenthosts](https://github.com/Artificer-Innovations/nanoclaw-agenthosts) | A RuntimeDriver registry for pluggable agent execution environments |
| [nanoclaw-agenthost-process](https://github.com/Artificer-Innovations/nanoclaw-agenthost-process) | Local child-process execution for running agents without Docker |
| [nanoclaw-agenthost-flyio](https://github.com/Artificer-Innovations/nanoclaw-agenthost-flyio) | Remote agent execution on Fly Machines, paired with HTTP session transport |

The runtime and transport abstractions are deliberately separate: an agent can move from Docker to a local process or remote machine without coupling its lifecycle to a shared filesystem.

## Other open-source work

- [BeakerStack](https://github.com/Artificer-Innovations/BeakerStack) — An opinionated Supabase foundation for web and mobile SaaS products, with authentication, billing, shared application code, and pull-request preview environments.
- [ScrambLLMe](https://github.com/Artificer-Innovations/ScrambLLMe) — A meaning-preserving paraphraser with redline review for disrupting statistical text watermarks.
- [AWS Static Site PR Deployment](https://github.com/Artificer-Innovations/aws-static-site-pr-deployment) — An AWS deployment template that gives every pull request an isolated preview environment with automated end-to-end testing.

## Background

Before my current agent-infrastructure work, I:

- Built much of High Fidelity’s real-time streaming server and networking stack, designed its spatial database, and later served as CTO.
- Led the architecture of Revenue Science’s behavioral-targeting platform, which processed more than one billion events per day.
- Helped build RealNetworks’ core client/server streaming platform and later led more than 200 engineers.
- Founded a consumer social platform, served as CTO of three venture-backed companies, and participated in raising more than $100 million.
- Was named as an inventor on nine U.S. patents covering streaming media, adaptive delivery, networking, DRM, advertising systems, distributed computing, spatial audio, and virtual worlds.

## Connect

- [Personal site](https://hefta-gaub.com)
- [LinkedIn](https://www.linkedin.com/in/bradheftagaub)
- [Artificer Innovations](https://artificerinnovations.com)
- [How Many CTOs](https://howmanyctos.com)
