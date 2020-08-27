---
title: Getting Started
nav: true
--- 

# Boolean Logic
When conducting college-level research, there is a general process to follow:

{% capture text %}

1. Select topic
2. Use Boolean logic to expand or narrow key concepts or keywords
3. Select a database
4. Evaluate and revise search strategy
5. Choose items and find full-text online or in print

{% endcapture %}

{% include card.md text=text header="Research Process" %}

Since you have already selected your topic, this guide will focus on the other aspects of research process. First, let’s talk about Boolean logic. 

Boolean logic used Boolean operators (such as `AND`, `OR`, `NOT`) to narrow, expand, or define your search, and is applicable to conducting searches in library catalog and most databases. Writing out your search terms using Boolean operators by connecting pieces of information and coming up with synonyms is a good exercise as it can specify wanted results and filter out unrelated results. These are some of the most common Boolean operators you can use:


| Tables   |      Are      |  Cool |
|----------|:-------------:|------:|
| col 1 is |  left-aligned | $1600 |
| col 2 is |    centered   |   $12 |
| col 3 is | right-aligned |    $1 |

| Boolean Operator 	| Explanation 	| Example 	|
|:----------------:	|-------------	|---------	|
|        AND       	|All search terms must be present in the results             	|Antibiotic AND farm         	|
|        OR        	|             	|         	|
|                  	|             	|         	|
|                  	|             	| dsf     	|
|                  	|             	|         	|
|                  	|             	|         	|
|                  	|             	|         	|

# Local Jekyll Setup [optional]

## Install Git

[Git](https://git-scm.com/) is a [free](https://www.gnu.org/philosophy/free-sw.en.html), [distributed](https://en.wikipedia.org/wiki/Distributed_version_control) version control system. [GitHub](https://github.com/) is a Git repository hosting service, a place to store and sync your work in the cloud--your Jekyll and GitHub Pages projects will be under Git version control, so you need the software on your machine. 

- Windows: install [Git for Windows](https://git-for-windows.github.io/) using the default options. This will give you Git, Git Bash, and Git GUI. Git Bash is a great terminal that lets you use UNIX style commands on Windows.
- Mac: check if Git is already installed by opening terminal and typing `git --version`. If you do not have it, download the official [Mac installer](https://git-scm.com/downloads).
- Linux: check if Git is already installed by opening terminal and typing `git --version`. If you do not have it, install from your distribution's software center or package manager (for Ubuntu `sudo apt install git`).

If you are interested in using a visual GUI application integrated with GitHub, Windows and Mac users should also install [GitHub Desktop](https://desktop.github.com/) using the default options.
You can install GitHub Desktop in addition to other versions of Git.

There are other [GUI apps available](https://git-scm.com/downloads/guis) for managing and visualizing Git repositories, including Linux options.

## Install Ruby

[Ruby](https://www.ruby-lang.org/en/) is a fairly young and developing programming language with some unique features. 
To use Jekyll, you do not need to know anything about Ruby, but if you are curious, check out [Ruby in 20 minutes](https://www.ruby-lang.org/en/documentation/quickstart/).
Frustratingly, different versions have many dependency and incompatibility problems.
Because of these issues, many use Ruby Managers, such as [RVM](http://rvm.io/), to switch between versions.
However, if you are just interested in working with Jekyll, using an installer for your OS should be sufficient.
Jekyll requires a Ruby version > 2.2.5.

- **Windows:** Use [RubyInstaller for Windows](https://rubyinstaller.org/). 
    - First, [download](https://rubyinstaller.org/downloads/) the suggested stable version "WITH DEVKIT" (as of this writing, Ruby+Devkit 2.4.X (x64)) and double click to install. Use the install defaults, but make sure "Add Ruby executables to your PATH" is checked. On the final step, ensure the box to start the MSYS2 DevKit is checked.
    - Second, the installer will open a terminal window with options to install MSYS2 DevKit components. Choose option 3, "MSYS2 and MINGW development toolchain", or simply press ENTER to install all the necessary dependencies. (This installer can be restarted by typing `ridk install` into a command prompt)
- **Mac:** OS X has a version of Ruby installed by default. Check the version with `ruby -v`. If it is > 2.2.5 you can use the system Ruby. However, a newer version can be installed using [Homebrew](https://brew.sh/), `brew install ruby`, or a manager such as [rbenv](https://github.com/rbenv/rbenv) or [RVM](http://rvm.io/). Check the official Jekyll [Mac install docs](https://jekyllrb.com/docs/installation/#macOS) for tips.
- **Linux:** Even though the version will not be the most up-to-date, the simplest method is to use your distro's repositories. For example on Ubuntu, `sudo apt install ruby-full`. Make sure the repository version is > 2.2.5. You will also need the build tools Make and GCC, on Ubuntu get them with `sudo apt install build-essential`. For a more up-to-date version, use a manager such as [RVM](http://rvm.io/).

## Install Jekyll

Jekyll is a Gem, a software package installed via Ruby's management system called RubyGems (similar to Python's Pip). 
Open a terminal and type:
`gem install jekyll bundler`

This will take a minute as Gem installs all the dependencies and builds extensions. 

{% capture alert %}*Note:* Jekyll does not officially support Windows, however it is cross platform (they just don’t officially write windows documentation or check for bugs).
There is a [Jekyll on Windows](https://jekyllrb.com/docs/windows/#installation) page, but it can be out of date and inaccurate.{% endcapture %}
{% include alert.md text=alert color="warning" %}

# Text Editor

When working with code you should have a good text editor.
Windows notepad does not handle UTF-8 encoding or UNIX line endings that are standard for cross platform applications. 
For basic editing, Windows [Notepad++](https://notepad-plus-plus.org/), Mac TextEdit, or Linux Gedit are sufficient.
However, a more complete code editor will be helpful for managing Jekyll projects.

Open-source cross platform suggestions:

- [Visual Studio Code](https://code.visualstudio.com/)
- [Atom](https://atom.io/)
