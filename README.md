# mailsenderssl
Sending emails over SSL port 465.

## How to use it

main.go
```go
package main

import (
	"github.com/jf17/mailsenderssl"
)

func main() {
	mailsenderssl.Send("smtp.example.com", "sender@example.com", "password", "recipient@example.com", "Title", "Body text")
}

```