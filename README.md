# 深度学习

# 可视化

小组成员：张泓潋、张瀚予、魏明达、袁弋

<!-- .slide -->

## Content

- Part a      CNN Explainer
- Part b      GAN Lab 

<!-- .slide -->

## Part a      CNN Explainer

<img src="https://i.loli.net/2021/01/04/xp21Sz75EeCXtIB.png" alt="image-20210104202804015.png" style="zoom:100%;" />

使用TensorFlow.js加载了一个10层的预训练模型。

交互方面使用 Svelte 作为框架并使用 D3.js 进行可视化。

<!-- .slide -->

![image-20210104202946681.png](https://i.loli.net/2021/01/04/6CPhjoYFzyW1qvJ.png)

TensorFlow.js是一个开源的基于硬件加速的JavaScript库，用于训练和部署机器学习模型。

<!-- .slide -->

![preview](https://pic1.zhimg.com/v2-0f4a1268171a38fc4b058822dee8ccec_r.jpg)

D3.js是一个JavaScript库，用于根据数据处理文档。

<!-- .slide -->

![image-20210104203733483.png](https://i.loli.net/2021/01/04/Xs9qhRBS4eOWDwL.png)

[CNN Explainer](https://poloclub.github.io/cnn-explainer/)  

<!-- .slide -->

## Part b  GAN Lab

![image-20210104204126701.png](https://i.loli.net/2021/01/04/LiyEVacTHe5USdw.png)

GAN Lab仅在两个维度上展示 GAN 学习点分布的过程。

<!-- .slide -->

<img src="https://i.loli.net/2021/01/04/qnXw3eJbkVhzl74.png" alt="image-20210104204212834.png" style="zoom:150%;" />

网站提供四种数据分布类型，也可以自定义自己的数据分布，可以使用预训练模型。

<!-- .slide -->

<img src="https://i.loli.net/2021/01/05/2sYFwp5qoTSQtyf.png" alt="img" style="zoom:175%;" />

<center>图 1：选择的数据分布被展示在两个位置。</center>

<!-- .slide -->

<img src="https://i.loli.net/2021/01/04/UIDwBAo9L8elmCN.gif" alt="02.gif" style="zoom:125%;" />

随着训练的进行，假样本的位置会不断更新。

<!-- .slide -->

<img src="https://i.loli.net/2021/01/05/D8HkF36MRKUXWlo.png" alt="1536577470885.png" style="zoom:150%;" />

生成器的数据转换可视化为流形，将输入噪声（最左边）转换为假样本（最右边）。

<!-- .slide -->

<img src="https://i.loli.net/2021/01/05/fs95YEacqyokV4S.png" alt="image-20210104204440870.png" style="zoom:125%;" />

鉴别器的性能可以通过2Dheatmap解释。

<!-- .slide -->

- 交互式超参数调整

点击「编辑」图标（<img src="https://i.loli.net/2021/01/05/lQmZx3eRDCOcg12.png" alt="1536577471174.png" style="zoom:150%;" />）来展示独立的超参数，然后在训练期间实时地编辑它们。

- 用户定义数据分布

如果你不喜欢我们提供的数据分布，可以通过点击数据分布列表最后的图标（<img src="https://i.loli.net/2021/01/05/23RPLu7dn94Ce1c.png" alt="1536577471337.png" style="zoom:150%;" />），编辑你想要的数据分布。
<!-- .slide -->

- 慢镜头模式

如果动画太快，可以点击「慢动作」图标（<img src="https://i.loli.net/2021/01/05/DTt7KxnCechi6kf.png" alt="1536577471433.png" style="zoom:150%;" />）进入慢动作模式。

- 手动逐步执行

如果你想进行更多的控制，可以点击该图标（<img src="https://i.loli.net/2021/01/05/bWjs7SOv51zGQYF.png" alt="img" style="zoom:150%;" />）一步步手动训练单个迭代。

[GAN Lab](https://poloclub.github.io/ganlab/) 

<!-- .slide -->

Thank you for your listening!
