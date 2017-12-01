# Mg3La2.common
~ 三镁化二镧🐙复盟小队

在 `好中文` 课程中, 每个人都在复训中文写作...

## 成员

- [BrookSongBrookSong](https://github.com/BrookSongBrookSong)


## 环境

## 工具


### 本地如何预防孤子分支合并
~ [HbUsageGithubBranch · DebugUself/du4proto Wiki](https://github.com/DebugUself/du4proto/wiki/HbUsageGithubBranch)

- 本地新建一个文件夹, git关联以上孤子分支. 
```
$ cd(注意, 这很重要, 不要在du4proto 里面建这个文件夹)
$ mkdir branch_name
༄  cd branch_name
༄  git init
...
༄  git remote add -t branch_name -f origin git@github.com:DebugUself/du4proto.git
༄  git co branch_name
༄  git br -a
* branch_name
  remotes/origin/branch_name
༄  git pl
Already up-to-date.

```


#### 获得最新代码
~ 为了不干挠主线的开发,并节省下载流量, 用`孤子分支`方式获得对应代码


从  [Downloads · TortoiseSVN](https://tortoisesvn.net/downloads.html)
下载安装:

- TortoiseSVN 
- 以及配套的 Language packs

先用资源管理器建立 `C:\uSEE` 目录:

- 如果原先有此目录
- 请将原有目录移走, 或是重命名


在资源管理器中进入 `C:\uSEE` 目录:

- 右键点击空白处
- 选择 SVN check out...
- 从 `https://github.com/uSEEet/uCl4xinsi.git/trunk`
- 下载为 `C:\uSEE\logger`
- 首次下载时要求填写帐号信息:
    + 用户: `useetech`
    + 口令: `plokijA2017`


## 是也乎

- 171201 创建


