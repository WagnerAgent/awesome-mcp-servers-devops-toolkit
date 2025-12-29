# Awesome MCP Servers for DevOps [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of Model Context Protocol servers for DevOps workflows — infrastructure, CI/CD, monitoring, security, and cloud operations.

**Curated by [Wagner](https://www.trywagner.dev)** — The first AI DevOps teammate

## Contents

- [Source Control](#-source-control)
- [Infrastructure as Code](#%EF%B8%8F-infrastructure-as-code)
- [Kubernetes and Containers](#%EF%B8%8F-kubernetes-and-containers)
- [CI/CD](#-cicd)
- [Cloud Platforms](#%EF%B8%8F-cloud-platforms)
- [Observability](#-observability)
- [Security](#-security)
- [Collaboration](#-collaboration)
- [Getting Started](#-getting-started)

## 🔀 Source Control

### GitHub

The official GitHub MCP server — battle-tested and feature-complete.

| | |
|---|---|
| **Repo** | [github/github-mcp-server](https://github.com/github/github-mcp-server) |
| **Maintainer** | 🏷️ GitHub (Official) |
| **What it does** | Repository operations, issues, PRs, code search, GitHub Actions workflows. |
| **Standout feature** | 🛡️ Lockdown mode for public repos to prevent prompt injection. |

### GitLab

Native GitLab integration via their Duo platform.

| | |
|---|---|
| **Docs** | [GitLab MCP Server Documentation](https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/) |
| **Maintainer** | 🏷️ GitLab (Official) |
| **What it does** | Issues, merge requests, pipelines, commits, cross-project search. |
| **Note** | ⚠️ Requires GitLab 18.6+ for HTTP transport. |

### Azure DevOps

| | |
|---|---|
| **Repo** | [tiberriver256/azure-devops-mcp-server](https://github.com/tiberriver256/azure-devops-mcp-server) |
| **Maintainer** | 👥 Community |
| **What it does** | Repos, work items, pipelines, boards. |

## 🏗️ Infrastructure as Code

### Terraform

HashiCorp's official MCP server for Terraform workflows.

| | |
|---|---|
| **Repo** | [hashicorp/terraform-mcp-server](https://github.com/hashicorp/terraform-mcp-server) |
| **Docs** | [HashiCorp Developer](https://developer.hashicorp.com/terraform/mcp-server) |
| **Maintainer** | 🏷️ HashiCorp (Official) |
| **What it does** | Registry search, workspace management, plan/apply operations, state inspection. |
| **Status** | 🧪 Beta. |

### Vault

Secrets management via MCP.

| | |
|---|---|
| **Repo** | [hashicorp/vault-mcp-server](https://github.com/hashicorp/vault-mcp-server) |
| **Docs** | [HashiCorp Developer](https://developer.hashicorp.com/vault/docs/mcp-server/overview) |
| **Maintainer** | 🏷️ HashiCorp (Official) |
| **What it does** | Mount management, KV operations, secrets access. |
| **Status** | 🧪 Beta — ⚠️ secrets exposure requires trusted clients. |

### Pulumi

| | |
|---|---|
| **Repo** | [pulumi/mcp-server](https://github.com/pulumi/mcp-server) |
| **Docs** | [Pulumi MCP Docs](https://www.pulumi.com/docs/iac/guides/ai-integration/mcp-server/) |
| **Maintainer** | 🏷️ Pulumi (Official) |
| **What it does** | Stack queries, resource search, Pulumi Cloud integration. |
| **Remote endpoint** | 🌐 `https://mcp.ai.pulumi.com/mcp` |

### OpenTofu

The open-source Terraform alternative has its own MCP server.

| | |
|---|---|
| **Repo** | [opentofu/opentofu-mcp-server](https://github.com/opentofu/opentofu-mcp-server) |
| **Maintainer** | 🏷️ OpenTofu (Official) |
| **What it does** | Registry search, provider/module documentation, resource docs. |
| **Remote endpoint** | 🌐 `mcp.opentofu.org` |

## ☸️ Kubernetes and Containers

### Kubernetes

Several solid options exist — pick based on your needs.

#### containers/kubernetes-mcp-server

Native Go implementation, no kubectl dependency.

| | |
|---|---|
| **Repo** | [containers/kubernetes-mcp-server](https://github.com/containers/kubernetes-mcp-server) |
| **Why choose it** | ⚡ Single binary, direct K8s API access, multi-cluster support. |

#### Azure/mcp-kubernetes

Microsoft's implementation.

| | |
|---|---|
| **Repo** | [Azure/mcp-kubernetes](https://github.com/Azure/mcp-kubernetes) |
| **Why choose it** | 🎯 Unified kubectl tool interface, minimal context consumption. |

#### Flux159/mcp-server-kubernetes

Popular community option.

| | |
|---|---|
| **Repo** | [Flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) |
| **Why choose it** | 🛡️ Non-destructive mode, secrets masking, easy Claude Code integration. |

#### alexei-led/k8s-mcp-server

Multi-tool support.

| | |
|---|---|
| **Repo** | [alexei-led/k8s-mcp-server](https://github.com/alexei-led/k8s-mcp-server) |
| **Why choose it** | 🧰 kubectl + helm + istioctl + argocd in one server. |

### Docker Hub

| | |
|---|---|
| **Repo** | [docker/hub-mcp](https://github.com/docker/hub-mcp) |
| **Docs** | [Docker Hub MCP](https://docs.docker.com/ai/mcp-catalog-and-toolkit/hub-mcp/) |
| **Maintainer** | 🏷️ Docker (Official) |
| **What it does** | 🐳 Image discovery, repository management, tag inspection. |

### Portainer

| | |
|---|---|
| **Repo** | [portainer/portainer-mcp](https://github.com/portainer/portainer-mcp) |
| **Maintainer** | 🏷️ Portainer (Official) |
| **What it does** | Container management, deployments, environment operations. |
| **Note** | 🛡️ Read-only mode available for safety. |

## 🚀 CI/CD

### Argo CD

GitOps deployment management via AI.

| | |
|---|---|
| **Repo** | [akuity/argocd-mcp](https://github.com/akuity/argocd-mcp) |
| **Maintainer** | 🏷️ Akuity (Official — Argo CD creators) |
| **What it does** | Application listing, sync operations, resource trees, logs. |
| **Transports** | 📡 stdio, HTTP stream. |

### Jenkins

| | |
|---|---|
| **Repo** | [jenkinsci/mcp-server-plugin](https://github.com/jenkinsci/mcp-server-plugin) |
| **Plugin page** | [Jenkins Plugin Index](https://plugins.jenkins.io/mcp-server/) |
| **Maintainer** | 👥 Jenkins Community |
| **What it does** | Build status, job triggers, console logs. |
| **Requires** | ⚠️ Jenkins 2.479+. |

## ☁️ Cloud Platforms

### AWS

AWS provides a collection of MCP servers for their services.

| | |
|---|---|
| **Repo** | [awslabs/mcp](https://github.com/awslabs/mcp) |
| **Docs** | [AWS MCP Servers](https://awslabs.github.io/mcp/) |
| **Maintainer** | 🏷️ AWS (Official) |
| **Includes** | 📦 AWS API server, Documentation server, Knowledge server, Prometheus server. |

### Cloudflare

Comprehensive coverage of Cloudflare's platform.

| | |
|---|---|
| **Repo** | [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) |
| **Docs** | [Cloudflare Agents Docs](https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/) |
| **Maintainer** | 🏷️ Cloudflare (Official) |
| **What it does** | ⚡ Workers, KV, R2, D1, observability. |
| **Count** | 📦 13 specialized MCP servers. |

### Alibaba Cloud

| | |
|---|---|
| **Repo** | [aliyun/alibaba-cloud-ops-mcp-server](https://github.com/aliyun/alibaba-cloud-ops-mcp-server) |
| **Maintainer** | 🏷️ Alibaba Cloud (Official) |
| **What it does** | ECS, Cloud Monitor, OOS operations. |
| **Also available** | 📦 [ACK (Kubernetes)](https://github.com/aliyun/alibabacloud-ack-mcp-server), [DataWorks](https://github.com/aliyun/alibabacloud-dataworks-mcp-server), [DMS](https://github.com/aliyun/alibabacloud-dms-mcp-server), [Function Compute](https://github.com/aliyun/alibabacloud-fc-mcp-server). |

## 📊 Observability

### Grafana

| | |
|---|---|
| **Repo** | [grafana/mcp-grafana](https://github.com/grafana/mcp-grafana) |
| **Maintainer** | 🏷️ Grafana Labs (Official) |
| **What it does** | 📈 Dashboard queries, alerts, datasource info, incident management. |
| **Requires** | ⚠️ Grafana 9.0+. |
| **Related** | 📦 [Loki MCP](https://github.com/grafana/loki-mcp), [Tempo MCP](https://github.com/grafana/tempo-mcp-server). |

### Prometheus

Several community implementations available.

| Repo | Lang | Notes |
|------|------|-------|
| [pab1it0/prometheus-mcp-server](https://github.com/pab1it0/prometheus-mcp-server) | 🐍 Python | ⭐ 177 stars, well-documented. |
| [yshngg/prometheus-mcp-server](https://github.com/yshngg/prometheus-mcp-server) | 🏎️ Go | ✅ 100% Prometheus API compatibility. |
| [idanfishman/prometheus-mcp](https://github.com/idanfishman/prometheus-mcp) | 📇 Node.js | 📡 stdio + HTTP transports. |

AWS also provides a [Prometheus MCP Server](https://awslabs.github.io/mcp/servers/prometheus-mcp-server) for Amazon Managed Prometheus with SigV4 auth.

## 🔒 Security

### Snyk

Vulnerability scanning directly from your AI assistant.

| | |
|---|---|
| **Docs** | [Snyk MCP Documentation](https://docs.snyk.io/cli-ide-and-ci-cd-integrations/snyk-cli/developer-guardrails-for-agentic-workflows/snyk-mcp-early-access) |
| **Maintainer** | 🏷️ Snyk (Official) |
| **What it does** | 🔍 Code scanning, dependency checks, container scanning, IaC analysis, SBOM generation. |
| **Access** | 💻 Via `snyk mcp` CLI command (v1.1296.2+). |

### Semgrep

| | |
|---|---|
| **Repo** | [semgrep/mcp](https://github.com/semgrep/mcp) |
| **Docs** | [Semgrep MCP Docs](https://semgrep.dev/docs/mcp) |
| **Maintainer** | 🏷️ Semgrep (Official) |
| **What it does** | 🔍 Static analysis, OWASP scanning, custom rule execution. |
| **Remote** | 🌐 `https://mcp.semgrep.ai` (no auth required). |

## 📝 Collaboration

### Atlassian (Jira + Confluence)

| | |
|---|---|
| **Repo** | [atlassian/atlassian-mcp-server](https://github.com/atlassian/atlassian-mcp-server) |
| **Docs** | [Atlassian Remote MCP](https://www.atlassian.com/platform/remote-mcp-server) |
| **Maintainer** | 🏷️ Atlassian (Official) |
| **What it does** | 📋 Jira issues, Confluence pages, Compass integration, cross-product workflows. |
| **Security** | 🔐 OAuth 2.0, respects existing permissions. |

Community alternative with Server/Data Center support: [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian).

### Notion

| | |
|---|---|
| **Repo** | [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server) |
| **Docs** | [Notion MCP](https://developers.notion.com/docs/mcp) |
| **Maintainer** | 🏷️ Notion (Official) |
| **What it does** | 📄 Page/database queries, content creation, workspace navigation. |
| **Options** | 🌐 Hosted server or 🏠 self-host via npm/Docker. |

## ⚡ Getting Started

### Basic Setup Pattern

Most MCP servers follow this configuration pattern for Claude Desktop or similar clients:

```json
{
  "mcpServers": {
    "server-name": {
      "command": "npx",
      "args": ["-y", "@org/mcp-server-package"]
    }
  }
}
```

For remote/hosted servers:

```json
{
  "mcpServers": {
    "server-name": {
      "type": "http",
      "url": "https://server-endpoint.example.com/mcp"
    }
  }
}
```

### 🛡️ Safety First

| | Recommendation |
|---|---|
| 1️⃣ | **Start read-only** — Most servers support read-only modes. Use them until you trust the integration. |
| 2️⃣ | **Scope permissions** — Use dedicated API tokens with minimal required access. |
| 3️⃣ | **Audit actions** — Log what your AI assistant does, especially for write operations. |
| 4️⃣ | **Test in staging** — Don't let AI touch production until you've validated behavior. |

## Contributing

Have a DevOps MCP server that should be here? See [contributing.md](contributing.md).

Requirements:
- ✅ Must have a working public repository or documentation.
- ✅ Must be relevant to DevOps workflows.
- ✅ Must include verified links.

## Resources

- [MCP Specification](https://modelcontextprotocol.io/)
- [Anthropic MCP Documentation](https://docs.anthropic.com/en/docs/agents-and-tools/mcp)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Wagner](https://www.trywagner.dev) has waived all copyright and related rights to this work.
