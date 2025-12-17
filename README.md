# translator
A translation program using Python that calls the DeepSeek or Tencent Hunyuan API.

以调用混元API为例，大致介绍使用环境及使用方法。

1.使用环境

（1）安装有3.0及以上版本Python，建议安装3.13版本。

（2）安装相应依赖，包括python-docx、tencentcloud-sdk-python-hunyuan等。

命令如下：

pip install python-docx -i https://pypi.tuna.tsinghua.edu.cn/simple

pip install tencentcloud-sdk-python-hunyuan -i https://pypi.tuna.tsinghua.edu.cn/simple

（3）于腾讯云（https://cloud.tencent.com/）控制台申请密钥并启用。

设置环境变量，操作过程如下。

♦右击“此电脑”，在弹出的快捷菜单中选择“属性”命令，弹出“设置”窗口，单击“高级系统设置”，弹出“系统属性”对话框。

♦单击“高级”选项卡中的“环境变量”按钮，弹出“环境变量”对话框。

♦在用户变量选项组中单击“新建”按钮，设置TENCENT_SECRET_ID和TENCENT_SECRET_KEY。

2.说明

（1）该程序完全由DeepSeek编制。

（2）支持多种源语言，若不支持，修改代码增加相应的映射即可。

3.使用示例

将待翻译word文件放于任意文件夹中，运行程序后输入文件夹的路径，再选择语言对应的缩写。



