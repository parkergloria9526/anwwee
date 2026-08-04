VS开户【Q-——333307——】VS开户【 辋芷《888yx●vip》 】
VS开户【Q-——333307——】VS开户【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025亲测有效）

你是否想过拥有一个完全属于自己的技术博客，却苦于服务器成本高、搭建流程复杂？今天这份教程，将手把手教你利用 GitHub Pages 和 Hexo，在30分钟内免费搭建一个高速、稳定、支持自定义域名的个人网站。

 为什么选择 GitHub Pages + Hexo？

在众多博客方案中，这套组合的核心优势非常突出：
1. 完全免费：托管在 GitHub 服务器上，无需购买云主机。
2. 版本管理：所有文章以 Markdown 格式存储，天然支持 Git 版本回溯。
3. 极致速度：全球 CDN 加速，国内访问速度表现优异。
4. 高安全性：静态页面无数据库注入风险，免维护。

 第一步：环境准备与基础安装

在开始前，请确保电脑已安装 Git 和 Node.js (建议v14+)。打开终端，执行全局安装命令：

`npm install -g hexo-cli`

安装完成后，初始化博客文件夹：
`hexo init my-blog && cd my-blog && npm install`

此时，本地博客骨架已建立。输入 `hexo s` 启动本地服务，浏览器访问 `http://localhost:4000` 即可预览默认主题。

 第二步：关联 GitHub 仓库

1. 在 GitHub 新建仓库，命名格式必须为 `你的用户名.github.io`（关键步骤）。
2. 修改根目录 `_config.yml` 配置文件，将 `deploy` 分支指向该仓库：

```
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

3. 安装自动部署插件：
`npm install hexo-deployer-git --save`

 第三步：一键部署与访问

依次执行三条命令，完成发布：
`hexo clean && hexo generate && hexo deploy`

浏览器访问 `https://你的用户名.github.io`，你的专属博客已上线！

 进阶技巧：绑定自定义域名与SEO优化

- 在 `/source` 目录下新建 `CNAME` 文件（内容填你的域名），并在域名服务商配置 CNAME 记录指向 `你的用户名.github.io`。
- 安装 SEO 插件 `hexo-generator-seo-friendly-sitemap`，自动生成站点地图，利于百度收录。

遇到报错怎么办？ 检查 Node.js 版本是否过旧，或尝试将 GitHub 仓库默认分支由 `master` 改为 `main`。如果部署超时，可删除 `.deploy_git` 文件夹后重试。

---

动手实践是掌握技能最快的方式。 如果在搭建过程中遇到 “Hexo命令无效”、“Git推送失败” 等高频问题，欢迎在评论区留言你的 操作系统及错误代码，我会逐一回复并提供解决方案。如果本文对你有帮助，记得点赞收藏，后续将更新《Hexo 主题深度定制与性能优化》专题！

相关推荐：

https://github.com/yangpatricia1/ybxyao/blob/main/2026%E5%AE%98%E7%BD%91%E7%9B%98%E7%82%B9%EF%BC%9AV8%E7%BD%91%E5%9D%80%E4%BB%A3%E7%90%86_%E5%92%8F%E9%9F%B6%E5%8F%B7%E5%87%B3%E6%A2%A2PVPPD.md

<img src="https://i.postimg.cc/d0w4g90d/V8-00002.png" />

相关推荐：

https://github.com/yangpatricia1/ybxyao/commit/1c362686259bdf3ba4ecf4d58997cbad8bbe2e5f

<img src="https://i.postimg.cc/nzw2jbGZ/V8-00006.png" />
相关推荐：

https://github.com/cruzdenise0/avxylh/blob/main/2026%E7%A7%91%E6%8A%80%E6%B1%87%E6%80%BB%EF%BC%9AV8%E7%BD%91%E5%9D%80app_%E6%82%A3%E6%8C%A4%E5%B0%B1%E5%8F%B6%E9%85%B6VBCYF.md

<img src="https://i.postimg.cc/5tbnDmt0/V8-00001.png" />
相关推荐：

https://github.com/cruzdenise0/avxylh/commit/b436c13e4ebf87d3e52b1fe20585476cbea8c9b7

<img src="https://i.postimg.cc/d05pBf9J/V8-00019.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
