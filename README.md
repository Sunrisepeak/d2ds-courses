# d2ds-courses | show your code 2024

存放参与d2ds-courses所有同学各自对应的代码练习仓库

---

**第一步: fork练习代码[仓库d2ds](https://github.com/Sunrisepeak/d2ds)**

**第二步: fork这个仓库(d2ds-courses)**

**第三步: 在本地拉取show-your-code-2024分支**

```bash

git clone -b show-your-code-2024 [your-d2ds-courses-url]

```

**第四步: 添加你的d2ds代码仓库**

```bash
git submodule add -b main <your-d2ds repository-url> <your-id>
git config -f .gitmodules submodule.<your-id>.update rebase
```

**第五步: 提交改动并向主仓库的your-d2ds-courses-url分支发起PR**