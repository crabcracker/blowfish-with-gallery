# blowfish-with-gallery

![GitHub repo size](https://img.shields.io/github/repo-size/crabcracker/blowfish-with-gallery?style=flat-square)
[![Powered by](https://img.shields.io/badge/powered%20by-hugo-ff4088?style=flat-square)](https://gohugo.io)

本项目是魔改版的 Hugo 主题 [blowfish](https://github.com/nunocoracao/blowfish)，在 blowfish 中植入了 Hugo 主题 [hermit](https://github.com/Track3/hermit) 作者 [Track3](https://github.com/Track3) 的个人博客 [Zakee's Planet](https://github.com/Track3/blog) 的 Gallery 元素。

## 注意事项

在使用项目站点形式的 GitHub Pages 链接 `https://<username>.github.io/<repository>` 作为 Hugo 博客的 baseURL 时，Gallery 首页的略缩图会因为路径错误无法正常显示。本项目临时采取的应对方法是在 `Gallery/照片文件夹/index.md` 中预览图的文件链接前加入仓库的名称，如 `/gallery/2020-06-20/DSCF2839_t.webp` 改为 `/blowfish-with-gallery/gallery/2020-06-20/DSCF2839_t.webp`。

如使用个人站点形式的 GitHub Pages 链接 `https://<username>.github.io` 或使用个人域名作为 Hugo 博客的 baseURL，需要将本仓库的改动复原。

Gallery 中的示例内容均来自Track3 的个人博客 [Zakee's Planet](https://github.com/Track3/blog)，这些内容均根据 Creative Commons BY-NC 4.0 许可协议许可。

## 致谢

- [nunocoracao/blowfish](https://github.com/nunocoracao/blowfish)
- [Track3/blog](https://github.com/Track3/blog)
- [lxgw/LxgwWenKai](https://github.com/lxgw/LxgwWenKai)