
#### 1. 预备 - 打通wine和pd

- 为什么要打通wine和pd<br>
通过打通wine和pd可以让同一份程序 直接在2个系统里运行。这样在两个系统里的歌词下载、显示、歌曲播放路径 都是一样的

- 共享
```
PD foobar2000 (和PD共享Home目录)

映射一个网络驱动器到Y盘: 网络 - Mac - Home 右键 映射网络驱动器 Y
共享软件路径：
Y~~~/Library/Application Support/CrossOver/Bottles/win7/drive_c/Program Files/foobar2000
```
#### 2. 在wine运行
```
crossover foobar2000
~/Library/Application Support/CrossOver/Bottles/win7/drive_c/Program Files/foobar2000

歌词路径：
Y:\Dropbox\lyrics aka(~/Dropbox/lyrics)
```
#### 3. 在pd里运行
```
共享软件路径：
Y~~~/Library/Application Support/CrossOver/Bottles/win7/drive_c/Program Files/foobar2000

共享歌词路径：
Y:\Dropbox\lyrics
```
### 结果

crossover 的 Y盘 (/目录) 和 PD视角的 Y盘 (~/目录) 是链接起来的

- wine-fb2k 和 pd-fb2k
在wine里拖入的歌曲，可以在pd里播放；在pd里搜到并保存的歌词，可以在wine里显示

-
