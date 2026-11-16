# Eclipse Leshan™ Website

Source code of the [Eclipse Leshan™](https://github.com/eclipse-leshan/leshan) project website,
published at **https://eclipse.dev/leshan/**.

Eclipse Leshan is an OMA Lightweight M2M (LWM2M) server and client implementation in Java.
The library itself, its demos and its documentation live in the main repository:
https://github.com/eclipse-leshan/leshan

## About this repository

This is a simple static website: plain HTML, CSS and JavaScript, with no build step
and no package manager.

```
.
├── index.html   # The website (single page)
├── css/         # Stylesheets
├── img/         # Images and logos
└── js/          # Scripts
```

## Run it locally

No installation is needed. Clone the repository and open `index.html` in your browser:

```bash
git clone https://github.com/eclipse-leshan/leshan-website.git
cd leshan-website
```

Or serve it with any static file server, for example:

```bash
python3 -m http.server 8000
```

Then browse to http://localhost:8000.

## Deployment

The website is deployed automatically by the Eclipse Foundation infrastructure:
the `main` branch is published at https://eclipse.dev/leshan/, so changes merged
into it go live without any manual step.

## Contributing

Contributions such as typo fixes, content updates and design improvements are welcome.

1. Fork the repository and create a branch from `main`.
2. Edit the files and check the result locally.
3. Open a pull request describing your change.

Eclipse Foundation projects require contributors to sign the
[Eclipse Contributor Agreement (ECA)](https://www.eclipse.org/legal/ECA.php).
See also the [Leshan contribution guide](https://github.com/eclipse-leshan/leshan/blob/main/CONTRIBUTING.md).

## Contact

- Website issues: [GitHub issues](https://github.com/eclipse-leshan/leshan-website/issues)
- Leshan questions and bugs: [main project issues](https://github.com/eclipse-leshan/leshan/issues)

## Security

To report a vulnerability, please follow the repository's
[security policy](https://github.com/eclipse-leshan/leshan-website/security/policy)
rather than opening a public issue.

## License

This work is licensed under the Eclipse Public License v2.0

`SPDX-License-Identifier: EPL-2.0`