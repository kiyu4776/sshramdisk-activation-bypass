[legacy iOS Kit](https://github.com/LukeZGD/Legacy-iOS-Kit)の sshramdiskでsetup.appを削除して、アクティベーションを擬似的に回避する

# step 1

```sh
mount.sh
```

#  STEP 2
```sh 
rm -fr /mnt1/Applications/Setup.app
```

# STEP 3
```sh
ls /mnt1/Applications/Setup.app/
```
ここで ``No such file or directory``　と出れば成功


# STEP 4
```sh
reboot_bak
```




