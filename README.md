# hustacm.com

[![Powered by MkDocs](https://img.shields.io/badge/Powered%20by-MkDocs-blue)](https://www.mkdocs.org/)
![AppVeyor](https://img.shields.io/appveyor/build/HUSTACM/hustacm.com)
[![Website](https://img.shields.io/website?down_message=offline&up_color=green&up_message=online&url=https%3A%2F%2Fhustacm.com)](https://hustacm.com)

🌐 HUSTACM 官方网站：<https://hustacm.com>

网站基于 [MkDocs](https://www.mkdocs.org/) 搭建，主要用于存放 HUSTACM 集训队历年成绩、训练计划、训练资源等内容。

## Build and Preview

你需要有 Python >= 2.7 或 3.4 环境。

安装依赖

```shell
$ pip install mkdocs
```

构建静态页面

```shell
$ mkdocs build
```

构建的静态文件将会存放在目录下新生成的文件夹 `site`。

运行以下命令在本地预览：

```shell
$ mkdocs serve
```

将会在 <http://127.0.0.1:8000/> 生成网页预览。

## Write Article

在 `docs` 目录下新建 `.md` 文件即可。

## LICENSE

GNU General Public License v3.0
