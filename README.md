# d2ds-courses | show your code 2024

存放参与d2ds-courses所有同学各自对应的代码练习仓库

---

**第一步: fork练习代码[仓库d2ds](https://github.com/Sunrisepeak/d2ds)**

**第二步: fork这个仓库(d2ds-courses)**

**第三步: 在本地拉取show-your-code-2024分支**

```bash

git clone -b show-your-code-2024 [your-d2ds-courses-url]

```

**第四步: 编辑.gitmodules并添加第一步中你的d2ds仓库**

> 格式

```bash
git submodule add -b main <repository-url> <path-to-submodule>
```

```text

[submodule "sunrisepeak"]
    path = sunrisepeak
    url = https://github.com/UnknownBugs/d2ds-sunrisepeak
    branch = main
    update = rebase

```

**第五步: 提交改动并向主仓库的your-d2ds-courses-url分支发起PR**