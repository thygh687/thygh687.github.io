# 个人博客

纯静态博客：首页文章列表 + 文章页 + 关于页，没有服务器、没有数据库、不用登录。
样式简洁干净，没有外部字体和 CDN，打开就能看。

## 文件

- `index.html` — 首页（文章列表）
- `posts/*.html` — 文章，一篇一个文件
- `about.html` — 关于页
- `style.css` — 全部样式

## 写新文章

1. 复制 `posts/dns-basics.html`，改文件名、标题、日期、正文。
2. 在 `index.html` 的文章列表最上面加一行（日期、标题、链接、简介）。

## 上线（免费，不用信用卡）

### 方法一：GitHub Pages（推荐，有 GitHub 账号就能用）

1. 在 GitHub 上新建一个**公开**仓库，名字必须是 `thygh687.github.io`，不要勾 README。
2. 把这个文件夹里的所有文件上传到仓库（或等 Muse 推送；GitHub App 需要先把这个仓库加到授权里）。
3. 仓库 Settings → Pages → Source 选 `Deploy from a branch`，分支选 `main`，保存。
4. 等一两分钟，地址就是 `https://thygh687.github.io/`。

### 方法二：Netlify Drop（不用注册）

1. 打开 https://app.netlify.com/drop
2. 把整个文件夹拖进去，等一会儿就得到一个地址。

### 方法三：Cloudflare Pages

1. 注册一个 Cloudflare 账号（邮箱就行，不用卡）。
2. Workers & Pages → Create → Pages → 直接上传这个文件夹。

## 本地预览

双击 `index.html` 就能在浏览器里看。
