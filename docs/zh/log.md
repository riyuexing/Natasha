## 日志


#### 开启日志：
```C#
NSucceedLog.Enabled = true;
NErrorLog.Enabled = true;
NWarningLog.Enabled = true;

```  

#### 关闭日志：
```C#
NSucceedLog.Enabled = false;
NErrorLog.Enabled = false;
NWarningLog.Enabled = false
```

#### 编译器开启日志开关：
```C#
// AssemblyBuilder 中：
Compiler.ErrorBehavior = ExceptionBehavior.Log;
Syntax.ErrorBehavior =  ExceptionBehavior.Log;
```
