# homebrew-your-usual

Homebrew tap for [YourUsual](https://github.com/s-age/YourUsual) — a macOS menu
bar app for quick access to your usual files, directories, and commands.

## Install

```bash
brew tap s-age/your-usual
brew install --cask your-usual
```

Requires macOS 15 (Sequoia) or later. The app is signed with a Developer ID
certificate and notarized by Apple.

Installing also symlinks the bundled executable onto your `PATH` as
`your-usual`, enabling the CLI (e.g. `your-usual cd <path>`).
