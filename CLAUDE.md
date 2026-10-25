# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

Ansible playbook and roles that install and configure [Docker Sandboxes](https://docs.docker.com/ai/sandboxes/) (`sbx` CLI, microVM-isolated environments for AI coding agents) on hosts.

## Checks

Run these after changing playbooks or roles:

- `yamllint .`
- `ansible-lint`
- `ansible-playbook --syntax-check <playbook>.yml`
- `molecule test` (inside a role directory)
