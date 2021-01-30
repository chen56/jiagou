## win10 dev init

```powershell
## https://docs.microsoft.com/en-US/office/troubleshoot/office-suite-issues/cannot-open-add-in-from-localhost
CheckNetIsolation LoopbackExempt -a -n="microsoft.win32webviewhost_cw5n1h2txyewy" 
```

## debug 

```powershell
# https://docs.microsoft.com/zh-cn/office/dev/add-ins/testing/runtime-logging
npx office-addin-dev-settings runtime-log --enable "C:\Temp\office\OfficeAddins.log"
# Runtime logging has been enabled. File: C:\Users\c\AppData\Local\Temp\OfficeAddins.log.txt
```