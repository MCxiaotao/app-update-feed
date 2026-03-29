# app更新源

这个仓库用于承接静态更新元数据和发布产物说明。

## 用途

- 托管 `stable.json`
- 对应 GitHub Releases 中的 bundle zip
- 给 `launcher.exe` 提供固定 manifest 地址

## 建议发布流程

1. 在 `app测试版` 构建 launcher 和 bundle
2. 上传 bundle zip 到本仓库的 GitHub Releases
3. 生成新的 `stable.json`
4. 提交并发布 `stable.json`
