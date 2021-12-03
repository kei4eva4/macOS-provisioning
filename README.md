# macOS-provisioning

#　準備
## Xcodeのインストール

```shell
sudo xcodebuild -license
```

## Homebrewのインストール

```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zshrc
eval "$ (/opt/homebrew/bin/brew shellenv)"
```

## ansibleのインストール

```shell
brew install ansible
```
