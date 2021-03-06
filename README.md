# Natural Language Procesing
This repository includes basic concepts of Natural Language Processing, textbooks and blogs of good reputation, popular papers and so on.  

This is also the Natural Language Processing part of [Machine Learning Resources](https://github.com/jindongwang/MachineLearning) created by a group of people including [jindongwang](https://github.com/jindongwang).

Contributors are welcomed to work together and make it BETTER!

## Resource of Textbooks and Lectures

### Mathemetical and Statistical Foundation
* Linear Algebra
  - 18.06 MIT(Gilbert Strang)[[pdf](http://www.math.hcmus.edu.vn/~bxthang/Linear%20algebra%20and%20its%20applications.pdf)][[video](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/)]

* Matrix Analysis

* Convex Optimization
  - EE364A Stanford(Stephen Boyd)[[pdf](https://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf)][[website](http://web.stanford.edu/~boyd/cvxbook/)]
  - Introductory Lectures on Convex Programming(Yu.Nesterov)[[pdf](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.693.855&rep=rep1&type=pdf)]


### Machine Learning
* [The Elements of Statistical Learning(ESL) - HTF](https://web.stanford.edu/~hastie/Papers/ESLII.pdf)
* [CS228 Probabilistic Graphical Model - Stanford](https://cs.stanford.edu/~ermon/cs228/index.html)
* [10708 Probabilistic Graphical Model - CMU](http://www.cs.cmu.edu/~epxing/Class/10708/index.html)

### Deep Learning
* [Deep Learning - Ian Goodfellow, Yoshua Bengio, Aaron Courville](https://github.com/HFTrader/DeepLearningBook)
* [CS231n Convolutional Neural Networks for Visual Recognition - Stanford](http://cs231n.stanford.edu/)

### Natural Language Processing
* Foundations of Statistical Natural Language Processing - 
    Chris Manning
* [Speech and Language Processing - Daniel Jurafsky and James H. Martin](http://www.cs.colorado.edu/~martin/slp2.html#Chapter3)
* 统计学习方法 - 李航
* [Advanced Natural Language Processing - MIT](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/index.htm)
* [CS 224n Natural Language Processing with Deep Learning - Stanford](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-864-advanced-natural-language-processing-fall-2005/index.htm)
* [Deep Learning for NLP at Oxford with Deepmind - Oxford](https://www.youtube.com/playlist?list=PL613dYIGMXoZBtZhbyiBqb0QtgK6oJbpm)
* [11-747 NN4NLP](http://www.phontron.com/class/nn4nlp2021/)
* [11-737 Multilingual NLP](http://demo.clab.cs.cmu.edu/11737fa20/)
* [Some Knowledge about Machine Learning](https://www.youtube.com/playlist?list=PL613dYIGMXoZBtZhbyiBqb0QtgK6oJbpm)
* [A list of datasets](https://github.com/awesomedata/awesome-public-datasets#naturallanguage)

## Models and Applications
- Probalistic Graphical Model
    - Hidden Markov Model
    - Conditional Random Fields

- Topic Model
    - Latent Dirichlet Allocation([paper](http://www.jmlr.org/papers/volume3/blei03a/blei03a.pdf))
 
- Deep Learning Model
    - [Long Short Term Memory(LSTM)](https://www.bioinf.jku.at/publications/older/2604.pdf) *Sepp Hochreiter, 1997*
        - [Interpretation](https://arxiv.org/pdf/1805.03716.pdf) *Omer Levy, UWashington, 2018* 
    - Recurrent Neuron Network
          - Seq2Seq([Tensorflow Tutorial](https://github.com/llSourcell/seq2seq_model_live/blob/master/2-seq2seq-advanced.ipynb))
          - [Machine Translation Tensorflow implement](https://github.com/tensorflow/nmt)  
   - Convolutional Neuron Network
   - Attention Model
   	- Overview([Chinese](https://blog.csdn.net/BVL10101111/article/details/78470716))
   - Generative Adversial Network(GAN)
   - Transformer
   	- [Training Tips](https://arxiv.org/abs/1804.00247)
   - [Bidirectional Encoder Representation from Transformers(BERT)](https://arxiv.org/abs/1810.04805)  *Jacob Devlin, Google 2018*

## Blog and Tutorials
- [Tensorflow implement on RNN and undocumented features](http://www.wildml.com/2016/08/rnns-in-tensorflow-a-practical-guide-and-undocumented-features/)
- [The Unreasonable Effectiveness of Recurrent Neural Networks](https://web.stanford.edu/class/cs379c/class_messages_listing/content/Artificial_Neural_Network_Technology_Tutorials/KarparthyUNREASONABLY-EFFECTIVE-RNN-15.pdf)

## Topics and Tasks
Category of areas is based on tracks in ACL 2018, ACL 2020, EMNLP 2020
### [Summerization](https://github.com/Nativeatom/NaturalLanguageProcessing/tree/master/Summerization)
- Task
    - Summerization
    - Opinion Summarization
    - Evaluation 
- Model
    - Extractive
    - Generative
    	- [PointNet, ACL2017](https://arxiv.org/pdf/1704.04368.pdf)
        - [BART, ACL2020](https://www.aclweb.org/anthology/2020.acl-main.703/)
        - [Pegasus, ICML2020](https://arxiv.org/pdf/1912.08777.pdf)
    - Hybrid 
- Dataset
    - [XSum, EMNLP2018](https://github.com/EdinburghNLP/XSum) [[paper](https://arxiv.org/abs/1808.08745)]
    - [CNN/DailyMail](https://github.com/JafferWilson/Process-Data-of-CNN-DailyMail)
    - NEWSROOM
    - Multi-News
    - Gigaword
    - arXiv
    - PubMed
    - BIGPATENT
    - WikiHow
    - Reddit TIFU (long, short)
    - AESLC
    - BillSum

### [Embedding](https://github.com/Nativeatom/NaturalLanguageProcessing/tree/master/Embedding)
- Model
    - Word2Vec
- Pre-trained Embedding
    - Glove
    - word2vec
    - FastText
- Contextual Word Embedding
    - ELMo
    - GPT
    - BERT
    - XLNet
    - BART
    - T-5

### Sentimental Analysis and Argument Mining

### Name Entity Recognition

### Tagging, Chunking
- Task
    - Word Segmentation
    - Syntactic Parsing
- Model
    - Hidden Markov Model (HMM)
    - Conditional Random Fields (CRFs)
    - Finetuned Language Models

### Syntax, Parsing
- Task
    - Constituency Parsing
    - Dependency Parsing
    - Visual Grounded Syntactic Aquisition
- Model
    - [Invertible Neural Projections, EMNLP 2018](https://arxiv.org/abs/1808.09111)
    - [Unsupervised Recurrent Neural Network Grammars (URNNG), NAACL 2019](https://arxiv.org/abs/1904.03746)
    - [Compound PCFG, ACL 2019](https://arxiv.org/abs/1906.10225)
    - [Lexical Compound PCFG, TACL 2020](https://www.aclweb.org/anthology/2020.tacl-1.42/)
    - [VG-NSL, ACL 2019](https://www.aclweb.org/anthology/P19-1180/)
- Dataset
    - [PennTreeBank (PTB)](https://catalog.ldc.upenn.edu/LDC99T42)

### Document Analysis

### [Sentence-level Semantics](https://github.com/Nativeatom/NaturalLanguageProcessing/tree/master/Sentence-level%20Semantics)
- Tasks
   - Semantic Parsing
       - AMR-to-text
       - Text-to-AMR
       - Table-to-text
       - Code Generation
- Model
   - [TRANX](https://www.aclweb.org/anthology/D18-2002/)
   
- Dataset
 
### Semantics: Lexical
- Tasks
    - Word Sense Disambiguation

### [Information Extraction and Text Mining](https://github.com/Nativeatom/NaturalLanguageProcessing/tree/master/Informaiton%20Extraction%20and%20Text%20Mining)
- Tasks
    - Topic Extraction
    - Sentimental Extraction
    - Aspect Extraction

### Machine Translation
- Task
    - Machine Translation
    - Non-autogressive Machine Translation
    - Word-alignment
- Model
    - [Back-translation, ACL 2016](https://www.aclweb.org/anthology/P16-1009/)
    - [OpenNMT, ACL 2017](https://www.aclweb.org/anthology/P17-4012/) [[project](https://opennmt.net/)][[code](https://github.com/OpenNMT/OpenNMT-py)]
    - [Transformer, NeurIPS 2017](https://papers.nips.cc/paper/2017/hash/3f5ee243547dee91fbd053c1c4a845aa-Abstract.html)
- Dataset
    - WMT 
    
### Text Generation

### Text Classification
- Task
    - SPAM Classification
    - Sentiment Analysis
- Model
    - [CNN-sentence, EMNLP2014](https://www.aclweb.org/anthology/D14-1181.pdf)
    - [CharCNN, NeurIPS2015](https://arxiv.org/pdf/1509.01626.pdf)
- Dataset
    - [Yelp Dataset](https://www.yelp.com/dataset/challenge)
    - [IMDB](https://www.imdb.com/interfaces/)
    - [Stanford Sentiment Treebank (SST)](https://nlp.stanford.edu/sentiment/index.html)

### Dialogue and Interactive Systems

### Question Answering
- Task
- Dataset
    - [CNN/DailyMail](https://cs.nyu.edu/~kcho/DMQA/)
    - [SQuAD](https://rajpurkar.github.io/SQuAD-explorer/) 
        - Benchmark: F1-86.967  [BERT + Synthetic Self-Training (ensemble)](https://github.com/google-research/bert)   *Jan 10, 2019*
    - [RACE](https://www.cs.cmu.edu/~glai1/data/race/)
        - Benchmark: RACE-83.2 RACEC-M-86.5 RACE-H-81.3 [RoBERTa](https://arxiv.org/abs/1907.11692) *July 2019*

### Resources and Evaluation

### Linguistic Theories and Cognitive Modeling

### [Multilinguality](https://github.com/Nativeatom/NaturalLanguageProcessing/tree/master/Multilinguality)
- Task
    - Code-Switching
    - Mutilingual Translation
- Model
- Dataset
    - [Linguistic Data Consortium](https://catalog.ldc.upenn.edu/) [[list](https://github.com/isi-nlp/mt_lit_lrec16/tree/master/ontology)] [[ordered by year](https://linguistics.cornell.edu/language-corpora)]
    	- [CALLFRIEND Mandarin - Mainland Dialect](https://catalog.ldc.upenn.edu/LDC96S55)
        - [CALLHOME Mandarin Chinese](https://catalog.ldc.upenn.edu/LDC2008T17)
	- [Chinese-English Name Entity List](https://catalog.ldc.upenn.edu/LDC2005T34)
    - [List of Chinese Dataset](https://github.com/Lab41/sunny-side-up/wiki/Chinese-Datasets)
    - [Cantonese Dataset](http://compling.hss.ntu.edu.sg/hkcancor/)
    - [SEAME (Mandarin-English Code-Switching in South-East Asia)](https://catalog.ldc.upenn.edu/LDC2015S04)

### [Phonology, Morphology and Word Segmentation](https://github.com/Nativeatom/NaturalLanguageProcessing/tree/master/Phonology%20Morphology%20and%20Word%20Segment)

### Textual Inference

### Vision, Robotics, Speech, Multimodal

### Language Modeling
- Tasks
- Model
    - N-gram
    - [ELMo, NAACL2018](https://www.aclweb.org/anthology/N18-1202.pdf)
    - GPT
    - [GPT-2, arXiv2019](https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf)
    - [GPT-3, NeurIPS2020](https://arxiv.org/pdf/2005.14165.pdf)
    - [BERT, NAACL2019](https://www.aclweb.org/anthology/N19-1423/)
    	- [RoBERTa, arXiv 2019](https://arxiv.org/pdf/1907.11692.pdf)
    	- [SpanBERT, TACL 2020](https://www.aclweb.org/anthology/2020.tacl-1.5/)
    	- Efficient
    		- [ALBERT, arXiv 2020](https://arxiv.org/abs/1909.11942)
    		- [SqueezeBERT, SustainNLP@EMNLP 2020](https://www.aclweb.org/anthology/2020.sustainlp-1.17/)
    	- Domain Specific
    		- [SciBERT, EMNLP 2019](https://www.aclweb.org/anthology/D19-1371/)
    		- [BioBERT, Bioinformatics 2019](https://arxiv.org/pdf/1901.08746.pdf)
    		- [patentBERT, arXiv 2019](https://arxiv.org/abs/1906.02124)
    		- [FinBERT, arXiv 2020](https://arxiv.org/abs/2006.08097)
    		- [MedBERT, arXiv 2020](https://arxiv.org/pdf/2005.12833.pdf) [[code](https://github.com/ZhiGroup/Med-BERT)]
    		- [ClinicalBERT, CHIL 2020](https://arxiv.org/abs/1904.05342)
    		- [LEGAL-BERT, EMNLP Finding 2020](https://www.aclweb.org/anthology/2020.findings-emnlp.261/)
    		- [Tutorial](https://mccormickml.com/2020/06/22/domain-specific-bert-tutorial/)
    	- Langauge Specific [[Latin BERT](https://arxiv.org/abs/2009.10053), [German BERT](https://deepset.ai/german-bert), [Italian BERT](http://ceur-ws.org/Vol-2481/paper57.pdf), [Chinese BERT](https://arxiv.org/abs/2004.13922)]
    	- [BERTology, TACL 2020](https://www.aclweb.org/anthology/2020.tacl-1.54/)
    - [XLNet, NeurIPS2019](https://arxiv.org/pdf/1906.08237.pdf)
    - [MASS, ICML2019](https://arxiv.org/pdf/1905.02450.pdf) [[code](https://github.com/microsoft/MASS)]
    - [ELECTRA, ICLR2020](https://openreview.net/forum?id=r1xMH1BtvB) [[code](https://github.com/google-research/electra)]
    - [T5, JMLR2020](https://arxiv.org/abs/1910.10683)
    - [BART, ACL2020](https://www.aclweb.org/anthology/2020.acl-main.703/)
- Finetuning
    - Invasive (LM not fixed)
    	- Regular finetuning 
    	- [Re-initlization for few-shot learning](https://arxiv.org/pdf/2006.05987.pdf) ICLR2021
    - Non-invasive (LM fixed)
    	- [Prefix-tuning](https://arxiv.org/pdf/2101.00190.pdf), arXiv2021
- Language Model as
	- [BERTScore](https://arxiv.org/pdf/1904.09675.pdf), ICLR2020
	- Few-shot learner
		- [Bias in few-shot examples](https://arxiv.org/pdf/2102.09690.pdf), arXiv2021
	- Knowledge base [EMNLP2019](https://www.aclweb.org/anthology/D19-1250.pdf), [Tutorial@AAAI2021](https://usc-isi-i2.github.io/AAAI21Tutorial/)
- Dataset
    - [CommonCrawl](https://commoncrawl.org/)
    - Wiki-Text
    - STORIES
    - [C4](https://arxiv.org/abs/1910.10683) [[huggingface](https://www.tensorflow.org/datasets/catalog/c4)]

### Computational Social Science and Social Media

### Discourse and Pragmatics

### Information Retrieval and Text Mining

### Language Grounding to Vision, Robotics and Beyond
- Papers
    - [Experience Grounds Language, EMNLP2020](https://arxiv.org/abs/2004.10151) 

### Machine Learning for NLP

### Theory and Formalism in NLP

### Ethics in NLP

### Commonsense Knowledge
- Tasks
    - Fact Verification
    - Commonsense Reasoning
    - Word-level Rationales
    - Factually Consistent Generation

- Model
    - [ConceptNet, AAAI2017](https://conceptnet.io/)
    - [COMET, ACL2019](https://mosaickg.apps.allenai.org/) [[paper](https://www.aclweb.org/anthology/P19-1470/)]

- Dataset
    - [FEVER](https://arxiv.org/abs/1803.05355)
    - [FEVER 2.0 Shared Task, EMNLP 2019](https://www.aclweb.org/anthology/D19-6601/) [[FEVER@EMNLP2021](https://fever.ai/index.html)]
    - [CommonGen, EMNLP Finding 2020](https://inklab.usc.edu/CommonGen/) [[paper](https://arxiv.org/abs/1911.03705)]
    - [VitaminC, NAACL 2021](https://github.com/TalSchuster/VitaminC) [[paper](https://arxiv.org/abs/2103.08541)]

### Interpretability

### NLP Applications
- Tasks
    - Grammartical Error Correction (GEC) [[BEA@NAACL2018](https://www.cs.rochester.edu/~tetreaul/naacl-bea13.html), [BEA@ACL2019](https://sig-edu.org/bea/2019), [BEA@ACL2020](https://sig-edu.org/bea/2020), [BEA@EACL2021](https://sig-edu.org/bea/current)]
    - Lexical Substitution
    - Lexical Simplification
- Model
    - BERT-based Lexical Substitution/GEC, [[ACL2019](https://www.aclweb.org/anthology/P19-1328/), [AAAI2020](https://arxiv.org/pdf/2001.03521.pdf)]
- Dataset
    - [ETS](https://www.ets.org/research/contact/data_requests/)

## Resources and Benchmarks
- [Huggingface Dataset](https://huggingface.co/datasets)
- [GLUE](https://gluebenchmark.com/)
- [SuperGLUE](https://super.gluebenchmark.com/)
- Leaderboards
    - [NLP-Progress](http://nlpprogress.com/)
    - [PaperwithCode](https://paperswithcode.com/sota)

## Interesting NLP
- [Google Books Ngram Viewer](https://books.google.com/ngrams)


## Package
- Machine Learning Package and Framework
    - sciki-learn
    - Tensorflow
    - Caffe2
    - Pytorch
    - MXNet
- NLTK
- gensim
- jieba
- Stanford NLP 
- Transformers (huggingface)

## 如何加入 How to contribute

如果你对本项目感兴趣，非常欢迎你加入！

- 正常参与：请直接fork、pull都可以
- 如果要上传文件：请**不要**直接上传到项目中，否则会造成git版本库过大。正确的方法是上传它的**超链接**。如果你要上传的文件本身就在网络中（如paper都会有链接），直接上传即可；如果是自己想分享的一些文件、数据等，鉴于国内网盘的情况，请按照如下方式上传：
	- (墙内)目前没有找到比较好的方式，只能通过链接，或者自己网盘的链接来做。
	- (墙外)首先在[UPLOAD](https://my.pcloud.com/#page=puplink&code=4e9Z0Vwpmfzvx0y2OqTTTMzkrRUz8q9V)直接上传（**不**需要注册账号）；上传成功后，在[DOWNLOAD](https://my.pcloud.com/publink/show?code=kZWtboZbDDVguCHGV49QkmlLliNPJRMHrFX)里找到你刚上传的文件，共享链接即可。

## 如何开始项目协同合作

[快速了解github协同工作 Learn how to collaborate through github](http://hucaihua.cn/2016/12/02/github_cooperation/)

[及时更新fork项目 Update through fork](https://jinlong.github.io/2015/10/12/syncing-a-fork/)

[如何使用git提交 How to submit in git](http://blog.csdn.net/u012150179/article/details/17172211)

[Fetch and Merge in Git](https://www.oschina.net/translate/git-fetch-and-merge?print)

#### [贡献者 Contributors](https://github.com/Nativeatom/NaturalLanguageProcessing/blob/master/Contributors.md)

