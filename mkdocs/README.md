## MkDocs
mkdocs用于部署文档十分方便

## 安装mkdocs和插件
```bash
pip install mkdocs
pip install pymdown-extensions
pip install mkdocs-material
pip install mkdocs-jupyter==0.21.0
pip install lxml-html-clean
pip install mkdocs-bibtex
```

## git 远程传输
[参考](https://blog.csdn.net/m0_62342492/article/details/140589266)
```bash
# 全局设置
git init
git config --global user.email "zhusitao1990@163.com"
git config --global user.name SitaoZ

# 远程获取仓库
git pull https://github.com/SitaoZ/wet-lab.git
# 添加文件到仓库
git add mkdocs.yml
git commit -m "Initial commit"

# 远程添加
git remote add origin https://github.com/SitaoZ/wet-lab.git

# 添加新的文件到仓库
git add docs/ref/ref.bib
git add docs/overrides/main.html
git commit -m "new commit"

# 推送
git push -u origin main

```

## mkdocs本地部署和GitHub部署
[参考](https://blog.csdn.net/m0_62342492/article/details/140589266)
```bash
mkdocs -h
mkdocs -V
# 注释mkdocs.tests.base
vi "/home/zhusitao/miniconda3/lib/python3.12/site-packages/mkdocs_jupyter/plugin.py"
pip install mkdocs-bibtex
mkdocs serve
mkdocs serve --dev-addr=0.0.0.0:8000

# 部署网页
mkdocs gh-deploy
```

