<div align="center">

<img src="https://raw.githubusercontent.com/farhan6667/farhan6667/main/assets/sfa-logo.webp" height="110" alt="SFA logo">

# Syed Farhan Ahmed

**Head of Cyber Security · Lead Penetration Tester**

Penetration testing · Digital forensics and incident response · Detection engineering · Security leadership

[Portfolio](https://farhan6667.github.io/portfolio/) ·
[LinkedIn](https://www.linkedin.com/in/sfa6667) ·
[NexaForge](https://nexaforge.eu.cc/) ·
[Email](mailto:nexaforge.services@gmail.com)

</div>

## About

I'm a cyber security leader and lead penetration tester based in Karachi, Pakistan, with 15 years in IT and the last nine in security. I lead security across offensive testing, defence and governance, and I stay hands on: I test applications myself, investigate incidents, and build the detections that catch the next attempt.

- **Offensive security.** Web, mobile and network penetration testing, vulnerability assessment and red team work.
- **Digital forensics and incident response.** Mobile and Windows forensics, evidence handling, ransomware response and threat hunting.
- **Detection engineering and SOC.** SIEM and EDR operations with Wazuh, mapped to MITRE ATT&CK.
- **Security leadership and compliance.** Building and leading a security team, ISO/IEC 27001 and risk management.

**Certifications:** PNPT, CEH, eJPT, CHFI, CISM, CISA, CSA (Certified SOC Analyst) and ISO/IEC 27001 Information Security Associate. The [portfolio](https://farhan6667.github.io/portfolio/) lists all of them with their issuers.

**Recognition:** acknowledged for responsible vulnerability reports by HackerOne (ranked #7 in Pakistan), OPPO, AT&T, Mastercard, Rockstar Games and other companies.

## How I use AI-assisted coding

When I run into a real problem that no good tool solves, I build one. I use AI-assisted development (vibe coding) to get from the need to a working tool quickly, then I review and test the result the way I would any code that touches security: threat model first, least privilege, no secrets in the code, and tests that fail when the behaviour breaks. The tools below come from my own work, and I release them as open source so other people can use them and improve them.

## Open source tools

### [Wazuh RuleGuard](https://github.com/farhan6667/wazuh-ruleguard)

A rule exception can silence the sample you tested and still affect detections you need. RuleGuard checks a JSON suite of sample logs against the Wazuh 4.x logtest API, compares runs before and after a rule change or upgrade, lints rule files for rules that load but never match, and shows which ATT&CK techniques your tests cover. Reports come as JSON, JUnit XML, Markdown and a readable offline HTML page.

### [Wazuh NoiseLens](https://github.com/farhan6667/wazuh-noiselens)

Before you suppress a busy rule, find out which alerts the exception would hide. NoiseLens reads exported Wazuh alerts offline, counts matches for a proposed exception, and flags any match against alerts you have protected. It also shows where the volume comes from (rule groups, directories, how many incidents the alerts really are) so you can build a narrow exception from your own data.

Both are early prototypes in Python with no runtime dependencies, with releases and Docker images on GitHub. The examples use synthetic data, and live validation on real Wazuh managers is the biggest thing still missing, so a [compatibility report](https://github.com/farhan6667/wazuh-ruleguard/issues/new?template=compatibility_report.md) is the most useful help you can give. Both are independent projects and are not affiliated with Wazuh Inc.

### [no-api-media-mcp](https://github.com/farhan6667/no-api-media-mcp)

An MCP server that lets Claude Code, Cursor and Codex make images and videos through the ChatGPT, Google AI Pro and Higgsfield accounts you already pay for, with no API keys. You sign in once yourself and it never sees your password. It reads your project first so the pictures match the site, saves them inside the project, and can cut out backgrounds, edit video and export every social size locally. It is Apache-2.0 licensed, and the README says plainly where the providers' terms limit automated use.

## Contributing and feedback

Contributions are welcome, and a real-world test result is worth more than a code change. Start with a [good first issue](https://github.com/farhan6667/wazuh-ruleguard/labels/good%20first%20issue), or open a discussion. Please never post credentials, hostnames or organization logs in public issues.

## NexaForge

<a href="https://nexaforge.eu.cc/">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/farhan6667/farhan6667/main/assets/nexaforge-lockup-dark.webp">
    <img src="https://raw.githubusercontent.com/farhan6667/farhan6667/main/assets/nexaforge-lockup-light.webp" height="56" alt="NexaForge">
  </picture>
</a>

I also run NexaForge, a small studio for cyber security and vibe coding, with web development and IT infrastructure alongside.
[nexaforge.eu.cc](https://nexaforge.eu.cc/) ·
[nexaforge.services@gmail.com](mailto:nexaforge.services@gmail.com)
