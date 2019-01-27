# Bash Shell Configuration

##  Description:
This repo holds useful bash shell client configurations. The .bash_profile contains a set of aliases and shell functions that eases your when life working with the terminal.

Create a ~/.work_profile! It will hold all individual configurations of your workstation! This will allow you to customize configurations in case you have multiple workstations and still share general configurations across at the same time. 

## Work from others

* [Solarized theme] Thanks to Ethan Schoonover
* [.bash_profile, .bash_prompt, .aliases] Many thanks to Nathaniel Landau
* [Sexy Bash Prompt] Many thanks to gf3
* [Git config in multiple files]


[Solarized theme]:                          http://ethanschoonover.com/solarized
[.bash_profile, .bash_prompt, .aliases]:    https://gist.github.com/natelandau/10654137
[Sexy Bash Prompt]:                         https://github.com/gf3/dotfiles
[Git config in multiple files]:
https://github.com/ciukes/CommonGitConf

## Installation

Download the git repo

```console
$ git clone https://github.com/effelow/bash-shell-configuration.git
```

Create a symlink in your home linking the .bash_profile, .bash_prompt, and .aliases in the repo

```console
$ ln -s ./bash-shell-configuration/.bash_profile ~/.bash_profile
```

```console
$ ln -s ./bash-shell-configuration/.bash_prompt ~/.bash_prompt
```

```console
$ ln -s ./bash-shell-configuration/.aliases ~/.aliases
```



Add the .gitconfig to your local git configuration

```console
$ edit ~/.gitconfig
    [include]
        path = ~/[path-to-repo]/bash-shell-configuration/.gitconifig
```
