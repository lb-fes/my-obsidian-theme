官方教程：https://docs.obsidian.md/Themes/App+themes/Build+a+theme

主题文件名必须和manifest.json中的 name 一样，否则 obsidian 不能正确加载该主题。

修改 manifest.json 代码后必须重启 obsidian 才能应用新的主题。

编译

```bash
sass theme.scss E:\backup\文档\.obsidian\themes\my-theme\theme.css --no-source-map
```

编译并监视

```bash
sass --watch theme.scss E:\backup\文档\.obsidian\themes\my-theme\theme.css --no-source-map
```

压缩代码(勿用，obsidian 对压缩代码的兼容性不好？)：

```bash
sass theme.scss E:\backup\文档\.obsidian\themes\my-theme\theme.css --style=compressed --no-source-map
```

