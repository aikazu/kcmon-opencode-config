<div align="center">
  <a href="README.md">English</a> | <a href="README-ID.md">Bahasa Indonesia</a>
</div>
<br/>

# 🛠️ OpenCode Configuration Files

This repository contains my personal OpenCode configuration files. These settings are optimized for my specific workflow but are designed to be flexible—feel free to use them as a reference or drop them directly into your setup.

## 🚀 How to Use

Follow these steps to apply the configuration:

1. Clone this repository.
2. Copy the files from `.config/opencode/*` to your local OpenCode configuration directory.
3. Run OpenCode.

### Quick Start (Linux/macOS)

```bash
# Copy configuration files
cp -r .config/opencode/* ~/.config/opencode/
```

### Run OpenCode
```bash
opencode
```

## Configuration Directory Structure

![Example Linux Directory Structure](/Screenshoot/config-folder-linux.png)

## 🎭 Orchestration: oh-my-opencode

I have provided two primary preset configurations for `oh-my-opencode` Agent/Skills Orchestration. You can swap between them depending on your preferred LLM provider:

*   [Full Gemini Preset](/.config/opencode/oh-my-opencode-full-gemini.json) – Optimized for Google's Gemini models.
*   [Full Claude Preset](/.config/opencode/oh-my-opencode-full-claude.json) – Optimized for Anthropic's Claude models.

**Usage:**
Simply copy the content of the desired preset file and replace the content of `oh-my-opencode.json` in your OpenCode config directory.

## 🔐 Antigravity Auth Config

The [antigravity.json](/.config/opencode/antigravity.json) file represents my personal antigravity auth setup.

*   **Reference:** You can use it as a direct reference or modify it.
*   **Customization:** To customize it properly, please refer to the official schema [here](https://raw.githubusercontent.com/NoeFabris/opencode-antigravity-auth/main/assets/antigravity.schema.json).