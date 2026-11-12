# Vs School · SMK MERBAU

校园心理支持 + 安全举报平台（Vs School 2.0）

## 项目结构

```
vs-school/
├── index.html          # 主入口（只放结构）
├── css/
│   └── app.css         # 全部样式
├── js/
│   └── app.js          # 全部逻辑
└── README.md
```

## 本地运行

直接用任意静态服务器打开即可，例如：

```bash
# 方法1：VS Code Live Server
# 方法2：Python
python -m http.server 5500

# 方法3：Node
npx serve .
```

然后访问 `http://localhost:5500`

## 部署到 GitHub Pages

1. 把整个 `vs-school` 文件夹推到 GitHub 仓库
2. 仓库 Settings → Pages → Source 选 `main` 分支（或 `docs` / `gh-pages`）
3. 访问 `https://你的用户名.github.io/仓库名/`

## 注意事项

- 目前 JS 还是单文件（`js/app.js`），后续可以再按功能拆成 `auth.js`、`test.js`、`chat.js` 等
- Supabase 配置在 `js/app.js` 顶部
- 修改样式请编辑 `css/app.css`
