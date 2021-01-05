# 深度学习
# 可视化

小组成员：张泓潋、张瀚予、魏明达、袁弋

<!-- .slide -->

## Content

- Part a      CNN Explainer
- Part b      GAN Lab 

<!-- .slide -->

## Part a      CNN Explainer

<div align=center>![image-20210104202804015.png](https://i.loli.net/2021/01/04/xp21Sz75EeCXtIB.png)</div>

使用TensorFlow.js加载了一个10层的预训练模型

交互方面使用 Svelte 作为框架并使用 D3.js 进行可视化

<!-- .slide -->

<div align=center>![image-20210104202946681.png](https://i.loli.net/2021/01/04/6CPhjoYFzyW1qvJ.png)</div>

TensorFlow.js是一个开源的基于硬件加速的JavaScript库，用于训练和部署机器学习模型。TensorFlow.js 可以为你提供高性能的、易于使用的机器学习构建模块，允许你在浏览器上训练模型，或以推断模式运行预训练的模型。

<!-- .slide -->

<div align=center>![preview](https://pic1.zhimg.com/v2-0f4a1268171a38fc4b058822dee8ccec_r.jpg)</div>

D3 是最流行的可视化库之一，它被很多其他的表格插件所使用。它允许绑定任意数据到DOM，然后将数据驱动转换应用到Document中。你可以使用它用一个数组创建基本的HTML表格，或是利用它的流体过度和交互，用相似的数据创建惊人的SVG条形图。

<!-- .slide -->

<div align=center>![image-20210104203733483.png](https://i.loli.net/2021/01/04/Xs9qhRBS4eOWDwL.png)</div>

[CNN Explainer](https://poloclub.github.io/cnn-explainer/)  

<!-- .slide -->

## Part b  GAN Lab

GAN Lab仅在两个维度上展示 GAN 学习点分布的过程。

<div align=center>![image-20210104204126701.png](https://i.loli.net/2021/01/04/LiyEVacTHe5USdw.png)</div>

<!-- .slide -->

<div align=center>![image-20210104204212834.png](https://i.loli.net/2021/01/04/qnXw3eJbkVhzl74.png)</div>

网站提供四种数据分布类型，也可以自定义自己的数据分布，可以使用预训练模型。

<!-- .slide -->

<div align=center>![1536577470769.png](https://i.loli.net/2021/01/04/Db53gxhYMXVNwrn.png)</div>

「model overview graph」展示了 GAN 的架构、主要组件及其连接方式，另外还可视化了这些组件生成的结果。

 「layered distributions」覆盖了「model overview graph」视图中的组件的可视化，因此你可以在分析模型时更容易地对比组件的输出。

<!-- .slide -->

随着训练的进行，假样本的位置会不断更新。

<div align=center>![02.gif](https://i.loli.net/2021/01/04/UIDwBAo9L8elmCN.gif)</div>



<!-- .slide -->

<div align=center>![1536577470885.png](https://image.jiqizhixin.com/uploads/editor/2968c6a6-fa77-408f-9493-740e94b19d3a/1536577470885.png)</div>

生成器的数据转换可视化为流形，将输入噪声（最左边）转换为假样本（最右边）。

<!-- .slide -->


<div align=center>![1536577471000.png](https://image.jiqizhixin.com/uploads/editor/f0d1ac90-d738-477b-94ae-cc0666935c23/1536577471000.png)</div>
<center>鉴别器的性能可以通过2Dheatmap解释。</center>

<!-- .slide -->

- 交互式超参数调整

点击「编辑」图标（![img](https://image.jiqizhixin.com/uploads/editor/0feb0ce0-fa51-4710-866b-e826202493dc/1536577471174.png)）来展示独立的超参数，然后在训练期间实时地编辑它们。

- 用户定义数据分布

如果你不喜欢我们提供的数据分布，可以通过点击数据分布列表最后的图标（![img](https://image.jiqizhixin.com/uploads/editor/dfeb4467-08c4-4e1e-a205-ffc8a2e330bb/1536577471337.png)），编辑想要的数据分布。
<!-- .slide -->

- 慢镜头模式

如果动画太快，可以点击「慢动作」图标（![img](https://image.jiqizhixin.com/uploads/editor/331fad22-7096-44c2-bbb1-fa12944d5c29/1536577471433.png)）进入慢动作模式。

- 手动逐步执行

如果你想进行更多的控制，可以点击该图标（![img](https://image.jiqizhixin.com/uploads/editor/50713379-dad9-4249-bc36-7fb0e72350ae/1536577471477.png)）一步步手动训练单个迭代。

[GAN Lab](https://poloclub.github.io/ganlab/) 

<!-- .slide -->

Thank you for your listening!
