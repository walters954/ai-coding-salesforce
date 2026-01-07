# AI Coding Rules for Salesforce Development

Cursor/AI coding rules and best practices for Salesforce development, administration, and architecture.

## Overview

This repository contains configuration rules for AI-assisted Salesforce development. The rules guide AI assistants to follow Salesforce best practices, Clean Code principles, and proper deployment workflows using the Salesforce CLI.

## Contents

- `.cursor/rules/salesforce-development.mdc` - Cursor rules for Salesforce development

## Key Features

### Salesforce CLI Standards
- Uses modern `sf` commands (not legacy `sfdx`)
- Deployment workflows for non-production and production orgs
- Proper test level configurations

### Apex Development Guidelines
- File structure conventions (`force-app/main/default`)
- Bulkification patterns
- Trigger handler best practices
- Code standards and naming conventions

### Apex Testing Standards
- Modern `Assert` class usage
- `Test.startTest()`/`Test.stopTest()` patterns
- Queueable job testing
- Mock class organization

## API Version

Current API version: **63.0**

## Usage

Clone this repository and the rules will automatically apply when using Cursor or compatible AI coding assistants in Salesforce projects.

## License

MIT
