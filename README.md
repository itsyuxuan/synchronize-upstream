# synchronize-upstream

获取上游最新内容，在 fork 后与原仓库同步，解决对开源项目多次提交 pull request 需要重新 fork 的问题

```
git fetch upstream && git reset --hard upstream/main && git push -f
```

> Reference: https://github.com/selfteaching/the-craft-of-selfteaching/issues/67
