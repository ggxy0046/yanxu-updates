# 砚序更新分发

本仓库用于发布 Windows Illustrator 砚序测试面板的安装包、签名更新清单和版本说明。

安装包请从 [Releases](https://github.com/ggxy0046/yanxu-updates/releases) 的对应版本附件获取。请下载 `Yanxu-版本号-OneClick-Windows.zip`，完整解压后按照包内说明安装；GitHub 自动生成的 Source code 压缩包不是安装包。

安装前请保存工作并退出 Illustrator。更新安装会核对安装包与签名，并保留旧测试面板备份。真实宿主兼容性与验收边界以对应版本说明为准。

首次安装若没有 Adobe 验签工具缓存，仍需访问 Adobe 官方 GitHub；腾讯云只提供砚序 ZIP、未镜像 Adobe 工具，已有缓存会经固定 SHA-256 和 Adobe Authenticode 校验后复用，日常双源更新无需每次重新下载工具。

开发源码仓库保持私有，本仓库不保存开发历史、签名私钥或客户工程。安装包包含运行所需的脚本，这些脚本可被解包读取；公开仓库及其安装附件不设访问限制。
