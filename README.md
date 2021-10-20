## Neural Ordinary Differential Equations Network and its Extensions
The original paper [Neural Ordinary Differential Equations](https://arxiv.org/pdf/1806.07366.pdf) that received the Best Paper Award at NeurIPS18 was very succinct and concise. In this Graduation Thesis, we explained step by step to make it easier to understand.

There are 3 remarkable things :

First, how to transfer from [Residual Network](https://arxiv.org/pdf/1512.03385.pdf) to Neural ODE, how Neural ODE's learning process takes place (forward and backward propagation) were clearly explained in Section 3. A classical proof for Adjoint Sensitive method ([Pontryagin et al., 1962]()) was also presented in this section to explain why we have very concise formulas in the original paper.

Second, we proved that Neural ODE cannot represent a class of non-increasing functions in Section 4. Section 4 also included properties, strengths, and weaknesses of Neural ODE.

Last, some limitations of Neural ODE were found from its properties. With an understanding of these limitations, the implemented methods used to improve the performance of Neural ODE were presented in this thesis.
