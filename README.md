# cybersecurity-analysis-tool

A cybersecurity analysis tool for log analysis, vulnerability scanning, and firewall configuration checks.

## Purpose

This project helps security teams review system logs, find known vulnerabilities in scanned hosts, and validate firewall rules before they go live. Each feature is built on its own branch and reviewed through a pull request.

## Branch layout

main is the primary production branch and only receives tested, reviewed changes.

development is the integration branch where ongoing work is merged and tested.

feature/* branches hold individual features, such as feature/log-analysis, feature/vulnerability-scan, and feature/firewall-configuration.

## Workflow

Create a feature branch from development. Commit changes with clear, descriptive messages. Push the branch and open a pull request into development with a summary of the changes. After review and merge, development is promoted to main for release.

Issues and progress are tracked in Freshworks, with one Freshworks issue per feature or bug.

## Documentation

Feature specifications live in the docs folder. The firewall validation rules are documented in docs/firewall-configuration.md.
