# Third-party software in KEPTA

KEPTA (the desktop application) is proprietary software, but it builds on open source. This
file lists the bundled components and their licenses. The open memory engine
underneath is licensed separately (AGPL-3.0, see [DamianTodorovic/kepta](https://github.com/DamianTodorovic/kepta)).

## Icon sets (embedded in the app)

| Set | License | Usage |
|---|---|---|
| **Solar** (480 Design, via Iconify) | **CC BY 4.0** | 61 glyphs of the KEPTA icon series (`solar:*-linear`) |
| **Tabler Icons** | MIT | 1 glyph (`binary-tree`, the Tree-view switcher) |

Solar is licensed under the Creative Commons Attribution 4.0 International
License (https://creativecommons.org/licenses/by/4.0/). The Solar icon set was
created by 480 Design (https://480.design / https://github.com/480-Design).

## Major libraries

| Library | License |
|---|---|
| Electron | MIT |
| React, React DOM | MIT |
| motion (framer-motion successor) | MIT |
| pdf.js (pdfjs-dist) | Apache-2.0 |
| better-sqlite3-multiple-ciphers | MIT |
| express, helmet, compression, express-rate-limit | MIT |
| markdown rendering: react-markdown + remark/rehype ecosystem | MIT |
## KEPTA's own open components

| Component | License |
|---|---|
| The memory engine and MCP server — [DamianTodorovic/kepta](https://github.com/DamianTodorovic/kepta), npm `kepta-mcp` | AGPL-3.0-or-later (from 2.11; the published 2.10.3 was MIT) |
| The Python client — PyPI `kepta` | MIT |
