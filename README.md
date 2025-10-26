# GitHub Actionsの使い方

## 参考
- [GitHub Actionsを使ってCI/CDを実装](https://www.youtube.com/watch?v=RxcUrg3OO3o)



## ブランチの作成と切り替え
```sh
$ git checkout -b ブランチ名
$ git switch -c ブランチ名 (version 2.23.0)

git switch -c feature/add_test
```

## ブランチ一覧確認
```sh
## 今いるブランチには「 * 」がつきます
git branch
```

## mainブランチに切り替える
```sh
$ git checkout main
$ git switch main (version 2.23.0)
```

## workfowsの作成
```sh
mkdir -p .github/workflows
```


[actions/checkout](https://github.com/actions/checkout)

[actions/setup-python](https://github.com/actions/setup-python)

## push
```sh
git add .
git commit -m "ワークフロー作成"

git push -u origin feature/add_test
```
