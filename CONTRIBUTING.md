# Contributing

This is the default for my repositories. It applies to any repository that does not
carry its own `CONTRIBUTING.md`, whatever that repository's visibility.

## The default is read-only

These are personal repositories, published for reference rather than assembled into
projects seeking contributors. Unless a repository says otherwise:

- Contributions are not solicited, and a pull request may be closed without review.
- Issues are read, but opening one carries no promise of a response or a fix.
- Nothing here comes with a support commitment. It is offered as-is.

This reflects available capacity rather than disinterest. The work is published
because it may be useful to read, and it is maintained alongside a job.

## A repository may say otherwise

The default above is a floor, not a ceiling. Any repository is free to set its own
posture, and where it does, that posture governs. Precedence, highest first:

1. A `CONTRIBUTING.md` in the repository itself, which supersedes this file entirely.
2. A contribution policy stated in the repository's README.
3. This file.

Check the repository before assuming the default applies. [sandbox][sandbox] is the
live example: it carries its own `CONTRIBUTING.md` and `SECURITY.md`, and those govern
it rather than anything written here.

## If a repository does accept contributions

My conventions apply.

| Requirement    | What it means                                                                                         |
| -------------- | ----------------------------------------------------------------------------------------------------- |
| Default branch | Confirm it rather than assuming `main`                                                                |
| Editor config  | Honour the repository's `.editorconfig`; do not reformat around it                                    |
| Signed commits | Required, and enforced by ruleset on repositories that carry one — see [verified signatures][signing] |
| Sign-off       | Required on every commit; `git commit -s`, per the [DCO][dco]                                         |
| Licensing      | My repositories are GPL-3.0, and contributions are accepted under those terms                         |

Keep a pull request to one subject, and describe what you changed and why. A change
that alters behaviour should say how you verified it.

Forks of upstream projects are the exception throughout: they follow their upstream's
licensing and conventions, and changes belong upstream rather than here.

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

[dco]: https://developercertificate.org/
[sandbox]: https://github.com/sanselme/sandbox
[security]: https://github.com/sanselme/sanselme/blob/main/SECURITY.md
[signing]: https://docs.github.com/en/authentication/managing-commit-signature-verification
