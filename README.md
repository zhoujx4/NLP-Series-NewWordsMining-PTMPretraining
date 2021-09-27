# 项目说明
本项目是新词挖掘+预训练模型继续预训练：  

- 新词挖掘用到了两种方法，分别是
   - 基于频次的新词挖掘
   - 基于自由凝固度以及左右邻字熵的新词挖掘  

详细请看./data/新词挖掘.ipynb  

- 继续预训练模型代码用的是huggingface/transformers库的examples  
地址在https://github.com/huggingface/transformers/tree/master/examples/research_projects/mlm_wwm  
可以直接看链接的介绍，这里只不过修改了部分源码罢了    

> 更具体方法原理和效果，请看我的知乎博客https://zhuanlan.zhihu.com/p/414384344

# 环境
python=3.6   
ltp=4.1.5  
torch=1.7  
transformers=4.5.0  