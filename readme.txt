Git is a version control system.
Git is a free software.
1.在项目根目录下打开git bash： git init
2.创建忽略上传文件清单（主要是忽略node modules）: touch .gitignore
编辑器打开生成的 .gitignore 文件，加入:
node_modules
/以及其他你想要忽略的文件或文件夹/
3.把文件添加到仓库：git add .
4.把文件提交到仓库：git commit -m ‘版本001’
5.关联到远程仓库：git remote add origin 你的git仓库ssh地址。
6.把本地库的所有内容推送到远程库上：git push -u origin master
