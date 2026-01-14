# 动手实践大语言模型

<a href="https://www.linkedin.com/in/jalammar/"><img src="https://img.shields.io/badge/Follow%20Jay-blue.svg?logo=linkedin"></a>
<a href="https://www.linkedin.com/in/mgrootendorst/"><img src="https://img.shields.io/badge/Follow%20Maarten-blue.svg?logo=linkedin"></a>
<a href="https://www.deeplearning.ai/short-courses/how-transformer-llms-work/?utm_campaign=handsonllm-launch&utm_medium=partner"><img src="https://img.shields.io/badge/DeepLearning.AI%20Course-NEW!-&labelColor=black&color=red.svg?logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAuMDAwMzY1MjgxIC0wLjAwMDE0MDE0MiAzMy4yOSAzMy4xNSI+Cgk8cGF0aCBkPSJNMTYuNjQzIDMzLjE0NWMtMy4yOTIgMC02LjUxLS45NzItOS4yNDYtMi43OTNhMTYuNTg4IDE2LjU4OCAwIDAxLTYuMTMtNy40MzhBMTYuNTA3IDE2LjUwNyAwIDAxLjMyIDEzLjM0YTE2LjU1IDE2LjU1IDAgMDE0LjU1NS04LjQ4NUExNi42NjUgMTYuNjY1IDAgMDExMy4zOTYuMzE4YTE2LjcxIDE2LjcxIDAgMDE5LjYxNi45NDQgMTYuNjI4IDE2LjYyOCAwIDAxNy40NyA2LjEwMyAxNi41MjIgMTYuNTIyIDAgMDEyLjgwNCA5LjIwN2MwIDQuMzk2LTEuNzUzIDguNjEtNC44NzQgMTEuNzE5YTE2LjY4IDE2LjY4IDAgMDEtMTEuNzY5IDQuODU0em0uMTI1LTYuNjI4YzYuOTA2IDAgMTIuNTE3LTUuNjk4IDEyLjUxNy0xMi43MyAwLTcuMDMtNS42MS0xMi43MjUtMTIuNTE3LTEyLjcyNS02LjkwNiAwLTEyLjUxNyA1LjY5OC0xMi41MTcgMTIuNzI1IDAgNy4wMjcgNS42MTEgMTIuNzMgMTIuNTE3IDEyLjczem0tLjEyNS0yLjkxOGMtNi4yODkgMC0xMS4zODYtNC45MjUtMTEuMzg2LTExLjAwMkM1LjI1NyA2LjUyIDEwLjM2IDEuNTkgMTYuNjQzIDEuNTljNi4yODQgMCAxMS4zODYgNC45MyAxMS4zODYgMTEuMDA3cy01LjA5NyAxMS4wMDItMTEuMzg2IDExLjAwMnptLS4yNDItNC41MDhjNC43NyAwIDguNjMzLTMuNjc5IDguNjMzLTguMjE4IDAtNC41MzgtMy44ODUtOC4yMjEtOC42MzMtOC4yMjEtNC43NDcgMC04LjYzMiAzLjY3OS04LjYzMiA4LjIyMSAwIDQuNTQzIDMuODg1IDguMjE4IDguNjMyIDguMjE4eiIgZmlsbD0iI0ZENEE2MSIvPgo8L3N2Zz4="></a>

