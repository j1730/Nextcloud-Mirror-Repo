# Nextcloud-Mirror-Repo
![Logo](https://liandanlu-text2img.oss-cn-beijing.aliyuncs.com/dataset/DING_XMD/XMD_RUNTIME/null/89f3a1c4-76c3-4daa-be25-b5de09c3367e?Expires=1738480086&OSSAccessKeyId=LTAI5tPGY1F8tmPStYcTP562&Signature=Q4hki2DsQdNV%2Fj5tWNNiP6O1t7Y%3D&x-oss-process=image%2Fwatermark%2Ctype_d3F5LXplbmhlaQ%2Csize_30%2Ctext_QUnnlJ_miJA%2Ccolor_FFFFFF%2Cshadow_50%2Ct_100%2Cg_sw%2Cx_10%2Cy_10)


[![GitHub Repo Size](https://img.shields.io/github/repo-size/alanwang233233/Nextcloud-Mirror-Repo)](https://github.com/alanwang233233/Nextcloud-Mirror-Repo)
[![GitHub Last Commit](https://img.shields.io/github/last-commit/alanwang233233/Nextcloud-Mirror-Repo)](https://github.com/alanwang233233/Nextcloud-Mirror-Repo/commits/main)

## 简介

这是一个用于解决 Nextcloud 官方源在中国无法使用问题的镜像源仓库。通过此镜像源，用户可以更稳定地获取 Nextcloud 应用商店中的资源和更新。

## 使用方法

### 配置步骤
1. **编辑 `config.php` 文件**:
   - 打开 Nextcloud 的 `config.php` 文件。
   - 在文件的倒数第二行添加以下内容：
     ```php
     'appstoreurl' => 'https://gh.llkk.cc/https://raw.githubusercontent.com/alanwang233233/Nextcloud-Mirror-Repo/refs/heads/main',
     ```
   - 确保添加的代码正确。

2. **保存更改并重启服务器**（如果需要）:
   - 根据你的服务器环境，可能需要重启 Web 服务器以使更改生效。

## 注意事项

- 请定期检查本仓库的更新，确保你使用的是最新的镜像源地址。
- 如果遇到任何问题或有改进建议，请随时提交 Issue 或 Pull Request。

## 贡献

欢迎所有开发者为本项目做出贡献！如果你有任何改进的想法或发现了错误，请不要犹豫，提交 Issue 或 Pull Request 来帮助我们共同维护这个镜像源。

## 许可证

本项目遵循 WTFPL 许可证，详情参见 [LICENSE](LICENSE) 文件。

---

感谢您使用本镜像源！如果有任何疑问或建议，请随时联系维护者或在 Issues 页面提出。

