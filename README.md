# Brewfile

本仓库是为了使用 Homebrew 方便管理和安装 macOS 软件以满足我的个人需求。

具体软件列表自行查看 [Brewfile](/Brewfile)

## 安装 Homebrew

- 在中国大陆：

```sh
/bin/zsh -c "$(curl -fsSL https://gitee.com/cunkai/HomebrewCN/raw/master/Homebrew.sh)"
```

- 在其他地方：

```sh
/bin/zsh -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

## 安装 Brewfile （默认）

将会安装大量软件，务必谨慎操作

```sh
git clone https://github.com/Mrered/brewfile.git
brew bundle
```

## 安装 Brewfile （自定义）

注释或删除 `Brewfile` 中你不需要的行，然后

```sh
git clone https://github.com/Mrered/brewfile.git
brew bundle
```
