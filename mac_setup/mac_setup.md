# Mac Setup

## Homebrew

https://brew.sh/

## Setup

```bash
# brew
brew bundle

# asdf
echo -e "\n. $(brew --prefix asdf)/libexec/asdf.sh" >> ${ZDOTDIR:-~}/.zshrc
echo "legacy_version_file = yes" > ~/.asdfrc
source ~/.zshrc

# install asdf plugin
asdf plugin update --all
asdf plugin add nodejs
asdf install nodejs lts
asdf set -u nodejs lts

# claude
npm install -g @anthropic-ai/claude-code
```

## asdf Usage

```bash
# Show current versions of all tools
asdf current

# Update all plugins
asdf plugin update --all

# List all available Node.js versions
asdf list all nodejs

# Which node
which node
```
