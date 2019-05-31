### Sentence-level Semantics

*At the other end of the spectrum, in the traditional semanticparsing literature, the problem is framedas predicting compositional semantic representations. These are mainly geared towards question-answering rather than task completion, and are usually directly executed against a knowledge base.Some of the standard datasets in this area include GeoQuery [24] and WebQuestions [2].Within both of these areas, neural approaches have supplanted previous feature-engineering basedapproaches in recent years [10, 14]. In the context of tree-structured semantic parsing, some otherinteresting approaches include Seq2Tree [7] which modifiesthe standard Seq2Seq decoder to betteroutput trees; SCANNER [5, 4] which extends the RNNG formulation specifically for semantic pars-ing such that the output is no longer coupled with the input; and TRANX [23] and Abstract SyntaxNetwork [19] which generate code along a programming language schema. For graph-structured se-mantic parsing [1, 11], SLING [21] produces graph-structured parses by modeling semantic parsingas a neural transition parsing problem with a more expressive transition tag set. While graph struc-tures can provide more detailed semantics, they are more difficult to parse and can be an overkill forunderstanding task oriented utterances.* *[Improving Semantic Parsing for Task Oriented Dialog](https://arxiv.org/pdf/1902.06000.pdf)*


- Tasks
    - Semantic Parsing
        - Code Generation
            - NL2SQL
            - NL2Python
                - Seq2Seq based
                - Retrieval-based
                    - [Retrieval-Based Neural Code Generation](https://arxiv.org/abs/1808.10025)
                - CNN based 
                    - [A Grammar-Based Structural CNN Decoder for Code Generation AAAI 19'](https://arxiv.org/abs/1811.06837)
                - Transition-based
                    - [TRANX: A Transition-based Neural Abstract Syntax Parser for Semantic Parsing and Code Generation ACL 18'](https://arxiv.org/abs/1810.02720)
            - NL2Java
            - Python2Java
     
- Models
    - TRANX (*[TRANX: A Transition-based Neural Abstract Syntax Parser for Semantic Parsing and Code Generation](https://arxiv.org/abs/1810.02720)*) **ACL 18'**
        

### Dataset and Benchmark
#### HeartStone
* ##### Description
* ##### Download
  [Github](https://github.com/deepmind/card2code) - Wang Ling *[Latent Predictor Networks for Code Generation](https://arxiv.org/abs/1603.06744)* **ACL 16'**
  
* ##### Benchmark
    - Zeyu Sun *[A Grammar-Based Structural CNN Decoder for Code Generation](https://arxiv.org/abs/1811.06837)* **AAAI 19'**
        - Accuracy: 30.3%
        - BLEU: 79.6%
        
#### Django
* ##### Description
* ##### Download
  [Github](https://github.com/odashi/ase15-django-dataset) - Yusuke Oda *[Learning to Generate Pseudo-Code from Source Code Using Statistical Machine Translation](https://ieeexplore.ieee.org/document/7372045)* **ASE 15'**

* ##### Benchmark
    - Pengcheng Yin *[TRANX: A Transition-based Neural Abstract Syntax Parser for Semantic Parsing and Code Generation](https://arxiv.org/abs/1810.02720)*) **ACL 18'**
        - Accuracy: 73.7%

#### WikiSQL
* ##### Description
* ##### Download
    [Github](https://github.com/salesforce/WikiSQL) - Victor Zhong *[Seq2SQL: Generating Structured Queries from Natural Language using Reinforcement Learning](https://arxiv.org/abs/1709.00103)* **ArXiv 18'**

* ##### Benchmark

#### ATIS
* ##### Description
* ##### Download

* ##### Benchmark

#### JOBS
* ##### Description
* ##### Download

* ##### Benchmark

#### GEO
* ##### Description
* ##### Download

* ##### Benchmark
