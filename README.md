# docker-go
Go

# Requirement
* [docker](https://www.docker.com/)

# Install
`.env.example` をコピー `.env` を作成。
各種設定値を修正。

* Docker起動
```
docker-compose up -d --build
```

* コンテナに入る
```
docker exec -it go sh
```

# Hello,World

``` go:main.go
package main

import "fmt"

func main() {
    fmt.Println("Hello, World!")
}
```

```
docker-compose exec go go run main.go
```

# Note

# Author
* [こぴぺたん](https://twitter.com/c_a_p_engineer)

# License
[MIT license](https://en.wikipedia.org/wiki/MIT_License).
