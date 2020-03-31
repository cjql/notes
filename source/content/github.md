# GitHub    
专注于完成现有的功能比完成新的开始更有价值。（一个善终强于无数个善始）    
**不要直接提交给主分支。** 有太多的分支，先集中解决其中一两个。    
修故障，开新分支。添加新功能，开新分支。    
好的经验法则，每个5~10分支提交一次。    
提交信息：在做什么（向人展示你的工作），为什么做，为啥要采用你的提交。（description and detailed description）    
WYSIWYG：所见即所得。WY死机。    
## Git    
定义    Git是一种版本控制系统。能查看文件随历史编辑的变化情况。    
功能    
回退    
大胆修改    
修改原因    
冲突解决    
完整的历史记录    
多分支历史记录    
独立的多分支历史记录    
## GitHub    
GitHub是一个网站，用于上传Git数据库的副本（存代码），也是功能强大的软件开发平台。可对代码及其修改进行说明、讨论和评估。    
GitHub独立于Git的机制：    
共享库    
fork    
pull    
issue    
wiki    
## GitHub与Git的区别    

GitHub的局限：    
重命名尤其是文件夹    
只能在单个文件上修改    
不能改写历史    
不能在线解决冲突    

Git的优势：    
运行    
测试    
IDE    
多个重命名    
离线    
## GitHub选项卡    
code    仓库文件列表。简要说明和URL    
commit 当前分支的提交历史    
branches 分支列表    
releases 标签列表    
可以将标签加入时的文件以归档形势（zip、tar.gz）下载到本地。软件在升级时一般需要打标签。    
https://git-scm.com/book/zh/v2/Git-基础-打标签  
像其他版本控制系统（VCS）一样，Git 可以给历史中的某一个提交打上标签，以示重要。 比较有代表性的是人们会使用这个功能来标记发布结点（v1.0 等等）。 在本节中，你将会学习如何列出已有的标签、如何创建新标签、以及不同类型的标签分别是什么。    
### contributors pull requests被采纳的人数+作者    
pulse、commit history：工作进展。    
commit：保存修改。    code和commit处都可以选分支，查看分支的历史要切换到待查的分支。    
commit message：提交消息。what、why、where（好在哪）。    
branch：新功能。    
feature branch：功能分支。    
master：提供发布。    
release branch：发布分支。Bug必修的分支。    
tag：标签。可用于记录发布版本。    
check out：查看。    
issue：需求（旧Bug报告和新性能添加）。方向性讨论功能，跟踪缺陷。Pull Request时会自动创建Issue。数字是**Open**状态的Issue数。    
PR(pull requests)：拉请求。请人复查分支历史流，并请求合并。最新变化和讨论。目前处于工作状态的所有不同功能。列表查看并管理。数字是Open的PR数量。正在做什么，每个修改的当前状态。    
merge PR ：仅对贡献者可见。    
revert the merge：回退合并。    
merge前可修改PR（修改时切换到PR所在的分支），以供审查和反馈。    
merge前最好自己clone并运行。也可交给测试团队或部门做。    
右边退订和订阅pull（评论、@、提交、合并、关闭）    
多去评论，以帮助项目改善质量    
fork：分叉。到个人账户或组织。参与这个库开发的人数。可自行修改、提交。PR后可提交到最初的（被fork的）项目。    
branch + PR（pull requests）：分支协作。    
releases：发布的版本个数。    
watch：关注。该仓库的更新信息都会显示在用户的公开活动中。    
star：喜欢。做书签用。反应仓库的受关注程度。判断仓库热门程度的指标。    
wiki：内容管理系统。便捷的链接页面。readme太长 ⇒ 用户文档和开发文档（待修bug、待加功能）。仅支持公开库。    
settings。当前仓库的设置。    
Options。    
GitHub Pages：可直接在settings中设置。需公开库或者Pro。内容是readme的内容。    
Collaborators    
Branches    
Webhooks：issue、PR自动发送到项目。（用于项目管理、Bug跟踪、自动化测试的持续集成服务器）    
Notifications    
Integrations & services    
Deploy keys    
Secrets    
Actions    
Insight    
SSH clone URL：克隆仓库时所需要的URL。    
Referring sites：访客来之前访问的网站。    
Pulse：显示该仓库最近的活动。issue和Pull Requests。周期可调。additions and deletions：增删行数。修改一行=增一行+删一行    
Contributors：贡献值图（master exclude merge）。主图可分块拉取，以查看时间段内的情况。（私有库需额外添加合作者）    
Community    
Traffic：仅贡献者可见。访客信息。以图表形式显示该仓库的各项指标。    
Commits：每周提交数。下图是上图被选中的周期块对应的日内分解图。    
Code frequency：码频图。看显著变化，尤其是重构。    
Dependency graph    
. Network：分支数。以图表行政显示仓库当前的状态及fork出的状态。同时会显示成员列表。    
. Forks：成员列表。     
顶层（根目录）、文件夹（目录）。    
../移动到父目录。    
git只关心文件，无法将空文件夹添加到项目。约定：想建空文件夹就加.gitkeep文件。        
readme.md：项目说明。（如何：安装、使用、自动化测试、对项目作贡献）    
徽章（本质是用图片做显示的套娃）https://shields.io/    
依赖项目及其版本    
自动测试正在通过（passing）    
依赖关系是最新的    
适应的浏览器和操作系统版本    
https://github.com/twbs/bootstrap#status    
例子    
[![Slack](https://bootstrap-slack.herokuapp.com/badge.svg)](https://bootstrap-slack.herokuapp.com/)    
[![Build Status](https://github.com/twbs/bootstrap/workflows/Tests/badge.svg)](https://github.com/twbs/bootstrap/actions?workflow=Tests)    
[![npm version](https://img.shields.io/npm/v/bootstrap.svg)](https://www.npmjs.com/package/bootstrap)    
[![Gem version](https://img.shields.io/gem/v/bootstrap.svg)](https://rubygems.org/gems/bootstrap)    
[![Meteor Atmosphere](https://img.shields.io/badge/meteor-twbs%3Abootstrap-blue.svg)](https://atmospherejs.com/twbs/bootstrap)    
[![Packagist Prerelease](https://img.shields.io/packagist/vpre/twbs/bootstrap.svg)](https://packagist.org/packages/twbs/bootstrap)    
[![NuGet](https://img.shields.io/nuget/vpre/bootstrap.svg)](https://www.nuget.org/packages/bootstrap/absoluteLatest)    
[![peerDependencies Status](https://img.shields.io/david/peer/twbs/bootstrap.svg)](https://david-dm.org/twbs/bootstrap?type=peer)    
[![devDependency Status](https://img.shields.io/david/dev/twbs/bootstrap.svg)](https://david-dm.org/twbs/bootstrap?type=dev)    
[![Coverage Status](https://img.shields.io/coveralls/github/twbs/bootstrap/master.svg)](https://coveralls.io/github/twbs/bootstrap?branch=master)    
[![CSS gzip size](https://img.badgesize.io/twbs/bootstrap/master/dist/css/bootstrap.min.css?compression=gzip&label=CSS+gzip+size)](https://github.com/twbs/bootstrap/tree/master/dist/css/bootstrap.min.css)    
[![JS gzip size](https://img.badgesize.io/twbs/bootstrap/master/dist/js/bootstrap.min.js?compression=gzip&label=JS+gzip+size)](https://github.com/twbs/bootstrap/tree/master/dist/js/bootstrap.min.js)    
[![BrowserStack Status](https://www.browserstack.com/automate/badge.svg?badge_key=SkxZcStBeExEdVJqQ2hWYnlWckpkNmNEY213SFp6WHFETWk2bGFuY3pCbz0tLXhqbHJsVlZhQnRBdEpod3NLSDMzaHc9PQ==--3d0b75245708616eb93113221beece33e680b229)](https://www.browserstack.com/automate/public-build/SkxZcStBeExEdVJqQ2hWYnlWckpkNmNEY213SFp6WHFETWk2bGFuY3pCbz0tLXhqbHJsVlZhQnRBdEpod3NLSDMzaHc9PQ==--3d0b75245708616eb93113221beece33e680b229)    
[![Backers on Open Collective](https://img.shields.io/opencollective/backers/bootstrap.svg)](#backers)    
[![Sponsors on Open Collective](https://img.shields.io/opencollective/sponsors/bootstrap.svg)](#sponsors)    
## 区分    
### download zip 与git clone    
download zip：单纯下载到本地，无法查看日志和对仓库进行修改    
https://www.prestonlamb.com/blog/creating-a-docker-image-with-github-actions    
### issue和PR    
* issue：未做的，可以和master无关    
* PR：已修bug和新增功能，但尚未合并。必须有master和分支    
### labels 和 milestone    
* lables：可同时多个。可按字母和issue数排序。    
* milestone。只能有一个。可用来做deadline。可按更新时间、完成度（同milestone中关闭的issue占比）、到期、字母、issue数排序    
## 大文件传输    
https://git-lfs.github.com/    
* 下载，安装    
* bash移动路径到对应仓库    
* git init    
* git lfs install    
* touch .gitattributes    
* git lfs track "*.pdf"    
* git lfs track "*.epub"    
* git add .gitattributes    
* git add *.epub    
* git commit -m "Add design file"    
* git remote add origin https://github.com/cqlj/allitebooks    
* git push origin master    
重复6、8、9、10、11    
```bash    
Git LFS has been disabled on your personal account cqlj because you’ve exceeded your data plan by at least 150%. Please purchase additional data packs to cover your bandwidth and storage usage:    
https://github.com/account/billing/data/upgrade    
Current usage as of 11 Jan 2020 09:20PM UTC:    
Bandwidth: 0.0 GB / 1 GB (0%)    
Storage: 7.37 GB / 1 GB (737%)    
```    
## 远程操控    
```bash    
git init    
echo "## allitebooks" >> README.md    
git add README.md    
git add -A(add all files)    
git commit -m "first commit"    
git remote add origin git@github.com:cqlj/allitebooks.git    
## git remote -v (for checking current repository)    
## git pull --rebase origin master    
git push -u origin master    
```     
## Errors    
**Updating the Git index failed**    
参考：[stackoverflow](https://stackoverflow.com/questions/10573815/why-is-updating-the-git-index-failed-displayed)    
```    
git config --global core.autocrlf false    
```    
```    
Updating the Git index failed.    A rescan will be automatically started to resynchronize git-gui.    
warning: LF will be replaced by CRLF in source/categories/index.md.    
The file will have its original line endings in your working directory    
```    

**Sorry, we had to truncate this directory to 1,000 files.**    
Large files detected. You may want to try    
[Git_Large_File_Storage](https://git-lfs.github.com)    
[**中文乱码**](https://www.cnblogs.com/scale/p/6258457.html)    
git config --global i18n.commitencoding utf-8    
git config --global i18n.logoutputencoding gbk    
git config --global gui.encoding utf-8    
https://services.github.com/    GitHub产品大全，包括Learning Lab、Developer API等    
## 其他    
https://help.github.com/en/github/authenticating-to-github/removing-sensitive-data-from-a-repository    
https://tecadmin.net/delete-commit-history-in-github/    
https://gist.github.com/stephenhardy/5470814    
https://github.com/cjql/archive/wiki/_history    
★MEMO★    
[shortcuts](https://help.github.com/en/articles/using-keyboard-shortcuts)    
[tips](https://blog.csdn.net/neilol/article/details/46568611)    
★update★    
[cjql](https://www.gitmemory.com/cjql)    
[issue](https://github.com/issues?q=is%3Aissue+author%3Acjql+sort%3Aupdated-desc)    
[repo](https://github.com/search?o=desc&q=user%3Acjql+&s=updated&type=Repositories)    
[wiki](https://github.com/cjql/webs/wiki/_history)    
[wikis](https://github.com/search?o=desc&q=user%3Acjql+&s=updated&type=Wikis)    
★scan★    
[repos](https://github.com/settings/repositories)    
[watching](https://github.com/watching)    
[trending](https://github.com/trending)    
[封禁用户](https://github.com/settings/blocked_users)    
[贡献墙](https://github-contributions.now.sh/)    
[changelog](https://github.blog/changelog/)    
[cheatsheet](https://github.com/tiimgreen/github-cheat-sheet/)    
[cheatsheet](https://github.github.com/training-kit/downloads/zh_CN/github-git-cheat-sheet/)    
[cheatsheetzh](https://github.com/tiimgreen/github-cheat-sheet/blob/master/README.zh-cn.md)    
[GitDoc](https://git-scm.com/book/en/v2)    
[stanford](http://www-cs-students.stanford.edu/~blynn/gitmagic/intl/zh_cn/)    
[geeeeeeeeek](https://github.com/geeeeeeeeek/git-recipes)    
[廖雪峰](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)    
[阳志平](https://www.yangzhiping.com/tech/github.html)    
[中文教程](https://github.com/gotgit/gotgithub)    
[gitimmersion](http://gitimmersion.com/index.html)    
[Version Control](https://www.git-tower.com/learn/)    
[美化git ](http://justinhileman.info/article/git-pretty/)    
[ sharing](http://codemancers.com/blog/posts/2014-05-01-using-git-for-knowledge-sharing/)    
★gitignore★    
[Create](https://www.gitignore.io/)    
[Joe](https://karan.goel.io/joe/)    
[csdn](https://blog.csdn.net/qq19414123/article/details/53435591)    
[segmentfault](https://segmentfault.com/q/1010000004164312?_ea=513255)    
[branch](https://learngitbranching.js.org/)    
[python](https://github.com/vinta/awesome-python)    
[others](https://github.com/sindresorhus/awesome)    
[API](https://api.github.com/users/cjql)    
[labels](https://developer.github.com/v3/issues/labels/)    
[shields](https://github.com/badges/shields)    
[hosts](https://github.com/racaljk/hosts)    
[Sourcetree](https://www.sourcetreeapp.com/)    
[hosts](http://gogs.io/)    
[censorship](https://github.com/citizenlab/chat-censorship)    
[teleirc](https://github.com/FruitieX/teleirc)    
★Famous★    
[Google](https://github.com/google)    
[Apple](https://github.com/apple)    
[Facebook](https://github.com/facebook)    
[Twitter](https://github.com/twitter)    
[Microsoft](https://github.com/microsoft)    
[Square](https://github.com/square)    
[alibaba](https://github.com/alibaba)    
[linux](https://github.com/torvalds/linux)    
[rails](https://github.com/rails/rails)    
[NodeJS](https://github.com/nodejs/node)    
[Swift](https://github.com/apple/swift)    
[Coffeescript](https://github.com/jashkenas/coffeescript)    
[Ruby](https://github.com/ruby/ruby)    
[Torvalds](https://github.com/torvalds)    
[Dhh](https://github.com/dhh)    
[JakeWharton](https://github.com/JakeWharton)    
★學習教程★    
[try](https://try.github.io/)    
[githug: Git your game on](https://github.com/Gazler/githug)    
[githug通关攻略](http://lingavin.com/githugtong-guan-gong-lue.html)    
[git-game: terminal game to test git skills ](https://github.com/git-game/git-game)    
[Learn Git Branching:形象直观的图形化练习网站。](https://learngitbranching.js.org/)    
[伯乐在线:git详解系列](http://blog.jobbole.com/tag/pro-git/)    
[猴子都能懂的Git入门](http://backlogtool.com/git-guide/cn/)    
[GitHub上的12个骚操作](https://segmentfault.com/a/1190000011380397)    
[bitbucket的教程](https://www.atlassian.com/git?atl_source=cac-bitbucket-1&atl_medium=ace&atl_campaign=ACE-158-Stash-GIT-on-Bitbucket-CAC_git")    
https://blog.csdn.net/chaishen10000    

## 搜索    
私有库的code也能被搜索到。    
默认搜索是从master分支搜索代码，只有小于384k的代码才是可以搜索到的    
https://github.com/search/advanced    
https://github.com/issues?q=author:cjql+sort:updated-desc+label:    
https://help.github.com/categories/searching-for-information-on-github/    
https://github.com/search?q=icon+size:>200000+extension:css&type=Code    
https://github.com/search?q=minitest+filename:test_helper    匹配文件名    
https://github.com/search?q=icon+size:>200000+extension:css&type=Code    
https://github.com/search?q=octocat+in:file&type=Code     文件    
https://github.com/search?q=octocat+in:path&type=Code    路径    
https://github.com/search?q=octocat+in:file,path&type=Code    文件或路径    
https://github.com/search?q=display+language:scss&type=Code    语言    
https://github.com/search?q=Integer&type=Code    关键词    
https://github.com/search?q=element+language:xml+size:100&type=Code    大小    
https://github.com/search?q=user:cjql    
https://github.com/search?q=user:cjql+php    作者    
https://github.com/search?q=user:cjql+"公元前613年"&type=Issues    精确匹配    
http://blog.sina.com.cn/s/blog_4e60b09d0102vcso.html    

## 参考书    
GitHub入门，李新叶，Introducing GitHub，Peter Bell& Brent Beer，2015年8月。（无源码）    
