# Benjamin Kincses

Full-stack developer and security researcher from Hungary.

I spend most of my time on open source and security research. I find real bugs, fix them, and get the fixes merged. When I find flaws in other people's code, I prove them first, then report them.

## Open source

47 merged pull requests across open source so far, in my current sprint toward 100. My work sits in mypy, Home Assistant, Payload CMS, Medusa, pnpm, prettier plugin-php, and a long list of smaller projects. I prefer fixes with tests over drive-by changes, and I stay on a thread until the maintainer is satisfied.

## Security research

Code audits and bug bounties. Active on HackerOne, Bugcrowd, Intigriti, and YesWeHack. Every finding gets a working proof of concept before it is reported.

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

## My own builds

- [lazycommit](https://github.com/Dextheking1/lazycommit): commit messages written from the actual diff. The clerical part of git, automated.
- [ShipCheck](https://github.com/Dextheking1/shipcheck): pre-flight checks for shipping web projects, built after one too many broken deploys.
- [DepVet](https://github.com/Dextheking1/depvet): dependency vetting for safer installs, built for a hackathon and kept alive after it.
- [benihacking.top](https://benihacking.top): my portfolio. Work history, write-ups, contact.

## Stack

TypeScript and JavaScript, Python, PHP. Node.js, React, Next.js. WordPress and WooCommerce when the job calls for it. Linux, Docker, Git, GitHub Actions. Burp Suite and the usual audit tooling on the security side.

## Contact

- GitHub: you are here.
- Portfolio and contact form: [benihacking.top](https://benihacking.top)
- Writing: [dev.to/dextheking1](https://dev.to/dextheking1)
- Security reports: if I filed an advisory on your project, reply on the advisory. It is the fastest route to me.
