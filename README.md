# git

生信相关项目仓库（`生信/git`）。

本目录已初始化为 Git 仓库，默认分支为 `main`，并推送到 GitHub 作为远程备份与协作入口。

## 使用

```bash
git clone <本仓库地址>
cd git
```

日常开发遵循常规 Git 流程：

```bash
git status
git add .
git commit -m "描述本次改动"
git push origin main
```

## 目录约定

| 路径 | 说明 |
| --- | --- |
| `README.md` | 项目说明 |
| `.gitignore` | 需要排除的临时文件、结果文件与大数据文件 |
| `scripts/` | 可复现的分析脚本（R / Python / Shell） |
| `data/` | 原始与中间数据（建议用 Git LFS 或外部存储管理） |
| `results/` | 分析输出与图表 |
