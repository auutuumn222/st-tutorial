# 空间转录组学入门讲义

面向计算机与人工智能背景初学者的中文讲义，从细胞、DNA、RNA 和蛋白质出发，介绍基因表达、空间转录组数据及计算研究问题。

## 阅读与编辑

- [阅读或下载最新讲义 PDF](空间转录组学_CS_AI入门_讲义.pdf)
- [查看 LaTeX 源稿与配图](源码/)
- [图片来源与许可](源码/空间转录组学_CS_AI入门_讲义_图片来源与许可.md)

PDF 根据本仓库中的最新源稿重新编译。内容按 17 章展开，覆盖生物学基础、实验测量、表达矩阵、空间信息、数据分析与研究验证。

## 文件结构

```text
st-tutorial/
├── README.md
├── 空间转录组学_CS_AI入门_讲义.pdf
└── 源码/
    ├── 空间转录组学_CS_AI入门_讲义.tex
    ├── 空间转录组学_CS_AI入门_讲义_使用说明.md
    ├── 空间转录组学_CS_AI入门_讲义_图片来源与许可.md
    └── 空间转录组学_CS_AI入门_讲义_配图/
```

## 编译

保留源稿与配图目录的相对位置，在“源码”目录使用 XeLaTeX 连续编译两次：

```sh
cd 源码
xelatex -interaction=nonstopmode -halt-on-error 空间转录组学_CS_AI入门_讲义.tex
xelatex -interaction=nonstopmode -halt-on-error 空间转录组学_CS_AI入门_讲义.tex
```

也可使用 Tectonic 自动完成多轮编译，或把“源码”目录上传至 Overleaf，选择 XeLaTeX 和对应主文件。中文使用 Fandol 字体，无需额外提供 .bib 文件。

## 图片与使用许可

第三方图片的作者、出处与许可见源稿中的图注及图片来源说明。仓库暂未添加统一开源许可证。

问题与修订建议可提交到 [Issues](https://github.com/auutuumn222/st-tutorial/issues)。
