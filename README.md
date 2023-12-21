### Forked from [lestrrat-go/file-rotatelogs](https://github.com/lestrrat-go/file-rotatelogs)
加了一个返回上一个日志文件名的功能
```go
rl := &rotatelogs.RotateLogs{}
rl.PreviousFileName()
```