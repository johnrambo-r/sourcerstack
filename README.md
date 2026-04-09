# ReputeScoper

**LinkedIn has profiles. Stack Overflow has proof.**

ReputeScoper is a free, open-source Stack Overflow expert search tool built for recruiters. Stack Overflow reputation is earned, not claimed — every point is a vote from a peer on a public technical answer. ReputeScoper lets recruiters search India-based Stack Overflow contributors by skill tag, reputation, badge level, and city, surfacing the kind of verified expertise signal that a LinkedIn headline or a CV bullet point cannot replicate.

Part of the [Sourcer.club](https://sourcer.club) suite — free tools for serious sourcers.

---

## Using the tool

ReputeScoper is a single HTML file with no dependencies, no backend, and no build step.

**Online:** [repute.sourcer.club](https://repute.sourcer.club)

**Offline / self-hosted:**
1. Download `index.html`
2. Open it in any modern browser
3. No server required

---

## Features

- Search Stack Overflow India contributors by skill tag, reputation score, and badge level
- Multi-city filter — covers Tier 1, Tier 2, and Tier 3 India cities
- Reputation and badge signals surfaced on every result card
- Boolean search across display names and tag expertise
- Saved candidates drawer — shortlist profiles within a session
- Light and dark mode
- No login, no tracking, no data sent anywhere

---

## Data source and coverage

ReputeScoper is built on the **Stack Exchange Data Dump**, a periodic public release of Stack Overflow's anonymised user and post data. The data is licensed under [Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)](https://creativecommons.org/licenses/by-sa/4.0/).

Current data: **April 2024 Stack Exchange Data Dump**

Coverage is limited to users with a location field matching Indian cities. Location data on Stack Overflow is self-reported and not standardised, so coverage will vary by city. The dataset is updated periodically as new data dumps are released.

---

## License

The **tool code** (HTML, CSS, JavaScript) is released under the MIT License.

MIT License

Copyright (c) 2026 Sourcer.club

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---

The **Stack Overflow data** embedded in this tool is sourced from the Stack Exchange Data Dump and is licensed separately under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/). Attribution: Stack Exchange Inc.

Any derivative works or redistributions that include this data must carry the same CC BY-SA 4.0 license and provide attribution to Stack Exchange Inc.

---

## Acknowledgements

- Data source: [Stack Exchange Data Dump](https://archive.org/details/stackexchange) — licensed under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) by Stack Exchange Inc.
- Stack Overflow and the Stack Exchange name and logo are trademarks of Stack Exchange Inc. This tool is not affiliated with or endorsed by Stack Exchange Inc.
- Fonts: [Syne](https://fonts.google.com/specimen/Syne) and [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) via Google Fonts (SIL Open Font License)
- Built with vanilla HTML, CSS, and JavaScript — no frameworks
