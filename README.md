* [Generalization/OOD](#generalizationood)
   * [2021](#2021)
   * [2020](#2020)
   * [OLD but Important](#old-but-important)
   * [综述](#综述)
* [Causality](#causality)
   * [2021](#2021-1)
   * [2020](#2020-1)
   * [综述](#综述-1)

domain generalization， OOD以及causality相关问题的前沿文章阅读清单，链接为笔记，没有链接就是还没看，欢迎大家commit

# Generalization/OOD
## 2021
1. Arxiv: [Towards a Theoretical Framework of Out-of-Distribution Generalization](https://zhuanlan.zhihu.com/p/382608823) （新理论）
2. Arxiv(**Yoshua Bengio**) _Invariance Principle Meets Information Bottleneck for Out-of-Distribution Generalization_
3. Arxiv _Delving Deep into the Generalization of Vision Transformers under Distribution Shifts_ (视觉transformer的泛化性讨论)
4. Arxiv _Training Data Subset Selection for Regression with Controlled Generalization Error_ (从大量训练实例中选择数据子集，并保持可比的泛化性)
5. Arxiv(**MIT**) _Measuring Generalization with Optimal Transport_ (网络复杂度与泛化性的理论研究，)
6. Arxiv(**SJTU**) [OoD-Bench: Benchmarking and Understanding Out-of-Distribution Generalization Datasets and Algorithms](https://view.inews.qq.com/a/20210615A04V1C00?tbkt=B1&uid=) (揭示OOD的评测标准尚不完善并提出评测方案)
7. ICML Oral： [Can Subnetwork Structure be the Key to Out-of-Distribution Generalization?](https://zhuanlan.zhihu.com/p/382608823) （彩票模型寻找模型中泛化能力更强的小模型）
8. ICML Oral：[Domain Generalization using Causal Matching](https://zhuanlan.zhihu.com/p/382608823) (contrastive loss特征对齐+特征不变性约束)
9. ICML Spotlight: [Environment Inference for Invariant Learning](https://zhuanlan.zhihu.com/p/382608823) (没有域标签如何学习域不变性特征？)
10. ICLR Poster: [Understanding the failure modes of out-of-distribution generalization](https://zhuanlan.zhihu.com/p/382608823) （OOD失败的两种原因）
11. ICLR Poster: [An Empirical Study of Invariant Risk Minimization](https://openreview.net/forum?id=jrA5GAccy_)(对IRM的实验性探索，如可见域的diversity如何影响IRM性能等)
12. ICLR Poster _In Search of Lost Domain Generalization_ (没有model selection的方法不是好方法，如何根据验证集选择模型？)
13. ICLR Spotlight(**Yoshua Bengio**) [Systematic generalisation with group invariant predictions](https://zhuanlan.zhihu.com/p/382608823) (将每个类分成不同的domain(_environment inference_，然后约束每个域的特征尽可能一致从而避免虚假依赖))
15. CVPR Oral: [Reducing Domain Gap by Reducing Style Bias](https://zhuanlan.zhihu.com/p/382608823) (channel-wise 均值作为图像风格，减少CNN对风格的依赖)
16. AISTATS _Linear Regression Games: Convergence Guarantees to Approximate Out-of-Distribution Solutions_

## 2020
1. Arxiv [I-SPEC: An End-to-End Framework for Learning Transportable, Shift-Stable Models](https://zhuanlan.zhihu.com/p/288980706)(将Domain Adaptation看作是因果图推理问题)
2. Arxiv (**Stanford**)_Distributionally Robust Lossesfor Latent Covariate Mixtures_.
3. NeurIPS: [Energy-based Out-of-distribution Detection](https://zhuanlan.zhihu.com/p/343678039)(使用能量模型检测OOD样本)
4. Arxiv [Invariant Risk Minimization](https://zhuanlan.zhihu.com/p/273209891) (奠基之作，跳出经验风险最小化--不变风险最小化)
5. ICLR Poster [The Risks of Invariant Risk Minimization](https://zhuanlan.zhihu.com/p/273209891) (不变风险最小化的缺陷:域数目过少IRM即失败)
6. NeurIPS _Self-training Avoids Using Spurious Features Under Domain Shift_ (使用target domain的无标签数据训练有助于避免使用虚假特征)

## OLD but Important
1. ICML 2018 Oral (**Stanford**) _Fairness Without Demographics in Repeated Loss Minimization._
2. ICCV 2017 [CCSA--Unified Deep Supervised Domain Adaptation and Generalization](https://blog.csdn.net/Adupanfei/article/details/85165667) (对比损失对齐源域目标域样本空间)

## 综述
1. [Domain Adaptation基础概念与相关文章解读](https://zhuanlan.zhihu.com/p/272508224)

# Causality

## 2021

## 2020
1. IJCAI(**CMU**) _Causal Discovery from Heterogeneous/Nonstationary Data_

## Old but Important
1. JSTOR (**Peters**)Causal inference by using invariant prediction: identification and confidence intervals.

## 综述
1.  [Causality 基础概念汇总](https://zhuanlan.zhihu.com/p/269625734)
