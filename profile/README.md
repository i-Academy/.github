<h1 align="center">i3 Academy</h1>

<p align="center">
  <strong>The open learning platform for organisations and independent learners.</strong><br>
  Courses, live sessions, required trainings and AI on your own account: open source, made in Europe.
</p>

<p align="center">
  <a href="https://academy.i3-innovation.com">Website</a> ·
  <a href="https://docs.academy.i3-innovation.com/en/">Documentation</a> ·
  <a href="https://docs.academy.i3-innovation.com/en/develop/architecture/">Architecture</a> ·
  <a href="https://academy.i3-innovation.com/security">Security</a>
</p>

---

i3 Academy brings everything an organisation needs to teach, train and prove it into one platform.
It covers self-paced courses, live classes and records an auditor accepts. AI runs on the
organisation's own provider account, and the code is open for anyone to run.

The platform is in a **public beta**. We build it in the open under the GNU AGPLv3. The hosted
service runs the same code, and there is no separate enterprise edition.

> [!NOTE]
> The repositories below introduce the projects first. The source code follows once the final tests
> of the public beta are complete.

### The projects

| Repository | What it is |
|---|---|
| [**portal**](https://github.com/i-Academy/portal) | The learning platform: web app, API, background services, database schema and the docs site. Start here. |
| [**admin**](https://github.com/i-Academy/admin) | The admin console a platform team uses to run an installation: operation, support, AI, finance, team. |
| [**learning-companion**](https://github.com/i-Academy/learning-companion) | The learning app for Android, Windows and Linux. It runs its AI on the device and keeps personal learning data there. |

### Principles

- **Open source, all of it.** One codebase under AGPL-3.0, for the hosted service and for every self-hosted installation.
- **Your AI, your account.** Organisations connect their own AI vendor and pay it directly. Nothing is resold.
- **Privacy by design.** Data is encrypted per organisation and access is controlled per row. The learning app keeps personal data on the device.
- **Standards, not lock-in.** SCORM, cmi5, xAPI, H5P, LTI 1.3, SCIM, OpenID Connect, SAML, Open Badges 3.0, webhooks, an automation API and MCP.
- **European.** Built in Estonia for the EU market, in six interface languages, with more prepared.

### Get involved

Read the [contribution guide](https://docs.academy.i3-innovation.com/en/develop/contributing/).
Report bugs and ideas in the repository they belong to. Report vulnerabilities privately through
the repository's **Security** tab.
