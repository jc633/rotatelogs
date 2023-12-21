### Forked from [lestrrat-go/file-rotatelogs](https://github.com/lestrrat-go/file-rotatelogs)
加了一个返回前一个日志文件名的功能
```bash
go get github.com/jc633/rotatelogs@latest
```
```go
//example
rl := &rotatelogs.RotateLogs{}
rl.PreviousFileName()
```