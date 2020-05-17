# 基于Vue + ElementUI的后台管理

## 修改element-ui的打包文件
    node_modules\element-ui\lib\element-ui.common.js    25377行修改源码
    去掉一个判断条件代码: 'includeHalfChecked &&'
