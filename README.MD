Based on [mac下使用apktool反编译](http://www.cnblogs.com/anee/p/4153411.html)

#use dex2jar
[dex2jar](https://github.com/pxb1988/dex2jar)
no need do unzip apk and get .dex
only use command:
```
sh d2j-dex2jar.sh -f ~/path/to/apk_to_decompile.apk
```
if `d2j-dex2jar.sh: line 36: ./d2j_invoke.sh: Permission denied` occurs
try
```
sudo chmod +x d2j_invoke.sh
```
from [stackoverflow](http://stackoverflow.com/questions/30875382/cannot-use-dex2jar-on-my-mac-permission-denied)
