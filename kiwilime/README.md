
# 1 关于

`kiwilime` 是一个源码安全审计的 *Sublime Text3* 插件，主要实现以下功能：

- 调用 `kiwi` 工具对当前 *Forder* 进行源码安全审计扫描
- 高亮显示 `kiwi` 工具的安全扫描报告，并且能够快速跳转到扫描报告中指定的相应代码位置
- 在当前 Forder 中快速搜索当前选中或当前光标所在的单词
- 将可以的代码位置加入到 **review-view**
- 将当前代码跟踪的关键位置记录到 **trace-viw**
- 将无用的代码审计信息删除到 **trash-view**
- 高亮显示当前打开的代码文件中可能存在安全问题的代码位置
- 根据当前单词或当前选中的单词，在当前文件中前后跳转

注：*Forder* 为 *Sublime Text3* 打开的 *project*，一般显示在左侧边栏


# 2 安装

**Step 1.** 

获取 kiwilime

    git clone https://github.com/alpha1e0/kiwi.git

**Step 2.** 

打开 Sublime Text 3 package-directory

    Preferences --> Browse packages

**Step 3.**

将 **kiwilime** 目录整个 copy 到 package-directory

**Setp 4.**

下载pt工具（kilime用该工具进行代码搜索）。[下载地址](https://github.com/monochromegane/the_platinum_searcher/releases)


