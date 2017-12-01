# Mg3La2.common
~ 三镁化二镧🐙复联小队

在 `好中文` 课程中, 每个人都在复训中文写作...

## 成员
~ 五仁儿成联

- 005-[![BrookSongBrookSong](https://avatars0.githubusercontent.com/u/25792264?s=60&v=4)](https://github.com/BrookSongBrookSong)
- 017-[![sallysong007](https://avatars1.githubusercontent.com/u/26237577?s=60&v=4)](https://github.com/sallysong007)
- 42-[![ZoomQuiet](https://avatars0.githubusercontent.com/u/22494?s=60&v=4)](https://github.com/ZoomQuiet)
- 109-[![qingkongdy](https://avatars2.githubusercontent.com/u/33743520?s=60&v=4)](https://github.com/qingkongdy)
- 182-[![gcw182nico](https://avatars3.githubusercontent.com/u/33693084?s=60&v=4)](https://github.com/gcw182nico)

## 环境
~ 列出主要的嗯哼渠道

- 作业发布: [好中文的样子 - 专题 - 简书](http://www.jianshu.com/c/6c9915be5f2c)
- 小组专辑: [GC4LW🐙复盟 - 专题 - 简书](http://www.jianshu.com/c/5d0d3f8d3345)
- 和合分支: [GC4WP/common at mg3la2](https://github.com/GC4WP/common/tree/mg3la2)
- 团队指派: @GC4WP/mg3la2 

### 和合技

参考:

- 

## 工具

- 自己习惯的编辑器: 
    + 必须支持 Markdown 语法
    + 推荐: sublime text 3
- github 操作:
    + 现代浏览器: FireFox 版本 56.0.2/Chrome 最新版本
        * 扩展: [It's All Text! - Firefox 附加组件](https://addons.mozilla.org/zh-CN/firefox/addon/its-all-text/) 可以加速网页端内容编辑
    + 版本管理工具: git/svn

## 孤子分支

为了和 master 决断, 又因是小组专用分支, 没有合并回 master 的必要性,
所以, 对应的创建了 `孤子分支` 

- [Git - git-checkout Documentation](https://git-scm.com/docs/git-checkout/1.7.3.1)
- [如何建立一個沒有 Parent 的獨立 Git branch | ihower { blogging }](https://ihower.tw/blog/archives/5691)

形成的效果:

![git-orphan-network.png（PNG 图像，372x335 像素）](http://zoomquiet.qiniucdn.com/res/gc4lw/git-orphan-network.png)


> 即: 俗称的无头分支


### git 访问孤子分支
~ 又:`本地如何预防孤子分支合并`

先安装好 git 工具

- 下载: [Git - Downloads](https://git-scm.com/downloads)
- 然后, 在终端中进行如下操作:
    + 本地新建一个文件夹, git关联以上孤子分支. 

```
$ cd path/2/you/work/path (进入全新的空目录 注意, 这很重要, 不要在即有仓库目录里面建这个文件夹)
$ mkdir mg3la2
$  cd mg3la2
$  git init .
    ...
$  git remote add -t mg3la2 -f origin git@github.com:DebugUself/du4proto.git
$  git co mg3la2
$  git br -a
    * mg3la2
      remotes/origin/branch_name
$  git pl
Already up-to-date.
...
```

注意: 使用了配置简化常用命令, 部分配置如下

    [alias]
        st = status
        re = remote
        br = branch
        ci = commit
        co = checkout
        pu = push
        pl = pull
        del = rm

对比常规的本地工作复本中,查阅分支情况时的汇报:

```
༄  git br -a
  master
* mg3la2
  remotes/origin/HEAD -> origin/master
  remotes/origin/master
  remotes/origin/mg3la2
```

参考: [HbUsageGithubBranch · DebugUself/du4proto Wiki](https://github.com/DebugUself/du4proto/wiki/HbUsageGithubBranch)


### svn 访问孤子分支
~ 强烈建议 windows 用户使用这种方式来访问 github 

从  [Downloads · TortoiseSVN](https://tortoisesvn.net/downloads.html)
下载安装:

- TortoiseSVN 
- 以及配套的 Language packs (`是也乎`: 是的简体中文语言包)

通过资源管理器 进入一个合理的写作目录:

- 右键点击空白处
- 选择 SVN check out...
- 从 `https://github.com/GC4WP/common.git`
- 同步仓库为 `common`
- 首次下载时要求填写你的 github 帐号信息
    + **提醒**: 选择记忆口令,以免下次反复输入

参考:

- [Which remote URL should I use? - User Documentation](https://help.github.com/articles/which-remote-url-should-i-use/)
- [What are the differences between Subversion and Git? - User Documentation](https://help.github.com/articles/what-are-the-differences-between-subversion-and-git/)
- [Support for Subversion clients - User Documentation](https://help.github.com/articles/support-for-subversion-clients/)

svn 和 git 最大的不同是将 分支显性化了:

- 完成克隆的仓库在本地自动形成两个根入口:
    + trunk ~ 即 git 中的 master 分支
    + branches ~ 则进入所有其它分支
        * branches/mg3la2 就是小组分支
- 以及推荐的: `TortoiseSVN` 工具
    + 创造性的和 windows 系统资源管理器融合在了一起
    + 没有其它特殊界面
    + 所有操作都集成在鼠标右击菜单中了
- 用户手册:[TortoiseSVN ~ 针对 Windows 平台的 Subversion 客户端](https://tortoisesvn.net/docs/release/TortoiseSVN_zh_CN/index.html) 

![ContextMenuDirControl](https://tortoisesvn.net/docs/release/TortoiseSVN_zh_CN/images/ContextMenuDirControl.png)


## 是也乎

- 171201 创建


