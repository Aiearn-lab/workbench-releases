# 自媒体工作台 · 发布仓库

这个仓库只放两样东西：

1. 安装包的 Release 资产（二进制不进 Git 历史）。
2. 每个版本的 SHA256、大小、更新说明。

## 当前状态

- V1.7.3 还在内测候选，未发布；Release 为 draft，资产未上传。
- 等 1.7.3 最终包过闸、官网下载直链 200、`latest.json` 六字段一致后，再把 draft 转正式。
- 1.7.2 封包不动。

## 下载入口

正式发布后：

- 官网：https://www.zhiweistudio.com.cn/workbench.html
- 自有下载域：https://dl.zhiweistudio.com.cn/workbench/1.7.3.zip
- GitHub Release：本仓库 Releases

## 校验

每个包同时给 SHA256；下载后先算哈希，再解压。哈希对不上就不要装。