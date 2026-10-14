# 使用指南

## 下载与安装

在官网[下载页](https://bidcore.cn/download.html)或本仓库的 [Releases](https://github.com/haozhentech/BidCore-Desktop/releases/latest) 下载 Setup.exe 安装，或者下载 Portable.exe 直接运行。需要 Windows 10 / 11 x64。安装包暂未做代码签名，Windows 可能提示发布者未知；请核对下载来源和同版本的 SHA256SUMS.txt。

PowerShell 校验命令：`Get-FileHash -Algorithm SHA256 -LiteralPath '下载的EXE完整路径'`，把结果和 SHA256SUMS.txt 对照。

已经装了旧版本的，打开软件按提示“立即更新”即可，项目、设置和密钥都保留。

## 第一次使用

1. 打开软件，进入“设置”，填写 BidCore 密钥（在官网[价格页](https://bidcore.cn/pricing.html)购买积分）。设置里可以查询剩余积分。
2. 建好公司档案：公司全称、统一社会信用代码、法定代表人、资质证书等，写作和审查都会用到。
3. 写新标书：点“开始新投标”，导入招标文件，确认要求和大纲后生成正文；在画布的文档卡里选中段落让 AI 修改，先看标出的改动再替换。
4. 审写好的标书：点“标书审查”，选投标文件和招标文件（Word、PDF、旧版 .doc 都可以）。除了问题清单，还能看评分对照（每个评分要素有没有回应）和承诺清单（带数字的承诺，可导出确认单）。审完可以导出批注版 Word、审查意见单，或者导入画布逐条修改，改完按原文件格式导出。
5. 导出 Word / PDF 后，逐项核对资质、报价、附件、签章和版式，再正式提交。

## 升级与备份

升级前备份项目和关联的原文件。不要把整个数据目录公开上传。
