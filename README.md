# Java SE API 中文文档（离线版）

![Java Logo](https://www.oracle.com/img/java-logo.png)  
*(建议替换成你自己仓库里的截图或更合适的图片)*

## 项目简介

这是一个为 Java 开发者准备的 **Java SE 标准库 API 文档中文参考**（离线友好版）。

主要特点：

- 完整覆盖 Java SE 核心类库（java.lang、java.util、java.io、java.time、java.util.concurrent 等）
- 提供大部分常用类的中文说明、方法翻译、示例代码
- 支持离线浏览（单文件 / 压缩包 / 静态网页三种形式可选）
- 适合以下人群快速查阅：
  - 初学 Java 的同学
  - 英文阅读不流畅的开发者
  - 网络不稳定或需要离线工作的场景
  - 想快速回顾某个类/方法签名的工程师

当前版本对应：**Java SE 17 LTS**（或 21 / 11 / 8，请根据实际情况修改）

## 文档预览

<!-- 如果你生成了静态网页，可以放截图 -->

![API 文档截图示例](docs/screenshot-01.png)  
*(把实际截图上传到仓库的 docs/ 或 images/ 文件夹)*

## 如何使用

### 方式一：直接在线浏览（推荐）

如果你部署到了 GitHub Pages，可直接访问：

🔗 https://你的用户名.github.io/你的仓库名/

### 方式二：下载离线单文件版

- [JavaSE-API-中文参考.md](JavaSE-API-中文参考.md) ← 点击下载（Markdown 版，体积小）
- [JavaSE-API-完整版.html](dist/JavaSE-API.html) ← 点击下载（单文件网页版）

### 方式三：下载完整压缩包（包含搜索功能）

- [JavaSE-API-Doc-offline-v1.0.zip](dist/JavaSE-API-Doc-offline-v1.0.zip)  
  解压后用浏览器打开 index.html 即可使用（支持 Ctrl+F 全文搜索）

## 文档内容范围（示例）

- java.lang：Object、String、Math、System、Thread、Enum...
- java.util：Collection、List、Set、Map、Queue、Optional、Stream...
- java.time：LocalDate、LocalDateTime、Instant、Duration、Period...
- java.io / java.nio：文件读写、Path、Files、Buffer...
- java.util.concurrent：线程池、锁、原子类、CompletableFuture...
- java.net / java.net.http：URL、HttpClient...
- 常用注解、函数式接口、模块系统（Java 9+）

（实际包含内容请根据你上传的文件修改这一段）

## 更新日志

- **2025-12**　初版发布，覆盖 Java 17 常用 API
- **2026-01**　补充 java.time 包、CompletableFuture 详细示例
- **待办**：增加 Java 21 虚拟线程相关说明

## 参与贡献

欢迎提交 PR 来完善翻译、补充示例、修复错误。

特别欢迎：

- 更自然的中文表达
- 更准确的技术术语
- 实用的代码示例
- 对 Java 21/23 新特性的补充

## 许可证

本项目文档内容主要基于 [Oracle Java SE Documentation](https://docs.oracle.com/en/java/) 并进行中文翻译与整理。

采用 [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) 协议开源。

## 致谢

- Oracle 官方 Java 文档
- OpenJDK 社区
- 所有参与翻译和校对的小伙伴

有任何问题或建议，欢迎在 [Issues](https://github.com/你的用户名/你的仓库名/issues) 中留言～
