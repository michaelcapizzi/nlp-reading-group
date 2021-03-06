
## Learning Natural Language Inference with LSTM
http://arxiv.org/pdf/1512.08849v1.pdf

(8 pages) Natural language inference (NLI) is a fun- damentally important task in natural lan- guage processing that has many applications. The recently released Stanford Nat- ural Language Inference (SNLI) corpus has made it possible to develop and eval- uate learning-centered methods such as deep neural networks for the NLI task. In this paper, we propose a special long short-term memory (LSTM) architecture for NLI. Our model builds on top of a recently proposed neutral attention model for NLI but is based on a significantly dif- ferent idea. Instead of deriving sentence embeddings for the premise and the hy- pothesis to be used for classification, our solution uses a matching-LSTM that per- forms word-by-word matching of the hy- pothesis with the premise. This LSTM is able to place more emphasis on important word-level matching results. In particu- lar, we observe that this LSTM remembers important mismatches that are critical for predicting the contradiction or the neutral relationship label. Our experiments on the SNLI corpus show that our model outper- forms the state of the art, achieving an ac- curacy of 86.1% on the test data.


## The Goldilocks Principle: Reading Children's Books with Explicit Memory Representations
http://arxiv.org/pdf/1511.02301v3.pdf

(9 pages) We introduce a new test of how well language models capture meaning in chil- dren’s books. Unlike standard language modelling benchmarks, it distinguishes the task of predicting syntactic function words from that of predicting lower- frequency words, which carry greater semantic content. We compare a range of state-of-the-art models, each with a different way of encoding what has been previ- ously read. We show that models which store explicit representations of long-term contexts outperform state-of-the-art neural language models at predicting seman- tic content words, although this advantage is not observed for syntactic function words. Interestingly, we find that the amount of text encoded in a single memory representation is highly influential to the performance: there is a sweet-spot, not too big and not too small, between single words and full sentences that allows the most meaningful information in a text to be effectively retained and recalled. Fur- ther, the attention over such window-based memories can be trained effectively through self-supervision. We then assess the generality of this principle by ap- plying it to the CNN QA benchmark, which involves identifying named entities in paraphrased summaries of news articles, and achieve state-of-the-art performance.


## Deep Compositional Question Answering with Neural Module Networks
http://arxiv.org/pdf/1511.02799v2.pdf

(8 pages) Visual question answering is fundamentally composi- tional in nature—a question like where is the dog? shares substructure with questions like what color is the dog? and where is the cat? This paper seeks to simultaneously exploit the representational capacity of deep networks and the com- positional linguistic structure of questions. We describe a procedure for constructing and learning neural module net- works, which compose collections of jointly-trained neural “modules” into deep networks for question answering. Our approach decomposes questions into their linguistic sub- structures, and uses these structures to dynamically instan- tiate modular networks (with reusable components for rec- ognizing dogs, classifying colors, etc.). The resulting com- pound networks are jointly trained. We evaluate our ap- proach on two challenging datasets for visual question an- swering, achieving state-of-the-art results on both the VQA natural image dataset and a new dataset of complex ques- tions about abstract shapes.


## Learning to Compose Neural Networks for Question Answering
http://arxiv.org/pdf/1601.01705v1.pdf

(8 pages) We describe a question answering model that applies to both images and structured knowl- edge bases.The model uses natural language strings to automatically assemble neural net- works from a collection of composable mod- ules. Parameters for these modules are learned jointly with network-assembly parameters via reinforcement learning, with only (world, question, answer) triples as supervision. Our approach, which we term a dynamic neural module network, achieves state-of-the-art re- sults on benchmark datasets in both visual and structured domains.


## Language to Logical Form with Neural Attention
http://arxiv.org/pdf/1601.01280v1.pdf

