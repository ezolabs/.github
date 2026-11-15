<a href="https://ezolabs.io"><img src="https://raw.githubusercontent.com/ezolabs/.github/main/profile/assets/banner.png" alt="EZO Labs. AI that works for you: custom AI, built for your company." width="100%"></a>

<p align="center">
  <a href="https://ezolabs.io"><img src="https://img.shields.io/badge/ezolabs.io-3b6ef6?style=flat" alt="ezolabs.io" height="28"></a>&nbsp;
  <a href="https://ezolabs.io/research"><img src="https://img.shields.io/badge/research-30363d?style=flat" alt="research" height="28"></a>&nbsp;
  <a href="https://ezolabs.io/security"><img src="https://img.shields.io/badge/security-30363d?style=flat" alt="security" height="28"></a>&nbsp;
  <a href="https://ezolabs.io/enterprise"><img src="https://img.shields.io/badge/enterprise-30363d?style=flat" alt="enterprise" height="28"></a>&nbsp;
  <a href="https://x.com/ezolabsinc"><img src="https://img.shields.io/badge/x-30363d?style=flat" alt="x" height="28"></a>&nbsp;
  <a href="https://www.linkedin.com/company/ezolabs"><img src="https://img.shields.io/badge/linkedin-30363d?style=flat" alt="linkedin" height="28"></a>
</p>

We unlock the gains of AI inside your company: custom AI apps, fine-tuned models, forward deployed engineers and AI security from EZO Labs Security, our security practice. This is where we publish the code we open up.

| Project | What it does | Links |
| --- | --- | --- |
| [**ezo‑watcher**](https://github.com/ezolabs/ezo-watcher)<br><sub>agent tools</sub> | The open-source AI SRE for your project. Monitoring your coding agent installs, proves and fixes. | [![live demo](https://img.shields.io/badge/live%20demo-3b6ef6?style=flat)](https://ezo-watcher-demo.pages.dev) [![npm](https://img.shields.io/npm/v/ezo-watcher?style=flat&color=30363d)](https://www.npmjs.com/package/ezo-watcher) [![MIT](https://img.shields.io/badge/MIT-30363d?style=flat)](https://github.com/ezolabs/ezo-watcher/blob/main/LICENSE) [![MCP server](https://img.shields.io/badge/MCP%20server-30363d?style=flat)](https://github.com/ezolabs/ezo-watcher#mcp) |
| [**reqsk‑uaf‑check**](https://github.com/ezolabs/reqsk-uaf-check)<br><sub>security</sub> | Tells you whether a Linux host carries the fix for the TCP request-socket use-after-free. One read-only script. | [![MIT](https://img.shields.io/badge/MIT-30363d?style=flat)](https://github.com/ezolabs/reqsk-uaf-check/blob/main/LICENSE) [![CVE-2026-99270](https://img.shields.io/badge/CVE--2026--99270-e5534b?style=flat)](https://www.cve.org/CVERecord?id=CVE-2026-99270) |
| [**megakernel‑b300**](https://github.com/ezolabs/megakernel-b300)<br><sub>research</sub> | DeepSeek-V4.1-Flash's fastest one-user decode past 1,000 tok/s on 4x B300, with NVIDIA's megakernel. The patch, the measured record and the setup kit. | [![article](https://img.shields.io/badge/article-3b6ef6?style=flat)](https://ezolabs.io/research/megakernel-b300) [![B300 patch](https://img.shields.io/badge/B300%20patch-30363d?style=flat)](https://github.com/ezolabs/megakernel-b300/tree/main/setup/patches) [![MIT](https://img.shields.io/badge/MIT-30363d?style=flat)](https://github.com/ezolabs/megakernel-b300/blob/main/LICENSE) [![results](https://img.shields.io/badge/results-30363d?style=flat)](https://github.com/ezolabs/megakernel-b300#results) |
| [**make.fun**](https://make.fun/?utm_source=github-ezolabs&utm_medium=profile&utm_campaign=entity-2026-11)<br><sub>agent tools</sub> | Our coding-bounty platform: people and their AI agents earn USDC by winning coding bounties. The example agent, its Agent Skill and Claude Code plugin are open. | [![example agent](https://img.shields.io/badge/example%20agent-3b6ef6?style=flat)](https://github.com/makedotfun/example-agent) [![MIT](https://img.shields.io/badge/MIT-30363d?style=flat)](https://github.com/makedotfun/example-agent/blob/main/LICENSE) [![MCP server](https://img.shields.io/badge/MCP%20server-30363d?style=flat)](https://github.com/makedotfun/makefun-mcp) |

### Security advisories

EZO Labs Security reports vulnerabilities upstream and follows each one through coordinated disclosure. Maintainers publish the advisory and credit [superbot-helper](https://github.com/superbot-helper), the account our reports are filed from.

<p align="center">
  <img src="https://img.shields.io/badge/7%20credited%20advisories-3b6ef6?style=flat" alt="7 credited advisories" height="28">&nbsp;
  <img src="https://img.shields.io/badge/highest%20severity%20high%207.8-e5534b?style=flat" alt="highest severity high 7.8" height="28">&nbsp;
  <a href="https://ezolabs.net/security"><img src="https://img.shields.io/badge/security%20page-30363d?style=flat" alt="security page" height="28"></a>
</p>

| Severity | Advisory | Project | What it was | Fixed in |
| --- | --- | --- | --- | --- |
| ![high 7.8](https://img.shields.io/badge/high%207.8-e5534b?style=flat) | [GHSA-6hqx-gqrx-c5r2](https://github.com/modelcontextprotocol/servers/security/advisories/GHSA-6hqx-gqrx-c5r2) | [modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers)<br><sub><code>mcp-server-git</code> · 92k stars</sub> | Arbitrary command execution through the repository's own Git config, triggered by read-only tools | 2026.11.11 |
| ![high 7.5](https://img.shields.io/badge/high%207.5-e5534b?style=flat) | [GHSA-xxvx-vcj6-rjq5](https://github.com/i18next/i18next-http-middleware/security/advisories/GHSA-xxvx-vcj6-rjq5) | [i18next/i18next-http-middleware](https://github.com/i18next/i18next-http-middleware)<br><sub><code>i18next-http-middleware</code> · 382k downloads/wk</sub> | Made-up namespaces posted to missingKeyHandler permanently slow down every later request | 3.10.2 |
| ![high 7.5](https://img.shields.io/badge/high%207.5-e5534b?style=flat) | [GHSA-4597-5x94-x3xg](https://github.com/J-F-Liu/lopdf/security/advisories/GHSA-4597-5x94-x3xg) | [J-F-Liu/lopdf](https://github.com/J-F-Liu/lopdf)<br><sub><code>lopdf</code> · 2.3k stars</sub> | Stack overflow via a chain of stream /Length references | no fixed release yet |

The full table is on the [reporting account's profile](https://github.com/superbot-helper).

### Get in touch

Work with us: [contact@ezolabs.io](mailto:contact@ezolabs.io). Report a vulnerability privately: [security@ezolabs.io](mailto:security@ezolabs.io).
