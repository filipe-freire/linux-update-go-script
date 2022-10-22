# Linux Go Install/Update Script

A custom bash script that installs/updates your Go version on linux. Because shipping a language with a command that updates itself is way too mainstream.

## Pre-Script Steps

**If it's your first time installing go:**

1. Add /usr/local/go/bin to the PATH environment variable.

You can do this by adding the following line to your `$HOME/.profile` or `/etc/profile` (for a system-wide installation):

`export PATH=$PATH:/usr/local/go/bin`

_Note: Changes made to a profile file may not apply until the next time you log into your computer. To apply the changes immediately, just run the shell commands directly or execute them from the profile using a command such as source $HOME/.profile._

**If you're updating from a previous version:**

1. Check that Go has been updated by running the following command:

```bash
go version
```

## Running the script

```bash
sh ./update-go
```

## Official Docs

For the official docs on how to install/update Go, please refer to <https://go.dev/doc/install>
