## GitUserGuide

### 安装完 Git 后的 首次初始配置

	2.1 git config --system core.autocrlf false
	2.2 git config --system core.symlinks false
	2.3 git config --global gui.encoding utf-8
	2.4 git config --global user.name  <姓名全拼>
	2.5 git config --global user.email <Email>
	2.6 git config --global core.editor vim
	2.7 git config --global http.sslVerify false     #禁用SSL证书校对
	
特别注意：2.7项关闭 SSL证书验证 项的配置需要格外谨慎，当与 Github 对接时，切记 **不要** 配置 2.7项！！否则，Git pull/push 都无法与 https 顺利建立直接通信！