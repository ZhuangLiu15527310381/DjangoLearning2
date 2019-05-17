# DjangoLearning2
## Introduction
![img](https://github.com/ZhuangLiu15527310381/DjangoLearning2/blob/master/resultGIF/show%20all%20blogs.gif)
### 首页主要是显示所有的blogs数据  根据请求url去查询mysql数据库 显示所有的blogPost类数据 后台做了按照提交顺时间的逆序进行显示 也就是时间比较新的blog会显示比较靠前  同时在首页的最上方是添加blog数据的提交表单
![img](https://github.com/ZhuangLiu15527310381/DjangoLearning2/blob/master/resultGIF/add%20blogs.gif)
### 在首页的最上方是Blog发布的框，当有用户发布blog时，后台会自动请求重新定位到首页是显示所有的blog数据  同时最上面的一条数据是刚发的blog类
![img](https://github.com/ZhuangLiu15527310381/DjangoLearning2/blob/master/resultGIF/update%20blogs.gif)
### 在修改某一条blog信息时，首先是将这条blog信息按照请求url的参数id去查询数据库，并将原始数据显示到Update.html页面上 如果用户修改后表单数据会提交给后台则会将该条blog信息修改并将请求重定向到首页 显示刚修改的信息
![img](https://github.com/ZhuangLiu15527310381/DjangoLearning2/blob/master/resultGIF/delete%20blogs.gif)
### 在用户点击修改的按钮时，后台会根据请求的URL的id参数提交给后台，这样后台会根据blog的id将其从mysql数据库中删除该条数据，并重新定位到首页显示删除数据后的所有数据
![img](https://github.com/ZhuangLiu15527310381/DjangoLearning2/blob/master/resultGIF/wrong%20page.gif)
### 当用户输入的URL在app应用找不到时，则会交给默认的404处理的handler处理显示404自定义的页面
