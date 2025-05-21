# 相部 羽也斗
- コマンドの練習

 ```
[user@localhost ~]$ chmod -R 777 /root
chmod: changing permissions of '/root': Operation not permitted
chmod: cannot read directory '/root': Permission denied 
```

```
[user@localhost ~]$ rm -rf --no-preserve-root /root
rm: cannot remove '/root': Permission denied
```