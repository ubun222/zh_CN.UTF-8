# zh_CN.UTF-8
适用于越狱后的IOS/iPad OS终端（不适用于无根越狱，因为/usr/share/locale不可写）

1. 下载仓库
2. 将zh_CN.UTF-8复制到/usr/share/locale/
```
cp -r zh_CN.UTF-8 /usr/share/locale/
```
3. 应用
```
export LC_ALL="zh_CN.UTF-8"
```
4. 写入.bashrc
```
echo "export LC_ALL=zh_CN.UTF-8" >>~/.bashrc
```
