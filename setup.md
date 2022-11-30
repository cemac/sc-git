---
layout: page
title: Setup
---

## Install software

### Windows

If you are using a Windows operating system, the [Git Bash][git_bash] software can be used.

If you have administrative access to your computer, you can download the *Standalone Installer* and
run through the installation process to install the software on your computer.  All of the defaults
are fine, but is recommended to change the *Configuring the terminal emulator to use with Git Bash*
option to **_Use Windows' default console_**.

If you do not have administrative access to your computer, you can download the *Portable edition*.
This is an executable, which when run will extract all the files required to run the software, and
includes the required executables. For the purposes of this session, it is recommended to extract
the files to the Desktop directory, which should result in a new directory named *PortableGit* on
the desktop.

### Apple MacOS

For MacOS, install Git for Mac by downloading and running the most recent "mavericks" installer from
[this list][git_macos].

Because this installer is not signed by the developer, you may have to right click
(control click) on the .pkg file, click Open, and click Open on the pop up window.

After installing Git, there will not be anything in your `/Applications` folder, as Git is a command
line program. For older versions of OS X (10.5-10.8) use the most recent available installer
labelled "snow-leopard" available [here][git_macos].

### Linux

If Git is not already available on your machine you can try to install it via your package manager.
For Debian/Ubuntu run `sudo apt-get install git` and for Fedora run `sudo dnf install git`.

### Additional installation notes

There are various instructions available regarding the installation of the Git software:

* [Official Git website][git-install-official]
* [GitHub][git-install-github]
* [GitLab][git-install-gitlab]

The Software Carpentries notes on installing Git can be found in [this section of the workshop template][workshop-setup].

[git-install-official]: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git
[git-install-github]: https://help.github.com/en/github/getting-started-with-github/set-up-git
[git-install-gitlab]: https://docs.gitlab.com/ee/topics/git/how_to_install_git/
[workshop-setup]: https://carpentries.github.io/workshop-template/#git

## Initial working directory

We'll do our work in the `Desktop` folder so make sure you change your working directory to it with:

~~~
$ cd
$ cd Desktop
~~~
{: .language-bash}

[git_bash]: https://git-scm.com/download/win
[git_macos]: http://sourceforge.net/projects/git-osx-installer/files/
