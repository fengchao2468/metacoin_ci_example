# metacoin_ci_example
以太坊DAPP使用Jenkins持续集成范例: https://www.jianshu.com/p/1dfcca96bb65

## 使用步骤

1. 在Jenkins的插件管理中添加`NodeJS`和`AnsiColor`两个插件:

![](https://upload-images.jianshu.io/upload_images/4228468-b2e3d9a180ce79f0.png)

![](https://upload-images.jianshu.io/upload_images/4228468-865550ab16014a4a.png)

2. 在Jenkins设置界面中全局工具设置中添加`Node 8.x`的nodejs安装设置:

![](https://upload-images.jianshu.io/upload_images/4228468-772266a7d13902fd.png)

3. 在Jenkins中新建`pipeline`项目，在pipeline配置中选择scm，地址填入`https://github.com/abcfy2/metacoin_ci_example.git`

![](https://upload-images.jianshu.io/upload_images/4228468-72e962d9ac9b6ed6.png)

![](https://upload-images.jianshu.io/upload_images/4228468-810d9da2234613ab.png)

4. 点击立即构建测试结果:

![](https://upload-images.jianshu.io/upload_images/4228468-3c89d25474054a43.png)

![](https://upload-images.jianshu.io/upload_images/4228468-f9fabb5f42fede54.png)
