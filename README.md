# -
导出小米浏览器书签，生成可以导入chrome的文件

注意：实现导出功能需要下载auto.js软件和手机root功能(如果安卓7.0以上，可以不用root，将所有Swipe替换为swipe即可)

步骤：
1.下载auto.js，部署好权限（就是无障碍功能和给root）。

注意，安卓7.0以上可以不用root，但请自行将js代码里所有Swipe替换为swipe（不过这个我没有测试过）

2.在auto.js软件里添加 "导出小米浏览器书签.js": 首页按右下角+号 =>导入=>选择你放到手机里的"导出小米浏览器书签.js"

auto.js有官网，可以简单学习下怎么用

3.打开手机浏览器的书签界面用autojs的悬浮窗运行，或者在autojs里按下运行后在9秒内手动打开浏览器并打开到书签界面（程序里设置了9秒后运行）

4.在 "/storage/emulated/0/aaZLY/小米浏览器书签导出.txt"  找到生成的txt文件，（传到电脑上），将后缀直接改为.html，导入chrome
