# <p align=center>`Methods` </p>

> 本章节既可以叫 Methods（加不加s都行），或者叫 Our Approach



## 第一段大致介绍一下结构

> 多强调你的方法的特点，与众不同之处，让审稿人一定能看到。



| 第一句：预热一下                                             |
| :----------------------------------------------------------- |
| **We now present our** xx **framework for** xx.              |
| **In this section**, **we provide a more detailed description of the presented approach**, xxx. |
| Given xx, **we aim to achieve** xxx (你文章是干什么的)       |
| Our goal is to ...                                           |
| This section introduces the overall working mechanism and specific technical implementations of the proposed xx. |



| 如果你的方法由多个部分构成的话                               |
| ------------------------------------------------------------ |
| **Our xx process is split into two parts**: **a** xx **branch**, **which** xxx, **and a** xx **branch that** xxx. |



| 章节结构安排                                                 |
| :----------------------------------------------------------- |
| **In the following, we first introduce** xx **in Sec. 3.1**, **before proceeding to** xx **in Sec 3.2**. |
| **The organization of this section is as follows**: We introduce xx **in Sec. 3.1**, including xx. **In Sec. 3.2**, we first describe xx. Then we present xx. |
| To begin with, we review the basic idea and pipeline of xxx. |
| To facilitate understanding, we begin with an overview of our framework xx |

> 插补一些有用的连词：Thereafter




| 最后一句：介绍核心的流程图                                   |
| :----------------------------------------------------------- |
| Fig. x **gives an overview of the training pipeline**.       |
| **Our model is illustrated in** Fig. x.                      |
| In essence, our method extends, ..., as demonstrated in Fig. 1 |
| Fig.1 depicts xx                                             |
| Fig.1 shows the framework of the proposed method.            |
| schematic illustrating                                       |



## 开始写方法

> 比较具体，这里就不再过多介绍。

### Training Details

| 训练细节                                                     |
| :----------------------------------------------------------- |
| We inherit the training procedure from xx with minimal changes. |
| The optimization is performed by Adam with learning rate of 0.002 and betas of 0 and 0.99 |
| Further details can be found in the source code.             |



## 其他

| 有的时候会为了简单起见，省略一些符号标记 |
| :--- |
| for the sake of simplicity, we |
| For ease of notation, we will use latent codes c to denote the concatenation of all latent variables ci. |



| 对公式的描述                                                 |
| :----------------------------------------------------------- |
| where λ is a positive constant trading off the importance of the first and second terms of the loss |



| 一些不错的说辞                                               |
| :----------------------------------------------------------- |
| we want to avoid investing effort into a component that is not a part of the actual solution. |





## 数学公式相关

just show many examples


$$
f_{j}^{\prime}=\left[\nabla_{\mathbf{x}} f_{j}\left(\mathbf{x}_{0}\right)\right]^{t} \mathbf{d}
$$

where $\nabla_{\mathbf{x}}$ is the symbol for the gradient w.r.t. $\mathbf{x}$ and the superscript $^{t}$ stands for transposition. One seeks for a vector $\mathbf{d}$ such that the scalar product of any objective gradient $\nabla_{x} f_{j}\left(\mathbf{x}_{0}\right)$ with the vector d remains strictly positive $f_{j}^{\prime} > 0$



we use xx to denote xx
