# lua-bytecode-compat

makes lua(64bit) work with lua bytecode(32bit)

lua bytecode files which create by this version, are the same with [lua-PUC.Rio](http://www.lua.org/)(32bit)

based on lua-5.1.5

## how to use patch

get [lua-5.1.5.tar.gz](http://www.lua.org/ftp/lua-5.1.5.tar.gz)


```
tar -xzf lua-5.1.5
cd lua-5.1.5
patch -p1 < path-of-compat.diff
```

