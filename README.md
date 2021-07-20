# 1_springmvc
Study sources

配置出现问题总结
1.ideal出现svn配置问题：he path to the Subversion executable is probably wrong  
解决方法：**a.第一种情况**：idea没有安装svn。
择file→settings→plugins，在右侧框中搜索"SVN"(有的是subversion)，选中搜索出来的东西，然后点击下面的install。
b.**第二种情况**这种情况是因为idea需要使用svn命令行客户端，但是在本地没有检索到相关的软件。
首先从官网下载：https://www.visualsvn.com/downloads/  解压后找到：svn.exe程序的路径
打开idea，file→settings，搜索"svn"。在红框内选中解压出来的bin文件夹中的svn.exe，然后重新打开svn即可
