# 伊摇 · 个人简历

在线简历页面，支持通过 GitHub Pages 生成可直接打开的链接。

## 个人照片

请将你的证件照或生活照放在本文件夹下，并命名为 **`photo.jpg`** 或 **`photo.png`**。页面头部会显示为大图；若未放置照片，会显示占位文字。

---

## 用 GitHub 把简历变成「一个链接」——详细步骤

下面按顺序做即可，全部在网页上完成，不需要装软件或敲命令。

---

### 一、准备工作：注册 / 登录 GitHub

1. 打开浏览器，访问：**https://github.com**
2. 若还没有账号：点右上角 **Sign up**，按提示填邮箱、设密码、起用户名，完成注册。
3. 若已有账号：点右上角 **Sign in**，输入账号密码登录。

---

### 二、第一步：新建一个仓库（用来放简历文件）

1. 登录后，在 GitHub 页面**右上角**找到 **「+」** 或 **「Create」**，点一下。
2. 在菜单里选 **「New repository」**（新建仓库）。
3. 进入新建页面后，按下面填写：
   - **Repository name**（仓库名）：填英文，例如 `resume` 或 `my-resume`（不要空格、不要中文）。
   - **Description**：可留空，或随便写一句如「个人简历」。
   - **Public**：选 **Public**（公开）。
   - 下面的 **「Add a README file」** 等选项**都不要勾选**，保持空白仓库。
4. 拉到底部，点绿色按钮 **「Create repository」**。  
   点完后会进入一个空仓库页面，提示 “Quick setup” 等，不用管。

---

### 三、第二步：把简历文件上传到这个仓库

1. 在你**刚建好的仓库页面**里，找到并点击 **「uploading an existing file」** 或 **「Add file」→「Upload files」**。
2. 会进入上传页面：
   - 要么把 **D 盘 person 文件夹里的所有文件**（`index.html`、`README.md`，若有 `photo.jpg` 或 `photo.png` 也一起）**拖进浏览器里**；
   - 要么点 **「choose your files」**，在弹窗里选中 person 文件夹里的这些文件，打开。
3. 确认上方文件列表里至少能看到 **`index.html`**（其它文件有就一起传）。
4. 在页面下方 **「Commit changes」** 那里：
   - 第一行说明可以写：`第一次上传简历`（或随便写）。
   - 然后点绿色按钮 **「Commit changes」**。
5. 上传成功后，仓库里会看到 `index.html`、`README.md` 等文件，说明上传完成。

---

### 四、第三步：开启 GitHub Pages（让链接能打开网页）

1. 在**同一个仓库页面**顶部，点 **「Settings」**（设置）。
2. 左侧一栏往下拉，找到 **「Pages」**，点进去。
3. 在 **「Build and deployment」** 下面：
   - **Source**：选 **「Deploy from a branch」**（从分支部署）。
   - **Branch**：点下拉框，选 **「main」**（或你看到的默认分支名），右边 **Folder** 选 **「/ (root)」**。
4. 点一下 **「Save」** 保存。
5. 等 **1～2 分钟**，刷新这个 Settings → Pages 页面，上面会出现一行绿色提示：**「Your site is live at https://你的用户名.github.io/仓库名/」**。  
   这个就是你的简历链接。

---

### 五、第四步：在浏览器里打开简历（新标签页）

- **方式一**：在 **Settings → Pages** 里，直接点那行 **「Your site is live at …」** 里的链接，会在新标签页打开简历。
- **方式二**：把链接复制下来（如 `https://你的用户名.github.io/resume/`），在浏览器地址栏粘贴，回车，即可打开。
- 以后要打开简历，只要在浏览器里输入或收藏这个链接即可；发给别人，别人点开也是这个简历页面。

---

### 链接长什么样（方便你对照）

| 情况 | 链接格式 | 示例 |
|------|----------|------|
| 仓库名是 `resume` | `https://你的用户名.github.io/resume/` | `https://zhangsan.github.io/resume/` |
| 仓库名是 `my-resume` | `https://你的用户名.github.io/my-resume/` | `https://zhangsan.github.io/my-resume/` |
| 仓库名是 `用户名.github.io` | `https://你的用户名.github.io/` | `https://zhangsan.github.io/` |

**注意**：链接末尾的 **`/`** 最好保留，否则有时会打不开。

---

### 以后想改简历怎么办？

1. 打开你的仓库页面，点进要改的文件（如 `index.html`）。
2. 点右上角 **「Edit」**（铅笔图标）进入编辑。
3. 改完后拉到底，点 **「Commit changes」** 保存。
4. 等一两分钟再打开你的简历链接，就会看到更新后的内容。  
   若你有照片，要更新照片：在仓库首页点 **「Add file」→「Upload files」**，上传新的 `photo.jpg` 覆盖原来的即可（需要和上次一样点 **Commit changes**）。

---

## 本地预览

用浏览器打开本文件夹下的 `index.html` 即可本地预览（双击文件或拖进浏览器窗口）。
