# CDN
实际上是资源仓库,当前用的是`jsDelivr CDN`。

## 更新

```bash
git tag <vx.y.z>
git push --tags
```

推送`tag`时触发`release action`。

## FAQ
会出现`jedelivr CDN`资源无法访问的情况，改用`fastly.jsdelivr.net`或`gcore.jsdelivr.net`访问。
