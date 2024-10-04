### I speak to computers too 👋

```go
package main

import "fmt"

// I is about me
type I struct {
	am       string
	love     []string
	workWith []string
	aspire   string
}

func main() {
	me := I{
		am:       "Naren Arya",
		love:     []string{"Software", "Books", "Travel"},
		workWith: []string{"Python", "Go", "AWS", "DevOps", "Developer Experience"},
		aspire:   "To make this world a better and safe place with technology",
	}
	fmt.Println(me)
}

```
