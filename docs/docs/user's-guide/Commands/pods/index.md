# pulse pods

### Description
Developing a indepedent gamemode, which relies on libraries isolated from cached ones, _Pulse Pods_, special
Pulse feature comes into play. Executing a command prompts Pods wizard with simple question which runtime version
would the user like to use. Pods lists all the possible runtime releases including the beta versions. 
The selected runtime version will later be downloaded to `.pods` folder within root directory. The folder holds
runtime data and is the server itself.


!!! note
    Isolation can always be executed later, thus, the project can be isolated anytime.

### Syntax and usage

```shell
pulse pods
```

### Errors and return values

This command doesn't return any value.