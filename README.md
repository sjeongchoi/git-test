# Git Test

git fetch, rebase test

1. develop 에서 pull --rebase 로 (git fetch + git rebase origin/develop)을 한다.

```shell
# git pull default option
$ git config pull.rebase true # 변경
$ git config -l # 확인
```
   
2. develop 에서 브랜치(feature)를 만들어 작업하고 develop에 rebase하여 merge 한다.

local1
local2

remote1
remote2


remote change
