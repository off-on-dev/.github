# Contributing to OffOn.dev

Thanks for taking the time to contribute! These guidelines apply across the
OffOn.dev organization. Individual repositories may add their own
`CONTRIBUTING.md` with project-specific details, which takes precedence.

## Code of Conduct

This project follows our [Code of Conduct](CODE_OF_CONDUCT.md). By
participating, you are expected to uphold it. Report unacceptable behavior to
**offondev@gmail.com**.

## Governance

OffOn.dev is **founder-led**: a Project Lead holds final say, supported by a
Governance Committee. How decisions are made, how the Committee is formed, and
how the project is protected from single-company control are described in
[GOVERNANCE.md](GOVERNANCE.md).

## Developer Certificate of Origin (DCO)

We use the [Developer Certificate of Origin](https://developercertificate.org/)
instead of a CLA — a lightweight statement that you have the right to submit your
contribution under the project's license.

Certify it by **signing off every commit**:

    git commit -s -m "Your message"

That appends a `Signed-off-by: Your Name <you@example.com>` line using your real
name. A CI check enforces sign-off on all commits in a pull request. To sign off
commits you already made:

    git rebase --signoff main

## Licensing of contributions

By contributing, you agree your contributions are licensed under the license(s)
of the repository you're contributing to, as declared in that repo's `LICENSE`,
`REUSE.toml`, and `LICENSES/` directory:

- **open-source-challenges** — code under MIT, written content under CC BY 4.0.
- **website** — code under MIT, written content under CC BY 4.0.

New files should carry an SPDX header (or be covered by the repo's `REUSE.toml`)
so `reuse lint` stays green, e.g.:

    # SPDX-FileCopyrightText: OffOn.dev contributors
    # SPDX-License-Identifier: MIT

The **OffOn** name and logo are reserved (see `TRADEMARK.md`); contributing does
not grant trademark rights.

## Making a change

1. Fork the repo and create a branch.
2. Make your change. Keep commits focused and sign them off (`-s`).
3. Run the repo's linters and tests before opening a PR (website:
   `npm run lint` and `npm test`).
4. Open a pull request and fill in the template. The CI checks (tests, REUSE,
   DCO) and any preview deploy must pass before review.

We appreciate every contribution.
