# NemoClaw on DGX Spark — The Complete Guide

An in-depth, hands-on guide to NVIDIA's NemoClaw autonomous AI agent platform, installed and tested on a DGX Spark.

**Live site:** [ohoachuck.github.io/nemoclaw-dgx-spark-guide](https://ohoachuck.github.io/nemoclaw-dgx-spark-guide/)

## What's inside

- **Installation walkthrough** — npm permissions fix, port 8080, Cloudflare tunnel, the install.sh script dissected, 7-step onboarding
- **Architecture deep dive** — Docker/k3s/Pod matryoshka, 6 running processes, sandbox internals
- **Cloud vs local inference** — Nemotron 3 Super 120B at 17.6 tok/s on GPU, switch in one command
- **Full dashboard tour** — All 13 sections of the OpenClaw Control dashboard with screenshots
- **51 skills catalog** — Exhaustive list organized by category with prerequisites
- **Security analysis** — Known bugs (#481, #272), skill trust levels, prompt injection risks
- **Honest conclusion** — What works, what doesn't, and why you shouldn't blindly trust it yet

## Languages

The site auto-detects your browser language and redirects to:
- **French**: `/fr/`
- **English**: `/en/`

Manual language switch available in the header.

## Screenshots

All screenshots were taken from a real NemoClaw installation on an NVIDIA DGX Spark (March 2026). Sensitive information (tokens, hostnames, API keys) has been redacted.

## Tech stack

- Single HTML files (no build step, no framework)
- CSS with NVIDIA dark theme
- SVG infographics (inline)
- Font Awesome 6 icons
- Vanilla JS (scroll spy + language detection)
- GitHub Pages hosting

## Disclaimer

This guide reflects the state of NemoClaw as of **March 22, 2026**. NemoClaw is an alpha product — bugs mentioned in this article (especially Issues [#481](https://github.com/NVIDIA/NemoClaw/issues/481) and [#272](https://github.com/NVIDIA/NemoClaw/issues/272)) may be fixed in later versions. Always check the [official NemoClaw repository](https://github.com/NVIDIA/NemoClaw) for the latest information.

This guide is not affiliated with or endorsed by NVIDIA. It is an independent, honest review based on personal testing.

## License

This work is licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) — you are free to share and adapt it, as long as you give credit and share under the same license.

## Author

Written by [@ohoachuck](https://github.com/ohoachuck), with the help of Claude (Anthropic).
