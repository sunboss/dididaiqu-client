# DIDIDAIQU Android 客户端

[dididaiqu.com](https://dididaiqu.com/)（WebGL 粒子/宇宙沉浸式体验站）的 Android WebView 壳应用。

- 包名：`com.sunboss.dididaiqu`
- 版本：1.0 (versionCode 1)
- 单 Activity，全屏 WebView 加载 https://dididaiqu.com/
- JavaScript / DOM Storage 开启，媒体自动播放无需手势，全屏视频支持
- 沉浸式粘性全屏，常亮屏，品牌启动页
- 返回键：WebView 可后退则后退，否则退出

## 构建

push 到 `main` 自动触发 GitHub Actions 云端构建（JDK 17 + Android SDK 34 + Gradle 8.7），
产物 `dididaiqu-client-debug.zip`（含 debug 签名 `app-debug.apk`）在 Actions Artifacts 下载。

- minSdk 26 / compileSdk 34 / targetSdk 34 / AGP 8.5.1