欢迎！在这个仓库中，您可以找到由 [Jay Alammar](https://www.linkedin.com/in/jalammar/) 和 [Maarten Grootendorst](https://www.linkedin.com/in/mgrootendorst/) 撰写的《[动手实践大语言模型](https://www.amazon.com/Hands-On-Large-Language-Models-Understanding/dp/1098150961)》一书中所有示例的代码，我们俏皮地将其称为：<br> 

<p align="center"><b><i>"图解大语言模型"</i></b></p>

通过本书的视觉教育性质和**近300个定制图表**，学习当今使用大语言模型所需的实用工具和概念！

<a href="https://www.amazon.com/Hands-Large-Language-Models-Understanding/dp/1098150961"><img src="images/book_cover.png" width="50% " alt="书籍封面"></a>

<br>

本书可在以下平台购买：

* [Amazon](https://www.amazon.com/Hands-Large-Language-Models-Understanding/dp/1098150961)
* [Shroff Publishers (印度)](https://www.shroffpublishers.com/books/computer-science/large-language-models/9789355425522/)
* [O'Reilly](https://www.oreilly.com/library/view/hands-on-large-language/9781098150952/)
* [Kindle](https://www.amazon.com/Hands-Large-Language-Models-Alammar-ebook/dp/B0DGZ46G88/ref=tmm_kin_swatch_0?_encoding=UTF8&qid=&sr=)
* [Barnes and Noble](https://www.barnesandnoble.com/w/hands-on-large-language-models-jay-alammar/1145185960)
* [Goodreads](https://www.goodreads.com/book/show/210408850-hands-on-large-language-models)

## 目录

我们建议通过 Google Colab 运行所有示例，以获得最简单的设置。Google Colab 允许您免费使用具有 16GB VRAM 的 T4 GPU。所有示例主要使用 Google Colab 构建和测试，因此它应该是最稳定的平台。不过，任何其他云提供商也应该可以工作。

| 章节  | 笔记本  |
|---|---|
| 第1章：语言模型简介  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HandsOnLLM/Hands-On-Large-Language-Models/blob/main/chapter01/Chapter%201%20-%20Introduction%20to%20Language%20Models.ipynb)   |
| 第2章：标记和嵌入  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HandsOnLLM/Hands-On-Large-Language-Models/blob/main/chapter02/Chapter%202%20-%20Tokens%20and%20Token%20Embeddings.ipynb)  |
| 第3章：深入了解Transformer大语言模型  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HandsOnLLM/Hands-On-Large-Language-Models/blob/main/chapter03/Chapter%203%20-%20Looking%20Inside%20LLMs.ipynb)  |
| 第4章：文本分类  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HandsOnLLM/Hands-On-Large-Language-Models/blob/main/chapter04/Chapter%204%20-%20Text%20Classification.ipynb)  |
| 第5章：文本聚类和主题建模  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HandsOnLLM/Hands-On-Large-Language-Models/blob/main/chapter05/Chapter%205%20-%20Text%20Clustering%20and%20Topic%20Modeling.ipynb)  |
| 第6章：提示工程  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HandsOnLLM/Hands-On-Large-Language-Models/blob/main/chapter06/Chapter%206%20-%20Prompt%20Engineering.ipynb)  |
| 第7章：高级文本生成技术和工具  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HandsOnLLM/Hands-On-Large-Language-Models/blob/main/chapter07/Chapter%207%20-%20Advanced%20Text%20Generation%20Techniques%20and%20Tools.ipynb)  |
| 第8章：语义搜索和检索增强生成  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HandsOnLLM/Hands-On-Large-Language-Models/blob/main/chapter08/Chapter%208%20-%20Semantic%20Search.ipynb)  |
| 第9章：多模态大语言模型  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HandsOnLLM/Hands-On-Large-Language-Models/blob/main/chapter09/Chapter%209%20-%20Multimodal%20Large%20Language%20Models.ipynb)  |
| 第10章：创建文本嵌入模型  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HandsOnLLM/Hands-On-Large-Language-Models/blob/main/chapter10/Chapter%2010%20-%20Creating%20Text%20Embedding%20Models.ipynb)  |
| 第11章：微调表示模型用于分类  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HandsOnLLM/Hands-On-Large-Language-Models/blob/main/chapter11/Chapter%2011%20-%20Fine-Tuning%20BERT.ipynb)  |
| 第12章：微调生成模型  | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HandsOnLLM/Hands-On-Large-Language-Models/blob/main/chapter12/Chapter%2012%20-%20Fine-tuning%20Generation%20Models.ipynb)  |

> [!TIP]
> 您可以查看 [setup](.setup/) 文件夹获取本地安装所有包的快速入门指南，也可以查看 [conda](.setup/conda/) 文件夹获取完整的环境设置指南，包括 conda 和 PyTorch 的安装。
> 请注意，根据您的操作系统、Python 版本和依赖项，您的结果可能会略有不同。但是，它们应该与书中的示例相似。


