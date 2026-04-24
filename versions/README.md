# Proxy UI 版本快照

为了避免在同一个 `proxy.js` 上反复合并冲突，这里把不同阶段的版本拆成独立文件：

- `proxy.v1-original.js`：初始原版（无新版 Dashboard 风格）
- `proxy.v2-themed.js`：仅加入新版主题风格与布局
- `proxy.v3-sidebar-nav.js`：加入侧边栏导航、页面切换与折叠逻辑

使用方式：
1. 按需选择一个版本文件。
2. 将所选文件内容覆盖到线上使用的 `proxy.js`。
3. 其他版本文件保持不动，避免再次在同一文件上产生冲突。
