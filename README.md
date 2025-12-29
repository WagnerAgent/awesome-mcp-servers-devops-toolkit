# Awesome MCP Servers for DevOps

> A curated list of Model Context Protocol (MCP) servers for DevOps teams, enabling AI-assisted infrastructure, CI/CD, monitoring, and security workflows.

**Curated by [Wagner](https://www.trywagner.dev)**

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

---

## What is MCP?

Model Context Protocol (MCP) is an open standard that enables AI assistants to securely interact with external tools and data via standardized servers. For DevOps teams, MCP servers unlock "ChatOps 2.0" — giving AI agents the ability to perform tasks across version control, CI/CD, infrastructure provisioning, monitoring, security scanning, and more.

---

## Table of Contents

- [Version Control & Code Management](#version-control--code-management)
- [CI/CD Pipelines](#cicd-pipelines)
- [Infrastructure as Code (IaC)](#infrastructure-as-code-iac)
- [Cloud Providers](#cloud-providers)
- [Container & Kubernetes](#container--kubernetes)
- [Monitoring & Observability](#monitoring--observability)
- [Security & Compliance](#security--compliance)
- [Documentation & Project Management](#documentation--project-management)
- [Command Line & Automation](#command-line--automation)
- [Aggregators & Frameworks](#aggregators--frameworks)

---

## Legend

| Icon | Meaning |
|------|---------|
| :medal_military: | Official implementation |
| :snake: | Python |
| :card_index: | TypeScript/JavaScript |
| :racing_car: | Go |
| :crab: | Rust |
| :hash: | C# |
| :coffee: | Java |

---

## Version Control & Code Management

### GitHub

| Server | Description | Link |
|--------|-------------|------|
| :medal_military: **GitHub MCP Server** | Official server for GitHub repositories. Supports file operations, code search, issues, PRs, comments, merging, and GitHub Actions workflows. Includes read-only mode for safety. | [GitHub](https://github.com/github/github-mcp-server) |
| :card_index: GitHub Actions Server | Interact with GitHub Actions workflows, trigger runs, and check statuses | [GitHub](https://github.com/rohitg00/awesome-devops-mcp-servers) |

### GitLab

| Server | Description | Link |
|--------|-------------|------|
| :medal_military: **GitLab MCP Server** | Official GitLab integration (Premium/Ultimate). Create issues/MRs, retrieve commits, diffs, pipelines, and cross-project issue search. | [GitLab Docs](https://docs.gitlab.com/ee/user/gitlab_duo/mcp.html) |

### Azure DevOps

| Server | Description | Link |
|--------|-------------|------|
| :card_index: **Azure DevOps MCP** | Repository browsing, work item queries, pipeline triggers for Azure DevOps services. | [GitHub](https://github.com/tiberriver256/azure-devops-mcp-server) |

### Other Git Platforms

| Server | Description | Link |
|--------|-------------|------|
| :card_index: Gitea MCP | Self-hosted Git service integration | Community |
| :card_index: Gitee MCP | Chinese Git platform integration | Community |

---

## CI/CD Pipelines

| Server | Description | Link |
|--------|-------------|------|
| :medal_military: **Argo CD MCP Server** | Akuity's official server for Argo CD (GitOps). List/manage applications, sync deployments, view resource trees and logs. | [GitHub](https://github.com/akuity/mcp-server-argocd) |
| :coffee: **Jenkins MCP Plugin** | Community plugin for Jenkins. Query build statuses, trigger/abort jobs, fetch console logs. | [GitHub](https://github.com/jenkinsci/mcp-server-plugin) |
| :card_index: Codemagic MCP | Mobile CI/CD platform integration | Community |

---

## Infrastructure as Code (IaC)

| Server | Description | Link |
|--------|-------------|------|
| :medal_military: **Terraform MCP Server** | HashiCorp's official server. Generate/analyze Terraform configs, search modules/providers, inspect workspace state, plan and trigger runs. | [GitHub](https://github.com/hashicorp/terraform-mcp-server) |
| :card_index: **OpenTofu MCP Server** | Open-source Terraform alternative. Runs locally or via Cloudflare Workers. | [GitHub](https://github.com/opentofu/mcp-opentofu) |
| :medal_military: **Pulumi MCP Server** | Official Pulumi server. Preview/deploy infrastructure, manage stacks, list resources via Automation API. | [Pulumi Docs](https://www.pulumi.com/docs/pulumi-cloud/access-management/mcp/) |
| :racing_car: HCP Terraform Server | Terraform Cloud/Enterprise integration | [GitHub](https://github.com/dulltz/mcp-server-hcp-terraform) |

---

## Cloud Providers

### AWS

| Server | Description | Link |
|--------|-------------|------|
| :medal_military: **AWS MCP Servers** | Official AWS servers covering Lambda, S3 Tables, Knowledge Base, and more. List/manage cloud resources via natural language. | [AWS Labs](https://github.com/awslabs/mcp) |
| :snake: AWS CLI MCP | Wrap AWS CLI commands for AI access | Community |

### Azure

| Server | Description | Link |
|--------|-------------|------|
| :card_index: Azure DevOps MCP | Full Azure DevOps integration | [GitHub](https://github.com/tiberriver256/azure-devops-mcp-server) |
| :card_index: Azure Data Lake Storage | ADLS Gen2 operations | Community |
| :card_index: Azure Resource Graph | Query Azure resources at scale | Community |

### Alibaba Cloud

| Server | Description | Link |
|--------|-------------|------|
| :medal_military: **Alibaba Cloud MCP** | Official Aliyun server. ECS, Cloud Monitor, OOS operations. | [GitHub](https://github.com/aliyun/alibabacloud-mcp-server) |

### Cloudflare

| Server | Description | Link |
|--------|-------------|------|
| :medal_military: **Cloudflare MCP Server** | Official server for Workers, KV, R2, D1. Deploy edge functions, manage storage. | [GitHub](https://github.com/cloudflare/mcp-server-cloudflare) |

### Other Providers

| Server | Description | Link |
|--------|-------------|------|
| :card_index: VMware ESXi MCP | VMware virtualization management | Community |
| :card_index: Nutanix MCP | Nutanix HCI operations | Community |

---

## Container & Kubernetes

| Server | Description | Link |
|--------|-------------|------|
| :snake: **Kubectl MCP Server** | Execute kubectl, helm, and k8s commands via natural language. Safe sandbox mode available. | [GitHub](https://github.com/rohitg00/kubectl-mcp-server) |
| :card_index: Kubernetes MCP | Alternative k8s management server | [GitHub](https://github.com/manusa/kubernetes-mcp-server) |
| :medal_military: **Portainer MCP Server** | Official Portainer server for container orchestration, deployments, and monitoring. | [GitHub](https://github.com/portainer/portainer-mcp-server) |
| :medal_military: **Docker Hub MCP** | Official Docker Hub integration. Query images, list tags, check image details. | [Docker Hub](https://hub.docker.com/extensions/docker/mcp-catalog) |
| :card_index: Tilt MCP | Development environment for k8s | Community |

---

## Monitoring & Observability

| Server | Description | Link |
|--------|-------------|------|
| :medal_military: **Grafana MCP Server** | Official server. Query dashboards, retrieve alerts, access metrics. Configurable toolset with optimized responses. | [GitHub](https://github.com/grafana/mcp-grafana) |
| :snake: Prometheus MCP | Query Prometheus metrics directly | Community |
| :snake: Alertmanager MCP | Manage Prometheus Alertmanager | Community |
| :card_index: VictoriaMetrics MCP | High-performance metrics backend | Community |
| :card_index: Dynatrace MCP | APM and observability platform | Community |
| :card_index: Last9 MCP | SRE and observability tools | Community |
| :card_index: Polar Signals MCP | Continuous profiling integration | Community |

---

## Security & Compliance

| Server | Description | Link |
|--------|-------------|------|
| :medal_military: **Snyk MCP Server** | Official server. Scan code, dependencies, containers, IaC, and SBOMs for vulnerabilities. Generate AI Bill of Materials. | [Snyk Docs](https://docs.snyk.io/scm-ide-and-ci-cd-integrations/snyk-ide-plugins-and-extensions/snyk-mcp-server) |
| :medal_military: **Semgrep MCP Server** | Official static analysis. Scan for OWASP Top 10, insecure patterns, and code quality issues. | [GitHub](https://github.com/semgrep/mcp-server-semgrep) |
| :snake: Ghidra MCP | Binary reverse engineering and analysis | Community |
| :snake: VirusTotal MCP | Malware and threat analysis | Community |
| :snake: Shodan MCP | Internet-connected device search | Community |
| :snake: CVE-Search MCP | Vulnerability database queries | Community |
| :card_index: Linux Security Audit | Security auditing for Linux systems | Community |

---

## Documentation & Project Management

| Server | Description | Link |
|--------|-------------|------|
| :medal_military: **Notion MCP Server** | Official Notion integration. Retrieve/update pages and databases. Access runbooks, docs, wikis. | [Notion Docs](https://developers.notion.com/docs/mcp) |
| :medal_military: **Atlassian MCP Server** | Official server for Jira, Confluence, Compass. Search/summarize tickets, create issues, chain tasks. OAuth 2.1 secured. | [Atlassian Docs](https://developer.atlassian.com/cloud/mcp/) |
| :card_index: Jira MCP | Standalone Jira integration | Community |
| :card_index: Confluence MCP | Standalone Confluence integration | Community |
| :card_index: Freshdesk MCP | Support ticketing integration | Community |
| :card_index: Topdesk MCP | Incident management | Community |

---

## Command Line & Automation

| Server | Description | Link |
|--------|-------------|------|
| :snake: Shell Command MCP | Execute shell commands with security policies | Community |
| :card_index: Terminal Automation | Automated terminal interactions | Community |
| :snake: Cisco pyATS MCP | Network device automation | Community |
| :card_index: Playwright MCP | Browser automation and testing | Community |
| :card_index: Puppeteer MCP | Headless Chrome automation | Community |

---

## Aggregators & Frameworks

| Server | Description | Link |
|--------|-------------|------|
| :snake: **FastMCP (Python)** | Framework for building MCP servers quickly in Python | [GitHub](https://github.com/jlowin/fastmcp) |
| :card_index: **FastMCP (TypeScript)** | TypeScript port of FastMCP | Community |
| :card_index: MCP Aggregator | Connect 500+ applications through single interface | Community |
| :card_index: MCP Proxy | Middleware for routing MCP requests | Community |

---

## Best Practices

1. **Start Read-Only**: Begin with read-only permissions when integrating MCP servers. Expand access as trust is established.

2. **Use Official Servers**: Prefer official (:medal_military:) implementations when available — they're maintained by the tool creators.

3. **Credential Security**: Store API tokens and credentials securely. Use environment variables, not hardcoded values.

4. **Audit Actions**: Log AI agent actions for compliance and debugging. Many servers support audit modes.

5. **Sandbox First**: Test in non-production environments before enabling write operations in production.

---

## Contributing

Found an MCP server we missed? Check out our [Contributing Guide](CONTRIBUTING.md) and open a PR!

---

## Resources

- [MCP Specification](https://modelcontextprotocol.io/)
- [Anthropic MCP Documentation](https://docs.anthropic.com/en/docs/agents-and-tools/mcp)
- [Awesome DevOps MCP Servers (source)](https://github.com/rohitg00/awesome-devops-mcp-servers)

---

## License

MIT License - See [LICENSE](LICENSE) for details.

---

[Wagner](https://www.trywagner.dev) — The first AI DevOps teammate
