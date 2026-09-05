# Contributing

This is the LABSONLINE organization-wide default. It applies to every repository in
the organization that does not carry its own `CONTRIBUTING.md`, whatever that
repository's visibility.

If you are a member working in a private or internal repository, the member handbook
governs and the read-only default below does not apply to you. What follows is
addressed to contributors from outside the organization.

## The default is read-only

Public repositories here are lab material, published for reference rather than
assembled into projects seeking contributors. Unless a repository says otherwise:

- Contributions are not solicited, and a pull request may be closed without review.
- Issues are read, but opening one carries no promise of a response or a fix.
- Nothing here comes with a support commitment. It is offered as-is.

This reflects available capacity rather than disinterest. The work is published
because it may be useful to read, not because it is staffed to be maintained on your
behalf.

## A repository may say otherwise

The default above is a floor, not a ceiling. Any repository is free to set its own
posture, and where it does, that posture governs. Precedence, highest first:

1. A `CONTRIBUTING.md` in the repository itself, which supersedes this file
   entirely.
2. A contribution policy stated in the repository's README.
3. This file.

Check the repository before assuming the default applies.

## If a repository does accept contributions

The estate's conventions apply. Sign-off is enforced organization-wide, so a commit
without it is rejected at push rather than flagged in review. The rest are
conventions you are expected to follow.

| Requirement    | What it means                                                                       |
| -------------- | ----------------------------------------------------------------------------------- |
| Default branch | Confirm it rather than assuming `main` — `altera_workshops` uses `DE25-Nano`        |
| Editor config  | Honour the repository's `.editorconfig`; do not reformat around it                  |
| Signed commits | Commits are expected to be signed — see [signature verification][signing]           |
| Sign-off       | Enforced organization-wide, web edits included — see the [sign-off policy][signoff] |
| Licensing      | Original repositories are GPL-3.0, and contributions are accepted under those terms |

Forks of upstream projects are the exception throughout: they follow their
upstream's licensing and conventions, and changes belong upstream rather than here.

Keep a pull request to one subject, and describe what you changed and why. A change
that alters behaviour should say how you verified it.

## Security issues

> [!CAUTION]
> Never report a security vulnerability through a pull request or a public issue.
> Use the private route in [SECURITY.md][security].

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

[security]: https://github.com/labsonline/.github/blob/main/SECURITY.md
[signing]: https://docs.github.com/en/authentication/managing-commit-signature-verification
[signoff]: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/managing-repository-settings/managing-the-commit-signoff-policy-for-your-repository
