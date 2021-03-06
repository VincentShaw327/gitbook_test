## 查看分支

* git branch     ——列出所有本地分支
* git branch --list      ——同上
* git branch --list  &lt;pattern&gt;   ——列出匹配到正则表达式的分支
* git branch -r   ——列出所有远程分支
* git branch -a   ——列出所有远程和本地分支
* git branch -a \[ --contains \[&lt;commit&gt;\] \]  ——列出所有包含指定commit的分支
* git branch -a \[ --no-contains \[&lt;commit&gt;\] \]   ——列出所有不包含指定commit的分支
* git branch - \[  \(  --merged  \|   --no-merged \)  \[&lt;commit&gt;\]  \]   ——列出所有包含了指定被合并的commit分支
* git branch  --point-at ~~_&lt;object&gt;_~~   ——根据给定的对象列出指定分支
* git branch  --format &lt;format&gt;
* git branch  \[ --color \[ =&lt;when&gt; \] \| --no-color\]  ——设置是否高亮显示当前所处分支。设定值必须是'always'（默认） , 'never','auto'.
* git branch  \[ --column \[ =&lt;options&gt; \] \| --no-column \]   ——设置是否按列显示分支名称。设定值只能是'always'和'never'.
* git branch  \[-v  \[--abbrev=&lt;length&gt; \| &lt;--no-abbrev&gt; \]  ——显示与上游commit的相关信息\(哈希值、注释等\) abbrev表示哈希值长度
* git branch  \[--sort=&lt;key&gt;\]  ——根据给定的key排序

## 创建分支

* git branch    \[--track \| --no-track\]   \[ -f \]  &lt;branchname&gt;   \[&lt;start-point&gt;\]

## 分支操作

* git branch  \( --set-upstream-to=&lt;upstream&gt; \| -u &lt;upstream&gt; \)  \[&lt;branchname&gt;\]
* git branch  --unset-upstream \[&lt;branchname&gt;\]    ——移除分支上游
* git branch  \(-m \| -M\) \[&lt;oldbranch&gt;\] &lt;newbranch&gt;     ——分支重命名
* git branch  \(-c \| -C\) \[&lt;oldbranch&gt;\] &lt;newbranch&gt;      ——分支复制
* git branch  \(-d \| -D\) \[-r\]  &lt;branchname&gt;…​    ——删除分支
* git branch --edit-description \[&lt;branchname&gt;\]   

## 

## 分支合并

git merge \[-n\] \[--stat\] \[--no-commit\] \[--squash\] \[--\[no-\]edit\]

	\[-s &lt;strategy&gt;\] \[-X &lt;strategy-option&gt;\] \[-S\[&lt;keyid&gt;\]\]

	\[--\[no-\]allow-unrelated-histories\]

	\[--\[no-\]rerere-autoupdate\] \[-m &lt;msg&gt;\] \[-F &lt;file&gt;\] \[&lt;commit&gt;…​\]

git merge --abort

git merge --continue



## 分支合并工具

git mergetool \[--tool=&lt;tool&gt;\] \[-y \| --\[no-\]prompt\] \[&lt;file&gt;…​\]





