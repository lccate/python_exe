# python_exe
将python文件打包成exe 
前提：安装了anaconda
1.直接打开cmd，安装pyinstaller  
pip install pyinstaller  
2.运行命令  
pyinstaller -F hello.py  
打包完后会有dist和build两个文件夹，dist里面有一个exe文件  
3.更改exe文件的图标  
pyinstaller -F --icon=图片.ico 程序.py  
ico图片格式在线转换：https://tool.lu/favicon/  

此方法仅限一个py文件的打包，如果有多个文件的话，还需要再考虑其他的问题，待续先  
