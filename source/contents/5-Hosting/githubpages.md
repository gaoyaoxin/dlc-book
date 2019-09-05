# 托管到 GitHub Pages


### 托管前提

- GitHub 账号与相应项目

    通过 GitHub 托管网页，需要有 GitHub 账号是肯定的。还需要新建用来存放项目的项目仓库。
    Github 的相关操作在“协同与版本控制”章节有详细讲解。

- GitHub Pages 托管机制与 docs 文件夹

    > You can configure GitHub Pages to publish your site's source files from `master`, `gh-pages`, or a `/docs` folder on your master branch for Project Pages and other Pages sites that meet certain criteria.

    GitHub Pages 托管来源要求是来自 `master` 或 `gh-pages` 分支或者名为'docs'的文件夹。

   GitHub Pages 是通过 `index.html` 作为入口识别托管的网页，这个 `index.html` 必须直接存放在 `master` 或 `gh-pages` 分支，而不是放在分支的其他文件夹中。把分支当作文件夹来看

   但我们的 Sphinx 项目构建发布为 html 版本之后，是存放于`build` 文件夹的，所以将整个 Sphinx 项目托管到 GitHub Pages 之后，从分支不能直接访问到 `index.html` 文件，就需要通过 `/docs` 文件夹托管。


### GitHub Pages 托管



参考链接：GitHub Pages 设置参考 https://help.github.com/en/articles/configuring-a-publishing-source-for-github-pages