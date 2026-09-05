# Security Policy

This is the LABSONLINE organization-wide default. It applies to every repository in
the organization that does not carry its own `SECURITY.md`, whatever that
repository's visibility, and any repository providing its own supersedes it.

The reporting route below is the same either way. What differs is context: on
private and internal repositories the member handbook governs day-to-day practice,
and this file is the disclosure route rather than the whole policy.

## What this code is

The repositories here are lab material — sandboxes and experiments, not production
software, and not held to a production stability bar. Public repositories are
offered as-is, without warranty or support.

That does not make a vulnerability uninteresting. If something here is exploitable,
or would become exploitable the moment someone copied it into real use, we would
rather know.

## Supported versions

None of these repositories publishes releases or tags, so there are no versions to
support. The latest commit on a repository's default branch is the only state that
receives fixes; earlier commits are not patched, and neither are forks you hold of
them.

## Reporting a vulnerability

Two routes. Prefer the first.

**GitHub Security Advisories.** On the affected repository, open the **Security**
tab and choose **Report a vulnerability**. If that button is there, use it — it
opens a private advisory visible only to you and the maintainers, keeps the
discussion attached to the code in question, and is what a fix, a credit, and a CVE
are issued from later. The form lives at
`https://github.com/labsonline/<repository>/security/advisories/new`.

**Email.** Write to <git@labsonline.ca> if the Security tab offers no such button,
if the problem spans several repositories, or if you would rather not use GitHub.

> [!CAUTION]
> Never open a public issue or pull request for a security vulnerability, and do not
> post working exploit code in a public discussion.

Include whatever you have:

- The affected repository, and the commit you found it on.
- What the problem is, and the shortest path to reproducing it.
- What an attacker gains — the impact matters more than the severity label.
- Any mitigation or workaround you already know of.

A partial report is worth more than no report. Send what you have.

If you find a credential committed to a repository, report it the same way. Any
secret that reached a remote is treated as compromised and rotated, whether or not
it was ever live.

## What to expect

Reports are handled on a best-effort basis. There is no service-level agreement, no
guaranteed response time, and no bounty programme — these are lab repositories
maintained alongside other work. You will get an acknowledgement, and then either a
fix or an explicit decision not to fix.

Reporters are credited in the published advisory unless you ask us not to. Where a
finding warrants one, we will request a CVE through the advisory; GitHub is a CNA
and can assign directly from it.

## Disclosure

We publish the advisory once a fix exists, and tell you before it goes public. Until
then, please hold off on disclosing.

That request comes with a limit, because asking for silence while promising no
timeline would otherwise be open-ended. If ninety days pass from your report without
a fix and without a substantive response from us, consider yourself free to publish.
You do not need our permission, and we will not treat it as a hostile act.

## Out of scope

| Case                       | Where it belongs                                                      |
| -------------------------- | --------------------------------------------------------------------- |
| Archived repositories      | Not maintained. They are retained for reference and will not be fixed |
| Forks of upstream projects | Report to the upstream project, which owns the code                   |

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
