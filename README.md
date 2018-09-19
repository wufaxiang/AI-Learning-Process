> This is a repository where you can find things associated with the AutoML, especially NAS(neural architecture search) now. 

> 记录下这段时间入坑学习，看过的东西，一个是整理方便自己随时查看，也希望可以有些帮助，不断更新整理中。。。

## Foundation Studies

- Machine Learning basic
  - Course: [Machine Learning by Andrew Ng](https://www.coursera.org/learn/machine-learning/home/welcome)
  - Course Notes: [Chinese](https://github.com/fengdu78/Coursera-ML-AndrewNg-Notes)
- Deep Learning
  - Course: [deeplearning.ai](https://www.deeplearning.ai/), [fast.ai](http://course.fast.ai/index.html)
  - Course Notes: [Chinese](https://github.com/fengdu78/deeplearning_ai_books), [English](https://github.com/mbadry1/DeepLearning.ai-Summary)
  - Book: [Deep Learning by Ian Goodfellow](https://www.deeplearningbook.org/), [Chinese Version](https://github.com/exacity/deeplearningbook-chinese)
- Python 
  - Course: [University of Michigan, by Charles Severance](https://www.coursera.org/learn/python/home/welcome)
- Framework
    - [Numpy](http://www.numpy.org/)，[Pandas](https://pandas.pydata.org/)，[Sklearn](http://scikit-learn.org/stable/)
    - [Pytorch](https://pytorch.org/): [Pytorch Tutorials](https://pytorch.org/tutorials/)
- Other Books From SaltTiger
  - [SaltTiger](https://salttiger.com/): An amazing website where can find many great programming books. 
  - [Python for Data Analysis, 2nd Edition](https://salttiger.com/python-for-data-analysis-2nd-edition/) : Learn Numpy and Pandas
  - [Deep Learning Cookbook](https://salttiger.com/deep-learning-cookbook/)
  - [Deep Learning with PyTorch](https://salttiger.com/deep-learning-with-pytorch/): Learn Pytorch, but Pytorch Tutorials first.
  - [Machine Learning Algorithms](https://salttiger.com/machine-learning-algorithms/)
  - [Deep Learning for Computer Vision with Python](https://salttiger.com/deep-learning-for-computer-vision-with-python/)
  - More ... Search by youself.
  
  
## Neural Architecture Search

- [Neural Architecture Search: A Survey](https://arxiv.org/abs/1808.05377)
  - Relative blog: [神经网络架构搜索（NAS）综述](https://www.jiqizhixin.com/articles/2018-08-31-4)
- [Neural Architecture Search with Reinforcement Learning](https://arxiv.org/abs/1611.01578)
  - Lecture: [Quoc Le in in UC Berkeley](https://www.youtube.com/watch?v=XDtFXBYpl1w&index=22&list=PLkFD6_40KJIwTmSbCv9OVJB3YaO4sFwkX&t=874s)
  - Slide: [Neural Architecture Search with Reinforcement Learning](http://rll.berkeley.edu/deeprlcoursesp17/docs/quoc_barret.pdf)
- [Efficient Neural Architecture Search via Parameter Sharing](https://arxiv.org/abs/1802.03268)
  - Implement: [tensorflow](https://github.com/melodyguan/enas), [pytorch](https://github.com/carpedm20/ENAS-pytorch)
  - Course: [video](https://www.youtube.com/watch?v=fbCcJaSQPPA), [slide](https://www.slideshare.net/JinwonLee9/efficient-neural-architecture-search-via-parameter-sharing)
  - Relative blog: [Jeff Dean等人提出ENAS：通过参数共享实现高效的神经架构搜索](https://www.jiqizhixin.com/articles/2018-02-14-3)
- [Progressive Neural Architecture Search](https://arxiv.org/abs/1712.00559)
- [DARTS: Differentiable Architecture Search](https://arxiv.org/abs/1806.09055)
  - Implement: [pytorch](https://github.com/quark0/darts)
- [Efficient Neural Architecture Search with Network Morphism](https://arxiv.org/abs/1806.10282)
  - Implement: [keras](https://github.com/jhfjhfj1/autokeras)
  - Website: [autokeara](http://autokeras.com/)

## Auto ML (#TODO)

**Introduce**

- Artical by Rachel Thomas in Fast.ai 
  - [Part I: What do machine learning practitioners actually do?](http://www.fast.ai/2018/07/12/auto-ml-1/)
  - [Part II: An Opinionated Introduction to AutoML and Neural Architecture Search
](http://www.fast.ai/2018/07/16/auto-ml2/)
  - [Google's AutoML: Cutting Through the Hype](http://www.fast.ai/2018/07/23/auto-ml-3/)

**Paper**
  - Auto ML Pipeline
  	- [Autostacker: A Compositional Evolutionary Learning System](https://arxiv.org/abs/1803.00684)
  	-  [Evaluation of a Tree-based Pipeline Optimization Tool for Automating  Data Science](https://arxiv.org/abs/1603.06212)
  - Neural Architecture Search
  	- [Neural Architecture Search with Reinforcement Learning](https://arxiv.org/abs/1611.01578)
  	- [Progressive Neural Architecture Search](https://arxiv.org/abs/1712.00559)
  	- [Efficient Neural Architecture Search via Parameter Sharing](https://arxiv.org/abs/1802.03268)
  	- [Neural Architecture Search: A Survey](https://arxiv.org/abs/1808.05377)
  - GA & EA algorithm 
  	- [CMA-ES for Hyperparameter Optimization of Deep Neural Networks](https://arxiv.org/abs/1604.07269)

**Blog**

- https://juejin.im/post/5ac9e707f265da2378408c89
- [What do machine learning practitioners actually do? · fast.ai](http://www.fast.ai/2018/07/12/auto-ml-1/)
- [AutoML 和神经架构搜索初探](https://www.leiphone.com/news/201808/sYLR0zaLlAv0VpFV.html)
- [Everything you need to know about AutoML and Neural Architecture Search](https://towardsdatascience.com/everything-you-need-to-know-about-automl-and-neural-architecture-search-8db1863682bf)

**Other Resources**

- [PPT: Neural Architecture Search with Reinforcement Learning](http://rll.berkeley.edu/deeprlcoursesp17/docs/quoc_barret.pdf)
- [VIDEO: Neural Architecture Search with Reinforcement, Quoc Le and Barret Zoph](https://www.youtube.com/watch?v=XDtFXBYpl1w&index=22&list=PLkFD6_40KJIwTmSbCv9OVJB3YaO4sFwkX&t=874s)
- [PPT: Efficient Neural Architecture Search via Parameter Sharing](https://www.slideshare.net/JinwonLee9/efficient-neural-architecture-search-via-parameter-sharing)
