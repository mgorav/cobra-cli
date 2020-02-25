# Installation

1. Install cobra

    `go get github.com/spf13/cobra/cobra`  


2. Run `main.go`. You would see full help and subcommands

    ```
    go run main.go

    This application shows how to create modern CLI
    applications in go using Cobra CLI library

    Usage:
    cobra-example [command]

    Available Commands:
    bye         says bye
    hello       says hello
    help        Help about any command

    Flags:
        --config string   config file (default is $HOME/.cobra-example.yaml)
    -h, --help            help for cobra-example
    -t, --toggle          Help message for toggle
    ```
3. Run a commaind 
 ```
  go run main.go bye
  ```
