projj add https://github.com/lewislulu/terminal-setup.git

cd terminal-setup && ./setup.sh

```bash
❯ ./setup.sh
[INFO] Detected macOS

Which shell do you want to use?

  1) Fish  — Modern shell, amazing defaults, not POSIX
  2) Zsh   — POSIX-compatible, fish-like with plugins

Choose [1/2]: 2

[INFO] Setting up with zsh on macos

══════════════════════════════════════════
  📦 Step 1/9: Package Manager
══════════════════════════════════════════
[OK] Homebrew already installed

══════════════════════════════════════════
  👻 Step 2/9: Terminal Emulator
══════════════════════════════════════════
[OK] Ghostty already installed

══════════════════════════════════════════
  🔤 Step 3/9: Nerd Font (MesloLGS NF)
══════════════════════════════════════════
[OK] MesloLGS NF fonts already installed

══════════════════════════════════════════
  🐚 Step 4/9: Zsh + Fish-like Plugins
══════════════════════════════════════════
[OK] zsh-autosuggestions already installed
[OK] zsh-syntax-highlighting already installed
[OK] zsh-completions already installed
[OK] Zsh is already the default shell

══════════════════════════════════════════
  🛠  Step 5/9: CLI Tools
══════════════════════════════════════════
[OK] bat already installed
[OK] eza already installed
[OK] fd already installed
[OK] ripgrep already installed
[OK] btop already installed
[OK] zoxide already installed
[OK] jq already installed
[OK] tldr already installed
[OK] git-delta already installed
[OK] lazygit already installed
[OK] fzf already installed

══════════════════════════════════════════
  🚀 Step 6/9: Starship Prompt
══════════════════════════════════════════
[OK] Starship already installed

══════════════════════════════════════════
  🟢 Step 7/9: fnm + Node.js (optional)
══════════════════════════════════════════

  ⚠ WARNING: fnm manages its own Node.js versions.
    If you already have Node.js installed (e.g. via nvm, Homebrew, or system),
    fnm may shadow your existing Node/npm and tools installed globally
    (e.g. Claude Code, Codex CLI, pnpm global packages).
    Only install fnm if you need to manage multiple Node versions.

  Install fnm + Node.js? (y/N, default: N): n
[INFO] Skipping fnm + Node.js

══════════════════════════════════════════
  🪟 Step 8/9: Zellij (optional)
══════════════════════════════════════════
[OK] Zellij already installed

══════════════════════════════════════════
  📦 Step 9/9: Deploying Configs
══════════════════════════════════════════
[WARN] Backed up existing Ghostty config
[OK] Ghostty config deployed
[WARN] Backed up existing starship.toml
[OK] Starship config deployed
[WARN] Backed up existing .zshrc
[OK] Zsh config deployed
[INFO] Configuring git-delta as git pager...
[OK] git-delta configured

══════════════════════════════════════════
  ✅ All done!
══════════════════════════════════════════

  Platform: macos

  Your terminal stack:
    👻 Ghostty              — terminal emulator
    🐚 Zsh                  — shell (POSIX-compatible)
    ✨ zsh-autosuggestions   — fish-like suggestions
    🎨 zsh-syntax-highlight — fish-like highlighting
    🚀 Starship             — prompt (Catppuccin Mocha)
    🔤 MesloLGS NF          — nerd font
    🟢 fnm                  — Node version manager (fast!)
    📦 bat eza fd rg        — modern coreutils
    📊 btop                 — system monitor
    🔀 lazygit + delta      — git tools
    📁 zoxide               — smart cd
    🔍 fzf                  — fuzzy finder
    🪟 zellij               — terminal multiplexer

  Next steps:
    1. Restart your terminal (or open Ghostty)
    2. Node is ready: node --version
    3. Pin a project: echo 22 > .node-version (fnm auto-switches)
    4. Try: Ctrl+R (fzf history) / Ctrl+T (fzf files)
```