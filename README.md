# Awesome MCP Servers - DevOps Toolkit [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome Model Context Protocol (MCP) servers focused on DevOps tools and capabilities.

The Model Context Protocol (MCP) is an open protocol that standardizes how applications provide context to LLMs. This list focuses specifically on MCP servers that enhance DevOps workflows, automation, and infrastructure management.

**Note:** This list includes both existing official MCP servers and community-desired servers that represent valuable DevOps integrations. Links marked with `mcp-contrib` are community project placeholders indicating desired integrations. Official implementations can be found in the [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) repository. Contributions to create these servers are welcome!

## Contents

- [Official Resources](#official-resources)
- [CI/CD](#cicd)
- [Infrastructure as Code](#infrastructure-as-code)
- [Cloud Platforms](#cloud-platforms)
- [Container & Orchestration](#container--orchestration)
- [Monitoring & Observability](#monitoring--observability)
- [Version Control](#version-control)
- [Configuration Management](#configuration-management)
- [Database Management](#database-management)
- [Security & Compliance](#security--compliance)
- [Communication & Collaboration](#communication--collaboration)
- [Development Tools](#development-tools)

## Official Resources

- [Model Context Protocol Documentation](https://modelcontextprotocol.io) - Official MCP documentation
- [MCP Specification](https://spec.modelcontextprotocol.io) - Technical specification
- [MCP GitHub Organization](https://github.com/modelcontextprotocol) - Official MCP repositories
- [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) - Python SDK for building MCP servers
- [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) - TypeScript SDK for building MCP servers

## CI/CD

MCP servers for continuous integration and continuous deployment pipelines.

- [GitHub MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/github) - Access and interact with GitHub repositories, pull requests, issues, and workflows
- [GitLab MCP Server](https://github.com/mcp-contrib/mcp-gitlab) - Interact with GitLab repositories, CI/CD pipelines, and merge requests
- [Jenkins MCP Server](https://github.com/mcp-contrib/jenkins-mcp-server) - Manage Jenkins jobs, builds, and pipeline configurations
- [CircleCI MCP Server](https://github.com/mcp-contrib/circleci-mcp-server) - Access CircleCI workflows, pipelines, and build information
- [Travis CI MCP Server](https://github.com/mcp-contrib/travis-mcp-server) - Monitor and manage Travis CI builds
- [Azure DevOps MCP Server](https://github.com/mcp-contrib/azure-devops-mcp-server) - Interact with Azure DevOps pipelines, work items, and repos

## Infrastructure as Code

MCP servers for infrastructure automation and configuration.

- [Terraform MCP Server](https://github.com/mcp-contrib/terraform-mcp-server) - Interact with Terraform configurations, state, and plan/apply operations
- [Ansible MCP Server](https://github.com/mcp-contrib/ansible-mcp-server) - Execute Ansible playbooks and manage inventory
- [Pulumi MCP Server](https://github.com/mcp-contrib/pulumi-mcp-server) - Work with Pulumi infrastructure as code
- [CloudFormation MCP Server](https://github.com/mcp-contrib/cloudformation-mcp-server) - Manage AWS CloudFormation stacks
- [CDK MCP Server](https://github.com/mcp-contrib/cdk-mcp-server) - Interact with AWS Cloud Development Kit

## Cloud Platforms

MCP servers for major cloud service providers.

- [AWS MCP Server](https://github.com/mcp-contrib/aws-mcp-server) - Interact with AWS services including EC2, S3, Lambda, and more
- [Google Cloud MCP Server](https://github.com/mcp-contrib/gcp-mcp-server) - Manage Google Cloud Platform resources
- [Azure MCP Server](https://github.com/mcp-contrib/azure-mcp-server) - Access Microsoft Azure services and resources
- [DigitalOcean MCP Server](https://github.com/mcp-contrib/digitalocean-mcp-server) - Manage DigitalOcean droplets and resources
- [Linode MCP Server](https://github.com/mcp-contrib/linode-mcp-server) - Interact with Linode cloud infrastructure

## Container & Orchestration

MCP servers for container management and orchestration platforms.

- [Docker MCP Server](https://github.com/mcp-contrib/docker-mcp-server) - Manage Docker containers, images, and networks
- [Kubernetes MCP Server](https://github.com/mcp-contrib/kubernetes-mcp-server) - Interact with Kubernetes clusters, deployments, and services
- [Helm MCP Server](https://github.com/mcp-contrib/helm-mcp-server) - Manage Helm charts and releases
- [Docker Compose MCP Server](https://github.com/mcp-contrib/docker-compose-mcp-server) - Work with Docker Compose configurations
- [Podman MCP Server](https://github.com/mcp-contrib/podman-mcp-server) - Manage Podman containers

## Monitoring & Observability

MCP servers for monitoring, logging, and observability tools.

- [Prometheus MCP Server](https://github.com/mcp-contrib/prometheus-mcp-server) - Query Prometheus metrics and alerts
- [Grafana MCP Server](https://github.com/mcp-contrib/grafana-mcp-server) - Interact with Grafana dashboards and data sources
- [Datadog MCP Server](https://github.com/mcp-contrib/datadog-mcp-server) - Access Datadog metrics, logs, and traces
- [New Relic MCP Server](https://github.com/mcp-contrib/newrelic-mcp-server) - Query New Relic monitoring data
- [ELK Stack MCP Server](https://github.com/mcp-contrib/elk-mcp-server) - Interact with Elasticsearch, Logstash, and Kibana
- [Splunk MCP Server](https://github.com/mcp-contrib/splunk-mcp-server) - Query Splunk logs and events

## Version Control

MCP servers for version control systems.

- [Git MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/git) - Local Git repository operations
- [Bitbucket MCP Server](https://github.com/mcp-contrib/bitbucket-mcp-server) - Bitbucket repository management

*Note: GitHub and GitLab MCP Servers are listed in the [CI/CD](#cicd) section as they provide broader DevOps capabilities beyond version control.*

## Configuration Management

MCP servers for configuration and secrets management.

- [Vault MCP Server](https://github.com/mcp-contrib/vault-mcp-server) - Access HashiCorp Vault secrets
- [Consul MCP Server](https://github.com/mcp-contrib/consul-mcp-server) - Interact with HashiCorp Consul
- [etcd MCP Server](https://github.com/mcp-contrib/etcd-mcp-server) - Manage etcd key-value store
- [AWS Secrets Manager MCP Server](https://github.com/mcp-contrib/aws-secrets-manager-mcp-server) - Access AWS Secrets Manager
- [Azure Key Vault MCP Server](https://github.com/mcp-contrib/azure-keyvault-mcp-server) - Manage Azure Key Vault secrets

## Database Management

MCP servers for database operations and management.

- [PostgreSQL MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) - Official PostgreSQL database server
- [MySQL MCP Server](https://github.com/mcp-contrib/mysql-mcp-server) - MySQL database operations
- [MongoDB MCP Server](https://github.com/mcp-contrib/mongodb-mcp-server) - MongoDB database interactions
- [Redis MCP Server](https://github.com/mcp-contrib/redis-mcp-server) - Redis key-value store operations
- [SQLite MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/sqlite) - Official SQLite database server

## Security & Compliance

MCP servers for security scanning and compliance tools.

- [Snyk MCP Server](https://github.com/mcp-contrib/snyk-mcp-server) - Security vulnerability scanning with Snyk
- [SonarQube MCP Server](https://github.com/mcp-contrib/sonarqube-mcp-server) - Code quality and security analysis
- [Trivy MCP Server](https://github.com/mcp-contrib/trivy-mcp-server) - Container security scanning
- [OWASP Dependency Check MCP Server](https://github.com/mcp-contrib/dependency-check-mcp-server) - Dependency vulnerability scanning

## Communication & Collaboration

MCP servers for team communication and collaboration tools.

- [Slack MCP Server](https://github.com/modelcontextprotocol/servers/tree/main/src/slack) - Official Slack integration
- [PagerDuty MCP Server](https://github.com/mcp-contrib/pagerduty-mcp-server) - Incident management with PagerDuty
- [Jira MCP Server](https://github.com/mcp-contrib/jira-mcp-server) - Atlassian Jira issue tracking
- [Confluence MCP Server](https://github.com/mcp-contrib/confluence-mcp-server) - Atlassian Confluence documentation

## Development Tools

MCP servers for development and build tools.

- [NPM MCP Server](https://github.com/mcp-contrib/npm-mcp-server) - Node.js package management
- [Maven MCP Server](https://github.com/mcp-contrib/maven-mcp-server) - Java build tool integration
- [Gradle MCP Server](https://github.com/mcp-contrib/gradle-mcp-server) - Gradle build automation
- [Make MCP Server](https://github.com/mcp-contrib/make-mcp-server) - GNU Make build system

## Getting Started

To use MCP servers, you'll need:

1. An MCP-compatible client (e.g., Claude Desktop, Cline, or other MCP clients)
2. The MCP server you want to use installed and configured
3. Proper authentication credentials for the service the server connects to

### Installation Example

Most MCP servers can be installed via npm or run directly:

```bash
# Using npx (no installation required)
npx @modelcontextprotocol/server-github

# Or install globally
npm install -g @modelcontextprotocol/server-github
```

### Configuration Example

Configure MCP servers in your Claude Desktop config file (`claude_desktop_config.json`):

```json
{
  "mcpServers": {
    "github": {
      "command": "npx",
      "args": ["-y", "@modelcontextprotocol/server-github"],
      "env": {
        "GITHUB_TOKEN": "your-github-token"
      }
    }
  }
}
```

## Contributing

Contributions are welcome! Please:

1. Check if the server is already listed
2. Ensure the server is actively maintained
3. Verify the server is specifically relevant to DevOps workflows
4. Follow the existing format and categories
5. Add new categories if needed (but keep them focused on DevOps)
6. Submit a pull request with a clear description

## Related Lists

- [Awesome MCP Servers](https://github.com/punkpeye/awesome-mcp-servers) - General MCP servers list
- [Official MCP Servers](https://github.com/modelcontextprotocol/servers) - Official MCP server implementations

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.