# B43 待处理 — security

**11** 项第三方样本目录索引。本仓仅保存路径与 upstream URL 索引，**不再使用 Git submodule**。

- 机器可读清单：`docs/submodule-catalog.tsv`
- 按需克隆某一条：`git clone <url> <本地目录>`

以下为历史索引（含原 pin 提交短 SHA，仅供参考；以各 upstream 仓库为准）。

## Submodule 列表

- `AllatoriCrack` — https://github.com/lqs1848/AllatoriCrack.git @ `d2984e6`
- `Android_InlineHook` — https://gitcode.com/zhuotong/Android_InlineHook.git @ `728eaca`
- `CacheEmulatorChecker` — https://github.com/Stevenxin/CacheEmulatorChecker.git @ `3ff4db5`
- `HookProject` — https://github.com/wangluAndroid/HookProject.git @ `545189d`
- `KeyAttestation` — https://github.com/vvb2060/KeyAttestation.git @ `b223a9b`
- `MagiskDetector` — https://github.com/vvb2060/MagiskDetector.git @ `1570969`
- `TestHook` — https://github.com/ZhangSir/TestHook.git @ `3797ea7`
- `android-inline-hook` — https://github.com/bytedance/android-inline-hook.git @ `a81a188`
- `android-key-attestation` — https://github.com/google/android-key-attestation.git @ `20df6d3`
- `cbor-java` — https://github.com/c-rack/cbor-java.git @ `2537033`
- `mobrisk-android-sample` — https://github.com/trustdecision/mobrisk-android-sample.git @ `afcb607`

## 克隆

```bash
git clone https://github.com/zhou256bug/B43-pending-security.git
cd B43-pending-security
# 需要某样本时从下方列表或 docs/submodule-catalog.tsv 取 URL 后自行 git clone
```

