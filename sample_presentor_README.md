# Working with GoLang (aka GO)

## Setting up GoLang

There are a few ways to install GoLang

- On Mac

```
brew install go
```

- On Windows

 1. Download Go from here https://golang.org/dl/
 2. Install Go using the installer


- Web Based Compiler (no need to install anything)

 1. Open a browser
 2. Go here https://play.golang.org/


## How Do I Start Writing Code

You need to setup your GOPATH, which is where all of your code will reside

- Mac:

```
export GOPATH=/Users/mack/go
```

### Let's Write a Simple Program<b>

Open up your favorite editor and create a new file, put the content list below in the file and save it in /Users/mack/go/src/example/main.go

```
package main

import "fmt"

func main() {
    fmt.Println("Hello Detroit Black Tech")
}
```

### Execute Your First Go Program

```
cd /Users/mack/go/src/example
go run main.go
```


## Value of GoLang - #1 - Single Binary

The ability to compile down to a single binary.  This means there are no dependency on external libraries

```
go build
./example
```

## Value of GoLang - #2 - Thread and Concurrency Built In

## Value of GoLang - #3 - Blah, Blah
