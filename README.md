# CCNA 200-301 v1.1 — Last-Minute Study Map

A single-file, mobile-first study page for the Cisco **CCNA 200-301 v1.1** exam. It follows the official exam blueprint: 6 domains and 53 sub-objectives.

**Live page:** https://lv-dang.github.io/ccna-study-map/ 

## What's inside

| Tab | Contents |
|---|---|
| **Map** | Overview panels for every blueprint objective, with 50 topology/flow diagrams and comparison tables. 24 complete configure + verify blocks: every *configure* objective, plus HSRP, management access, DNS client, SNMP v2c/v3, syslog, TFTP/FTP/IOS upgrade and AAA (TACACS+/RADIUS, 802.1X). |
| **Cards** | 332 flip cards, each with a short explanation and its source. |
| **Quiz** | 330 scenario questions, including 36 exhibits with CLI output, 9 matching and ordering questions, and an explanation for every option. |
| **Numbers** | Ports, timers, defaults, administrative distances, priorities and limits, grouped by objective. |
| **Exam day** | One line per objective (number plus topic name) to review before the exam. |
| **Find** | Search across all of the content above. |

Readiness tracking (per domain, weighted by the blueprint percentages) and mock-exam history are kept in your browser's `localStorage` (`ccna11-*` keys). Nothing leaves your device.

## Use it

- Open `index.html` in any browser. It works offline and has no dependencies.
- Or host it with GitHub Pages: **Settings → Pages → Deploy from a branch → `main` / root**.

## Sources

Content was cross-checked against:

- Cisco *200-301 CCNA v1.1 Exam Topics* (blueprint)
- Wendell Odom, *CCNA 200-301 Official Cert Guide*, Vol. 1 & 2, 2nd ed. (OCG1 / OCG2)
- Allan Johnson, *31 Days Before Your CCNA Exam*
- Anthony Sequeira, *CCNA 200-301 Exam Cram*
- NetworkLessons.com CCNA course (NL)
- INE CCNA Exam Review

Each card and question is tagged with its source. Where the books disagree (for example, WLC AP limits), both values are shown.

## Caveats

- This is an independent study aid. It is **not affiliated with or endorsed by Cisco**. *CCNA* and *Cisco* are trademarks of Cisco Systems, Inc.
- The readiness score is an estimate and does not predict your exam result.
- Some defaults vary by platform and IOS version, such as vty line counts and OSPF `maximum-paths`. The page notes where this applies.

## License

MIT — see [LICENSE](LICENSE).
