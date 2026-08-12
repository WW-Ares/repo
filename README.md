# WW-Ares 个人 Sileo 源

这是个人使用的 Sileo 软件源，用于备份自己需要保存的其他源 deb 包，以及自己修改或制作的 deb 包。

在 Sileo 中添加以下地址：

```text
https://ww-ares.github.io/repo/
```

当前包含：

- Axon 简体中文包（roothide）
- BlurryBadges 简体中文包（roothide）
- CocoaTop 简体中文包（roothide）

## 维护方式

- 所有可安装的 deb 包放在 `debs/` 目录，并使用 ASCII 文件名，避免 URL 编码兼容问题。
- 每次新增、更新或删除 deb 后，需要重新生成根目录的 `Packages`、`Packages.gz` 和 `Release`。
- `Packages` 与 `Packages.gz` 是 Sileo 用来读取软件包信息的索引文件。
