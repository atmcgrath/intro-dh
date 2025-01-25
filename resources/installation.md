## Installation guide

### Install Git and other command line tools

Git version control system is a piece of software you install on your computer. This is necessary to sync with your GitHub project and record the history of your work.

Installing this free and open source software is pretty straightforward:

#### Windows:

Install [Git for Windows](https://git-scm.com/downloads) using the default options, except when setup asks you to choose the default editor used by Git, select “Use the Nano editor by default”. This will give you Git, Git Bash, and Git GUI. Git Bash is a terminal that lets you use UNIX style commands and utilities on Windows, and will be used as your default terminal when working with Jekyll.

#### Mac:

Mac systems will require the “Xcode Command Line Tools” installed, which includes Git. Open a terminal (to find your terminal search for “terminal” in your Spotlight), type in the command `xcode-select --install`, and follow the prompts. After the install finishes, try typing `git --version`. (Optionally, if you want a newer version of Git, [check alternative Mac install methods](https://git-scm.com/downloads/mac))

### Linux:

Open a terminal and try typing `git --version`. If Git is not already available, install from your distribution’s software center or package manager (for Ubuntu `sudo apt install git`), or check [alternative Linux install methods](https://git-scm.com/downloads/linux).

Instructions from [CollectionBuilder documentation](https://collectionbuilder.github.io/cb-docs/docs/software/git/).