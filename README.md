<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:000000,50:003311,100:00ff41&height=170&section=header&text=BENJAMIN%20KINCSES&fontSize=40&fontColor=00ff41&animation=fadeIn&fontAlignY=35&desc=full-stack%20developer%20//%20security%20researcher&descSize=15&descAlignY=58" width="100%"/>

```
______ _____ _   _ _____ _   _   ___  _____  _   _______ _   _ _____
| ___ \  ___| \ | |_   _| | | | / _ \/  __ \| | / /_   _| \ | |  __ \
| |_/ / |__ |  \| | | | | |_| |/ /_\ \ /  \/| |/ /  | | |  \| | |  \/
| ___ \  __|| . ` | | | |  _  ||  _  | |    |    \  | | | . ` | | __
| |_/ / |___| |\  |_| |_| | | || | | | \__/\| |\  \_| |_| |\  | |_\ \
\____/\____/\_| \_/\___/\_| |_/\_| |_/ \____/\_| \_/\___/\_| \_/\____/
```

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&pause=1100&color=00FF41&center=true&vCenter=true&width=640&lines=find+the+bug.+prove+it.+fix+it.+merge+it.;bug+bounty+hunter;open+source+contributor;security+researcher+from+hungary" alt="typing animation"/>

</div>

```bash
$ whoami
benjamin kincses — full-stack developer & security researcher, hungary

$ cat mission.txt
find real bugs in other people's code. prove every one of them.
fix them properly, with tests. get the fix merged.

$ ./status --now
50 PRs merged in the current sprint to 100, across mypy, Home Assistant,
Payload CMS, pnpm, Medusa, prettier/plugin-php and more.
10 CVEs published on WPScan on 2026-11-09, listed below.
first paid bug bounty accepted on YesWeHack.
```

<div align="center">

