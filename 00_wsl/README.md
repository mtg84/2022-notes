# Windows Subsystem for Linux

List distributions:

```
 wsl.exe --list --all
```

List running distributions:

```
wsl.exe --list --running
```

Execute a distribution (Ubuntu-20.04):

```
wsl.exe -d Ubuntu-20.04
```

Accessing Linux networking apps from Windows (localhost):
<br>
Inside the distro
```
ip addr | grep eth0
```

Terminate a distribution (Ubuntu-20.04):
```
wsl -t Ubuntu-20.04
```


To access Windows filesystem from the distro:

``` 
/mnt/c
/mnt/d
/mnt/e
```

To access the distro filesystem from Windows:
```
\\WSL$
```

Converts from Windows route to Linux route:
```
wslpath [route]
```

Converts from Linux route to Windows route:
```
wslpath -w [route]
```
