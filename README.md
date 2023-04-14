# shimeji_D5
>2017年左右制作的3个桌宠

我并非该软件的原作者（我甚至并非IT工作人员，我画这些画只是觉得好玩），关于版权等说明请查看下载内容中的LICENSE.txt文件（我在每个桌宠对应的文件夹中都保留了它），我会在我的理解范围内对我发布的这份桌宠进行说明，包括如何更改它的一些设置，希望大家能够从这些小桌宠身上得到些乐趣。

I didn't create this tool(I'm not even an IT worker, I drew these little desktop companions just for fun). The LICENSE file is kept in each folder in the zip files. Hope you enjoy it(them?).

## 如何在MacOS上运行桌宠（How to run shimeji on MacOS）
### Step1：下载相应的文件（Download the proper zip file）
请下载“桌宠_macOS.zip”，解压后你会看见3个文件夹（也就是3个桌宠），分别名为“小白_OS”、“小黑_OS”和“杰克跟宠”。(你可以给这些文件夹重命名，比如改成英文字母拼音，有的时候中文字符可能会导致桌宠启动失败)

Please download "桌宠_macOS.zip", once you unzip it you'll see 3 folds named: "小白_OS", "小黑_OS" and "杰克跟宠". You could just change their name into English, incase your operation systerm may not support Chinese.

### Step2：打开你的命令行终端（Open the terminal）
在很久以前，双击相应文件夹中的*.app就可以直接打开桌宠（你也可以先这么试试，我猜java6可以做到？），不过随着java的更新，可能需要通过命令行去运行相应的jar文件了。

Few years ago, you can just double click the .app file to launch it(you could still try it if you are using java6). But right now I guess we need to run the .jar file in command line.

MacOS自带一个名为“Terminal”的app，启动它，你就会得到一个可以输入命令行的窗口。

首先，我们进入桌宠所在的路径（位置），先在命令行输入`cd `（是空格，我加了空格）。

然后直接拖动桌宠所在文件夹到终端，松开鼠标，路径自动就写好了。

接着按回车，这一条命令就运行好了，也就意味着你已经进入了桌宠所在的路径（位置）。

你可以输入`ls -l`然后回车，就可以看见当前目录（文件夹）中的文件，你会发现有一个名为`run.sh`的文件，它里面已经写好了启动桌宠所需要的命令，你可以直接在命令行输入`nohup sh run.sh &`然后回车，大约需要几秒中的时间，你就会看见桌宠从屏幕上方落下来。

>剩下的我明天写。真的。
>
>此处需要插入一个说明动画

## 如何在Windows上运行桌宠（How to run shimeji on Windows）
TODO【虚拟机还没搞赢就是说

## 其他
### 这些按钮式什么意思
### 修改最大分裂次数（Set MaxCount）

>最大分裂次数是什么：桌宠会随机分裂成多个，最大分裂次数就是你的屏幕上最多会出现多少个桌宠的克隆。
>
>WHAT is MaxCount：The MAX number of desktop companions.

在conf目录中，有一个名为“行動.xml”的文件，你可以用你喜欢的软件去打开它并编辑它（我会在VSCode中直接编辑，偶尔也在Terminal中用vim）

文件的第5行可以看见相关的设置，修改`値=`后面的数字，即可改变最大分裂次数。

`<定数 名前="maxCount" 値="3" />`

### 调整
### 

