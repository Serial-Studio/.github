# Security Policy

## Reporting a vulnerability

Do not open a public issue for a security vulnerability.

Report it privately by email to **alex@serial-studio.com**, or through GitHub's
[private vulnerability reporting](https://docs.github.com/en/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability)
on the affected repository (Security tab → Report a vulnerability).

Please include:

- The affected repository, version, and platform
- What an attacker can do with the issue, and what access they need to start
- Steps to reproduce, ideally with a minimal project file, payload, or capture
- Any proof-of-concept code or crash output you have

You will get an acknowledgement within 5 business days. Expect an assessment and a plan
within 30 days. Fixes ship in the next release, and reporters are credited in the release
notes unless they ask not to be.

Please give a reasonable window to release a fix before disclosing publicly.

## Supported versions

Security fixes land in the latest stable release. Older releases are not patched; upgrade to
the current version before reporting.

## In scope

- Memory-safety and parsing bugs reachable from device data: frame parsers, protocol
  decoders (MAVLink, NMEA, UBX, Modbus, CAN/DBC, MDF4, and others), and project file
  (`.ssproj`) loading
- Sandbox escapes or unintended host access from JavaScript or Lua parsers, per-dataset
  transforms, and the Canvas widget scripting API
- Authentication, authorization, or injection flaws in the TCP API (port 7777), the gRPC
  server (port 8888), and the MCP server
- Vulnerabilities in the cloud backend that handles license activation
- License-check bypasses, credential leaks, and exposure of user API keys stored for the AI
  assistant

## Out of scope

- Attacks that require the user to already have local administrator or physical access
- Reports generated only by automated scanners, with no demonstrated impact
- Missing hardening flags or best practices with no exploitable consequence
- Denial of service caused by feeding deliberately malformed data to a parser that the user
  configured themselves, unless it corrupts memory
- Social engineering, and vulnerabilities in third-party services the project merely links to
