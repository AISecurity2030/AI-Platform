### 人工智能安全理论及验证平台

1. 无法创建空文件夹，为了保持目录结构完整，各文件夹预留空白__init__.py，后续可删掉
2. 分支解释
	main：主分支，用来版本发布
	develop：日常开发分支，保存开发的最新代码
	feature_name：课题功能负责人（name）上传代码分支
	release：用于发布正式版本之前（即合并到 master 分支之前），需要有的预发布的版本进行测试
