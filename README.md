# Framer SEO Writer

Framer SEO Writer is a Codex skill for writing and revising Framer marketing pages, metadata, FAQs, and answer-first SEO/AEO copy.

## Install

Copy this command into Codex, Claude, or a terminal on macOS/Linux:

```bash
INSTALL_DIR="${CODEX_HOME:-$HOME/.codex}/skills"; TMP_ZIP="$(mktemp -t framer-seo-writer.XXXXXX).zip"; trap 'rm -f "$TMP_ZIP"' EXIT; curl -fsSL "https://github.com/jurrehoutkamp/framer-seo-writer/raw/main/framer-seo-writer.zip" -o "$TMP_ZIP" && mkdir -p "$INSTALL_DIR" && rm -rf "$INSTALL_DIR/framer-seo-writer" && unzip -q "$TMP_ZIP" -d "$INSTALL_DIR"
```

Restart Codex, then invoke the skill with:

```text
$framer-seo-writer
```

## What It Helps With

- Framer feature, solution, comparison, and answer-oriented pages
- SEO/AEO structure, metadata, FAQs, and internal linking
- Product-specific positioning for Framer AI, Framer Agents, CMS, hosting, SEO, performance, and publishing
