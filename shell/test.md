# 语法规则


### 注释 rem 

https://xstarcd.github.io/wiki/windows/windows_cmd_summary_commands.html
https://www.w3cschool.cn/dosmlxxsc1/wvqyr9.html
https://wsgzao.github.io/post/windows-batch/



## 需要两个批处理

### 1. my_quant更新  dev更新到main  main更新到release

第一步: 切换到dev 分支然后          git  pull
第二步: 切换到main分支然后          git  pull, 再git merge dev ,git push
第三步: 切换到release_v2.0分支然后  git  pull, 再git merge main,git push
