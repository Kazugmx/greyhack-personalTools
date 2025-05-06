# libsql
## 1.0.0
### Alter password
Vulnerable memory zone: 0x7FD31865
Vulnerable variable: ghlightminitaused_bloc

### Reveal /lib directory
Vulnerable memory zone: 0x49AE82BB
Vulnerable variable: yte
Requirement : /usr
```sh
if params.len <= 4 then
    sessInit = sock.dump_lib.overflow(memspace,unsafeVar) //BoF
else
    sessInit = sock.dump_lib.overflow(memspace,unsafeVar,params[4]) //BoF
end if
print("response :"+sessInit)
files = sessInit.get_files
for file in files
    print(file.path)
end for
end i
```

### Returns computer object(Guest)
Vulnerable memory zone: 0x49AE82BB
Vulnerable variable: ypeopn
var2 : doseintxse
### Get guest shell

Vulnerable memory zone: 0x7AC359B1
Vulnerable variable: engths