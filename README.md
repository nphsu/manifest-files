# Manifest Files

When you restart on new Macbook, you have to set up your environment quickly to reference this guide.

1. Set up your System Preference
2. Install Chrome
3. Install homebrew
4. Configure iTerm2

## 1. System Preference

Trackpad >> Tracking speed >> Fast

## 2. Chrome

Download chrome and login to your account.
You should also login GitHub account by using Chrome account.

## 3. Homebrew

Install homebrew to your new computer.
https://brew.sh/

```
$ mkdir ~/Dev/03_manifest_files && cd 03_manifest_files
$ git clone <this repository> .
$ cd ~ && cp ~/Dev/03_manifest_files/brew/Brewfile .
$ brew bundle
```

#### After using "*brew install*"

If you add another libraries from brew, you have to renew updated Brewfile by using command below.

```
$ bundle bundle dump
```

## 4. iTerm2

Select the path of iTerm config file.
https://qiita.com/reoring/items/a0f3d6186efd11c87f1b

### TODO
- vim
- zshrc
