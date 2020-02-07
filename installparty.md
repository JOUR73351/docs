# Install Party

Before we dive into the course material, we will need to install all of the tools that we will be using for this class. We will mostly be using the **command line**, also known as the **terminal** to install these tools. You will become comfortable with it, as you will need it to use Python, publish projects on GitHub, and submit your assignments.

### What is the command line?

The command line is a text-based interface that runs commands on your computer. Using the command is similar to using the Finder on the Mac. Finder is a graphical user interfaces (GUI) for the command line. The command line removes that layer of abstraction as a text-based way to interact with your computer. The default terminal app on your Mac is called Terminal. We will be installing a better version of it.

_Note: “Running” a command means writing (or copying) a given command in the terminal and hitting enter. Commands will be shown in a highlighted box, e.g. `node --version`. There is no text cursor in the command line, so you must use the left and right arrow keys to navigate text._

#### iTerm2

iTerm2 is a replacement for the default MacOS Terminal app that comes with extra features and has superior text highlighting.

1. Download [iTerm2](https://iterm2.com/).
2. Unzip it.
3. Drag it to your Applications folder.
4. Drag it to your Dock.

#### Xcode

Xcode is an Integrated Development Environment (IDE), which means it pulls all the tools needed to produce an application for Mac and iOS developers. We won't be using it as an IDE, but Homebrew depends on it, so we need to install it.

1. Run `xcode-select --install`
2. You will see a popup on your screen. Click on `Install`.
3. Click on `Agree`.
4. Click `Done` when it finishes installing.

#### Homebrew

[Homebrew](https://brew.sh/) which is a package manager that simplifies the installation of software on macOS, and we need it to install a lot of the tools for this class. Installing required programs is a pain for people with no coding experience; Homebrew tries to make it easier.

1. Run `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`.
2. Hit enter.

#### Zsh

The terminal is the a GUI for the shell, which is the program that actually interprets the commands you write. ZSH, also called the Z shell, is an extended version of the Bourne shell, the default version, with plenty of new features, and support for plugins and themes.
Features include:

- **Automatic cd**: Just type the name of the directory without `cd`
- **Recursive path expansion**: For example `/u/lo/b` expands to `/usr/local/bin`
- **Spelling correction and approximate completion**: If you make a minor mistake typing a directory name, ZSH will fix it for you
- **Plugin and theme support**: ZSH includes many different plugin frameworks

1. You can check if you already have it installed by running `zsh --version`.
2. If you don't, run `brew install zsh`.
3. Check if Zsh is already your default shell by running `echo $SHELL`. MacOS Catalina and later makes it the default.
4. If it isn't run, `chsh -s /bin/zsh`.
5. Install [Oh My Zsh](https://ohmyz.sh/) by running `sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`.
   Oh My Zsh is a community-driven framework that manages your Zsh configuration, and it includes plugins and themes to customize your terminal. Here is a [cheatsheet](https://github.com/ohmyzsh/ohmyzsh/wiki/Cheatsheet) of various useful shortcuts.

#### Git and GitHub

Git is version control system. When developers create something (an app, for example), they make constant changes to the code. Git helps you keep track of all those changes. Git is a command-line tool, and GitHub is where developers store their projects in repositories, or repos.

1. Check if you have Git installed by running `git --version`.
2. If you don't, run `brew install git`.
3. Make an account on [GitHub](https://github.com/) if you don't already have one and save the password in [1Password](https://1password.com/).

[Git Immersion](http://gitimmersion.com/) is a helpful tutorial on how to use Git.

##### Setting up a GitHub ssh key

When you want to push your project up to GitHub, GitHub needs a way of authenticating you. You need to set up an ssh key as a way to identify yourself that doesn't require entering your username and password every time. Go through the [tutorial](https://help.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh) to set up your key.

#### VS Code

VS Code is a text editor that has powerful tools that allow you to be more productive when writing code.

1. Download [VS Code](https://code.visualstudio.com/).
2. Unzip it.
3. Drag it to your Applications folder.
4. Drag it to your Dock.

##### Launching from the command line

1. Launch VS Code.
2. Open the Command Palette by pressing `⇧⌘P` and type in `shell command` and click on **Shell Command: Install 'code' command in PATH**.
3. Restart your terminal for it to take effect.
4. Test if it worked by typing in `code .`.

You can open VS Code from the terminal with the command `code` followed by a path, usually `.`, the current directory.

We will also be installing [Prettier](https://github.com/prettier/prettier-vscode), which is a code formatter. Prettier will make your code easier to read, helping you have consistent code style and catch bugs and syntax errors.

##### Prettier

1. Press `⌘P` in VS Code to launch Quick Open and run `ext install esbenp.prettier-vscode`.
2. To format on save, go to Code → Preferences → Settings and search for `format on save` and check the box.

#### Python

1. In your terminal, run `brew install python3 pipenv`.
2. After it's completed, run `python3 --version` to confirm.

Here is a useful tutorial on [how to install Python the IRE way](https://docs.google.com/document/d/1cYmpfZEZ8r-09Q6Go917cKVcQk_d0P61gm0q8DAdIdg/edit).

Check out this interactive [introduction to Python](http://littlecolumns.com/learn/python/).