## 评价

> "*Jay 和 Maarten 在他们的新书中延续了提供精美插图和深刻见解的传统，解释复杂主题。凭借工作代码、时间线和关键论文参考，他们的书对于任何希望了解大语言模型构建背后主要技术的人来说都是宝贵的资源。*"
>
> **Andrew Ng** - [DeepLearning.AI](https://www.deeplearning.ai/) 的创始人

---

> "*这是一本关于语言模型及其在行业中实际应用的出色指南。它高度可视化地涵盖了语言模型的生成、表示和检索应用，使读者能够快速理解、使用和改进大语言模型。强烈推荐！*"
>
> **Nils Reimers** - Cohere 机器学习总监 | [sentence-transformers](https://github.com/UKPLab/sentence-transformers) 的创建者

---

> "*我想不出现在还有哪本书比这本更重要。在每一页上，我都学到了这个语言模型时代成功的关键知识。*"
>
> **Josh Starmer** - [StatQuest](https://www.youtube.com/channel/UCtYLUTtgS3k1Fg4y5tAhLbw)

---

> "*如果您想全面了解大语言模型的一切，别再找了！在这本精彩的书中，Jay 和 Maarten 将带您从零开始，了解大语言模型的历史和最新进展。通过非常直观的解释、真实生活的例子、清晰的插图和全面的代码实验室，这本书揭开了Transformer模型、分词器、语义搜索、RAG和许多其他尖端技术的复杂性。对于任何对最新AI技术感兴趣的人来说，这是一本必读书！*"
>
> **Luis Serrano, PhD** - [Serrano Academy](https://www.youtube.com/@SerranoAcademy) 的创始人兼首席执行官

---

> "*《动手实践大语言模型》这本书为AI的炒作带来了清晰和实用的例子。它提供了丰富的图表和视觉辅助工具来补充清晰的解释。实例代码将其他书籍中抽象的内容变得具体。这本书从简单的介绍开始，稳步扩大范围。到最后几章，您将能够自信地微调并构建自己的大语言模型。*"
>
> **Leland McInnes** - Tutte 数学与计算研究所研究员 | [UMAP](https://github.com/lmcinnes/umap) 和 [HDBSCAN](https://github.com/scikit-learn-contrib/hdbscan) 的创建者

---

## [附加内容！](bonus/)

我们试图在不过度堆砌的情况下将尽可能多的信息放入书中。然而，即使是一本400页的书，仍有许多内容有待探索！

我们继续创建更多指南来补充本书，并深入探讨新的和[令人兴奋的主题](bonus/)：

| [A Visual Guide to Mamba](https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-mamba-and-state)             |  [A Visual Guide to Quantization](https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-quantization) | [The Illustrated Stable Diffusion](https://jalammar.github.io/illustrated-stable-diffusion/) |
:-------------------------:|:-------------------------:|:-------------------------:
![](images/mamba.png)  |  ![](images/quant.png) |  ![](images/diffusion.png)
**[A Visual Guide to Mixture of Experts](https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-mixture-of-experts)**  | **[A Visual Guide to Reasoning LLMs](https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-reasoning-llms)**  |  **[The Illustrated DeepSeek-R1](https://newsletter.languagemodels.co/p/the-illustrated-deepseek-r1)**
![](images/moe.png)  |  ![](images/reasoning.png) |  ![](images/deepseek.png)

## 引用

如果您认为本书对您的研究有用，请考虑引用：

```
@book{hands-on-llms-book,
  author       = {Jay Alammar and Maarten Grootendorst},
  title        = {Hands-On Large Language Models},
  publisher    = {O'Reilly},
  year         = {2024},
  isbn         = {978-1098150969},
  url          = {https://www.oreilly.com/library/view/hands-on-large-language/9781098150952/},
  github       = {https://github.com/HandsOnLLM/Hands-On-Large-Language-Models}
}
```