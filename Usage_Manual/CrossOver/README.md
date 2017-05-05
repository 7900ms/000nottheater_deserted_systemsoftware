
[安装](https://github.com/7900ms/000nottheater_deserted_systemsoftware/tree/master/Installation_Manual/CrossOver)

```
1.
新建容器 win7
~/Library/Application Support/CrossOver/Bottles/win7

2.
打开C盘

3.
字体优化
拷入字体到 Fonts 文件夹
(CrossOver.app 的界面语言 设置为英文(默认))
界面英文(默认)
defaults write com.codeweavers.CrossOver AppleLanguages -array en
(CrossOver.app 的某个瓶子的程序的语言 设置为中文)
程序中文
nano ~/Library/Application Support/CrossOver/Bottles/win7/cxbottle.conf 在 [EnvironmentVariables] 下添加

;;"LANG" = "en_US.UTF-8"
"LANG" = "zh_CN.UTF-8"


4.
运行程序(保存到指令面板)

(CrossOver.app 禁止联网)




= = = 脑容量回收站(碎碎念) = = =

/Applications/Safari.app/Contents/MacOS/Safari -AppleLanguages '(de)' 支持
/Applications/CrossOver.app/Contents/MacOS/CrossOver -AppleLanguages '(de)' 不支持
G mac 一个程序 系统语言

G crossover language
界面英文
https://www.codeweavers.com/support/wiki/mac/faq/cxdifferentlang
瓶子和程序中文
https://www.codeweavers.com/support/wiki/mac/faq/cxoffice62_choosedifferentlanguage

脑容量回收站
https://www.zhihu.com/question/24310666/answer/40138485
```
