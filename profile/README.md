# Welcome 👋

This page is the public face of the organization: what it is for, what is published
here, and what you can reasonably expect from it. Everything below concerns the
public repositories — internal working practice lives elsewhere.

## Table of Contents

- [1. What this organization is](#1-what-this-organization-is)
- [2. What is public here](#2-what-is-public-here)
- [3. Using this code](#3-using-this-code)
- [4. Issues and contributions](#4-issues-and-contributions)
- [5. Contact](#5-contact)
- [License](#license)

## 1. What this organization is

LABSONLINE is a lab estate. The repositories here are sandboxes, experiments, and
lab material — places to test an idea under realistic conditions before committing
to it. **Repositories here are experimental by design, and production stability is
not the bar they are held to.** Treat anything you find as work in progress unless
its own documentation says otherwise.

This organization occupies the middle stage of a three-stage lifecycle:

1. **Origin.** An idea begins as personal scratch work, outside this organization.
2. **Incubation.** Once it warrants sustained effort, it moves here to be built out,
   tested, and hardened. This is the work the organization exists for.
3. **Promotion.** When it matures and is bound for production, it is promoted out of
   this organization to its production home.

Two consequences are worth internalising. A repository arriving here is not
finished, and a repository leaving here has not been abandoned — it graduated.

Most of the estate is private or internal, so what is visible from outside is a
deliberate slice rather than the whole of it. A reference to a repository you cannot
open is a repository you lack access to, not a dead link.

## 2. What is public here

Four sandboxes are published in full. Each carries its own README, and each is the
place to start for the platform it covers.

| Repository               | What it is                                                                                     |
| ------------------------ | ---------------------------------------------------------------------------------------------- |
| [kube-sandbox][kube]     | Kubernetes: KCM/k0rdent management and workload clusters, Flux and Helm, cfssl PKI             |
| [linux-sandbox][linux]   | U-Boot, Linux kernel and Ubuntu rootfs builds, eBPF programs, and loadable kernel modules      |
| [apple-sandbox][apple]   | Swift and Xcode prototypes across macOS, iOS, watchOS, tvOS, and visionOS                      |
| [zephyr-sandbox][zephyr] | Swift on Zephyr RTOS, built on [zephyr-lang-swift][zls]                                        |

> [!NOTE]
> Three further public repositories are forks of upstream projects —
> [altera_workshops][altera], [att-charts][charts], and [att-cicd][cicd] — and carry
> their upstream's licensing and conventions rather than ours. Two more are archived
> and retained for reference only. Neither group is a pattern to follow for new
> work.

The full inventory, forks and archives included, is at
<https://github.com/orgs/labsonline/repositories>.

## 3. Using this code

Everything published here is offered as-is, without warranty and without support. It
is lab material: read it, borrow from it, and run it somewhere you can afford to
break.

Licensing differs between the sandboxes and the forks, so check before reusing
anything:

| Repository                                       | Licence                                                             |
| ------------------------------------------------ | ------------------------------------------------------------------- |
| The four sandboxes above                         | GPL-3.0, with a `LICENSE` file in each                              |
| [att-cicd][cicd]                                 | Apache-2.0, inherited from upstream                                 |
| [att-charts][charts], [altera_workshops][altera] | No licence file — upstream terms apply, so check the parent project |

Confirm a repository's default branch rather than assuming `main`. Most use it, but
`altera_workshops` builds from `DE25-Nano` and the `att-*` forks from `master`.

## 4. Issues and contributions

By default these repositories are read-only from the outside. They are published for
reference, contributions are not solicited, and no support commitment or response
time attaches to an issue or a pull request.

That default is a floor rather than a ceiling. An individual repository may set its
own posture, and where it does, that posture governs: a repository carrying its own
`CONTRIBUTING.md`, or stating a policy in its README, supersedes what is written
here. Check the repository itself before assuming the default applies.

> [!CAUTION]
> Never report a security vulnerability in a public issue. Use the private route
> described in [SECURITY.md][security].

## 5. Contact

| Route                              | Use it for                                 |
| ---------------------------------- | ------------------------------------------ |
| <https://labsonline.ca>            | The organization itself                    |
| <git@labsonline.ca>                | Repository access and anything estate-wide |
| Issues on the repository concerned | Anything specific to one repository        |

## License

Copyright (c) 2026 Schubert Anselme <schubert@anselm.es>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program. If not, see <https://www.gnu.org/licenses/>.

[altera]: https://github.com/labsonline/altera_workshops
[apple]: https://github.com/labsonline/apple-sandbox
[charts]: https://github.com/labsonline/att-charts
[cicd]: https://github.com/labsonline/att-cicd
[kube]: https://github.com/labsonline/kube-sandbox
[linux]: https://github.com/labsonline/linux-sandbox
[security]: https://github.com/labsonline/.github/blob/main/SECURITY.md
[zephyr]: https://github.com/labsonline/zephyr-sandbox
[zls]: https://github.com/anselmes/zephyr-lang-swift
