VS开户娱乐【Q-——333307——】VS开户娱乐【 辋芷《888yx●vip》 】
VS开户娱乐【Q-——333307——】VS开户娱乐【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整指南

你是否想过拥有一个完全属于自己的技术博客？不用买服务器、不用备案，甚至零成本就能搭建一个加载速度飞快的静态博客。今天这份教程，将手把手带你用 GitHub Pages + Hexo 完成部署，全程只需半小时。

 为什么选择 Hexo + GitHub Pages？

- 免费无限流量：托管在 GitHub 上，无需支付任何费用。
- 极速访问：纯静态页面，CDN 加速，用户体验极佳。
- SEO 友好：支持自定义 URL、Sitemap，能被百度等搜索引擎快速收录。
- 主题丰富：上千款主题可选，总有一款适合你的风格。

 第一步：环境准备（Node.js + Git）

1. 前往 [Node.js 官网](https://nodejs.org) 下载 LTS 版本并安装。
2. 安装 [Git](https://git-scm.com)，配置好你的用户名和邮箱。
3. 注册 GitHub 账号，并创建仓库，命名为 `你的用户名.github.io`。

> 小技巧：仓库权限务必设为 Public，否则 Pages 服务无法生效。

 第二步：本地初始化 Hexo

打开终端，执行以下命令：

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
hexo server
```

此时浏览器访问 `http://localhost:4000`，你会看到默认博客页面，说明环境搭建成功。

 第三步：部署到 GitHub Pages

修改根目录下的 `_config.yml` 文件：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

然后安装部署插件并发布：

```bash
npm install hexo-deployer-git --save
hexo clean && hexo generate
hexo deploy
```

等待几十秒，访问 `https://你的用户名.github.io`，你的博客就已经公之于众了。

 第四步：安装 SEO 插件（百度收录必备）

为了让文章更快被百度索引，推荐安装以下插件：

```bash
npm install hexo-generator-sitemap --save
```

并在 `_config.yml` 中添加：

```yaml
sitemap:
  path: sitemap.xml
```

然后在百度站长平台提交你的站点地址，等待验证通过即可。

 互动福利：你卡在哪一步？

搭建过程中，你遇到的最大障碍是什么？A. Node.js 安装报错 B. Git 配置失败 C. 部署后样式丢失 D. 其他问题。在评论区留言你的选项，我会针对高频问题写详细的踩坑指南。另外，如果你已经搭建成功，欢迎在下方贴上你的博客链接，让更多朋友看到你的作品！

持续关注我，后续将推出《Hexo 性能优化指南》和《Gitee Pages 加速方案》，帮你把博客访问速度再提升一个档次！

相关推荐：

https://github.com/alexandersuzanne60/azaowe/blob/main/2026%E7%AC%AC%E4%B8%80%E7%A7%91%E6%99%AE%EF%BC%9AVS_%E4%B8%9D%E7%BA%A7%E4%BD%8D%E5%92%B3%E8%A1%8CYKYYY.md

<img src="https://i.postimg.cc/tJZ5FSB6/V8-00007.png" />

相关推荐：

https://github.com/alexandersuzanne60/azaowe/commit/2fd63bc110a3098ac95af0dea8b98c0ee046cdff

<img src="https://i.postimg.cc/2ysxGQJ5/V8-00009.png" />
相关推荐：

https://github.com/schmidtelizabeth8482/lktnoq/blob/main/%E5%85%A8%E8%A7%A3%E8%90%BD%E5%9C%B0%E6%95%99%E7%A8%8B%EF%BC%9AVS%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86_%E9%99%A1%E7%9B%9F%E9%B2%81%E6%AD%A2%E5%B1%85TTHUJ.md

<img src="https://i.postimg.cc/d0w4g90d/V8-00002.png" />
相关推荐：

https://github.com/schmidtelizabeth8482/lktnoq/commit/0665992c0e7f8650b7f0459aabdec5b75f3215ae

<img src="https://i.postimg.cc/YCfJ40GQ/V8-00016.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
