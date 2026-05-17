# Attention

本文件是 CodeStable 技能启动必读的项目注意事项入口。所有 CodeStable 子技能开始工作前必须读取它。

## 项目碎片知识

<!-- cs-note managed: 用 cs-note 维护，新条目按下面分节追加 -->

### 编译与构建

### 运行与本地起服务

### 测试

### 命令与脚本陷阱

### 路径与目录约定

### 环境变量与凭证

### Fork 二次开发工作流

- 本仓库是 gdlwolf/author（fork 自 YuanShiJiLoong/author）
- `origin` → 你的 fork（https://github.com/gdlwolf/author）
- `upstream` → 原作者仓库（https://github.com/YuanShiJiLoong/author）
- `dev` 分支是二次开发主分支
- 拉取原作者更新：`git checkout main && git pull upstream main && git push origin main`，然后 rebase/merge 到 dev
- .codestable/ 仅存在于 dev 分支和你的 fork，不提交到 upstream

### 其他
