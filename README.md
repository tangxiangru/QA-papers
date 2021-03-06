# ACL
## 2017 ACL

[A Constituent-Centric Neural Architecture for Reading Comprehension](http://www.aclweb.org/anthology/P/P17/P17-1129.pdf)

task:reading comprehension ||  data:SQuAD 

[A FOFE-based Local Detection Approach for Named Entity Recognition and Mention Detection](https://arxiv.org/abs/1611.00801)

task:NER、mention detection

[An End-to-End Model for Question Answering over Knowledge Base with Cross-Attention Combining Global Knowledge](https://www.researchgate.net/publication/318737344_An_End-to-End_Model_for_Question_Answering_over_Knowledge_Base_with_Cross-Attention_Combining_Global_Knowledge)

data:WebQuestions || focus：question representation（问题无论它的候选答案是什么，都会被转换成为一个固定长度的vector）

[Attention-over-Attention Neural Networks for Reading Comprehension](https://arxiv.org/abs/1607.04423)

task:阅读理解 



[Automatically Labeled Data Generation for Large Scale Event Extraction](https://www.aclweb.org/anthology/P/P17/P17-1038.pdf)

focus:对event extraction提供标注数据的方法



[Coarse-to-Fine Question Answering for Long Documents ](https://homes.cs.washington.edu/~eunsol/papers/acl17eunsol.pdf)

advantage：高效地扩展到长文档(longer documents)的同时，能够维持甚至提升state-of-the-art模型的性能

[Comparing Apples to Apples: Learning Semantics of Common Entities Through a Novel Comprehension Task ](http://cs.rochester.edu/~omidb/papers/apples-apples-semantics.pdf)

task:提出阅读理解新任务GuessTwo（给定一个短段落，与两个真实在语义上相似的(semantically-similar)两个entities分别比较，系统应该能猜出来这两个entities是什么）

[Deep Keyphrase Generation ](https://arxiv.org/abs/1704.06879)

method：使用encoder-decoder框架来预测生成式keypghrase

[Exploiting Argument Information to Improve Event Detection via Supervised Attention Mechanisms](http://ir.ia.ac.cn/bitstream/173211/14522/1/acl2017.pdf)

focus:event detection(引入了identifying和categorizing event) || method:利用argument信息来显式地进行event detection

[Gated Self-Matching Networks for Reading Comprehension and Question Answering](http://www.aclweb.org/anthology/P/P17/P17-1018.pdf)

method:gated self-matching networks || data:SQuAD

[Gated-Attention Readers for Text Comprehension](https://arxiv.org/abs/1606.01549)

data:document上回答cloze风格 || method:multi-hop架构和一个新的attention机制结合

[Generating Natural Answer by Incorporating Copying and Retrieving Mechanisms in Sequence-to-Sequence Learning](http://www.nlpr.ia.ac.cn/cip/shizhuhe/articles/acl2017-coreqa.pdf)

data:kbqa

[Going out on a limb : Joint Extraction of Entity Mentions and Relations without Dependency Trees](https://www.aclweb.org/anthology/P/P17/P17-1085.pdf)


[Weakly Supervised Cross-Lingual Named Entity Recognition via Effective Annotation and Representation Projection](https://arxiv.org/abs/1707.02483)

[http://www.pilevar.com/taher/pubs/ACL2017b_Gritta_etal.pdf](http://www.pilevar.com/taher/pubs/ACL2017b_Gritta_etal.pdf)

focus:转喻(metonymic)与NER  || data:SemEval2007的Metonymy Resolution

[Search-based Neural Structured Learning for Sequential Question Answering](https://cs.umd.edu/~miyyer/pubs/2017_acl_dynsp.pdf)

method:dynamic neural semantic parsing,使用弱监督的reward-guided search

[Reading Wikipedia to Answer Open-Domain Questions](https://arxiv.org/abs/1704.00051)

method:bigram hashing进行搜索和使用RNN进行TF-IDF matching ||data:Wikipedia

[Neural Symbolic Machines: Learning Semantic Parsers on Freebase with Weak Supervision](https://arxiv.org/abs/1611.00020)

method:neural programmer(比如说一个端到端的模型来将语言映射到程序)+symbolic computer(比如说一个能够执行程序的Lisp的解释器)+rl

[hierarchical RNN](https://arxiv.org/abs/1704.06194)

method:hierarchical RNN +residual learning || data:single-relation(SimpleQuestions)和multi-relation(WebQSP)

[Joint Extraction of Entities and Relations Based on a Novel Tagging Scheme](https://arxiv.org/abs/1706.05075)

entities和relations的joint extraction--->tagging problem

[Joint Extraction of Relations with Class Ties via Effective Deep Ranking](https://arxiv.org/abs/1612.07602)

一个实体tuple可能有多个关系fact、三个新的ranking loss function

[Leveraging Knowledge Bases in LSTMs for Improving Machine Reading](http://www.aclweb.org/anthology/P/P17/P17-1132.pdf)
data:ACE2005的entity extraction和event extraction


