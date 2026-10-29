# NetProxy overlay（不进 main）

这个分支只放自用覆盖包，**不要 merge 进 main**。

跟上游：只同步 `main`（`git fetch upstream && git merge upstream/main`）。
手机：先刷官方 NetProxy zip（保留数据），再刷本包。

内容：自签 APK 8.8.8 + 配对 DEX + `bin/netproxyctl`（链式 UI + AnyTLS Reality 导入）。不改 `sing-box`。
安装后会在几秒内删掉 Overlay 目录，KernelSU 列表里不应留下 Overlay 项。不要禁用原来的 NetProxy。
