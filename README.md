# YKMyGithubProject
1.安装git

2.注册github账号

3.创建GitHub仓库

4.创建公匙私匙

	4.1配置git账户

	4.2创建密匙

	4.3将公匙id-rsa.pub中的内容在github中建立密匙


5.将GitHub上建立的项目clone到本地磁盘，比如e盘底下某个目录这步执行有问题，
	可以多试几遍git clone命令，每次试之前要把上次clone的目录删掉

6.以后可以执行同步脚本‘syn.bat’

	6.1以后可以直接在github中下载文件到本地电脑的仓库，每次修改完仓库内容，可以点击bat文件完成同步

7.IDEA中进行git操作
	7.1 在VCS中点击commit进行提交至本地仓库操作，然后使用push更新至GitHub远程仓库。
	不是idea操作的文件，比如这里的本文文件就不会被idea更新到GitHub，仍需要使用‘sys.bat’
	进行同步。