先介绍整体的操作，1下载git，2安装git，3制定git的用户名和邮箱，同时将git和github进行SSH关联，4选一个文件夹进行git init，5git clone,6愉快地使用吧，不懂再进行查找。

git安装到官网，[观看教程](https://www.cnblogs.com/xueweisuoyong/p/11914045.html),由于版本差异在安装过程中存在一些差异，不影响操作。

建议先在github上搭建自己的仓库repository，之后在通过git来克隆到自己的电脑上。
+ 那么git是如何关联自己的github呢？有两种方法，一种是HTTPS传输，缺点每次输入密码，麻烦；
+ 另一种是通过SSH密钥对的方式，[具体操作点我](https://blog.csdn.net/qq_36667170/article/details/79094257).

添加了SSH密钥之后，就可以通过ssh的方法来进行文件的传输。
* 在github上点击自己的repo，项目名右侧有一个绿色的标识CODE，点击会出现不同的下载方法，我们选择SSH，可以进行复制git@github.com:QuietZhangn/Machine Learning with Python.
* 找一个英文路径的文件夹，右键打开git bash面板，git clone git@github.com:QuietZhangn/Machine Learning with Python，
就可以成功的将github上建立好的项目clone到自己的电脑上了。为之后在电脑端上传做好了准备。

啊啊啊啊啊我疯了，xdm 在github上建立文件时，**不要加标点符号！！**。我就是因为加了一个问号，结果一直不能成功clone到自己的本地仓库。否则就会一直出现下面这个错误。

'''
error: invalid path 'Machine Learning/what is machine learning?.md'
fatal: unable to checkout working tree
warning: Clone succeeded, but checkout failed.
You can inspect what was checked out with 'git status'
and retry with 'git restore --source=HEAD :/'
'''
