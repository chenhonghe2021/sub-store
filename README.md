# sub-store
原始脚本：https://ghfast.top/https://raw.githubusercontent.com/Keywos/rule/main/rename.js

新的重命名脚本：newrename.js
# 如何使用新增功能
要在 Sub-Store 中使用你想要的效果（例如：美国 01-diy-80），你需要在脚本 URL 后面的 # 参数部分进行设置。
参数,值,作用
port,on,启用端口号添加到节点名称。
diy,diy,设置自定义字段为 diy。
diyfgf,-,设置自定义字段和端口之间的分隔符为 -。
fgf,-,设置主要字段（国家/序号）之间的分隔符为 -。

# 示例 URL 参数

如果你希望最终格式为：[国家] [序号]-[自定义内容]-[端口]，并且在 Sub-Store 中使用默认的中文、空格分隔，并加上你的自定义字段和端口，你可以使用以下参数：

#port=on&diy=diy&diyfgf=-

# 示例运行结果：
原始名称	脚本处理后的名称
美国 01 (原始名)	美国 01-diy-80
美国 02 (原始名)	美国 02-diy-2053
美国 03 (原始名)	美国 03-diy-80
