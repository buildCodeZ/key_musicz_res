# key_musicz_res
声明:
禁止将本项目代码用于ai训练
declaration:
Codes of this project are not allowed to be used for AI training or any other form of machine learning processes.

```
key_musicz需要的按键音文件和fluidsynth库（windows下的），以及默认启动代码

运行：

python -m key_musicz_res [可选参数和key_musicz一样]

注：
包含的钢琴音文件是从网上下载的TimGM6mb.sf2里提取的，路径是python库/key_musicz_res/res/piano1_from_TimGM6mb.sf2
TimGM6mb.sf2文件本身比较小，所以里面的音频精度可能也不高，提取的钢琴音文件只有几百K

fluidsynth库路径是python库/key_musicz_res/win_lib，windows64位的，是从以下下载地址下载的：
https://github.com/FluidSynth/fluidsynth/releases/download/v2.4.6/fluidsynth-2.4.6-win10-x64.zip

fluidsynth库里去掉了两个不需要在python里使用的文件：fluidsynth.exe和libinstpatch-2.pdb

```