# Development Setups

This repository is for storing and sharing your development environment configurations, tools, and preferences. It helps you quickly set up your environment on a new machine or share your setup with others.

## Contents

- `vscode-extensions.txt`: List of all your VS Code extensions. Update this file with:
  ```sh
  code --list-extensions > vscode-extensions.txt
  ```
- (Add more files for settings, snippets, or other tools as needed)

## Usage

1. Clone this repository to your new machine.
2. Install VS Code extensions:
   ```sh
   cat vscode-extensions.txt | xargs -L 1 code --install-extension
   ```
3. Add more configuration files (e.g., settings, dotfiles, scripts) as your setup grows.

## Tips

- Keep this repository up to date as you add or remove tools/extensions.
- Use it as a backup or to share your setup with teammates.

---

Feel free to customize this README as your environment evolves!
