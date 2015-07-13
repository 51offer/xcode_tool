源自[唐巧的snippets](https://github.com/tangqiaoboy/xcode_tool)
做了一些修改
更符合自身使用

- 原理简单说明
	- 每一个code snippet都是一个文件
	- Xcode的codesnippets都存放于`~/Library/Developer/Xcode/UserData/CodeSnippets`
	- setup_snippets.sh将git仓库中的codesnippets替换原先的Xcode的codesnippets
- Usage:
	
	-  git clone https://github.com/PeterPan507/xcode_tool
	-  cd xcode_tool
	-  ./setup_snippets.sh
