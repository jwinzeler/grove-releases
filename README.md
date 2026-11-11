# Grove

Desktop git client for Linux and Windows. Reviews changes across many repositories and their worktrees.

This repository has only the releases. An installed Grove updates itself.

## Linux

```bash
curl -fsSL https://github.com/jwinzeler/grove-releases/releases/latest/download/install.sh | sh -s -- --autostart
```

The command installs Grove in `~/.local/share/grove` and adds an entry to the application menu. With `--autostart`, Grove also starts at login.

## Windows

1. Install [Git for Windows](https://git-scm.com/download/win).
2. Download `Grove-Setup.exe` from the [latest release](https://github.com/jwinzeler/grove-releases/releases/latest) and run it.

The installer has no code signature, so Windows shows a SmartScreen warning. Select "More info", then "Run anyway".
