# d2l-zh注意事项
配置清华pypi镜像时，书中代码应改为：conda config --prepend channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/  
第三步是在文件的cmd中输入，并非Anaconda Prompt，不然会显示找不到文件environment.yml  
记住激活代码：conda activate gluon  
关闭代码：conda deactivate  
书中没有说明需要pip install mxnet，所以在运行jupyter notebook时会显示No module named 'mxnet'  
之后需要在开启conda虚拟机的情况下pip ipython和pip jupyter  
