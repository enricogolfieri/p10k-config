# Powerlevel10k Configuration

This repository contains my personal Powerlevel10k (p10k) ZSH theme configuration, structured as an Antigen bundle.

## Overview

[Powerlevel10k](https://github.com/romkatv/powerlevel10k) is a highly customizable ZSH theme that provides rich prompt information while remaining fast and efficient. This repository contains my preferred configuration settings.

## Installation

### Using Antigen

Add the following to your `.zshrc` file:

```zsh
# Load the Powerlevel10k theme
antigen theme romkatv/powerlevel10k

# Load my personal p10k configuration
antigen bundle enricogolfieri/p10k-config --branch=main
```

### Manual Installation

If you prefer to install manually:

1. Clone this repository:
   ```
   git clone https://github.com/username/p10k-config.git ~/.zsh/p10k-config
   ```

2. Source the configuration in your `.zshrc`:
   ```
   source ~/.zsh/p10k-config/p10k.zsh
   ```

## Configuration

The main configuration is contained in `p10k.zsh`, which defines:

- Prompt segments and their appearance
- Color schemes
- Icons and symbols
- Layout preferences
- Conditional display logic

The `p10k-config.plugin.zsh` file serves as the entry point when loaded as an Antigen bundle.

## License

This configuration is provided under the [MIT License](LICENSE).
