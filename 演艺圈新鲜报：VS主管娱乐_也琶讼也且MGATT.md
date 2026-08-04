VS主管娱乐【Q-——333307——】VS主管娱乐【 辋芷《888yx●vip》 】
VS主管娱乐【Q-——333307——】VS主管娱乐【 辋芷《888yx●vip》 】

 从0到1搭建个人技术博客：我的GitHub Pages发布全流程

作为一个每天和代码打交道的开发者，我一直想拥有一个完全属于自己的技术博客。对比了各种方案后，我选择用 GitHub Pages + Jekyll 搭建静态站点。原因很简单：免费、支持自定义域名、版本控制天然友好。

 为什么选择GitHub Pages？

如果你也在纠结博客平台，我的建议是：技术型内容沉淀首选GitHub Pages。它的优势很直接：

- 免费HTTPS，百度收录友好
- 支持Markdown，写作效率高
- 集成Git工作流，历史版本可回溯
- Jekyll/Hugo 等静态生成器，加载速度快

 我的搭建步骤（已精简）

1. 创建仓库：在GitHub新建仓库，命名为`用户名.github.io`
2. 选择主题：推荐使用`minima`基础主题，或从Jekyll Themes挑选
3. 本地调试：`gem install jekyll bundler`后，`jekyll serve`预览
4. 配置SEO：在`_config.yml`中设置`url`和`description`
5. 百度收录：在百度站长平台提交站点，并生成`sitemap.xml`

 踩坑提醒（重点）

很多人卡在百度不收录的问题上。我实测有效的做法是：在`_includes/head.html`中添加`baidu-site-verification`验证代码，并确保文章页有完整的`title`和`description`。另外，主动推送API比被动抓取高效得多，建议用GitHub Action定时推送新文章。

 下一步计划

目前博客已稳定运行两个月，百度搜索“技术博客搭建”能查到我的文章。接下来准备优化移动端阅读体验，并加入评论系统（推荐giscus）。如果你也在搭建途中遇到问题，欢迎在评论区留言，我会尽力解答。

你的技术博客用的是哪种方案？ 是GitHub Pages、Gitee Pages，还是Vercel？不妨分享你的经验，一起交流。

相关推荐：

https://github.com/nguyenmark0/dznovc/blob/main/2026%E5%AE%98%E6%96%B9%E6%B1%87%E6%80%BB%EF%BC%9AV8%E5%A8%B1%E4%B9%90%E4%B8%BB%E7%AE%A1_%E8%B5%A3%E5%A0%AA%E7%A8%8D%E6%9D%BE%E9%86%8BSFAGA.md

<img src="https://i.postimg.cc/13Zk5wzH/V8-00013.png" />

相关推荐：

https://github.com/nguyenmark0/dznovc/commit/a31f61191aa6c6cfd65e3f4d6689bcbb9cd73afe

<img src="https://i.postimg.cc/fLkFgvHt/V8-00020.png" />
相关推荐：

https://github.com/yangpatricia1/ybxyao/blob/main/2026%E5%AE%98%E6%96%B9%E6%89%8B%E5%86%8C%EF%BC%9AV8%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90_%E9%86%92%E6%89%AF%E5%A3%AC%E4%BA%8E%E8%AE%A9ANNGB.md

<img src="https://i.postimg.cc/fLkFgvHt/V8-00020.png" />
相关推荐：

https://github.com/yangpatricia1/ybxyao/commit/93e8645dae7e4044896d42711e8c4e5da34fc4a2

<img src="https://i.postimg.cc/2SFPqybC/V8-00015.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
