###  鲜花网


项目说明

此项目采用es6 模块化 进行开发

该网站为鲜花网，
login-details 为详情页
login-flower 为注册页
login-index  为主页
login-page   为登录页
login-shopping 为购物车页面

主页添加轮播效果  第二个展示栏八个列表框采用渲染
登录注册页面 为表单验证页面，先进行js表单验证，再向数据库发送请求，请求为form表单post请求，为保证安全性，密码采用php sha1 进行加密
详情页添加tabs效果 因官网没提供放大镜 未添加 详情页的所有商品数据全部选用渲染，未添加结算功能，点击加入购物车后跳转至 购物车页面 因官网效果 进入购物车页面后显示参数默认为1
购物车页面 保存cookie值 添加 可单独结算，删除 按钮  添加可全选按钮 进行全部结算和删除 实时保存cookie数据  可手动输入或点击按钮输入参数 参数自动计算 点击删除后 所勾选的内容和cookie将删除
input 未采用正则验证  type 为number 导致出现 可输入参数为负数的效果（未解决） 加减按钮正常使用 

网页中 scolltop效果未添加，细节的hover效果未添加 