# DocMan 官方文档

DocMan 是一个自由开源的文档站点生成器，它可以让我们优雅、简洁的生成和部署开发文档，API 接口文档，教程，笔记等多种类型的站点。

## 项目地址

DocMan：[Gitee](https://gitee.com/monkeyhbd/docman) | [GitHub](https://github.com/monkeyhbd/docman)

Docman 文档：[Gitee](https://gitee.com/monkeyhbd/docman-document) | [GitHub](https://github.com/monkeyhbd/docman-document)

## 尝试一下

你可以将本项目当作一个 DocMan 文档项目的示例，用 DocMan 将本项目生成为文档站点。

进入 DocMan 实例

```sh
cd /path-to-docman
npm install
```

新建 `docs` 文件夹

```sh
mkdir docs
```

拉取本文档项目

```sh
# Gitee
git clone https://gitee.com/monkeyhbd/docman-document.git

# GitHub
git clone https://github.com/monkeyhbd/docman-document.git
```

编辑 DocMan 根目录下的配置文件 `docman.config.json`

```json
{
	"inputDir": "./docs/docman-document",

	"outputDir": "./dist",

	"themeDir": "./themes/docman-theme-classic"
}
```

运行 DocMan 生成文档站点

```sh
npm run build
```

DocMan 将会输出 HTML 文件至发行目录 `dist` 下。
