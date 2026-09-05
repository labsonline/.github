---
name: Bug report
about: Something in a lab repository does not work as its README describes
title: ""
labels: bug
assignees: ""
---

<!--
These are lab repositories, offered as-is and without a support commitment. A report
is read, but no response time is promised. See CONTRIBUTING.md.

Do NOT report a security vulnerability here. Use the Security tab on the affected
repository, or email git@labsonline.ca. See SECURITY.md.
-->

## Where

- Repository:
- Commit (`git rev-parse --short HEAD`):
- Branch, if not the default:

## What happens

A short description of the behaviour, and what you expected instead.

## How to reproduce

The commands you ran, in order. A shell transcript is worth more than prose.

```shell

```

## Environment

Host OS and architecture, plus whichever of the following applies to the repository:

- **kube-sandbox** — docker, kind, kubectl, helm, flux versions
- **linux-sandbox** — kernel version, target architecture, cross toolchain
- **apple-sandbox** — macOS version, Xcode version, target platform and OS version
- **zephyr-sandbox** — Zephyr and west versions, target board

## Output

Build log, `dmesg`, serial console, or `kubectl` output, as text in a code fence
rather than a screenshot — it needs to be searchable.

```text

```

## Anything you already tried

Workarounds, related issues upstream, or a diagnosis if you have one. Optional.
