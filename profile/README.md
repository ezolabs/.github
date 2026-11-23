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

EZO Labs Security reports vulnerabilities upstream and follows each one through coordinated disclosure. Maintainers publish the advisory and credit [superbot-helper](https://github.com/superbot-helper), the account our reports are filed from, as reporter or, where marked, as analyst.

<p align="center">
  <img src="https://img.shields.io/badge/50%20credited%20advisories-3b6ef6?style=flat" alt="50 credited advisories" height="28">&nbsp;
  <img src="https://img.shields.io/badge/highest%20severity%20critical%209.8-e5534b?style=flat" alt="highest severity critical 9.8" height="28">&nbsp;
  <a href="https://ezolabs.net/security"><img src="https://img.shields.io/badge/security%20page-30363d?style=flat" alt="security page" height="28"></a>
</p>

| Severity | Advisory | Project | What it was | Fixed in |
| --- | --- | --- | --- | --- |
| ![critical 9.8](https://img.shields.io/badge/critical%209.8-e5534b?style=flat) | [GHSA-h924-jfhp-9vjr](https://github.com/christianhelle/refitter/security/advisories/GHSA-h924-jfhp-9vjr) | [christianhelle/refitter](https://github.com/christianhelle/refitter)<br><sub><code>Refitter</code>, <code>Refitter.Core</code>, <code>Refitter.MSBuild</code>, <code>Refitter.SourceGenerator</code></sub> | Schema property names, discriminator fields, defaults and enum values are emitted into C# literals unescaped | 2.4.1 |
| ![critical 9.4](https://img.shields.io/badge/critical%209.4-e5534b?style=flat) | [GHSA-mwmx-rgj6-f8mc](https://github.com/Privasys/identity-platform/security/advisories/GHSA-mwmx-rgj6-f8mc) | [Privasys/identity-platform](https://github.com/Privasys/identity-platform)<br><sub><code>identity-platform-idp</code></sub> | A pending sign-in session could be completed as any account the request names | 0.3.105 |
| ![critical 9.3](https://img.shields.io/badge/critical%209.3-e5534b?style=flat) | [GHSA-fxh8-363w-wx5g](https://github.com/Privasys/identity-platform/security/advisories/GHSA-fxh8-363w-wx5g) | [Privasys/identity-platform](https://github.com/Privasys/identity-platform)<br><sub><code>identity-platform-idp</code></sub> | An app holding a token issued to it could act as the user at the identity provider's account endpoints | 0.3.106 |
| ![critical 9.2](https://img.shields.io/badge/critical%209.2-e5534b?style=flat) | [GHSA-cjh8-m3cm-xw57](https://github.com/Privasys/platform-gateway/security/advisories/GHSA-cjh8-m3cm-xw57) | [Privasys/platform-gateway](https://github.com/Privasys/platform-gateway)<br><sub><code>platform-gateway</code></sub> | A client with no credential can exhaust the gateway's memory with oversized sealed WebSocket messages | 0.6.1 |

<!-- cve records:begin -->
**CVE records.** CVE ids assigned to findings we reported:

[CVE-2026-132133](https://www.cve.org/CVERecord?id=CVE-2026-132133), [CVE-2026-132267](https://github.com/i18next/i18next-http-middleware/security/advisories/GHSA-mjcw-gfh6-3cxm) (reserved, record not yet published)

**CVE ids we requested.** For a fix others reported and wrote:

[CVE-2026-99270](https://www.cve.org/CVERecord?id=CVE-2026-99270)
<!-- cve records:end -->

<!-- vendor notices:begin -->
**Vendor notices.** Public notices from vendors that name EZO Labs Security for a report, and advisories that name the practice only in their credits text. They are not accepted reporter credits and are not counted above.

| Notice | Project | What we reported |
| --- | --- | --- |
| [GHSA-9426-q567-pc36](https://github.com/MervinPraison/PraisonAI/security/advisories/GHSA-9426-q567-pc36) | [MervinPraison/PraisonAI](https://github.com/MervinPraison/PraisonAI)<br><sub><code>praisonaiagents</code>, <code>praisonai</code>, <code>praisonai-code</code>, <code>praisonai-bot</code>, <code>praisonai-mcp</code>, <code>praisonai-sandbox</code>, <code>praisonai-browser</code>, <code>praisonai-deploy</code></sub> | the vendor's advisory names superbot-helper in its credits text, not its accepted reporter credit; our report of the npm serve host-guard bypass was folded into this consolidated advisory. |
| [T16943](https://we.phorge.it/T16943)<br><sub>[J18](https://we.phorge.it/J18)</sub><br><sub>[J19](https://we.phorge.it/J19)</sub> | [phorgeit/phorge](https://github.com/phorgeit/phorge) | we reported that file.uploadchunk accepts a chunk from any member who can view a partial upload, so a member can replace bytes in another member's upload in progress; the vendor's public task is authored by EZO Labs Security, and the fix is in rPcd747af84672 (master) and rPd26d0cac53a2 (stable) |
| [seafile-13.0.30](https://plus.seafile.com/wiki/publish/seafile-wiki/O50D/) | [haiwen/seahub](https://github.com/haiwen/seahub) | We would like to thank EZO Labs Security and superbot-helper for responsibly reporting this vulnerability. |
| [mime-tools-5.523](https://metacpan.org/release/DSKOLL/MIME-tools-5.523/changes) | [DSKOLL/MIME-tools](https://metacpan.org/dist/MIME-tools) | Bug found and fixed by EZO Labs Security. |
| [golang-vulndb-7027](https://github.com/golang/vulndb/issues/7027) | [go-ap/auth](https://github.com/go-ap/auth) | The findings were correct, and EZO Labs helped also with the mitigation. |
| [startos-0.4.3-rc.3](https://github.com/Start9Labs/start-technologies/releases/tag/start-os/v0.4.3-rc.3) | [Start9Labs/start-technologies](https://github.com/Start9Labs/start-technologies) | Require authentication for registry requests relayed through the server, preventing anyone who can reach its interface from directing it to connect to hosts on its own network. Thanks to EZO Labs Security for reporting this. |
| [CVE-2026-114938](https://www.cve.org/CVERecord?id=CVE-2026-114938)<br><sub>[apolloconfig/apollo#5719](https://github.com/apolloconfig/apollo/discussions/5719)</sub> | [apolloconfig/apollo](https://github.com/apolloconfig/apollo)<br><sub><code>apollo-configservice</code>, <code>apollo-adminservice</code>, <code>apollo-portal</code></sub> | we reported to Apollo Config that its official 3.0.0 images ship the affected Java runtime, which decodes Basic headers before authentication; the CVE itself is OpenJDK's, and Apollo's public notice names EZO Labs Security as the reporter |
<!-- vendor notices:end -->

The full table is on the [reporting account's profile](https://github.com/superbot-helper).

### Get in touch

Work with us: [contact@ezolabs.io](mailto:contact@ezolabs.io). Report a vulnerability privately: [security@ezolabs.io](mailto:security@ezolabs.io).
