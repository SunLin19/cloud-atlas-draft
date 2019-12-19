

```go
package main

import "fmt"

func main() { // "{" 符号需要和关键字func同一行
	fmt.Println("Hello world!")
}
```

go语言对代码格式化要求严格。提供了 `gofmt` 工具检查代码规范，可以用来格式化指定包中所有文件或者当前文件夹中文件。很多文本编辑器可以配置为每次保存文件时自动运行gofmt，以便保证源文件正确的形式。

# 命令行参数

os包提供函数和变量，以与平台无关的方式和操作系统打交道。命令行参数以os包中Args名字的变量供程序访问，在os包外面，使用os.Args。变量 os.Args 是一个字符串 slice 。

> 请思考 Python 中的 slice 切片

表达式 s[m:n] 表示一个从第m个到第n-1个元素的slice。

