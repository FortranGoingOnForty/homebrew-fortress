# Homebrew Fortress

Homebrew tap for [fortress](https://github.com/FortranGoingOnForty/fortress) - a command-line file explorer written in modern Fortran.

## Installation

```bash
brew tap FortranGoingOnForty/fortress
brew install fortress
```

## Shell Integration

After installation, add to your shell config:

**Bash/Zsh:**
```bash
# Add to ~/.bashrc or ~/.zshrc
source $(brew --prefix)/share/fortress/fortress.sh
```

**Fish:**
```fish
# Add to ~/.config/fish/config.fish
source (brew --prefix)/share/fortress/fortress.fish
```

Then restart your shell or source the config file.

## Usage

```bash
fortress  # Start the file explorer
```

Press `c` on any directory to cd there and exit.

## About Fortress

FORTRESS is a dual-pane file explorer with:
- Color-coded file display
- Smart navigation with position memory
- CD-on-exit functionality
- Arrow key navigation
- Visual hierarchy

See the [main repository](https://github.com/FortranGoingOnForty/fortress) for more details.
