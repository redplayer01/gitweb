# 目录文章说明

这里演示 **一个子目录 = 一篇文章**，图片放在 **该目录下的 `images/`** 里。

## 自动进导航

`articles/.pages` 里用 **`...`** 收录本目录下**全部**子目录中的页面（含 `sample-a/index.md` 等），**不必**每加一篇文章就改 `.pages`。

只需在 `articles/` 下新建 `某目录/index.md`（及图片），保存构建即可。

## 目录约定示例

```text
docs/articles/
  index.md            # 本说明页（在 .pages 里固定为「说明」）
  文章目录甲/
    index.md
    images/
  文章目录乙/
    index.md
```

侧栏分组名由 `articles/.pages` 里的 `title` 控制。
