# Polkit-Permission-promotion-compiled
Polkit提权包 CVE-2021-4034 （Easy access for those who need it)

源项目（需编译）：https://github.com/berdav/CVE-2021-4034

此为已编译后项目，全部导入

```python
chmod -R 777 2>/dev/null
```

```python
./exp
```

eg. dir tree：
```
CVE-2021-4034
├─ GCONV_PATH=.%
│    └─ pwnkit.so:.
├─ exp
├─ gconv-modules
├─ pwnkit.c
└─ pwnkit.so
```

Environment：
> ubuntu-16.04.7
> glibc 2.23
