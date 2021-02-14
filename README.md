# somelib

A test go library for learning go mod versioning.

I found especially the [Major version
suffixes](https://golang.org/ref/mod#major-version-suffixes) very hard
to grasp. This is my own experiments and descriptions. It may or may
not be of use for others.

## Test program

A test program may look like this;

```go
package main

import (
	"fmt"
	"github.com/uablrek/somelib/pkg/function"
)

func main() {
	fmt.Println("Somelib version ", function.GetVersion())
}
```

## Module path

In the [module-path](https://golang.org/ref/mod#module-path) it is
said about the major version suffix, e.g. `v2`;

> This may or may not be part of the subdirectory name.

In this example I choose to *not* have the suffix in any path.


## v1.0.0

