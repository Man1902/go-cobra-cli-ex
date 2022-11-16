* Install the cobra generator : 
```
go install github.com/spf13/cobra-cli@latest
```

* Initalizing a module : 
```
mkdir go-cobra-cli-ex
cd go-cobra-cli-ex
go mod init github.com/Man1902/go-cobra-cli-ex
```

* Initalizing a Cobra CLI application : 
```
cobra-cli init
```

* Add commands to a project : 
```
cobra-cli add <COMMAND_NAME>
```

* Add sub-command : 
```
cobra-cli add <COMMAND_NAME> -p <PARENT_COMMAND_NAME>
```

* Cmmand usage Example : 
```
go-cobra-cli-ex net ping -u google.com

go-cobra-cli-ex info diskUsage
```

* Reference Link : 
- https://github.com/spf13/cobra
- https://github.com/spf13/cobra-cli
- https://github.com/spf13/cobra/blob/main/user_guide.md
- https://www.youtube.com/watch?v=SSRIn5DAmyw
