# Machine-Learning-with-Python
Discover the way to learn/use/master the Machine Learning with Python. For data analysis, particularly at regression.

在这里记录学习过程，供回顾知识和交流参考，在记录和讨论的过程中，掌握机器学习。Record helps. And train our mind.
## 提出问题
做事都是去解决问题，那么在做事之前明确地提出问题，一定是很有帮助的。**那么我们机器学习是为了什么呢？** 毫无疑问不是为了成为机器学习专家Orz~**我们学习机器学习的目的**是通过使用机器学习算法来帮助我们分析数据，从数据中找到规律，为指导实践找到依据。这样的话，机器学习于我们就是一个工具。如果说我们使用机器学习就像是骑自行车，那么造自行车就交给自行车生产厂商吧，同理彻底掌握机器学习的底层数学逻辑和原理，这样的要求就交给机器学习专家吧。当然这是在初步学习时说的话哈，如果后面需要掌握一些底层的知识，那我们就学呗哈哈，又不是有多大仇~

整个过程更强调的是**循序渐进**，在不同的阶段有不同的任务，由易到难，由简入繁，为大于其细，为难于其易。**我相信正确的方法和持续的学习，我们都可以学习和掌握机器学习**。So relax, and enjoy it:)

## 学习路径
在这里我推荐一本入门书 **《机器学习Python实践》作者：魏贞原-电子工业出版社** 。本书主导的思想是“像工程师一样使用机器学习，而不是像机器学习专家一样使用机器学习。”主要介绍机器学习在实践中的应用，介绍python的生态环境，使用机器学习算法来解决工程实践中的问题，而不是介绍算法本身。我之前的学习存在一个误区就是常常在外围绕圈子，不得要领。长期学下去会不知道自己在做什么？没有一个明确清晰的学习路径，经常是“中道崩殂”...为了给学习一个良好的反馈，增加学习的乐趣，我建议先从例子着手，知道机器学习模型是如何搭建的，先看个大概知其模样，继而逐步地深入进行研究。此思维逻辑也正合这本 **《机器学习Python实践》** 的逻辑原理。
### what is Machine Learning?
机器学习是一门多领域的交叉学科，涉及概率论、统计学、线性代数、算法等多门学科。..._逐渐天书_... 简单来说，它专门研究计算机如何模拟和学习给定的数据，以获取数据深层包含的信息。这里需要用到一个python机器学习库scikit—learn，这个库里拥有丰富的机器学习函数，足够我们进行机器学习模型的搭建。
### 算法和模型？
算法是一种算数方法，像是我们之前学习过的二分法就是一种算法；而模型是包含算法的，直接可以用来分析数据。

机器学习模型是一个由机器学习算法自动编写、或创建、或学习的程序，用来解决我们的问题。作为开发人员，我们对人工智能意义上的机器学习算法的“学习”不太感兴趣。我们并不关心模拟学习过程。有些人可能会关心，这很有趣，但这不是我们使用机器学习算法的原因。相反，我们更看重的是机器学习算法提供的自动编程能力更感兴趣。我们希望能够有效地创建一个有效的模型，并将其融入到我们的软件项目中。**机器学习算法执行自动编程，而机器学习模型是为我们创建的程序。** 可以[点击这里查看更多](https://zhuanlan.zhihu.com/p/162086776)

说的有不够严谨的地方，还需在后续的学习中不断更正。

### 学习环境
工欲善其事，必先利其器。想要利用python进行数据分析，首先要搭建一个数据分析的工作台，在这个工作台上需要包含python、sickit-learn库、pandas（相当于二维表）。对于数据分析领域，事实上Anaconda 和 Jupyter（包括Jupyter Notebook和JupyterLab，其中JupyterLab是从Notebook发展而来的）已成为数据分析的标准环境。简单来说，Anaconda是包管理器和环境管理器，Jupyter可以将数据分析的代码、图像和文档全部组合到一个web文档中。关于Anaconda的介绍和安装[可点击这里](https://www.zhihu.com/question/58033789/answer/254673663).Jupyter notebook是一个网页式的文件，可以在浏览器中进行代码的调试，安装了anaconda之后，就可以使用。
#### jupyter notebook的目录设置
设置目录，[可以参看此文章](https://zhuanlan.zhihu.com/p/44357064),写的挺清晰的。

### python
打开Jupyter notebook，可以在里面输入python的语法进行学习。基础的语法熟悉就可以，在写代码的时候不懂的语法，再去查找，这样磕磕绊绊地走起来，越走越熟练。
#### pandas
使用python了，这时可以简单了解一下pandas，它含有使数据清洗和分析工作变得更快更简单的数据结构和操作工具。
##### 数据结构
一个是series，类似于一维数组对象，一个是DataFrame，相当于二维表，excel那种的格式。
##### 操作工具
最方便的是可以直接导入我们准备好的数据，比如excel表格，或者csv数据格式。导入进创建的文件之后，就以dataframe格式供我们调用，下一步就是构建模型的一系列操作，在构建模型的过程中会用到适用于解决不同问题的算法。

是不是跃跃欲试，那就开始第一个机器学习算法吧！
## 第一个机器学习算法
