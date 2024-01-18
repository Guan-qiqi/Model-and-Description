# Model-and-Description
收集模块的结构图以及模块的描述。


| Name | Architecture | Description |
|----|----|----|
| DenseNet | ![image](https://github.com/Guan-qiqi/Model-and-Description/assets/63685364/deb26683-807f-4f4c-8a03-d08b6f833c83) | 由于密集连接方式，DenseNet提升了梯度的反向传播，使得网络更容易训练。由于每层可以直达最后的误差信号，实现了隐式的“deep supervision”；<br>参数更小且计算更高效，这有点违反直觉，由于DenseNet是通过concat特征来实现短路连接，实现了特征重用，并且采用较小的growth rate，每个层所独有的特征图是比较小的； |


| | | |
