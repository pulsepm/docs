# pulse configure

### Description
Configuration-dedicated command is `configure`. The commands prompts a configuration wizard, which have several options. If
configuration file is not present, it will prompt the creation wizard, otherwise the modification one. User select the option
with a particular number for the respective option which is latter serialized to a configuration file (TOML). 
Options:

1. Modify GitHub username
2. Modify GitHub Token
3. Exit with saving
4. Exit without saving


### Syntax and usage

```shell
pulse configure
```

### Errors and return values

This command doesn't return any value.