# InfraMCP Organization

Welcome to **InfraMCP**, a curated collection of open-source Model Context Protocol (MCP) servers that enable secure, AI-driven management and automation across your entire infrastructure stack. Our projects provide seamless integration with leading platforms, empowering AI agents, developers, and automation tools to interact with complex environments using a unified protocol.

## What is Model Context Protocol (MCP)?

MCP is an open standard for exposing infrastructure and application context to AI assistants and developer tools. Each MCP server acts as a bridge between your systems and AI-powered workflows, providing structured tools for querying, managing, and automating your environment.

---

## InfraMCP Projects

InfraMCP maintains a family of specialized MCP servers for different infrastructure domains:

### 🟦 Atlassian MCP Server
- **Repo:** [atlassian-mcp-server](https://github.com/InfraMCP/atlassian-mcp-server)
- **Purpose:** Manage Atlassian Cloud (Jira, Confluence, Service Management) with AI-driven workflows.
- **Features:** OAuth 2.0, granular permissions, Jira & Confluence tools, supply chain security.

### 🟦 Win MCP Server
- **Repo:** [win-mcp-server](https://github.com/InfraMCP/win-mcp-server)
- **Purpose:** Secure PowerShell and system management for Windows servers via WinRM.
- **Features:** Domain credential management, macOS Keychain, remote PowerShell, service & disk tools.

### 🟦 SSH MCP Server
- **Repo:** [ssh-mcp-server](https://github.com/InfraMCP/ssh-mcp-server)
- **Purpose:** AI-driven remote management of Linux hosts over SSH.
- **Features:** Secure credential storage, command execution, system info, process/service tools.

### 🟦 vSphere MCP Server
- **Repo:** [vsphere-mcp-server](https://github.com/InfraMCP/vsphere-mcp-server)
- **Purpose:** VMware vSphere automation for VM and infrastructure management.
- **Features:** macOS Keychain, VM operations, datacenter/network/discovery tools, VLAN extraction.

### 🟦 Foreman MCP Server
- **Repo:** [foreman-mcp-server](https://github.com/InfraMCP/foreman-mcp-server)
- **Purpose:** Foreman API integration for host inventory, discovery, and infrastructure queries.
- **Features:** Host search, organization/location/hostgroup management, secure API access.

---

## Organization-wide Standards

All InfraMCP projects adhere to the following standards:

- **Consistent Documentation:** Every repo provides detailed README, CHANGELOG, and SECURITY policies.
- **Changelog Discipline:** All changes are tracked per [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).
- **Supply Chain Security:** 
  - Pinned dependency versions
  - Automated scanning with Safety & pip-audit
  - Weekly GitHub Action security checks
  - Human & machine-readable dependency reports
- **Credential & Secret Security:** 
  - No credentials in code or logs
  - Secure storage (Keychain or environment variables)
  - Least-privilege permissions
- **Code Quality:** 
  - Pylint workflows (10/10 target)
  - Automated linting, security, and dependency workflows
- **Open Source:** 
  - MIT License across all projects

---

## Getting Started

1. **Choose a Server:** Find the MCP server for your target environment.
2. **Read the Docs:** Visit the repo's README for installation and configuration.
3. **Configure Security:** Follow SECURITY.md for supply chain and credential best practices.
4. **Integrate with AI:** Use your favorite AI assistant (Claude, Copilot Chat, Q, Continue, etc.) and point it to your MCP server.
5. **Contribute:** See the CONTRIBUTING.md in each repo for guidelines.

---

## Security & Responsible Disclosure

We take supply chain, credential, and data security seriously.
- Each repo has a dedicated `SECURITY.md` with detailed policies.
- Please report vulnerabilities directly to **rory.mcmahon@vocus.com.au** (not via GitHub issues).

---

## Organization Contacts

| Maintainer        | Contact                          |
|-------------------|----------------------------------|
| Rory McMahon      | rory.mcmahon@vocus.com.au        |

---

## Join or Contribute

We welcome improvements, new integrations, and feature requests!  
- Fork a repo and open a pull request
- Submit issues for bugs or enhancements
- Suggest new infrastructure integrations

**InfraMCP: Making infrastructure AI-ready, securely and openly.**

---
