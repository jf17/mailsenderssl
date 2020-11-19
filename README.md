# mailsenderssl
For send email.

## How to use it

Example:
```go
package main

import (
	"github.com/jf17/mailsenderssl"
)

func main() {
	mailsenderssl.Send("host", "sender@example.com", "password", "recipient@example.com", "Title", "Body text")
}

```