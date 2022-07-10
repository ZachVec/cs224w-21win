# CS224W: Machine Learning with Graphs.

本仓库是本人根据斯坦福 CS224W 2021 Winter 的 Colab 整理出来的资料，关于图神经网络的构建及训练。课程的官方主页[在此](http://snap.stanford.edu/class/cs224w-2020/)。

本项目对该课程的 Colab 进行了本地化，有两层含义：

1. 首先是将实验从线上搬到线下。因为一些众所周知的原因，原来的线上实验可能不是很好用。
2. 其次是将 Colab 整理成为中文版。希望能帮助到更多入门图神经网络的同学。

## 配置

> 本人的实验在 Ubuntu 20.04 LTS 上进行，其它系统不做保证。

要下载本仓库进行学习，请在终端依次输入如下三行指令：

```bash
git clone git@github.com:ZachVec/cs224w-21win.git ~/cs224w
wget -P ~/cs224w https://github.com/ZachVec/cs224w-21win/releases/download/%E6%95%B0%E6%8D%AE%E9%9B%86/dataset.zip
unzip ~/cs224w/dataset.zip -d ~/cs224w
```

如果不熟悉终端操作也可以从 GitHub 上[直接下载](https://github.com/ZachVec/cs224w-21win/archive/refs/heads/master.zip)仓库解压，然后[下载数据集](https://github.com/ZachVec/cs224w-21win/releases/download/%E6%95%B0%E6%8D%AE%E9%9B%86/dataset.zip)并自行将数据集解压至仓库根目录下。

最后，在实验开始之前需要自己配置一下环境。本系列中，需要用到的库有 [PyTorch](https://pytorch.org/get-started/locally/)、[PyG](https://pytorch-geometric.readthedocs.io/en/latest/notes/installation.html)、[OGB](https://ogb.stanford.edu/docs/home/)、[NetworkX](https://anaconda.org/anaconda/networkx) 以及 [DeepSNAP](https://snap.stanford.edu/deepsnap/notes/installation.html)。

