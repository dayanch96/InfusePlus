# 第一步：准备工作（仅限第一次）

Fork 仓库：登录你的 GitHub 账号，访问 dayanch96/InfusePlus，点击页面右上角的 Fork 按钮，将代码克隆到你自己的账号下。

开启权限：

在你自己的这个 Fork 仓库中，点击顶部的 Settings（设置）选项卡。

在左侧栏找到 Actions -> General。

在 "Workflow permissions" 部分，确保选中 Read and write permissions，然后点击 Save（保存）。

# 第二步：获取解密后的 Infuse IPA

由于 GitHub Actions 需要对原始 App 进行注入，你需要准备一个**砸壳版（解密后）**的 Infuse .ipa 文件。
[https://armconverter.com/decryptedappstore/us](https://armconverter.com/decryptedappstore/us/infuse)
你需要将这个 .ipa 文件上传到云端(storage.soloin.cc.cd)。
关键点：你必须获得该文件的直链（Direct Download Link）。如果是网页跳转链接，构建会失败。

# 第三步：运行构建流程

进入 Actions：在你的 Fork 仓库页面，点击顶部的 Actions 选项卡。

选择 Workflow：在左侧列表找到名为 Create Infuse Plus app 的工作流。

运行工作流：

点击右侧的 Run workflow 下拉按钮。

在 IPA URL 框中，粘贴你刚才准备好的解密版 Infuse IPA 的下载直链。

Tweak version：默认会填入最新版本，一般不需要修改。

Bundle ID / Display Name：如果你想修改 App 的包名或显示名称（例如改成 "Infuse Pro"），可以在这里修改。

点击绿色的 Run workflow 按钮。

第四步：下载生成的 IPA

等待大约 5-10 分钟，直到工作流运行完成（图标变绿）。

构建完成后，点击顶部的 Code 选项卡回到主页。

在页面右侧找到 Releases 部分。

你会看到一个新生成的 Release（通常标记为 "latest"），点击进去即可下载构建好的 InfusePlus.ipa。
