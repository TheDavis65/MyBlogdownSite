---
date: "1012-01-01"
tags:
- test
title: Test 1
---

Test 1
I am referencing a footnote[^1]

```go {linenos=inline}
package main

import "fmt"

func main() {
  fmt.Println("{linenos=inline}")
}
```

```go {linenos=table}
package main

import "fmt"

func main() {
  fmt.Println("{linenos=table}")
}
```

```
Detter en test fo at se om dette virker
```

[^1]: I am the footnote
