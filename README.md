# Drew Richburg, IT Support / Support Engineer

[![WakaTime](https://wakatime.com/badge/user/2a7a60c6-848c-456f-b2fc-0206876e36ab.svg)](https://wakatime.com/@Drewlius) [![freeCodeCamp Python](https://img.shields.io/badge/freeCodeCamp-Python_cert-0a0a23?logo=freecodecamp)](https://www.freecodecamp.org/certification/drewlius/python-v9)

Remote-first support engineer in training. Ex-HVAC service tech. I spent 4 years diagnosing systems solo in the field and explaining fixes in plain language. Now I do the same on Linux.

- 📍 Lexington, SC. Open to Remote / Hybrid
- 📬 drewrichburg97@icloud.com
- 👉 **Start here: [oc-supermemory-redux](https://github.com/Drewlius/oc-supermemory-redux)**: my OpenCode memory plugin. The write-up of how I traced its silent failure is the best sample of how I troubleshoot.

## How I troubleshoot (one real example)

Every new session came up empty. No profile, no recall. Instead of blaming the API, I traced session start: 17 calls, all returning zero results. My digging surfaced a design flaw in the plugin's routing mechanics: it queried 6 auto-generated container tags, while my 1,300+ memories lived in a 7th container tag it never asked about. One config line fixed it.

That's the same loop I ran in HVAC: reproduce, isolate, verify. FY25: $313,822 revenue, 56% conversion, $650 average sale. Exceeded expectations yearly.

## Daily driver

Arch Linux homelab. A handful of self-hosted services on one box, HTTPS that renews itself, locked down and encrypted. My editor time is tracked on [WakaTime](https://wakatime.com/@Drewlius).

## More proof

- [MergePDF](https://github.com/Drewlius/MergePDF): Python CLI (pypdf)
- [CryptAutomount](https://github.com/Drewlius/CryptAutomount): Linux encryption and auto-mount guide
- [Gists](https://gist.github.com/Drewlius): Bash/NVIDIA/Arch utilities
- [freeCodeCamp forum](https://forum.freecodecamp.org/u/drewlius/summary): 115 replies, mostly Python help

## Certs

freeCodeCamp Python (~300h, [verified](https://www.freecodecamp.org/certification/drewlius/python-v9)) · Linux+ studying (80–90% practice, not yet certified) · Nexstar Certified Service Technician (2024) · EPA 608 Type 2
