# JSFE - JSON批量编辑器
## JSON批量编辑器是一个多功能工具，旨在帮助用户高效地对给定文件夹中的JSON文件进行批量修改。
 
* Software description is also available in English. See [JSFE - JSON Bulk Editor EN](https://github.com/telegram-prime/json-files-editor)
* Описание программы так же доступно на русском языке. См. [JSFE - JSON Bulk Editor RUS](https://github.com/telegram-prime/json-files-editor-RU)

## 功能特点：
1. 参数修改
  - 允许用户指定JSON文件中的某个参数（键）进行修改或添加。
  - 用户可以为该参数提供一个值，脚本会更新已有键，或者在键不存在的情况下添加它。
  - 用户可以通过下拉列表选择预定义参数，也可以手动输入自己的参数键。
  - 字符串转换选项：提供了始终将参数值视为字符串的选项，无论其原始数据类型为何。
2. 支持Spintax语法
  - 支持spintax语法（例如：{123|456}），可以在多个可能值中进行随机选择。
  - 自动处理spintax以生成参数的随机值。
3. 基于文件名的动态参数值
  - 用户可以基于JSON文件名来设置参数值。
  - 当文件名具有特定意义时，这种方式非常有用（例如设置“phone”参数以匹配文件名）。
4. 删除参数
  - 提供从所有JSON文件中删除指定参数的选项。
  - 这对于批量删除不必要或过时的键非常有用。
5. 编辑文件专用文件夹
  - 用户可以指定将编辑后的文件保存在专用的输出文件夹中，而不是覆盖原文件。
  - 创建一个带有时间戳的文件夹，用于存储修改后的JSON文件版本，便于与原文件区分。
6. 对应的.session文件处理
  - 脚本自动检查源文件夹中是否存在对应的.session文件（与.json文件具有相同的基础名称）。
  - 如果找到匹配的.session文件，它将与编辑后的.json文件一起复制到目标文件夹中，以保留会话文件的关联。
7. 备份功能
  - 提供修改前创建原文件夹备份的选项。
  - 备份存储在原文件夹旁边的一个带有时间戳的独立文件夹中，确保在需要时可以轻松恢复。
8. GUI状态更新
  - "更新JSON文件"按钮根据脚本状态动态更新其标签和颜色（例如“处理中”、“完成”），以便用户了解正在进行的操作。
  - 提供进度通知和警告，例如达到操作上限或备份成功创建。
9. 错误处理和通知
  - 集成错误处理功能，提供详细消息，通知用户在修改过程中遇到的任何问题。
  - 使用弹出消息通知用户操作状态，如备份、JSON编辑或许可问题。
10. 更新和支持
  - 包括免费更新至后续版本。
  - 团队提供免费在线支持。

## 我们提供24小时免费试用期，用户在此期间可以编辑50个JSON文件，以测试并确认系统的效率，然后再进行购买。
### - 软件界面中有请求演示密钥的按钮。

## 试用期结束后，产品有两种付费订阅方式：
- 许可证：月度订阅 - 可编辑1,000个JSON文件（以先达到的为准）
- 许可证：永久订阅 - 终身访问，编辑JSON文件数量无限制。


## 下载:
 - [始终使用最新版本](https://github.com/telegram-prime/json-files-editor-CN/releases/latest)



## 截图:
![image](https://github.com/user-attachments/assets/90959655-bf73-464c-bc8f-1ccd1e3863f6)



##  联系方式:
- Email:    manager[@]telegramprime.net
- Telegram: [Send message](https://telegramprime.net/telegram-contact)
- TamTam:   [Send message](https://telegramprime.net/tamtam-contact)
- Discord:  [Send message](https://telegramprime.net/discord-contact)
- Element:  [Send message](https://telegramprime.net/element-contact)

* 或通过我们网站上的联系表：
- Wеb: https://telegramprime.net/ - EN Version
- Wеb: https://telegramprime.com/ - RU Version


## 捐赠:
* [给我们买杯咖啡 :)](https://nowpayments.io/donation/telegramprime)
* 谢谢！


