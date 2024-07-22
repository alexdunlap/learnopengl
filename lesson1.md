
# Homebrew
Homebrew is a program that we can use to install new software for MacOS.

## Install Homebrew
Install command from [https://brew.sh/](https://brew.sh/):
```
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Check system integrity:
```
$ brew doctor
```

## brew command summary
- brew --version (show the version of Homebrew)
- brew list (show all installed applications)
- brew update (update brew's internal list of applications)
- brew install APPLICATION (install a specific application)
- brew reinstall APPLICATION (reinstall a specific application)
- brew upgrade (upgrade all installed applications)
- brew doctor (check system integrity)

For a detailed list of brew commands run:
```
$ man brew
```

# tmux
If you were successfull above you should now be able to install new software using brew.

## Install tmux
First check whether tmux is installed.
```
$ tmux
```

If it is not installed, then we install it.
```
$ brew install tmux
```

