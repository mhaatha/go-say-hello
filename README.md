# go-say-hello
`go-say-hello` is a simple Go module that provides a function to return a "Hello" string. This module is intended as a basic example for creating and sharing Go modules.

### Installation
To use this module in your project, you can install it by running:
```bash
go get github.com/mhaatha/go-say-hello@v1.0.0
go mod tidy
```

### Usage
After installing the module, you can import it and use the SayHello function as follows:
```go
package main

import (
	"fmt"
	"github.com/mhaatha/go-say-hello"
)

func main() {
	message := go_say_hello.SayHello()
	fmt.Println(message)
}
```
This will output:
```bash
Hello
```

### Versioning
This project uses [SemVer](https://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/mhaatha/go-say-hello/tags)

