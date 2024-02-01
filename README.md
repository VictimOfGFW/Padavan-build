# Padavan-build说明
现在不需要新建Release了，已经更改了脚本，直接fork，修改好之后，点击右上角的 Star 星星按钮即可开始自动编译（自己点击才会编译）。

git action 云编译方法详见：
https://www.jianshu.com/p/c31b58728778

newifi3和psg1218以外的branch需要重新修改build-padavan.yml
19行  runs-on: 后面修改为 ubuntu-latest 否则git action 会报错 Waiting for a runner to pick up this job
31行  cpio git python-docutils 修改为 cpio git docutils
