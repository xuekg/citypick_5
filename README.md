###                     citypick_5
基于bootstrap的城市选择控件，支持省市区镇村五级显示

首先声明，这是网上找的一个地址控件，原地址是https://www.17sucai.com/pins/16400.html
因为原插件是写死的地址数据，而且只有三级选择，而我这边的项目需求需要做到精确到村，而且是从数据库动态取值的，所以就对插件进行了改造（city_picker.js）.

### 功能改造：
  1：三级选择---->五级选择
  2：写死数据---->动态赋值
  3：添加地址改变监听事件
  
### IMPORTANT:
  很尴尬的是，今天发现了这个控件是可以回显数据的，亏我还用了一天多时间(不咋懂js)来改造这个回显，真是坑死了。
  目前city_picker.js里还有我改造的代码，先留着吧。做个留念吧。
 
 ### 效果图：
![Image text](https://github.com/ni1huo/citypick_5/blob/master/images/picker1.jpg)
![Image text](https://github.com/ni1huo/citypick_5/blob/master/images/picker2.jpg)
 ### Tips：
 如果感兴趣需要下载测试的话，请去上面链接下载文件，本项目文件不够，主要是为了记录改造city_picker.js的过程。
 我就来试试vscode 的 git 扩展
