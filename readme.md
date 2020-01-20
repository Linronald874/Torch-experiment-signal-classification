## 文件列表

different_functions.ipynb: 根据函数表达式，生成人造的信号数据，格式为.npy，数据标签包括在文件名里。

pack_generated_signals.ipynb: 将上一个文件生成的人造信号数据打乱，划分出训练集和测试集，保存为.json文件。

multi_classification.ipynb: 卷积神经网络模型和训练过程。

请按顺序阅读和运行。

## 说明

由于我使用的开发环境是jupyter notebook，它具有交互特性，即不使用print()函数，输入一个变量名，按运行，就可以print出这个变量的值，代码中多处没有使用print()。

如果使用pycharm等不支持交互特性的开发环境，需要修改一下对应的代码。