(8 pages) Semantic parsing aims at mapping natural language to machine interpretable meaning representations. Traditional approaches rely on high-quality lexicons, manually-built tem- plates, and linguistic features which are either domain- or representation-specific. In this pa- per, we present a general method based on an attention-enhanced sequence-to-sequence model. We encode input sentences into vec- tor representations using recurrent neural net- works, and generate their logical forms by conditioning the output on the encoding vec- tors. The model is trained in an end-to-end fashion to maximize the likelihood of target logical forms given the natural language in- puts. Experimental results on four datasets show that our approach performs competi- tively without using hand-engineered features and is easy to adapt across domains and mean- ing representations.


## Basic Reasoning with Tensor Product Representations
http://arxiv.org/abs/1601.02745 

(12 pages (very theoretical)) In this paper we present the initial development of a general theory for mapping inference in predicate logic to computation over Tensor Product Representations (TPRs; Smolensky (1990), Smolensky & Legendre (2006)). After an initial brief synopsis of TPRs (Section 0), we begin with particular examples of inference with TPRs in the ‘bAbI’ question-answering task of Weston et al. (2015) (Section 1). We then present a simplification of the general analysis that suffices for the bAbI task (Section 2). Finally, we lay out the general treatment of inference over TPRs (Section 3). We also show the simplification in Section 2 derives the inference methods described in Lee et al. (2016); this shows how the simple methods of Lee et al. (2016) can be formally extended to more general reasoning tasks.


## Deep Neural Decision Forests
http://www.cv-foundation.org/openaccess/content_iccv_2015/papers/Kontschieder_Deep_Neural_Decision_ICCV_2015_paper.pdf

(8 pages (Training decision trees using backpropagation)) We present Deep Neural Decision Forests – a novel ap- proach that unifies classification trees with the representa- tion learning functionality known from deep convolutional networks, by training them in an end-to-end manner. To combine these two worlds, we introduce a stochastic and differentiable decision tree model, which steers the rep- resentation learning usually conducted in the initial lay- ers of a (deep) convolutional network. Our model differs from conventional deep networks because a decision for- est provides the final predictions and it differs from con- ventional decision forests since we propose a principled, joint and global optimization of split and leaf node param- eters. We show experimental results on benchmark machine learning datasets like MNIST and ImageNet and find on- par or superior results when compared to state-of-the-art deep models. Most remarkably, we obtain Top5-Errors of only 7.84%/6.38% on ImageNet validation data when in- tegrating our forests in a single-crop, single/seven model GoogLeNet architecture, respectively. Thus, even without any form of training data set augmentation we are improv- ing on the 6.67% error obtained by the best GoogLeNet ar- chitecture (7 models, 144 crops).


## Return of Frustratingly Easy Domain Adaptation
http://arxiv.org/pdf/1511.05547v2.pdf

(7 pages (not NLP)) Unlike human learning, machine learning often fails to handle changes between training (source) and test (target) input distributions. Such domain shifts, common in practical scenarios, severely damage the performance of conventional machine learning methods. Supervised domain adaptation methods have been proposed for the case when the target data have labels, including some that perform very well despite being "frustratingly easy" to implement. However, in practice, the target domain is often unlabeled, requiring unsupervised adaptation. We propose a simple, effective, and efficient method for unsupervised domain adaptation called CORrelation ALignment (CORAL). CORAL minimizes domain shift by aligning the second-order statistics of source and target distributions, without requiring any target labels. Even though it is extraordinarily simple--it can be implemented in four lines of Matlab code--CORAL performs remarkably well in extensive evaluations on standard benchmark datasets.


## Solving Geometry Problems: Combining Text and Diagram Interpretation
http://geometry.allenai.org/assets/emnlp2015.pdf

(9 pages) This paper introduces GEOS, the first au- tomated system to solve unaltered SAT ge- ometry questions by combining text un- derstanding and diagram interpretation. We model the problem of understanding geometry questions as submodular opti- mization, and identify a formal problem description likely to be compatible with both the question text and diagram. GEOS then feeds the description to a geometric solver that attempts to determine the cor- rect answer. In our experiments, GEOS achieves a 49% score on official SAT ques- tions, and a score of 61% on practice ques- tions.1 Finally, we show that by integrat- ing textual and visual information, GEOS boosts the accuracy of dependency and se- mantic parsing of the question text.


