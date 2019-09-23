 **1.安装虚拟环境**
 
 1.1 虚拟环境用于隔离不同项目使用版本不同的情况，项目之前互相隔离
 
 1.2 安装过程：
  
  1. pip install virtualenv
  
  2. pip 镜像加速  pip install -i https://pypi.douban.com/simple/  django  
     卸载 pip uninstall django 
     
  3. 新建虚拟环境 virtualenv name  会在当前目录下创建名字为 name 的虚拟环境
  
  4. windows 进入script目录下 source activate  mac 进入 bin目录下 source activate 
  
  5. 关闭虚拟环境 deactivate
  
  6. 为了保持您的环境的一致性，可以将当前环境安装的包和版本，记录在一个文件下。即“冷冻住（freeze）”环境包当前的状态，请运行：
$ pip freeze > requirements.txt

当重新创建这样的环境时，会非常容易，使用
$ pip install -r requirements.txt

这能帮助确保安装、部署和开发者 
 