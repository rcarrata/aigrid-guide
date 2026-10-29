# AI Grid Guide

What AI Grid is, which components it is made of, and how an inference request travels across a multi-cluster grid.

**Documentation:** https://rcarrata.github.io/aigrid-guide/

> **Note:** This is a community companion guide, not official Red Hat OpenShift AI documentation and not a replacement for it. The architecture described here comes from the public upstream project documentation ([Praxis Grid](https://praxis.fast/grid/v0.2.2/architecture/overview/) and [Praxis](https://praxis.fast/praxis/v0.7.2/architecture/overview/)) and from publicly shareable material. It contains no roadmap and no forward-looking statements.

## Scope

This first iteration covers the architecture phase only. Installation, configuration and verification phases are not written yet.

| Page | Description |
|------|-------------|
| [What is AI Grid](https://rcarrata.github.io/aigrid-guide/modules/main/01-what-is-ai-grid.html) | Definition, the problem it solves, personas, end-to-end flow, tenancy model |
| [Architecture Overview](https://rcarrata.github.io/aigrid-guide/modules/main/02-architecture.html) | Control plane versus data plane, the layered stack, hub and spoke, deployment topologies |
| [Components](https://rcarrata.github.io/aigrid-guide/modules/main/03-components.html) | Components and custom resources, routing overlay lifecycle, scoring |
| [Request Flow](https://rcarrata.github.io/aigrid-guide/modules/main/04-request-flow.html) | Step by step request path, the two gateway pipelines, credential rules |
| [Interactive Topology](https://rcarrata.github.io/aigrid-guide/modules/main/05-topology-diagram.html) | Clickable multi-cluster topology diagram |

## Credits

The interactive topology diagram was created by **Mario Vazquez** and is reused here with credit. The only change from his original is the datacenter name, replaced by a fictional one so it can be published publicly.

## Build locally

```bash
npm install
npx antora generate site.yml
# open www/index.html
```
