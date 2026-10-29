# NetProxy overlay（不进 main）

这个分支只放自用覆盖包，**不要 merge 进 main**。

跟上游：只同步 `main`（`git fetch upstream && git merge upstream/main`）。
手机：先刷官方 NetProxy zip（保留数据），再刷本包。

内容：自签 APK 8.8.8 + 配对 DEX + `bin/netproxyctl`（链式 UI + AnyTLS Reality 导入）。不改 `sing-box`。
模块 id 是 `netproxy-overlay`，可删除；不要禁用原来的 NetProxy。
