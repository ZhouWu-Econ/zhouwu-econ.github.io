# Zhou Wu 学术主页

这是一个用于 GitHub Pages 的静态网站，无需安装依赖或运行构建工具。本地双击 `index.html` 即可预览。

## 文件目录

```text
index.html
assets/
  style.css
  photo.jpg
files/
  Zhou_Wu_CV.pdf
papers/
  one-way-versus-two-way-clustering.pdf
  joint-bayesian-model-predictive-selection.pdf
```

`papers/` 仅发布以上两篇工作论文的全文。其他稿件请勿加入公开仓库。

页面 Research 区域展示 1 篇 Job Market Paper、2 篇已发表论文和 4 篇其他工作论文。新增的 3 篇工作论文只展示题名、合作者和介绍，不提供全文链接。目前仅 JMP 和贝叶斯联合选择论文标注 Journal of Econometrics 在审；其他工作论文不展示投稿状态。

JMP 和其余工作论文均列出研究领域关键词。会议信息按简历中的录用状态展示：JMP 为 GBESG 2026，贝叶斯联合选择论文为 AMES 2024，矩阵补齐论文为第 26 届中国经济学年会；均使用“Accepted for presentation”，不将录用写成已经完成报告。

页面还包括教育与访问经历、浙江大学助教与计量经济学复习课教学经历和技能。教育与访问经历位于 Research 之前；两类教学经历并列展示；技能位于最后一个内容栏目。研究项目经历仅保留在简历中。

## 发布

将上述文件及目录上传到仓库 `main` 分支的根目录，保留目录结构。进入 **Settings → Pages**，将 Source 设为 **Deploy from a branch**，选择 **main** 和 **/(root)**，点击 **Save**。

发布后的网址为：https://zhouwu-econ.github.io/

## 更新

- 修改文字与链接：编辑 `index.html`。
- 修改配色与排版：编辑 `assets/style.css`。
- 更换照片：替换 `assets/photo.jpg`。
- 更新简历或两篇工作论文：用同名 PDF 替换对应文件，更新页面中的日期或版本说明，再上传更改。

上传后，GitHub Pages 会自动更新网站。
