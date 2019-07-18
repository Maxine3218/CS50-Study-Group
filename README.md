# 简易翻译教程

## 翻译原则
严禁盲翻：即不看视频直接拿文本翻译，只有结合场景剧情才能翻译的准确出彩。

## 翻译软件
### 文件格式
字幕文件为 srt 格式，采用翻译软件Aegisub 编辑。先确认字幕文件的编码是unicode，然后用ae打开后，点击【文件】再【配置】按照下图设置。
字幕文件也可以用记事本, Notepad++, Sublime Text 等其他文本编辑器打开。
 
### 软件界面
黄色方框的时间轴部分请勿改动。如有断句需要改动的，直接在字幕中标出，后期校对会修改。红色方框中，把中文字幕四个字替换为中文翻译即可，中文在上英文在下。不要随意改动英文字幕。记事本也是一样：

### 翻译导出
在 ae 里选择【导出】再【存储】成 srt 文件，文件命名格式：Lecture[i] Part[j] - [译者姓名]
> 比如 Lecture0 Part1 - Athena。


## 翻译指南

### 内容
-	字幕中若出现旁白/解释/说明的部分不用翻译，应直接删掉；如果此行只有这种说明性文字，则连带整个时间轴全部删掉。
> 比如：[Applause]，完全可以删除。

> 再比如：英文字幕中偶尔会有 David: xxxx，这种情况下 David: 也可以删除。
-	对话类：不同两人的对白开头都要加英文半角的短横 “–” 引导，后一句和前一句对白内容之间为 2 个空格。
> 比如：-你吃了吗  -我吃了

> 格式：- AAAAA (两个空格) - BBBBB

### 格式
#### 标点符号
-	逗号句号：以一个空格代替。
-	英文半角下引号： ”” 仅用在引用或说话处，从英文字幕中直接复制。
-	音乐符号： ♪ 歌词 ♪ ---音乐符号直接从英文字幕中直接复制。
-	省略号： ... 这三个点中文字幕中务必保留。
- 感叹号问号：/* TODO */

#### 数字
- 数字统一用阿拉伯数字，字幕追求一目了然。
> 反例如，Week 0 应译成 “第 0 周”，而不是 “第零周”。

 
## 常见问题 

#### 问: 教授在课上讲软件界面上的按钮保留英文可以么？
答：可以。

#### 问：[Meow] 此处中文也要加方括号么？
答：不用。

#### 问：中文字幕和英文字幕是上下排版，还是左右排版？
 
答1：用记事本的话，请手动换行，用 ae 的，在中文字幕后加上 \N 就行，不要空格。这个情况大概是合轴的时候软件把代码去掉了，麻烦手动换下行吧。

答2：如果后期确实发现需要大量调整排版的话，我们可以用字符串处理程序去调整。

#### 问：Mac 上可以在 ae 中先进行翻译操作，再保存修改，不需要导出。这样可以么？

答：这是来自 Mac 的自动保存功能，这个做法容易造成数据丢失，不够安全，建议大家还是选择 ae 中的导出功能。