## Addressing a Question Answering Challenge by Combining Statistical Methods with Inductive Rule Learning and Reasoning
http://www.public.asu.edu/~cbaral/papers/aaai2016-sub.pdf

(6 pages) A group of researchers from Facebook has recently pro- posed a set of 20 question-answering tasks (Facebook’s bAbl dataset) as a challenge for the natural language un- derstanding ability of an intelligent agent. These tasks are designed to measure various skills of an agent, such as: fact based question-answering, simple induction, the ability to find paths, co-reference resolution and many more. Their goal is to aid in the development of sys- tems that can learn to solve such tasks and to allow a proper evaluation of such systems. They show existing systems cannot fully solve many of those toy tasks. In this work, we present a system that excels at all the tasks except one. The proposed model of the agent uses the Answer Set Programming (ASP) language as the pri- mary knowledge representation and reasoning language along with the standard statistical Natural Language Processing (NLP) models. Given a training dataset con- taining a set of narrations, questions and their answers, the agent jointly uses a translation system, an Induc- tive Logic Programming algorithm and Statistical NLP methods to learn the knowledge needed to answer simi- lar questions. Our results demonstrate that the introduc- tion of a reasoning module significantly improves the performance of an intelligent agent.


## Extracting Thee-Structured Representations of Trained Networks
https://papers.nips.cc/paper/1152-extracting-tree-structured-representations-of-trained-networks.pdf

(7 pages) A significant limitation of neural networks is that the represen- tations they learn are usually incomprehensible to humans. We present a novel algorithm, TREPAN, for extracting comprehensible, symbolic representations from trained neural networks. Our algo- rithm uses queries to induce a decision tree that approximates the concept represented by a given network. Our experiments demon- strate that TREPAN is able to produce decision trees that maintain a high level of fidelity to their respective networks while being com- prehensible and accurate. Unlike previous work in this area, our algorithm is general in its applicability and scales well to large net- works and problems with high-dimensional input spaces.


## sense2vec - A Fast and Accurate Method for Word Sense Disambiguation In Neural Word Embeddings
http://arxiv.org/pdf/1511.06388v1.pdf

(7 pages) Neural word representations have proven useful in Natural Language Processing (NLP) tasks due to their ability to efficiently model complex semantic and syntactic word relationships. However, most techniques model only one representation per word, despite the fact that a single word can have multiple meanings or "senses". Some techniques model words by using multiple vectors that are clustered based on context. However, recent neural approaches rarely focus on the application to a consuming NLP algorithm. Furthermore, the training process of recent word-sense models is expensive relative to single-sense embedding processes. This paper presents a novel approach which addresses these concerns by modeling multiple embeddings for each word based on supervised disambiguation, which provides a fast and accurate way for a consuming NLP model to select a sense-disambiguated embedding. We demonstrate that these embeddings can disambiguate both contrastive senses such as nominal and verbal senses as well as nuanced senses such as sarcasm. We further evaluate Part-of-Speech disambiguated embeddings on neural dependency parsing, yielding a greater than 8% average error reduction in unlabeled attachment scores across 6 languages.


## Reasoning in Vector Space: An Exploratory Study of Question Answering
http://arxiv.org/pdf/1511.06426v2.pdf

(11 pages) Question answering tasks have shown remarkable progress with distributed
vector representations. In this paper, we look into the recently proposed
Facebook 20 tasks (FB20). Finding the answers for questions in FB20 requires
complex reasoning. Because the previous work on FB20 consists of end-to-end
models, it is unclear whether errors come from imperfect understanding of
semantics or in certain steps of the reasoning. To address this issue, we
propose two vector space models inspired by tensor product representation (TPR)
to perform analysis, knowledge representation, and reasoning based on
common-sense inference. We achieve near-perfect accuracy on all categories,
including positional reasoning and pathfinding that have proved difficult for
all previous approaches due to the special two-dimensional relationships
identified from this study. The exploration reported in this paper and our
subsequent work on generalizing the current model to the TPR formalism suggest
the feasibility of developing further reasoning models in tensor space with
learning capabilities.

