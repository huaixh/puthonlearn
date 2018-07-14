### 安装 jupyter notebook
$ jupyter notebook
### Conda 创建一个新环境
1. conda create -n $name python=p_version
1. source activate tensorflow
3. pip install --ignor_installed --upgrade tensorflow

### 添加kernel：
1. 切换python版本 source activate $name
2. 安装 jpykernel： pip install ipykernel
1. 安装 kernel： python -m ipykernel install --name $name

