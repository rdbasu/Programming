
## INSTALL GO

*Download the package file* -
https://golang.org/dl/

- The package installs the Go distribution to */usr/local/go*
- The package should put the */usr/local/go/bin* directory in your PATH environment variable. 

```
LM-SJN-XXXXXXXX:~ robasu$ go version
go version go1.11 darwin/amd64
LM-SJN-XXXXXXXX:~ robasu$ `
```

*Create your workspace directory, **$HOME/go**. (If you'd like to use a different directory, you will need to set the GOPATH environment variable.)*

*make the directory **src/helloworld** inside your workspace, and in that directory create a file named **helloworld.go***

```
LM-SJN-XXXXXXXX:src robasu$ ls -ltr
total 0
drwxr-xr-x   3 robasu  120020480  102 Sep 17 10:05 github.braintreeps.com
drwxr-xr-x   3 robasu  120020480  102 Sep 17 10:07 golang.org
drwxr-xr-x  15 robasu  120020480  510 Sep 18 15:10 github.com
drwxr-xr-x   2 robasu  120020480   68 Feb 13 23:12 helloworld
LM-SJN-XXXXXXXX:src robasu$ 
```
## HELLO WORLD 
### helloworld.go
```
LM-SJN-XXXXXXXX:helloworld robasu$ cat helloworld.go 
package main

import "fmt"

func main() {
	fmt.Printf("hello, world\n")
}
LM-SJN-XXXXXXXX:helloworld robasu$ 
```

## Build & Run

```
LM-SJN-XXXXXXXX:helloworld robasu$ go build
LM-SJN-XXXXXXXX:helloworld robasu$ ./helloworld 
hello, world
LM-SJN-XXXXXXXX:helloworld robasu$ 
```

## 5 THINGS
- Goroutines
