## pytorch-learn
PyTorch learning notes of Elliot, including all kinds of demos of PyTorch


### 1. Install libraries

```
conda install numpy
conda install scikit-learn
conda install matplotlib
```

&nbsp;

### 2. Change install source

```
conda config --add channels http://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free
conda config --add channels http://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main
conda config --add channels http://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/pro
conda config --add channels http://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/msys2
conda config --add channels http://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/pytorch
conda config --set show_channel_urls yes
```

&nbsp;

### 3. Fix problem of "Solving environment: failed with initial frozen solve. Retrying with flexible solve"

```
conda config --add channels conda-forge

conda config --set channel_priority flexible
```

### 4. Install pytorch

```
conda install pytorch torchvision torchaudio
```

&nbsp;

### 5. Install torchviz


- 5-1) Download pytorchviz from github

```

https://githubfast.com/szagoruyko/pytorchviz

```

- 5-2) Install from source
```
cd /Users/kg/Downloads
pip3 install torchviz-0.0.2.tar.gz

pip3 install pytorchviz-master.zip

conda install graphviz

```



























