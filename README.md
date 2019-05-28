# devops
DevOps 演示项目

1.使用Git Bash生成证书

	$ssh-keygen.exe -t rsa

切换到用户家目录的.ssh目录下
	$cd ~/.ssh

列出目录下所有文件
	$ ls
	id_rsa  id_rsa.pub

查看文件内容
	$ cat id_rsa.pub

2.把公钥id_rsa.pub的内容放置到github上。

打开Github。点击用户图像--Settings--SSH and GPG keys--New SSH

3.克隆仓库代码

	git clone git@github.com:su-cloud/devops.git












