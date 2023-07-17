![Office 365](/365.png)

## Activating Office 365

<br>

### 1. Turn Defender off

<br>

### 2. Open command prompt as Administrator

<br>

### 3. Run any of the following commands depending on the machine-

```
cd /d %ProgramFiles%\Microsoft Office\Office16

```
```
cd /d %ProgramFiles(x86)%\Microsoft Office\Office16
```

<br>

### 4. Take care of office license

```
for /f %x in ('dir /b ..\root\Licenses16\proplusvl_kms*.xrm-ms') do cscript ospp.vbs /inslic:"..\root\Licenses16\%x"
```

<br>

### 5. Run the following commands one after another

```
cscript ospp.vbs /inpkey:XQNVK-8JYDB-WJ9W3-YJ8YR-WFG99
```
```
cscript ospp.vbs /unpkey:BTDRB >nul
```
```
cscript ospp.vbs /unpkey:KHGM9 >nul
```
```
cscript ospp.vbs /unpkey:CPQVG >nul
```
```
cscript ospp.vbs /sethst:e8.us.to
```
```
cscript ospp.vbs /setprt:1688
```
```
cscript ospp.vbs /act
```


<br><br>

### Developer

Shamim Hossain<br>
sparrowmtm@gmail.com<br>
[https://sparrowtech.org](https://sparrowtech.org)<br>
+880 1758900389