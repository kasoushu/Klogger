# klogger
a logrus formatted logger for kratos

# Basic
This package will offer you a logger which can be conbined with kratos.

This logger implement kratos Log interface 

And  implement logrus Format interface 
# Usage
```go
MyLogger := klogger.NewLogger()

// kratos/log 
log.NewHelper(MyLogger).Info("interface is initiating!")

// log.SetLogger(logger)
```
