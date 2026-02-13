[English](README.md) | [繁體中文](README.zh.md)

# canvas-design

A Claude Code skill that creates beautiful visual art in .png and .pdf documents using design philosophy. It generates a design philosophy manifesto first, then expresses it visually on a canvas with expert-level craftsmanship.

## What It Does

1. Creates a **Design Philosophy** -- a named aesthetic movement with specific principles for form, space, color, and composition
2. Deduces a **Subtle Reference** from the user's request, weaving it invisibly into the artwork
3. Produces a **Canvas** -- museum-quality .pdf or .png artwork that embodies the philosophy with meticulous craftsmanship
4. Performs a **Refinement Pass** to polish every detail to pristine quality

## Features

- Generates original design philosophies as named art movements
- Produces high-quality .png and .pdf visual outputs
- Includes a curated font library (`canvas-fonts/`) with 30+ typefaces and OFL licenses
- Emphasizes visual expression over text -- designs are 90% visual, 10% essential text
- Supports multi-page output for coffee table book style collections

## Prerequisites

- **Playwright MCP** -- Used as the rendering engine. The skill writes HTML/CSS, opens it in Playwright's browser, and screenshots the result to PNG. PDF output uses the `write_pdf` tool.
- **CJK fonts** (for Chinese text) -- On macOS, use `PingFang TC` (built-in) or install `Noto Sans CJK TC`.
- No external API keys required

## Installation

```bash
git clone https://github.com/joneshong-skills/canvas-design.git ~/.claude/skills/canvas-design
```

## Usage

```
/canvas-design Create a poster inspired by Japanese minimalism
/canvas-design Design a visual piece about the passage of time
/canvas-design Make art that captures the feeling of a rainy afternoon
```
