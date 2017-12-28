# 在GibHub上使用Jekyll生成静态博客

之前曾经有过几次写博客的尝试，包括放在Wordpress上，自己搭空间，微信公众号等，都没有坚持下来。这次再试试新玩意，看看能不能坚持下来。

对于Windows用户来说，Jekyll并不是那么友善。要在GitHub上挂一个静态博客我做了下面一些步骤，z在网络状态OK的情况下，总共耗时2小时30分：
环境: Window10 Pro Build 16299.125
1. 注册一个[Github][1]账号。
2. 按照[指引][2]，生成一个GitHub Pages。注意，在这个过程中顺便在 **What git client are you using?** 中把 GitHub for Windows 也安装好。
3. 按照[指引][3]安装Windows Subsystem for Linux。
4. 根据[Jekyll的指引][4]的 **Installation via Bash on Windows 10** 方法安装Jekyll。
5. 把生成后的位于 `C:\Users\你的名字\AppData\Local\Packages\CanonicalGroupLimited.UbuntuonWindows_后缀会不一样\LocalState\rootfs\home\你的Linux用户名\你的Jekyll博客名字` 的内容复制出来，放到你的GitHub的repository的文件夹。然后Commit并Publish.


**打完收工**



  [1]: github.com
  [2]: https://pages.github.com/
  [3]: https://docs.microsoft.com/zh-cn/windows/wsl/install-win10
  [4]: https://jekyllrb.com/docs/windows/