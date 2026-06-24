# Framer SEO Writer

Framer SEO Writer is a Codex and Claude Code skill for writing and revising Framer marketing pages, metadata, FAQs, and answer-first SEO/AEO copy.

## Install

Copy this command into Codex, Claude Code, or a terminal on macOS/Linux:

```bash
TMP_DIR="$(mktemp -d)"; trap 'rm -rf "$TMP_DIR"' EXIT; curl -fsSL "https://raw.githubusercontent.com/jurrehoutkamp/framer-seo-writer/main/framer-seo-writer.zip" -o "$TMP_DIR/framer-seo-writer.zip" && for INSTALL_DIR in "${CODEX_HOME:-$HOME/.codex}/skills" "$HOME/.claude/skills"; do mkdir -p "$INSTALL_DIR" && rm -rf "$INSTALL_DIR/framer-seo-writer" && unzip -q "$TMP_DIR/framer-seo-writer.zip" -d "$INSTALL_DIR"; done
```

Invoke the skill in Codex with:

```text
$framer-seo-writer
```

Invoke the skill in Claude Code with:

```text
/framer-seo-writer
```

If Codex or Claude Code was already running, restart it if the skill does not appear.

## What It Helps With

- Framer feature, solution, comparison, and answer-oriented pages
- SEO/AEO structure, metadata, FAQs, and internal linking
- Product-specific positioning for Framer AI, Framer Agents, CMS, hosting, SEO, performance, and publishing
