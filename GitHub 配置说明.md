# GitHub 配置说明

建议把整个 Vault 发布到 GitHub 私有仓库。这样每次学习笔记、图片和 Canvas 图都有历史版本。

## 首次发布

1. 打开 GitHub Desktop。
2. 选择 `File → Add local repository`。
3. 选择本 Vault 的根目录。
4. 若提示不是 Git 仓库，选择创建仓库。
5. 第一次 Commit 后，点击 `Publish repository`。
6. 勾选 `Keep this code private`，再发布。

## 日常操作

```text
开始编辑前：Fetch origin / Pull origin
写完笔记后：Commit to main → Push origin
```

## 不要上传

- 密码、Token、私钥、API Key
- 客户数据、生产日志、个人身份信息
- 未获得授权的公司内部文档

根目录中的 `.gitignore` 已经排除了部分个人窗口状态和常见临时文件。
