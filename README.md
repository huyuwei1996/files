# files

## aria2

### 下载aria2

```
brew install aria2
```
### 下载aria2配置文件

```
curl -o ~/.aria2/aria2.conf "https://raw.githubusercontent.com/huyuwei1996/files/master/.aria2/aria2.conf"

curl -o aria2.conf "https://raw.githubusercontent.com/huyuwei1996/files/master/.aria2/aria2.conf"
```

默认下载路径的「/Users/xxx/Downloads」可以改为任何你想要的绝对路径。此处写为 Downloads 目录，xxx 请自行替换成你的 Mac 用户名

### 下载aria2c应用程序

```
mkdir /Applications/aria2c/
curl -o /Applications/aria2c/aria2.log "https://raw.githubusercontent.com/huyuwei1996/files/master/aria2c/aria2.log"
curl -o /Applications/aria2c/session.dat "https://raw.githubusercontent.com/huyuwei1996/files/master/aria2c/session.dat"
```

### webUI

https://ziahamza.github.io/webui-aria2/