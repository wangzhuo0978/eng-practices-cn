## 如何参与？
首先在github上fork本项目到自己的仓库下，然后一切改动都基于自己的仓库修改，最后提交 __Pull Request__ 将自己的改动提交到本仓库。 

#### 添加远程仓库   
`git remote add upstream git@github.com:xindoo/eng-practices-cn.git`
#### 将远程仓库的更新拉取到本地  
`git fetch upstream`  
#### 将远程更新合并到本地
`git rebase upstream/master`  

## 翻译要求  
0. [强制] pr前请先rebase到最新版本，参考以上几条git命令。 
1. [强制] 每次pr只包含一个commit，可以通过`git rebase -i` 将多个commit合并成一个。   
2. [建议] 适当意译，但要保证不丢失原意。
3. [注意] 为避免多人同时翻译同一篇文章，请先提PR在下方的翻译进度表中认领翻译任务，并确认翻译时间。
4. [注意] 为了保证翻译进度，如果翻译任务长时间未完成，任务将释放给其他人。 
5. [注意] 为了追踪后期内容更新，请认领任务时标注当前翻译内容的git提交版本号（可以在github文件详情右上方获取到，参考README其他示例）  

## 翻译进度

| 章节 | 译者 | 翻译进度 | 预计完成时间 |   
| :------------- |:-------------:|:-----:| :-----:|  
| [README.md](README.md) |[@xindoo](https://github.com/xindoo)| 翻译完成(版本:47ea81e) | 2019-09-13 | 
| [review/developer/cl-descriptions.md](review/developer/cl-descriptions.md) | [@Ensteinjun](https://github.com/Ensteinjun) | 翻译完成(版本:dda5915) | 2019-09-29 | 
| [review/developer/handling-comments.md](review/developer/handling-comments.md) |[@xindoo](https://github.com/xindoo)| 翻译完成(版本:47ea81e) | 2019-10-11 | 
| [review/developer/index.md](review/developer/index.md) | [@LargeOrange](https://github.com/LargeOrange) | 翻译完成(版本:47ea81e) | 2019-09-16 |    
| [review/developer/small-cls.md](review/developer/small-cls.md)  | [@LargeOrange](https://github.com/LargeOrange) | 翻译完成(版本:47ea81e) | 2019-10-06 |  
| [review/emergencies.md](review/emergencies.md) | [@wangzhuo] | 翻译完成(版本:47ea81e) | 2019-09-22 |    
| [review/index.md](review/index.md) |[@xindoo](https://github.com/xindoo) | 翻译完成(版本:47ea81e) | 2019-09-15 |    
| [review/reviewer/comments.md](review/reviewer/comments.md ) | [@LargeOrange](https://github.com/LargeOrange)  | 翻译完成(版本:47ea81e) | 20191008 |  
| [review/reviewer/index.md](review/reviewer/index.md ) | [@xindoo](https://github.com/xindoo) | 翻译完成(版本:47ea81e) |  2019-09-16 |  
| [review/reviewer/looking-for.md](review/reviewer/looking-for.md ) | [@xindoo](https://github.com/xindoo) | 翻译完成(版本:1ff5706) | 2019-10-08 |  
| [review/reviewer/navigate.md](review/reviewer/navigate.md ) | [@LargeOrange](https://github.com/LargeOrange)  | 翻译完成(版本:47ea81e) | 20191008 |  
| [review/reviewer/pushback.md](review/reviewer/pushback.md ) | [@xindoo](https://github.com/xindoo)  | 翻译完成(版本:47ea81e)| 2019-10-09 |  
| [review/reviewer/speed.md](review/reviewer/speed.md ) |  [@xindoo](https://github.com/xindoo)  | 翻译完成(版本:47ea81e) | 2019-09-25 |  
| [review/reviewer/standard.md](review/reviewer/standard.md ) | [@xindoo](https://github.com/xindoo) |  翻译完成(版本:47ea81e) | 2019-09-18|   
