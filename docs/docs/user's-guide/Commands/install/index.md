# pulse install

### Description
Managing and coding on a succesful project may require dependencies. Instead of writting some complicated code, users
can use existing libraries and plugins, as well as install them immediately to the project by using `install` command.
The command takes one argument which is a part of GitHub URL in pattern of `username/project` which later is being inserted
into respective URL leading to inputted repository. It clones the repository to the project tree and caches it, firstly checking
if the repository is valid Pulse package (has `pulse.toml`).

!!! note
    Pulse has compatibility with sampctl, SA:MP package manager, therefore if a repository has pawn.json, it will
    treat it as a normal Pulse package!

### Syntax and usage

```shell
pulse install [PACKAGE]
```
**Arguments:**

- PACKAGE: package to install.

!!! note
    Package must be a valid GitHub repository.

### Errors and return values

This command doesn't return any value.