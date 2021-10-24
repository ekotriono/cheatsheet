# GO Cheat Sheet

## Basic Syntax

```bash
package main

import "fmt"

func main() {
    fmt.Println("Hello Go")
}
```

## Declarations

```bash
var lala int = 30
lala := 30
```

## Functions

```bash
func thisIsFunction() {}

func thisIsFunction () int {
    return 30
}
```

## Variadic Functions

```bash
func main() {
    fmt.Println(addArray(10,10))
}

func addArray(args ...int) int {
    total := 0
	for _, v := range args { 
		total += v
	}
	return total
}
```

## Loops

```bash
for i := 1; i < 30; i++ {
    
}
```


