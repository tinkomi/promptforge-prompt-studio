# PromptForge Prompt Studio Lite

**A free, interactive prompt-building demo with a Korean-language interface.**

PromptForge Lite is a single-file HTML introduction to a structured AI prompt-building workflow. Try it without purchasing the separate PRO edition.

> The app interface is in Korean (한국어). This README is in English.

## Try it

- **[Launch the free demo](https://mcjin87-eng.github.io/promptforge-prompt-studio/)** (available once GitHub Pages finishes deploying)
- [View the source repository](https://github.com/mcjin87-eng/promptforge-prompt-studio)

## What Lite includes

- Three built-in Korean prompt templates: code review/refactoring, marketing copy, and structured JSON extraction
- A custom prompt editor with `{{variable}}` placeholders
- Automatically generated input fields for detected variables and live prompt preview
- Character count and an approximate token estimate
- Copy the completed prompt to the clipboard, download it as a `.txt` file, or reset the editor
- One self-contained `index.html` file; no installation or build step

Lite is an interactive prompt-building tool. It does not provide AI model access or API credits. The token count is an estimate, and the browser clipboard feature may depend on browser permissions.

## Quick start

### GitHub Pages

Open the [PromptForge Lite demo](https://mcjin87-eng.github.io/promptforge-prompt-studio/) after deployment and use the Korean-language controls.

### Run locally

1. Download or clone this repository.
2. Open `index.html` in a web browser.
3. Choose a built-in template or write your own prompt using placeholders such as `{{role}}` and `{{topic}}`.
4. Fill the generated variable fields and review the live result.
5. Copy, download, or reset the completed prompt using the buttons.

## Lite and PRO

Lite is a free standalone demo. PromptForge PRO is a separate paid product with a broader feature set, including advertised Claude XML optimization, OpenAI/Gemini code generation, and a bundle of 100+ premium templates. Those PRO features are not included in this Lite repository.

[Explore PromptForge PRO on Gumroad](https://mcjinster.gumroad.com/l/nqpdjy) — optional; purchasing PRO is not required to use Lite.

## Project files

- `index.html` — the PromptForge Lite application
- `README.md` — project information and usage guide

## Feedback and contributions

Bug reports, suggestions, and documentation improvements are welcome through GitHub Issues and Pull Requests. For bug reports, include steps to reproduce the issue. Please review the repository licensing information before redistributing or reusing the code; no license terms are stated in this README.

## FAQ

**Is Lite free?** Yes. The Lite project is free to access; PRO is optional.

**Is the interface in English?** No. The confirmed application interface is Korean. This README is written in English.

**Does Lite generate SDK code or connect to an AI service?** Those capabilities are not part of the Lite app documented here. No AI access or credits are included.

**Does it save prompts automatically?** No automatic saving is claimed. Copy or download a prompt if you want to keep it.