![GitHub](https://img.shields.io/badge/GitHub-benjaminkincses-181717?style=for-the-badge&logo=github)
![GitLab](https://img.shields.io/badge/GitLab-benjaminkincses-FC6D26?style=for-the-badge&logo=gitlab)
![X](https://img.shields.io/badge/X-@benihacking-000000?style=for-the-badge&logo=x)
![HackerOne](https://img.shields.io/badge/HackerOne-zer0__c0ol-111111?style=for-the-badge)
![Bugcrowd](https://img.shields.io/badge/Bugcrowd-Cor-F26522?style=for-the-badge)
![Intigriti](https://img.shields.io/badge/Intigriti-zero__cool-1B1B3A?style=for-the-badge)
![YesWeHack](https://img.shields.io/badge/YesWeHack-zero__cool-E4002B?style=for-the-badge)

<img src="https://skillicons.dev/icons?i=ts,js,python,php,nodejs,react,nextjs,linux,docker,git,github,gitlab,bash" alt="stack icons"/>

</div>

## ~/open-source

I spend most of my time on open source and security research. I find real bugs, fix them, and get the fixes merged. 50 merged pull requests in my current sprint toward 100, sitting in mypy, Home Assistant, Payload CMS, Medusa, pnpm, prettier plugin-php, and a long list of smaller projects. I prefer fixes with tests over drive-by changes, and I stay on a thread until the maintainer is satisfied.

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=benjaminkincses&theme=github_dark" alt="profile details" width="100%"/>
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=benjaminkincses&theme=github_dark" alt="github stats"/>
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=benjaminkincses&theme=github_dark" alt="repos per language"/>

</div>

## ~/security-research

Code audits and bug bounties. Active on HackerOne, Bugcrowd, Intigriti, and YesWeHack. Every finding gets a working proof of concept before it is reported. No proof, no report.

**Published on WPScan, 2026-11-09: 10 CVEs in Security For WooCommerce <= 1.0.16**

All 10 unauthenticated, all credited to me on WPScan, no fix available:

- [CVE-2026-123696](https://wpscan.com/vulnerability/60efadce-ae1b-448c-9e9c-aa65ee5e028d), two-factor authentication reset, CVSS 7.5
- [CVE-2026-123697](https://wpscan.com/vulnerability/58f2562b-e108-46ab-92bb-3430109dab1f), two-factor code and secret disclosure, CVSS 7.5
- [CVE-2026-123698](https://wpscan.com/vulnerability/f13ecbe7-8abb-4736-be5c-fd38f402181c), plugin settings disclosure via REST API, CVSS 5.3
- [CVE-2026-123699](https://wpscan.com/vulnerability/344ca520-dc28-4d52-a400-559d23359d23), forced plugin, theme and core updates, CVSS 4.8
- [CVE-2026-123700](https://wpscan.com/vulnerability/3facdee3-eb7e-458c-b496-9946f8e2d1f0), mass comment deletion, CVSS 7.5
- [CVE-2026-123701](https://wpscan.com/vulnerability/9d65f64f-b9d5-488d-a81d-4013a1b1fc9e), plugin settings reset, CVSS 5.3
- [CVE-2026-123702](https://wpscan.com/vulnerability/28de2af4-74aa-497d-9f1a-69d40c72fea5), wp-config keys and salts reset and denial of service, CVSS 6.5
- [CVE-2026-123703](https://wpscan.com/vulnerability/6b255385-26ae-416c-8c2d-a673508aa212), arbitrary user logout, CVSS 5.3
- [CVE-2026-123704](https://wpscan.com/vulnerability/b7e8fa76-32c0-48ea-a685-2a75ffe94cd1), administrator email address disclosure, CVSS 5.3
- [CVE-2026-123705](https://wpscan.com/vulnerability/cb9bbd7a-c13a-4129-a910-45746af203ce), server configuration information disclosure, CVSS 5.3

The same list is on my [research page](https://benihacking.top/research.html).

Filed GitHub security advisories:

**Octopus-SI-OS**
- [GHSA-c558-f85p-7349](https://github.com/miuuyy/Octopus-SI-OS/security/advisories/GHSA-c558-f85p-7349), High
- [GHSA-2j3j-m84x-gjfh](https://github.com/miuuyy/Octopus-SI-OS/security/advisories/GHSA-2j3j-m84x-gjfh), Moderate
- [GHSA-82h9-785j-3rj4](https://github.com/miuuyy/Octopus-SI-OS/security/advisories/GHSA-82h9-785j-3rj4), Moderate
- [GHSA-qmhj-fjrr-g529](https://github.com/miuuyy/Octopus-SI-OS/security/advisories/GHSA-qmhj-fjrr-g529), Low
- [GHSA-32mw-j8wg-r86j](https://github.com/miuuyy/Octopus-SI-OS/security/advisories/GHSA-32mw-j8wg-r86j), Low

**Nacos**
- [GHSA-q43p-chvx-vpx2](https://github.com/alibaba/nacos/security/advisories/GHSA-q43p-chvx-vpx2), High, config authorization cluster
- [GHSA-hm4f-5v62-vrm2](https://github.com/alibaba/nacos/security/advisories/GHSA-hm4f-5v62-vrm2), Moderate, unauthenticated gRPC lock handler
- [GHSA-vffc-gmfm-fwh5](https://github.com/alibaba/nacos/security/advisories/GHSA-vffc-gmfm-fwh5), Moderate, unauthenticated admin bootstrap
- [GHSA-mjpp-mhh4-69j9](https://github.com/alibaba/nacos/security/advisories/GHSA-mjpp-mhh4-69j9), High, OIDC authorization fails open
- [GHSA-3qwh-8qph-35mg](https://github.com/alibaba/nacos/security/advisories/GHSA-3qwh-8qph-35mg), High, rolling upgrade latch disables cluster auth
- [GHSA-qg9f-29q9-5f9x](https://github.com/alibaba/nacos/security/advisories/GHSA-qg9f-29q9-5f9x), Moderate, cipher configs stored in plaintext

**Experiential**
- [GHSA-3fwg-p649-gfhr](https://github.com/experientiallabs/experiential/security/advisories/GHSA-3fwg-p649-gfhr), High, batch grant bypass
- [GHSA-5mj6-3wwp-4627](https://github.com/experientiallabs/experiential/security/advisories/GHSA-5mj6-3wwp-4627), High, budget bundle
- [GHSA-8v36-qh6v-jgq4](https://github.com/experientiallabs/experiential/security/advisories/GHSA-8v36-qh6v-jgq4), High, capture working directory code execution
- [GHSA-h5mm-j8x5-rh37](https://github.com/experientiallabs/experiential/security/advisories/GHSA-h5mm-j8x5-rh37), Moderate, planted .env leaks gateway key
- [GHSA-g97v-p7hf-cxq6](https://github.com/experientiallabs/experiential/security/advisories/GHSA-g97v-p7hf-cxq6), Moderate, unauthenticated Pi agent bridge
- [GHSA-p6vv-xw4p-p5vp](https://github.com/experientiallabs/experiential/security/advisories/GHSA-p6vv-xw4p-p5vp), Low, gateway usage and metrics without auth

**OpenCode**
- [GHSA-cvp8-pmjf-grpr](https://github.com/anomalyco/opencode/security/advisories/GHSA-cvp8-pmjf-grpr), High, stored XSS on share pages
- [GHSA-6cwg-8rrp-47rr](https://github.com/anomalyco/opencode/security/advisories/GHSA-6cwg-8rrp-47rr), Moderate, webfetch redirect SSRF

**GhidraMCP**
- [GHSA-77r9-34rq-86x4](https://github.com/bethington/ghidra-mcp/security/advisories/GHSA-77r9-34rq-86x4), High, combined advisory

**Robo**
- [GHSA-q6qf-27wx-9gpm](https://github.com/igniteenow/robo/security/advisories/GHSA-q6qf-27wx-9gpm), High, combined advisory

## ~/builds

- [lazycommit](https://github.com/benjaminkincses/lazycommit): commit messages written from the actual diff. The clerical part of git, automated.
- [ShipCheck](https://github.com/benjaminkincses/shipcheck): pre-flight checks for shipping web projects, built after one too many broken deploys.
- [DepVet](https://github.com/benjaminkincses/depvet): dependency vetting for safer installs, built for a hackathon and kept alive after it.
- [benihacking.top](https://benihacking.top): my portfolio. Work history, write-ups, contact.

## ~/stack

TypeScript and JavaScript, Python, PHP. Node.js, React, Next.js. WordPress and WooCommerce when the job calls for it. Linux, Docker, Git, GitHub Actions. Burp Suite and the usual audit tooling on the security side.

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/benjaminkincses/benjaminkincses/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/benjaminkincses/benjaminkincses/output/github-contribution-grid-snake.svg">
  <img alt="contribution snake eating my graph" src="https://raw.githubusercontent.com/benjaminkincses/benjaminkincses/output/github-contribution-grid-snake-dark.svg">
</picture>

</div>

## ~/contact

- GitHub: you are here.
- Portfolio and contact form: [benihacking.top](https://benihacking.top)
- Writing: [dev.to/benjaminkincses](https://dev.to/benjaminkincses)
- Security reports: if I filed an advisory on your project, reply on the advisory. It is the fastest route to me.

<div align="center">

<img src="https://komarev.com/ghpvc/?username=benjaminkincses&color=00ff41&style=flat-square&label=profile+views" alt="profile views"/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ff41,50:003311,100:000000&height=110&section=footer" width="100%"/>

</div>
