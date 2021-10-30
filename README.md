# ForgeModExample
声明：此模板是我自己为在 win10 的 vscode 上开发Forge mod而制作的
## 使用步骤：
拷贝此代码库的所有文件到你喜欢的文件夹里\
然后用 vscode 打开此模板文件夹，vscode 在打开文件夹时会自动构建项目\
之后在终端里输入：.\gradlew genVSCodeRuns 来获取运行游戏的资源文件\
最后修改模板里的配置信息(build.gradle)，具体如下：
* 修改 archivesBaseName 为你的模组名称
* 修改 group 的值为你的包路径，具体按模板上的默认英文提示修改
* 修改 version 的值为你自己定义的当前模组版本号
* 把文档下面除注释外的 examplemod 字段都替换为你的 modid 即 archivesBaseName 的值

修改完build.gradle之后就可以正常启动游戏了\
想要自己的模组显示在mods里面，还需要按照forge官方文档的要求创建mods.toml文件\
forge官方关于mods.toml的说明：https://mcforge.readthedocs.io/en/1.16.x/gettingstarted/structuring/
* PS：如果你还没有标记mod的开始入口(使用@MOD标记你的模组运行入口，标记在类上)则创建好mods.toml文件之后进入游戏会报错

