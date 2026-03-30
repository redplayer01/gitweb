# 常见问题

??? question "新建 Markdown 后要改导航吗？"

    在 `examples/.pages` 里用了 `...` 时，**本目录下**新建的 `.md` 会自动出现在侧栏，一般**不用**改 `mkdocs.yml`。

??? question "想固定某一页排在最前怎么办？"

    在 `examples/.pages` 的 `nav` 里把该页写在 `...` **前面**，例如先写 `- 概述: index.md`，再写 `- ...`。

??? tip "构建失败提示 strict"

    本地执行 `mkdocs build --strict`，按报错修链接或配置；CI 里也是同样命令。
