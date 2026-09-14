## 项目的由来
虽然国内教育网站已提供免费资源，但大多数普通人获取信息的途径依然受限。有些人利用这一点，在某站上销售这些带有私人水印的资源。为了应对这种情况，我计划将这些资源集中并开源，以促进义务教育的普及和消除地区间的教育贫困。

还有一个最重要的原因是，希望海外华人能够让自己的孩子继续了解国内教育。

## 学习数学
希望未来出现更多不是为了考学而读书的人。

### 大学数学
- [高等数学](https://github.com/TapXWorld/ChinaTextbook/tree/master/%E5%A4%A7%E5%AD%A6/%E9%AB%98%E7%AD%89%E6%95%B0%E5%AD%A6/%E5%90%8C%E6%B5%8E%E5%A4%A7%E5%AD%A6%E9%AB%98%E7%AD%89%E6%95%B0%E5%AD%A6%E7%AC%AC%E4%B8%83%E7%89%88)
- [线性代数](https://github.com/TapXWorld/ChinaTextbook/tree/master/%E5%A4%A7%E5%AD%A6/%E7%BA%BF%E6%80%A7%E4%BB%A3%E6%95%B0)
- [离散数学](https://github.com/TapXWorld/ChinaTextbook/tree/master/%E5%A4%A7%E5%AD%A6/%E7%A6%BB%E6%95%A3%E6%95%B0%E5%AD%A6)
- [概率论](https://github.com/TapXWorld/ChinaTextbook/tree/master/%E5%A4%A7%E5%AD%A6/%E6%A6%82%E7%8E%87%E8%AE%BA)

- [更多数学资料-(大学数学网)](http://www.dxsx.net/index.php)

## 问题：如何合并被拆分的文件？

由于 GitHub 对单个文件的上传有最大限制，超过 100MB 的文件会被拒绝上传，超过 50MB 的文件上传时会收到警告。因此，文件大小超过 50MB 的文件会被拆分成每个 35MB 的多个文件。

### 示例
文件被拆分的示例：
- 义务教育教科书 · 数学一年级上册.pdf.1
- 义务教育教科书 · 数学一年级上册.pdf.2

### 解决办法
要合并这些被拆分的文件，您只需执行以下步骤(其他操作系统同理)：
1. 将合并程序 `mergePDFs-windows-amd64.exe` 下载到包含 PDF 文件的文件夹中。
2. 确保 `mergePDFs-windows-amd64.exe` 和被拆分的 PDF 文件在同一目录下。
3. 双击 `mergePDFs-windows-amd64.exe` 程序即可自动完成文件合并。

### 下载方式
您可以通过以下链接，下载文件合并程序：

[下载文件合并程序](https://github.com/TapXWorld/ChinaTextbook-tools/releases)

### 文件和程序示例
- mergePDFs-windows-amd64.exe
- 义务教育教科书 · 数学一年级上册.pdf.1
- 义务教育教科书 · 数学一年级上册.pdf.2

## 重新下载
- 如果您位于内地，并且网络不错，想重新下载，您可以使用 [tchMaterial-parser](https://github.com/happycola233/tchMaterial-parser) 项目（鼓励开源），进行重新下载。
- 如果您位于国外，和内地网络通信速度较慢，建议使用本存储库进行签出。

## 教材捐献
如果这个项目帮助您免费获取教育资源，请考虑支持我们推广开放教育的努力！您的捐献将帮助我们维护和扩展这个资源库。

加入我们的 Telegram 社区，获取最新动态并分享您的想法：https://t.me/+1V6WjEq8WEM4MDM1
