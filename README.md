<div align="center">

# Jluna Commands!

##### An always growing collection of my personal and most useful terminal commands and utilities

![License](https://img.shields.io/badge/license-GPLv3-green.svg) ![Platforms](https://img.shields.io/badge/platform-Linux%20%7C%20MacOS-blue.svg)



### These scripts have been tested on both Linux and MacOS. Not sure if they will work under the ubuntu-under-windows thingy. Be the first to test it! Forge the new frontier!

</div>

## Commands

<details>
<summary>Github</summary>

### Github

A very thin and tiny github-api wrapper. It allows you to create, list and clone your github repositories.

For it to work you need to get a [Github API token](https://github.com/settings/tokens) and store it in a shell variable called ``` GITHUB_API_TOKEN ```. I would export the variable at the end of your ``` .bashrc ``` like:

```
...
export GITHUB_API_TOKEN=98fds832HUNTER02fs9ghh0t92


```
#### Usage:

The usage is simple:

```
github command | optional-arguments

```
#### Commands:
- **create**: Creates a repository in github.com
- **list**: Lists all your github.com repositories
- **clone**: Clones a github.com repository by name in your machine

#### Optional arguments:
- **-n | --projectname **: Name of the project you want to create or clone.
- **-p | --public **: Wether you want the repository you are about to create public or private. By default is set to private.
- **-u | --upload **: Detects if you have a local repository in the current directory, sets the remote to the github.com repo you've created and pushes everything (commited)
- **--ssh**: Forces the use of ssh when connecting to github.com (default is https)

#### Examples:
- #####Creates public github.com repository and uploads local git repo, using ssh
``` github create -n jluna-commands -u --pulic --ssh```

- ##### Lists all of your github.com repositories
``` github list ```

- ##### Clones this github.com repository over ssh
``` github clone -n JavierLuna/jluna-commands --ssh ```
(Notice how I use here the author part)
</details>

<details>
<summary>Flask boilerplate</summary>

#Flask boilerplate

#### TODO


</details>







## Installing

### TODO


## Donate
If this project helped you in any way and you feel like supporting me well you can't. I do it for the pure enjoyment of making you happy (and to automate all the boring stuff we all do), so why don't you go and have a beer or whatever is your drink of choice? You deserve it!

Why are you still here?
You really want to make me happy don't you?

So help me expand this command-list and improve already existing scripts!!

Thank you so much for everything!


#### Inspired by: [Bash-Scripts](https://github.com/alexanderepstein/Bash-Snippets)