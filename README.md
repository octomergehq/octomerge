<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/banner-dark.png">
    <img alt="Octomerge: an agent workspace for your machines, your tools and your choice of model. Continued from anywhere." src=".github/assets/banner-light.png" width="100%">
  </picture>
</p>

Octomerge is an agent workspace in the cloud. Configure your agents once and run them on any machine you connect, with the models you already pay for, mixing providers in one conversation. Follow and steer every session from a phone, another laptop or the terminal.

This repository holds Octomerge's user manual and its public issue tracker.

- **Use Octomerge:** [octomerge.dev](https://octomerge.dev)
- **Read the manual:** [docs.octomerge.dev](https://docs.octomerge.dev)
- **Report a problem:** [open an issue](https://github.com/octomergehq/octomerge/issues/new/choose)

## Report a problem

Found a bug in Octomerge, or a mistake in the manual? Search the [open issues](https://github.com/octomergehq/octomerge/issues) first: if someone has reported it, add what you see there. Otherwise [open an issue](https://github.com/octomergehq/octomerge/issues/new/choose) and choose **Bug report**. A good report says:

- what you did, what you expected and what happened instead;
- where it happened: the app, an agent's conversation, one of the command-line tools (`otti`, `otti-worker`, `otti-browser`, `otti-macos-vm`) or the manual;
- the versions involved (`otti --version`; a worker's version is in **Settings → Workers**), your operating system and, for the app, your browser.

Issues are public. Leave out secrets, tokens, private repository contents and anything else you wouldn't post publicly.

- **An idea or a missing feature:** open a [feature request](https://github.com/octomergehq/octomerge/issues/new?template=feature_request.yml).
- **A security vulnerability:** don't open an issue. Email [contact@octomerge.dev](mailto:contact@octomerge.dev) ([SECURITY.md](SECURITY.md)).
- **Plans, teams and Enterprise:** use the [contact form](https://octomerge.dev/contact).

## The manual

[`docs/`](docs) is the manual, in [Mintlify](https://mintlify.com)'s format: `docs/docs.json` sets its navigation, and each page is an MDX file. docs.octomerge.dev is built from this repository's `main` branch, which describes the Octomerge that runs at octomerge.dev.

The manual is written by Octomerge's maintainers, who take pull requests only from collaborators. To point out a mistake or a gap in it, open an issue.

## Licence

The manual is licensed under [Creative Commons Attribution 4.0 International](LICENSE) (CC BY 4.0): you may share and adapt it, also commercially, if you credit Octomerge and link the licence. The name Octomerge, Otti and the Octomerge logos are Octomerge's trademarks and aren't covered by the licence.

© 2026 Octomerge
