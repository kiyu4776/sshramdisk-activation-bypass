sshramdisk で　setup.appを削除して、アクティベーションを回避する

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
ls /Applications/
```
ここで ``No such file or directory``　と出れば成功


# STEP 4
```sh
reboot_bak
```




