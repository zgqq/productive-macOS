
# 简介
- 为什么使用macOS?
有着linux命令行的体验，比 window 更漂亮的ui，而且没有广告的困扰，另外macOS有很多是专门为了productity 而生的软件也是一个重要的原因，比如window和linux 并没有像 alfred 生态丰富的启动器

- 我自已用了很久的mac，总结了不小可以提高生产力的软件和技巧，很多可以说是
最优的选择了，这里我会分为通用型，和编程相关类型


# 通用型
* 这里不涉及到任何编程相关的
## Alfred 自带workflow
这个软件应该用过macOS都知道，很多细节就不多说，推荐几个比较实用的workflow
- `剪切板管理` 这个应该是最常用的了，很多时候我们复制一些东西，然后过段时间，
又需要这些东西，又得重新去复制一遍，有了这个神器就不需要那么麻烦了，`cmd +option + c ` 唤起Alfred，就可以看到最近复制的内容了
- `搜索chrome书签`
正常的流程是，打开浏览器，然后搜索书签打开，有了这个workflow就可以直接唤起Alfred搜索了
- `snippet` 这个workflow也算是神器了， 如果你经常需要输入某段文字的话，可以设置缩写，然后会自动替换成这段文字，比如 经常需要输入手机号 `1888888888` ，设置缩写`;phone`，这样你在任何可以输入文本的地方输入 `;phone`，就会自动变成`1888888888`了
- `文件搜索` 经常接受或者下载一个文件，然后就忘记放在哪里，用这个workflow输入部分文件名就可以显示出来

## Alfred 第三方workflow
- `有道词典` 具体使用访问 https://github.com/whyliam/whyliam.workflows.youdao

## 快速启动
切换程序是最常用的操作，所以我们得重视这个高频的操作，正常的话 切换程序是通用 `cmd + tab`， 但是使用 Alfred 切换明显高效一点，这个是大部分人的方式了，
其实这个不是最高效的，使用快捷键切换才是正确的姿势，为什么呢？ 使用Alfred切换的时候，你需要关注搜索出来，然后确认进入，看似简单的操作，其实包含了一系列的操作，用快捷键就是一步到位，很多软件都有全局的快捷键，不过
这种方式也不算最完美的，因为要记住每个软件的全局快捷键而且有些软件还没内置全局快捷键，全局快捷键还容易冲突，后面会提到`hammerspoon` 这个软件，完美解决这个问题

## 使用谷歌搜索
谷歌搜索是要比百度好用很多，用好谷歌能够有效提高我们的生产力，比如遇到一个问题，如果使用百度搜索的话，很多可能搜出来一大堆复制来复制去的陈年博客，不但没有帮助，甚至会误导我们，反而降低效率， 谷歌搜索是真的强，它可以从你输入的关键词，推出最可能的context，展示正确的结果，因为我谷歌账号是一直登录的，我怀疑谷歌可能会记录搜索习惯，从而给出最合适的结果

## emacs快捷键
这个绝对是macOS的大招，`ctrl-e` 相当与 windows 的 `end` 键，`ctrl-a` 相当 `home`...还有很多，有了这些快捷键可以让你做到手不用离开键盘，详细快捷键功能查看 https://support.apple.com/zh-cn/HT201236

## 使用chrome
使用 chrome 的主要原因是  chrome有很多好用的插件， 插件推荐 https://github.com/zhaoolee/ChromeAppHeroes 另外一个原因是 chrome是跨平台的，可以保持我们的使用习惯，减低学习成本


