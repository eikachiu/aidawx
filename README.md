# aidawx
Aida WxApp

### [必读须知] 项目说明事项

本项目为小程序整体项目的其中一部分。

主要目标是完成以下几点
1. 卡片的加载（通过服务器的API）
2. 卡片的交互（用户可以左右滑动操作卡片，用户还可点数字浮点）
3. 按钮的交互（通过条件控制按钮的显示状态）
4. 详情浮层的展示（及交互）

## 1. 卡片的加载

### （1）读取服务器的JSON数据格式到本地JS变量

【产品思考】
考虑分页来提高加载的速度
一次性读取有限条的数据，最初只读取 n 条，当用户交互到第 (n/2 + 1)条时，读取之后的 n 条

### （2）根据变量的对象描画当前卡片以及卡片之后的一张卡片

### （3）参照数据参数在卡片上方绘制数字浮点序号
