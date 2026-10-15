# cn

Merge Tailwind CSS classes like the cn() helper of shadcn/ui. Later classes win over conflicting earlier ones.

## Install

```sh
go get github.com/alexisbcz/cn
```

## Use

```go
package main

import (
	"fmt"

	"github.com/alexisbcz/cn"
)

func main() {
	fmt.Println(cn.Cn("px-2 py-1 bg-red-500", "p-3 bg-blue-500")) // p-3 bg-blue-500
}
```

## License

MIT. See [LICENSE](LICENSE) and [NOTICE](NOTICE).
