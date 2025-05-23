---
{"dg-publish":true,"permalink":"/sapere-aude/brain-ai/neuron-1-56/","dgPassFrontmatter":true}
---

> [Wild breakthrough on Math after 56 years](https://www.youtube.com/watch?v=vC9nAosXrJw&t=1888s)
> 
> 湛叔：看完一半，真的能感到火花AlphaEvolve的几个工程师发布性对话，Key Words: prompts, prompts, prompts

> [!abstract] AI快读
> **介绍了 Google DeepMind 的新 AI 系统 Alpha Evolve**，它是一个**结合了大型语言模型和进化算法**的编程代理。Alpha Evolve **在科学发现和优化现实世界系统方面取得了显著成就**，最突出的是**在矩阵乘法领域找到了一种比 Strassen 算法更快的算法**，这是自 1969 年以来的首次突破。它也**成功优化了 Google 内部的关键计算基础设施**，例如数据中心的作业调度。文本还**讨论了 Alpha Evolve 的技术架构**，包括其如何通过迭代改进代码、利用自动化评估和进化搜索来增强预训练 LLM 的能力，并探讨了**人类与 AI 协作的未来**以及如何应对诸如停机问题等挑战。


## 关注点

- 4x4 矩阵乘法的突破：为什么将乘法次数从 49 次减少到 48 次是一个重大进展，这与Strassen 算法的历史以及几十年来无法找到更优方法有关。
- Alpha Evolve 的工作原理： 理解 LLM、进化算法和自动化评估器这三个关键组件如何协同工作。LLM 提供创意和想法，评估器提供反馈，进化算法指导搜索和多样性保持。
- 系统的通用性和实际影响： 注意 Alpha Evolve 不仅在理论数学问题上取得成果，还能直接优化 Google 的实际基础设施，这显示了其广泛的应用潜力。
- 人与 AI 的协作模式： AI 被视为一种工具，需要人类的指导和迭代精炼。
- 超越传统 LLM 用法： Alpha Evolve 的方法通过搜索、评估和迭代改进，比简单地一次性查询 LLM 更强大得多。
- 处理离散问题和评估困难： 系统如何通过辅助奖励、课程学习或评估级联来在难以直接优化的离散搜索空间中取得进展。

## 湛叔小灶

> 大家可能注意到 AlphaEvolve 的加法运算要比别的算法多很多次，但是没关系，现代计算机做加法飞快但是乘法比较慢所以

![683021d2e4b071bc0705377a.png|500](/img/user/TARDIS/Assets/2025/683021d2e4b071bc0705377a.png)

![AlphaEvolve_1.png](/img/user/TARDIS/Assets/2025/AlphaEvolve_1.png)
![AlphaEvolve_2.png](/img/user/TARDIS/Assets/2025/AlphaEvolve_2.png)
![AlphaEvolve_3.png](/img/user/TARDIS/Assets/2025/AlphaEvolve_3.png)