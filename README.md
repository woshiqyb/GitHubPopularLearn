# GitHubPopularLearn

#### 永久修改默认端口

1. v0.57中在node_modules/react-native/local-cli/runIOS/runIOS.js 中修改默认的react-native监听端口（8081）
2. 在Xcode中修改Targets->React->Build Phases->start Packager脚本中的端口（是用来指定加载js路径上的端口），与上面保持一致。
3. Xcode全局搜索出来的其他需要修改端口是用来调试和拦截页面用的，也需要修改成上述变更后的端口。
