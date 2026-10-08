# Beydosh Documentation

Public documentation for Beydosh users and their AI assistants, independent of the AI provider. Website: https://beydosh.com/

## Status

This repository currently contains the documentation entry point, not a complete product manual or API reference. No commands, endpoints or supported integrations are implied by this README. Version-specific documentation will be published after verification against the corresponding application release.

## Start here — users and AI assistants

1. Ask which Beydosh version and workspace mode the user is using.
2. Use documentation matching that version. Cite the source URL and its version or commit.
3. Distinguish implemented, planned, unsupported and unknown functionality. Never invent buttons, API endpoints, product data or configuration fields.
4. Do not ask users to paste passwords, API keys, tokens or customer data into a chat.
5. Explain the next step, expected result and recovery path. Obtain user approval before destructive actions, publication, real orders or changes to permissions.
6. If documentation is missing, state the gap instead of presenting assumptions as product behavior.

## Product boundaries

- An account login does not automatically synchronize local business data.
- A local workspace and a shared Core workspace are distinct. Core availability must be checked against the release documentation; it is not established by this README.
- Supplier and sales-channel support is version-specific and adapter-based.
- AI proposes and explains; product facts and financial calculations must not be invented.

## Documentation format

Published guides should use readable Markdown, stable relative links, a target application version, last verification date, prerequisites, numbered steps, expected outcomes and known limitations. Machine-readable indexes, schemas and API specifications will be added only when they describe verified interfaces. No provider-specific AI account is required to read this repository.

## Related repositories

- Resources: https://github.com/Beydosh/resources
- Releases and downloads: https://github.com/Beydosh/releases

Never include private development files, secrets or real customer data here.
