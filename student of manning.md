## Sepandar Kamvar
在搞一些奇怪的东西
## Lynn Berry
同上
## Dan Klein
https://people.eecs.berkeley.edu/~klein/
My education, in reverse order:
	Stanford University 	MS, PhD in Computer Science 	1999-2004
	Oxford University, St. John's College 	MSt in Linguistics 	1998-1999
	Cornell University 	BA in Math, CS, Linguistics (summa cum laude) 	1994-1998
	Mt. Lebanon High School 	  	1990-1994

Some fellowships / awards:

    Diane S. McEntyre Award for Excellence in Teaching, 2011
    UC Berkeley Distinguished Teaching Award, 2010
    Jim and Donna Gray Award for Excellence in UG Teaching, 2009
    Okawa Research Award, 2009
    ACM Grace Murray Hopper Award, 2007
    Alfred P. Sloan Fellowship, 2007
    NSF CAREER Award, 2007
    Microsoft Faculty Fellowship, 2005
    Microsoft Graduate Fellowship, 2003
    British Marshall Fellowship, 1998

### EMNLP Analogs of Linguistic Structure in Deep Representations
Abstract
We  investigate  the  compositional  struc-
ture  of  message  vectors  computed  by  a
deep network trained on a communication
game.
By  comparing  truth-conditional
representations of encoder-produced mes-
sage  vectors  to  human-produced  refer-
ring  expressions,  we  are  able  to  identify
aligned  (vector,  utterance)  pairs  with  the
same meaning.  We then search for struc-
tured  relationships  among  these  aligned
pairs   to   discover   simple   vector   space
transformations   corresponding   to   nega-
tion,  conjunction,  and  disjunction.    Our
results suggest that neural representations
are  capable  of  spontaneously  developing
a  “syntax”  with  functional  analogues  to
qualitative properties of natural language

### EMNLP Effective Inference for Generative Neural Parsing
Abstract
Generative  neural  models  have  recently
achieved  state-of-the-art  results  for  con-
stituency parsing. However, without a fea-
sible search procedure, their use has so far
been limited to reranking the output of ex-
ternal parsers in which decoding is more
tractable.    We  describe  an  alternative  to
the conventional action-level beam search
used for discriminative neural models that
enables us to decode directly in these gen-
erative models.  We then show that by im-
proving our basic candidate selection strat-
egy and using a coarse pruning function,
we  can  improve  accuracy  while  explor-
ing significantly less of the search space.
Applied to the model of Choe and Char-
niak (2016),  our inference procedure ob-
tains 92.56 F1 on section 23 of the Penn
Treebank, surpassing prior state-of-the-art
results for single-model systems.

### EMNLP Where is Misty? Interpreting Spatial Descriptors by Modeling Regions in Space
Abstract
We  present  a  model  for  locating  regions
in  space  based  on  natural  language  de-
scriptions.   Starting with a 3D scene and
a sentence, our model is able to associate
words in the sentence with regions in the
scene,  interpret  relations  such  as on  top
of or next  to,and  finally  locate  the  re-
gion described in the sentence.  All com-
ponents form a single neural network that
is trained end-to-end without prior knowl-
edge  of  object  segmentation.    To  evalu-
ate our model, we construct and release a
new dataset consisting of Minecraft scenes
with  crowdsourced  natural  language  de-
scriptions.  We achieve a 32% relative er-
ror reduction compared to a strong neural
baseline.

### ACL A Minimal Span-Based Neural Constituency Parser
Abstract
In this work, we present a minimal neural
model  for  constituency  parsing  based  on
independent  scoring  of  labels  and  spans.
We  show  that  this  model  is  not  only
compatible  with  classical  dynamic  pro-
gramming  techniques,  but  also  admits  a
novel  greedy  top-down  inference  algo-
rithm  based  on  recursive  partitioning  of
the  input.
We  demonstrate  empirically
that both prediction schemes are competi-
tive with recent work, and when combined
with basic extensions to the scoring model
are  capable  of  achieving  state-of-the-art
single-model  performance  on  the  Penn
Treebank  (91.79  F1)  and  strong  perfor-
mance on the French Treebank (82.23 F1).

### ACL Abstract Syntax Networks for Code Generation and Semantic Parsing
Abstract
Tasks  like  code  generation  and  semantic
parsing require mapping unstructured (or
partially structured) inputs to well-formed,
executable  outputs.
We  introduce  abstract syntax networks, a modeling framework  for  these  problems.
The  outputs are  represented  as  abstract  syntax  trees (ASTs) and constructed by a decoder with
a dynamically-determined modular struc-
ture paralleling the structure of the output
tree.   On  the benchmark  HEARTHSTONE
dataset for code generation, our model ob-
tains 79.2 BLEU and 22.7% exact match
accuracy,  compared  to  previous  state-of-
the-art values of 67.1 and 6.1%.  Further-
more,  we  perform  competitively  on  the
ATIS,  JOBS,  and  GEO semantic  parsing
datasets with no task-specific engineering.

### ACL Fine-Grained Entity Typing with High-Multiplicity Assignments
Abstract
As entity type systems become richer and
more fine-grained, we expect the number
of types assigned to a given entity to in-
crease. However, most fine-grained typing
work has focused on datasets that exhibit
a low degree of type multiplicity.  In this
paper,  we  consider  the  high-multiplicity
regime  inherent  in  data  sources  such  as
Wikipedia  that  have  semi-open  type  sys-
tems.   We  introduce  a  set-prediction  ap-
proach to this problem and show that our
model outperforms unstructured baselines
on  a  new  Wikipedia-based  fine-grained
typing corpus.

### ACL Improving Neural Parsing by Disentangling Model Combination and Reranking Effects
Abstract
Recent work has proposed several genera-
tive neural models for constituency pars-
ing  that  achieve  state-of-the-art  results.
Since  direct  search  in  these  generative
models  is  difficult,  they  have  primarily
been  used  to  rescore  candidate  outputs
from  base  parsers  in  which  decoding  is
more straightforward.  We first present an
algorithm  for  direct  search  in  these  gen-
erative models.  We then demonstrate that
the rescoring results are at least partly due
to implicit model combination rather than
reranking  effects.   Finally,  we  show  that
explicit  model  combination  can  improve
performance even further, resulting in new
state-of-the-art  numbers  on  the  PTB  of
94.25 F1 when training only on gold data
and 94.66 F1 when using external data.

### ACL Translating Neuralese
Abstract
Several approaches have recently been pro-
posed for learning decentralized deep mul-
tiagent policies that coordinate via a dif-
ferentiable communication channel. While
these policies are effective for many tasks,
interpretation of their induced communi-
cation strategies has remained a challenge.
Here we propose to interpret agents’ mes-
sages by translating them. Unlike in typi-
cal machine translation problems, we have
no parallel data to learn from. Instead we
develop a translation model based on the
insight that agent messages and natural lan-
guage strings mean the same thing
if they
induce the same belief about the world in a
listener
. We present theoretical guarantees
and empirical evidence that our approach
preserves both the semantics and pragmat-
ics of messages by ensuring that players
communicating through a translation layer
do not suffer a substantial loss in reward rel-
ative to players with a common language.

### ICML Modular Multitask Reinforcement Learning with Policy Sketches
Abstract
We describe a framework for multitask deep re-
inforcement learning guided by
policy sketches
.
Sketches annotate tasks with sequences of named
subtasks, providing information about high-level
structural relationships among tasks but not how
to  implement  them—specifically  not  providing
the  detailed  guidance  used  by  much  previous
work on learning policy abstractions for RL (e.g.
intermediate  rewards,  subtask  completion  sig-
nals,  or  intrinsic  motivations).    To  learn  from
sketches, we present a model that associates ev-
ery subtask with a modular subpolicy, and jointly
maximizes  reward  over  full  task-specific  poli-
cies by tying parameters across shared subpoli-
cies.  Optimization is accomplished via a decou-
pled actor–critic training objective that facilitates
learning  common  behaviors  from  multiple  dis-
similar reward functions.  We evaluate the effec-
tiveness  of  our  approach  in  three  environments
featuring  both  discrete  and  continuous  control,
and with sparse rewards that can be obtained only
after  completing  a  number  of  high-level  sub-
goals. Experiments show that using our approach
to learn policies guided by sketches gives better
performance than existing techniques for learn-
ing  task-specific  or  shared  policies,  while  nat-
urally inducing a library of interpretable primi-
tive behaviors that can be recombined to rapidly
adapt to new tasks.

### ACL Parsing with Traces: An O(n^4) Algorithm and a Structural Representation
Abstract
General  treebank  analyses  are  graph  struc-
tured,  but  parsers  are  typically  restricted  to
tree structures for efficiency and modeling rea-
sons.   We  propose  a  new  representation  and
algorithm for a class of graph structures that
is flexible enough to cover almost all treebank
structures, while still admitting efficient learn-
ing and inference.  In particular, we consider
directed, acyclic, one-endpoint-crossing graph
structures,   which  cover  most  long-distance
dislocation, shared argumentation, and similar
tree-violating  linguistic  phenomena.   We  de-
scribe how to convert phrase structure parses,
including traces, to our new representation in
a  reversible  manner.   Our  dynamic  program
uniquely decomposes structures, is sound and
complete, and covers 97.3%of the Penn En-
glish Treebank.  We also implement a proof-
of-concept parser that recovers a range of null
elements and trace types.

### EMNLP Reasoning About Pragmatics with Neural Listeners and Speakers
Abstract
We present a model for contrastively describ-
ing  scenes,  in  which  context-specific  behav-
ior  results  from  a  combination  of  inference-
driven pragmatics and learned semantics. Like
previous learned approaches to language gen-
eration,   our  model  uses  a  simple  feature-
driven architecture (here a pair of neural “lis-
tener” and “speaker” models) to ground lan-
guage in the world.  Like inference-driven ap-
proaches  to  pragmatics,  our  model  actively
reasons  about  listener  behavior  when  select-
ing utterances.  For training, our approach re-
quires only ordinary captions, annotated
without demonstration of the pragmatic behavior
the model ultimately exhibits. In human eval-
uations  on  a  referring  expression  game,  our
approach succeeds 81% of the time, compared
to 69% using existing techniques.

### ACL Learning-Based Single-Document Summarization with Compression and Anaphoricity Constraints
Abstract
We  present  a  discriminative  model  for
single-document summarization that
integrally    combines    compression    and
anaphoricity   constraints.
Our   model selects   textual   units   to   include   in   the summary  based  on  a  rich  set  of  sparse
features  whose  weights  are  learned  on  a
large  corpus.   We  allow  for  the  deletion
of  content  within  a  sentence  when  that
deletion is licensed by compression rules;
in our framework, these are implemented
as   dependencies   between   subsentential
units  of  text.
Anaphoricity  constraints then   improve   cross-sentence   coherence by  guaranteeing  that,  for  each  pronoun included  in  the  summary,  the  pronoun’s antecedent   is   included   as   well   or   the pronoun  is  rewritten  as  a  full  mention.
When  trained  end-to-end,  our  final  system
1 outperforms   prior   work   on   both
ROUGE as well as on human judgments
of linguistic quality.

### NAACL Capturing Semantic Similarity for Entity Linking with Convolutional Neural Networks
Abstract
A key challenge in entity linking is making ef-
fective  use  of  contextual  information  to  dis-
ambiguate mentions that might refer to differ-
ent entities in different contexts.  We present
a  model  that  uses  convolutional  neural  net-
works to capture semantic correspondence be-
tween a mention’s context and a proposed tar-
get entity. These convolutional networks oper-
ate at multiple granularities to exploit various
kinds of topic information, and their rich pa-
rameterization gives them the capacity to learn
which n-grams  characterize  different  topics.
We combine these networks with a sparse lin-
ear  model  to  achieve  state-of-the-art  perfor-
mance on multiple entity linking datasets, out-
performing  the  prior  systems  of  Durrett  and
Klein (2014) and Nguyen et al. (2014).

### NAACL Learning to Compose Neural Networks for Question Answering
Abstract
We describe a question answering model that
applies to both images and structured knowl-
edge  bases. The  model  uses  natural  lan-
guage strings to automatically assemble neu-
ral networks from a collection of composable
modules.   Parameters  for  these  modules  are
learned jointly with network-assembly param-
eters  via  reinforcement  learning,  with  only
(world,  question,  answer)  triples  as  supervi-
sion. Our approach, which we term a
dynamic neural module network
, achieves state-of-the-art results on benchmark datasets in both visual and structured domains.

### CVPR Neural Module Networks
Abstract
Visual  question  answering  is  fundamentally  compositional in nature—a question like
where is the dog?
shares substructure with questions like
what color is the dog?
and where is the cat?
This paper seeks to simultaneously exploit
the representational capacity of deep networks and the compositional linguistic structure of questions.  We describe a procedure for constructing and learning neural module net-
works, which compose collections of jointly-trained neural“modules” into deep networks for question answering. Our approach  decomposes  questions  into  their  linguistic  substructures, and uses these structures to dynamically instantiate modular networks (with reusable components for recognizing dogs, classifying colors, etc.).  The resulting compound  networks  are  jointly  trained.   We  evaluate  our  approach on two challenging datasets for visual question answering, achieving state-of-the-art results on both the VQA natural image dataset and a new dataset of complex ques-
tions about abstract shapes.

## Kristina Toutanova
在microsoft
### ACL A Nested Attention Neural Hybrid Model for Grammatical Error Correction
Abstract
Grammatical error correction (GEC) sys-
tems strive to correct both global errors in
word order and usage, and local errors in
spelling and inflection.  Further develop-
ing upon recent work on neural machine
translation, we propose a new hybrid neural
model with nested attention layers for GEC.
Experiments show that the new model can
effectively correct errors of both types by
incorporating word and character-level in-
formation, and that the model significantly
outperforms  previous  neural  models  for
GEC as measured on the standard CoNLL-
14  benchmark  dataset.   Further  analysis
also shows that the superiority of the pro-
posed model can be largely attributed to
the use of the nested attention mechanism,
which has proven particularly effective in
correcting local errors that involve small
edits in orthography.

### ACL NLP for Precision Medicine
Abstract
Past work in relation extraction has focused
on binary relations in single sentences.   Re-
cent NLP inroads in high-value domains have
sparked  interest  in  the  more  general  setting
of  extracting n-ary  relations  that  span  mul-
tiple sentences.   In this paper,  we explore a
general relation extraction framework based
on graph long short-term memory networks
(graph LSTMs) that can be easily extended to
cross-sentence n-ary relation extraction. The
graph formulation provides a unified way of
exploring different LSTM approaches and in-
corporating various intra-sentential and inter-
sentential  dependencies,  such  as  sequential,
syntactic,  and discourse relations.   A robust
contextual representation is learned for the en-
tities, which serves as input to the relation clas-
sifier. This simplifies handling of relations with
arbitrary arity, and enables multi-task learning
with related relations. We evaluate this frame-
work in two important precision medicine set-
tings, demonstrating its effectiveness with both
conventional supervised learning and distant
supervision.   Cross-sentence  extraction  pro-
duced larger knowledge bases. and multi-task
learning significantly improved extraction ac-
curacy. A thorough analysis of various LSTM
approaches yielded useful insight the impact
of linguistic analysis on extraction accuracy.

### ACL Compositional Learning of Embeddings for Relation Paths in Knowledge Base and Text
Abstract

Modeling relation paths has offered significant gains in embedding models for knowledge base (KB) completion. However, enumerating paths between two entities is very expensive, and existing approaches typically resort to approximation with a sampled subset. This problem is particularly acute when text is jointly modeled with KB relations and used to provide direct evidence for facts mentioned in it. In this paper, we propose the first exact dynamic programming algorithm which enables efficient incorporation of all relation paths of bounded length, while modeling both relation types and intermediate nodes in the compositional path representations. We conduct a theoretical analysis of the efficiency gain from the approach. Experiments on two datasets show that it addresses representational limitations in prior approaches and improves accuracy in KB completion.

### LREC E-TIPSY: Search Query Corpus Annotated with Entities, Term Importance, POS Tags, and Syntactic Parses
Abstract

We present E-TIPSY, a search query corpus annotated with named Entities, Term Importance, POS tags, and SYntactic parses. This corpus contains crowdsourced (gold) annotations of the three most important terms in each query. In addition, it contains automatically produced annotations of named entities, part-of-speech tags, and syntactic parses for the same queries. This corpus comes in two formats: (1) Sober Subset: annotations that two or more crowd workers agreed upon, and (2) Full Glass: all annotations. We analyze the strikingly low correlation between term importance and syntactic headedness, which invites research into effective ways of combining these different signals. Our corpus can serve as a benchmark for term importance methods aimed at improving search engine quality and as an initial step toward developing a dataset of gold linguistic analysis of web search queries. In addition, it can be used as a basis for linguistic inquiries into the kind of expressions used in search.

### EMNLP A Dataset and Evaluation Metrics for Abstractive Compression of Sentences and Short Paragraphs

Abstract
We   introduce   a   manually-created,    multi-
reference dataset for abstractive sentence and
short paragraph compression. First, we exam-
ine  the  impact  of  single-  and  multi-sentence
level  editing  operations  on  human  compres-
sion quality as found in this corpus.  We ob-
serve  that  substitution  and  rephrasing  opera-
tions are more meaning preserving than other
operations,  and  that  compressing  in  context
improves quality.  Second, we systematically
explore  the  correlations  between  automatic
evaluation  metrics  and  human  judgments  of
meaning  preservation  and  grammaticality  in
the compression task, and analyze the impact
of the linguistic units used and precision ver-
sus recall measures on the quality of the met-
rics.   Multi-reference  evaluation  metrics  are
shown to offer significant advantage over sin-
gle reference-based metrics.

## Roger Levy
cv http://www.mit.edu/~rplevy/roger-cv.pdf
好多脑与认知的东西
不是纯nlp
### Modeling Sources of Uncertainty in Spoken Word Learning.  Proceedings of the 39th Annual Meeting of the Cognitive Science Society. 
Abstract
In order to successfully learn the meaning of novel words such as bin or pin, language learners must not only be able to perceive relevant differences in the speech signal but also learn mappings from words to referents. Prior work in native (Stager
& Werker, 1997) and second (Pajak, Creel, & Levy, 2016) language acquisition has found that the ability to perceptually discriminate between words does not guarantee successful word learning. Put differently, learners fail to utilize knowledge that
they can otherwise use in speech perception. To explore possible mechanisms accounting for this phenomenon, we present a probabilistic model capable of inferring a word’s phonetic
form and of integrating the result with prior label/referent representations  in  memory.   By  analyzing  the  reasons  for  successes and failures when fitting different versions of the model
to experimental results from Pajak et al. (2016), we argue that a mechanism for spoken word learning needs to incorporate both perceptual uncertainty as well as additional, task-related sources of uncertainty to successfully account for the data.

### EACL Noisy-context surprisal as a human sentence processing cost model
Abstract
We  use  the  noisy-channel  theory  of  hu-
man  sentence  comprehension  to  develop
an   incremental   processing   cost   model
that   unifies   and   extends   key   features
of  expectation-based  and  memory-based
models. In  this  model,  which  we  call
noisy-context surprisal,  the  processing
cost  of  a  word  is  the  surprisal  of  the
word   given   a   noisy   representation   of
the  preceding  context. We  show  that
this   model   accounts   for   an   outstand-
ing  puzzle  in  sentence  comprehension,
language-dependent  structural  forgetting
effects  (Gibson  and  Thomas,  1999;  Va-
sishth  et  al.,  2010;  Frank  et  al.,  2016),
which are previously not well modeled by
either expectation-based or memory-based
approaches.   Additionally,  we  show  that
this  model  derives  and  generalizes  local-
ity  effects  (Gibson,  1998;  Demberg  and
Keller,  2008),  a  signature  prediction  of
memory-based  models.   We  give  corpus-
based  evidence  for  a  key  assumption  in
this derivation.

## Bill MacCartney
不是很活跃 
最近一篇是14年的
做nlp与stock的
### LREC On the Importance of Text Analysis for Stock Price Prediction
Abstract
We investigate the importance of text analysis for stock price prediction. In particular, we introduce a system that forecasts companies’
stock price changes (UP, DOWN, STAY) in response to financial events reported in 8-K documents. Our results indicate that using text
boosts prediction accuracy over
10%
(relative) over a strong baseline that incorporates many financially-rooted features. This impact is
most important in the short term (i.e., the next day after the financial event) but persists for up to five days.

##  Pi-Chuan Chang
在google工作
最后一篇是10年的

## Jenny Finkel
Engineering Manager + Tech Lead, Machine Learning Team

## Daniel Ramage


As of December 2011, I am a research scientist at Google in Mountain View. My PhD was advised by Christopher D. Manning in the Stanford Natural Language Processing Group, part of the Stanford Artificial Intelligence Lab.

Much of my dissertation work was with the interdisciplinary Mimir Project, focusing on building models and tools that can help us understand the world through the lens of the text people write about it. I develop techniques to analyze academic publications, cluster tagged web pages, and mine Twitter posts, among other applications.

My undergraduate degrees from MIT are in Computer Science and Math. Prior to Stanford, I spent some time at IBM's Zurich Research Lab working on data mining. In Fall 2009, I worked at Microsoft Research in Redmond with Susan Dumais. In summers past, I taught software engineering and project management to Palestinian and Israeli teenagers in Jerusalem through MEET.

### Communication-Efficient Learning of Deep Networks from Decentralized Data
不在搞nlp了好像

## Robert Munro
  
VP of Machine Learning at CrowdFlower Inc.
也不在学术界了

## Marie-Catherine de Marneffe
**I am an assistant professor in Linguistics at The Ohio State University.**

 Stanford University
2006 - 2012
Ph.D. Program in Linguistics

2004 - 2006
Visiting researcher (NLP Group, working with Christopher D. Manning)

Université catholique de Louvain (UCL), Belgium
2000 - 2002
Advanced Studies in Applied Sciences, Computing Science.
Thesis: (Magna cum laude)
Modalités temporelles et aléthiques pour la traduction d'un fragment de la langue française
(Temporal and mandatory modalities for translating a subset of French).

最近只有这一篇
### LREC Universal Stanford dependencies: A cross-linguistic typology
Abstract

Cross-linguistically consistent annotation is necessary for sound comparative evaluation and cross-lingual learning experiments. It is also useful for multilingual system development and comparative linguistic studies. Universal Dependencies is an open community effort to create cross-linguistically consistent treebank annotation for many languages within a dependency-based lexicalist framework. In this paper, we describe v1 of the universal guidelines, the underlying design principles, and the currently available treebanks for 33 languages.

## Jason Chuang
http://jason.chuang.info/

 I am currently a visiting research scientist at the Allen Institute for Artificial Intelligence.
I received my Ph. D. in Computer Science from Stanford University, working with Jeffrey Heer and Christopher D. Manning, and was previously a post-doctoral researcher at the University of Washington.

My research on data analytics focuses on the design of interactive visualizations and statistical models to enable people and algorithms to work in tandem to yield insights from complex data.

My work has appeared in top-tier venues in human-computer interaction (CHI, TOCHI), machine learning (ICML), and natural language processing (EMNLP), and has contributed to publications in multiple disciplines including social sciences and genetics research. 

最近一篇:
### UIST Predictive translation memory: a mixed-initiative system for human language translation

Abstract

The standard approach to computer-aided language translation is post-editing: a machine generates a single translation that a human translator corrects. Recent studies have shown this simple technique to be surprisingly effective, yet it underutilizes the complementary strengths of precision-oriented humans and recall-oriented machines. We present Predictive Translation Memory, an interactive, mixed-initiative system for human language translation. Translators build translations incrementally by considering machine suggestions that update according to the user's current partial translation. In a large-scale study, we find that professional translators are slightly slower in the interactive mode yet produce slightly higher quality translations despite significant prior experience with the baseline post-editing condition. Our analysis identifies significant predictors of time and quality, and also characterizes interactive aid usage. Subjects entered over 99% of characters via interactive aids, a significantly higher fraction than that shown in previous work.

## Mengqiu Wang
I graduated in Spring 2014 from the PhD program in the Computer Science Department of Stanford University. My advisor is Prof. Chris Manning, and I work in the NLP Lab at Stanford. Here is a picture of me and Chris at the graduation ceremony :) Other members of my dissertation committee are Dan Jurafsky, Percy Liang, John DeNero, and Lester Mackey.
Prior to Stanford, I was a CS master's student at Carnegie Mellon University,
working with Teruko Mitamura and Noah Smith on Open-Domain Question Answering.

Education

Ph.D. in Computer Science 	Stanford University 	2007-2014 (on leave:
2008-11)
M.S. in Computer Science 	Carnegie Mellon University 	2005-2007
Exchange student 	University of Texas at Austin 	2003-2004
B.S. in Computer Science 	University of Otago 	2001-2004
B.App.S. in Telecom
(1st class honours) 	University of Otago 	2001-2005
Work Experience

Fellow 	XSeed Capital 	2013.2-2014.3
Software Engineer 	Twitter Inc. 	2010.6-2012.1
Data Scientist 	Alibaba Cloud Computing 	2009.5-2009.12
Data Scientist Intern 	Facebook Inc. 	2008.6-2008.9

最近的paper是14年的
### ACL  Two Knives Cut Better Than One: Chinese Word Segmentation with Dual Decomposition
Abstract
There  are  two  dominant  approaches  to
Chinese  word  segmentation:  word-based
and character-based models, each with re-
spective strengths.  Prior work has shown
that  gains  in  segmentation  performance
can  be  achieved  from  combining  these
two types of models; however, past efforts
have  not  provided  a  practical  technique
to  allow  mainstream  adoption.   We  pro-
pose  a  method  that  effectively  combines
the strength of both segmentation schemes
using  an  efficient  dual-decomposition  al-
gorithm  for  joint  inference.   Our  method
is  simple  and  easy  to  implement.
Ex-
periments  on  SIGHAN  2003  and  2005
evaluation datasets show that our method
achieves  the  best  reported  results  to  date
on 6 out of 7 datasets.

### TACL Cross-lingual Projected Expectation Regularization for Weakly Supervised Learning
Abstract
We consider a multilingual weakly supervised
learning scenario where knowledge from an-
notated  corpora  in  a  resource-rich  language
is transferred via bitext to guide the learning
in  other  languages.   Past  approaches  project
labels across bitext and use them as features
or  gold  labels  for  training.
We  propose  a
new method that projects model expectations
rather  than  labels,  which  facilities  transfer
of model uncertainty across language bound-
aries.  We encode expectations as constraints
and  train  a  discriminative  CRF  model  using
Generalized  Expectation  Criteria  (Mann  and
McCallum,  2010).
Evaluated  on  standard
Chinese-English  and  German-English  NER
datasets,  our method demonstrates F
1
scores
of  64%  and  60%  when  no  labeled  data  is
used.   Attaining  the  same  accuracy  with  su-
pervised CRFs requires 12k and 1.5k labeled
sentences. Furthermore, when combined with
labeled  examples,  our  method  yields  signifi-
cant improvements over state-of-the-art super-
vised methods, achieving best reported num-
bers to date on Chinese OntoNotes and Ger-
man CoNLL-03 datasets.

## Richard Socher
http://www.socher.org/
Aloha, I'm the chief scientist at Salesforce and an adjunct professor at Stanford's computer science department. Previously, I was the founder and CEO/CTO of MetaMind which was acquired by Salesforce in 2016. I enjoy improving the state of the art in AI through research (deep learning, natural language processing and computer vision) and making AI easily accessible to everyone. In 2014, I got my PhD in the CS Department at Stanford and have been teaching there since, see CS224n - NLP with Deep Learning. This Forbes article has more info about my bio. This New York Times article covers one project from Salesforce Research. I'm on Twitter and like adventures, traveling and photography. 
这个人学术相当多

### Seq2SQL: Generating Structured Queries from Natural Language using Reinforcement Learning, TechCrunch, Venturebeat 
A significant amount of the world's knowledge is stored in relational databases. However, the ability for users to retrieve facts from a database is limited due to a lack of understanding of query languages such as SQL. We propose Seq2SQL, a deep neural network for translating natural language questions to corresponding SQL queries. Our model leverages the structure of SQL queries to significantly reduce the output space of generated queries. Moreover, we use rewards from in-the-loop query execution over the database to learn a policy to generate unordered parts of the query, which we show are less suitable for optimization via cross entropy loss. In addition, we will publish WikiSQL, a dataset of 87726 hand-annotated examples of questions and SQL queries distributed across 26375 tables from Wikipedia. This dataset is required to train our model and is an order of magnitude larger than comparable datasets. By applying policy-based reinforcement learning with a query execution environment to WikiSQL, our model Seq2SQL outperforms attentional sequence to sequence models, improving execution accuracy from 35.9% to 60.3% and logical form accuracy from 23.4% to 49.2%. 

### Learned in Translation: Contextualized Word Vectors MIT Tech Review 

Abstract
Computer vision has benefited from initializing multiple deep layers with weights
pretrained on large supervised training sets like ImageNet. Natural language pro-
cessing (NLP) typically sees initialization of only the lowest layer of deep models
with pretrained word vectors.  In this paper, we use a deep LSTM encoder from
an attentional sequence-to-sequence model trained for machine translation (MT)
to contextualize word vectors. We show that adding these context vectors (CoVe)
improves performance over using only unsupervised word and character vectors on
a wide variety of common NLP tasks: sentiment analysis (SST, IMDb), question
classification (TREC), entailment (SNLI), and question answering (SQuAD). For
fine-grained sentiment analysis and entailment, CoVe improves performance of our
baseline models to the state of the art

###  Regularizing and Optimizing LSTM Language Models
Recurrent neural networks (RNNs), such as long short-term memory networks (LSTMs), serve as a fundamental building block for many sequence learning tasks, including machine translation, language modeling, and question answering. In this paper, we consider the specific problem of word-level language modeling and investigate strategies for regularizing and optimizing LSTM-based models. We propose the weight-dropped LSTM which uses DropConnect on hidden-to-hidden weights as a form of recurrent regularization. Further, we introduce NT-ASGD, a variant of the averaged stochastic gradient method, wherein the averaging trigger is determined using a non-monotonic condition as opposed to being tuned by the user. Using these and other regularization strategies, we achieve state-of-the-art word level perplexities on two data sets: 57.3 on Penn Treebank and 65.8 on WikiText-2. In exploring the effectiveness of a neural cache in conjunction with our proposed model, we achieve an even lower state-of-the-art perplexity of 52.8 on Penn Treebank and 52.0 on WikiText-2. 

### Revisiting Activation Regularization for Language RNNs ICML
Recurrent neural networks (RNNs) serve as a fundamental building block for many sequence tasks across natural language processing. Recent research has focused on recurrent dropout techniques or custom RNN cells in order to improve performance. Both of these can require substantial modifications to the machine learning model or to the underlying RNN configurations. We revisit traditional regularization techniques, specifically L2 regularization on RNN activations and slowness regularization over successive hidden states, to improve the performance of RNNs on the task of language modeling. Both of these techniques require minimal modification to existing RNN architectures and result in performance improvements comparable or superior to more complicated regularization techniques or custom cell architectures. These regularization techniques can be used without any modification on optimized LSTM implementations such as the NVIDIA cuDNN LSTM. 

### A Joint Many-Task Model: Growing a Neural Network for Multiple NLP Tasks EMNLP
Transfer and multi-task learning have traditionally focused on either a single source-target pair or very few, similar tasks. Ideally, the linguistic levels of morphology, syntax and semantics would benefit each other by being trained in a single model. We introduce a joint many-task model together with a strategy for successively growing its depth to solve increasingly complex tasks. Higher layers include shortcut connections to lower-level task predictions to reflect linguistic hierarchies. We use a simple regularization term to allow for optimizing all model weights to improve one task's loss without exhibiting catastrophic interference of the other tasks. Our single end-to-end model obtains state-of-the-art or competitive results on five different tasks from tagging, parsing, relatedness, and entailment tasks. 

### A Deep Reinforced Model for Abstractive Summarization 
Forbes, MIT Tech Review, TechCrunch ] 

Attentional, RNN-based encoder-decoder models for abstractive summarization have achieved good performance on short input and output sequences. However, for longer documents and summaries, these models often include repetitive and incoherent phrases. We introduce a neural network model with intra-attention and a new training method. This method combines standard supervised word prediction and reinforcement learning (RL). Models trained only with the former often exhibit "exposure bias" -- they assume ground truth is provided at each step during training. However, when standard word prediction is combined with the global sequence prediction training of RL the resulting summaries become more readable. We evaluate this model on the CNN/Daily Mail and New York Times datasets. Our model obtains a 41.16 ROUGE-1 score on the CNN/Daily Mail dataset, a 5.7 absolute points improvement over previous state-of-the-art models. It also performs well as the first abstractive model on the New York Times corpus. Human evaluation also shows that our model produces higher quality summaries. 

### Knowing When to Look: Adaptive Attention via A Visual Sentinel for Image Captioning CVPR
Attention-based neural encoder-decoder frameworks have been widely adopted for image captioning. Most methods force visual attention to be active for every generated word. However, the decoder likely requires little to no visual information from the image to predict non-visual words such as "the" and "of". Other words that may seem visual can often be predicted reliably just from the language model e.g., "sign" after "behind a red stop" or "phone" following "talking on a cell". In this paper, we propose a novel adaptive attention model with a visual sentinel. At each time step, our model decides whether to attend to the image (and if so, to which regions) or to the visual sentinel. The model decides whether to attend to the image and where, in order to extract meaningful information for sequential word generation. We test our method on the COCO image captioning 2015 challenge dataset and Flickr30K. Our approach sets the new state-of-the-art by a significant margin.

### Dynamic Coattention Networks For Question Answering
ICLR
Several deep learning models have been proposed for question answering. However, due to their single-pass nature, they have no way to recover from local maxima corresponding to incorrect answers. To address this problem, we introduce the Dynamic Coattention Network (DCN) for question answering. The DCN first fuses co-dependent representations of the question and the document in order to focus on relevant parts of both. Then a dynamic pointing decoder iterates over potential answer spans. This iterative procedure enables the model to recover from initial local maxima corresponding to incorrect answers. On the Stanford question answering dataset, a single DCN model improves the previous state of the art from 71.0% F1 to 75.9%, while a DCN ensemble obtains 80.4% F1. 

### Quasi-Recurrent Neural Networks ICLR
Recurrent neural networks are a powerful tool for modeling sequential data, but the dependence of each timestep's computation on the previous timestep's output limits parallelism and makes RNNs unwieldy for very long sequences. We introduce quasi-recurrent neural networks (QRNNs), an approach to neural sequence modeling that alternates convolutional layers, which apply in parallel across timesteps, and a minimalist recurrent pooling function that applies in parallel across channels. Despite lacking trainable recurrent layers, stacked QRNNs have better predictive accuracy than stacked LSTMs of the same hidden size. Due to their increased parallelism, they are up to 16 times faster at train and test time. Experiments on language modeling, sentiment classification, and character-level neural machine translation demonstrate these advantages and underline the viability of QRNNs as a basic building block for a variety of sequence tasks. 

### Tying Word Vectors and Word Classifiers: A Loss Framework for Language Modeling ICLR
Recurrent neural networks have been very successful at predicting sequences of words in tasks such as language modeling. However, all such models are based on the conventional classification framework, where the model is trained against one-hot targets, and each word is represented both as an input and as an output in isolation. This causes inefficiencies in learning both in terms of utilizing all of the information and in terms of the number of parameters needed to train. We introduce a novel theoretical framework that facilitates better learning in language modeling, and show that our framework leads to tying together the input embedding and the output projection matrices, greatly reducing the number of trainable variables. Our framework leads to state of the art performance on the Penn Treebank with a variety of network models

### Pointer Sentinel Mixture Models,  ICLR
Recent neural network sequence models with softmax classifiers have achieved their best language modeling performance only with very large hidden states and large vocabularies. Even then they struggle to predict rare or unseen words even if the context makes the prediction unambiguous. We introduce the pointer sentinel mixture architecture for neural sequence models which has the ability to either reproduce a word from the recent context or produce a word from a standard softmax classifier. Our pointer sentinel-LSTM model achieves state of the art language modeling performance on the Penn Treebank (70.9 perplexity) while using far fewer parameters than a standard softmax LSTM. In order to evaluate how well language models can exploit longer contexts and deal with more realistic vocabularies and larger corpora we also introduce the freely available WikiText corpus

### A Way out of the Odyssey: Analyzing and Combining Recent Insights for LSTMs
LSTMs have become a basic building block for many deep NLP models. In recent years, many improvements and variations have been proposed for deep sequence models in general, and LSTMs in particular. We propose and analyze a series of augmentations and modifications to LSTM networks resulting in improved performance for text classification datasets. We observe compounding improvements on traditional LSTMs using Monte Carlo test-time model averaging, average pooling, and residual connections, along with four other suggested modifications. Our analysis provides a simple, reliable, and high quality baseline model. 

### MetaMind Neural Machine Translation System for WMT 2016
Abstract
Neural  Machine  Translation  (NMT)  sys-
tems,   introduced   only   in   2013,   have
achieved  state  of  the  art  results  in  many
MT  tasks.
MetaMind’s  submissions  to
WMT ’16 seek to push the state of the art
in one such task, English
→
German news-
domain translation.  We integrate promis-
ing recent developments in NMT, includ-
ing subword splitting and back-translation
for  monolingual  data  augmentation,  and
introduce  the  Y-LSTM,  a  novel  neural
translation architecture.

### Dynamic Memory Networks for Visual and Textual Question Answering ICML
Neural network architectures with memory and attention mechanisms exhibit certain reasoning capabilities required for question answering. One such architecture, the dynamic memory network (DMN), obtained high accuracy on a variety of language tasks. However, it was not shown whether the architecture achieves strong results for question answering when supporting facts are not marked during training or whether it could be applied to other modalities such as images. Based on an analysis of the DMN, we propose several improvements to its memory and input modules. Together with these changes we introduce a novel input module for images in order to be able to answer visual questions. Our new DMN+ model improves the state of the art on both the Visual Question Answering dataset and the \babi-10k text question-answering dataset without supporting fact supervision. 

### Ask Me Anything: Dynamic Memory Networks for Natural Language Processing ICML
Most tasks in natural language processing can be cast into question answering (QA) problems over language input. We introduce the dynamic memory network (DMN), a neural network architecture which processes input sequences and questions, forms episodic memories, and generates relevant answers. Questions trigger an iterative attention process which allows the model to condition its attention on the inputs and the result of previous iterations. These results are then reasoned over in a hierarchical recurrent sequence model to generate answers. The DMN can be trained end-to-end and obtains state-of-the-art results on several types of tasks and datasets: question answering (Facebook's bAbI dataset), text classification for sentiment analysis (Stanford Sentiment Treebank) and sequence modeling for part-of-speech tagging (WSJ-PTB). The training for these different tasks relies exclusively on trained word vector representations and input-question-answer triplets

## Spence Green
http://www.spencegreen.com/
I recently started Lilt with John DeNero. We’re building an interactive translation environment.

Before that, I was a Ph.D student in Computer Science at Stanford University. I worked with Chris Manning and Jeff Heer on mixed-initiative translation. I graduated in 2014.

I co-organized the first Workshop on Interactive Language Learning, Visualization, and Interfaces held at ACL 2014.
最近在公司里做事

### Models and Inference for Prefix-Constrained Machine Translation. In ACL
Abstract
We apply phrase-based and neural models
to a core task in interactive machine trans-
lation: suggesting how to complete a par-
tial translation. For the phrase-based sys-
tem, we demonstrate improvements in sug-
gestion quality using novel objective func-
tions, learning techniques, and inference
algorithms tailored to this task. Our con-
tributions include new tunable metrics, an
improved beam search strategy, an
n
-best
extraction method that increases sugges-
tion diversity, and a tuning procedure for a
hierarchical joint model of alignment and
translation. The combination of these tech-
niques improves next-word suggestion accu-
racy dramatically from 28.5% to 41.2% in
a large-scale English-German experiment.
Our recurrent neural translation system in-
creases accuracy yet further to 53.0%, but
inference is two orders of magnitude slower.
Manual error analysis shows the strengths
and weaknesses of both approaches

### Hierarchical Incremental Adaptation for Statistical Machine Translation. In EMNLP
Abstract
We present an incremental adaptation ap-
proach for statistical machine translation
that maintains a flexible hierarchical do-
main structure within a single consistent
model. Both weights and rules are updated
incrementally on a stream of post-edits. Our
multi-level domain hierarchy allows the sys-
tem to adapt simultaneously towards local
context at different levels of granularity, in-
cluding genres and individual documents.
Our experiments show consistent improve-
ments in translation quality from all com-
ponents of our approach

## Sonal Gupta
http://www.cs.stanford.edu/people/sonal/
I am a final year PhD student in Computer Science at Stanford University. I work with Christopher D. Manning in the Stanford Natural Language Processing (NLP) group and closely collaborate with the Interactive Data Lab under Jeffrey Heer.


My research interests are building natural language processing and data analysis systems using machine learning tools. Recently, my work has focused on practical and interpretable information extraction systems (such as extracting entities and relations from text) that use only a few examples (or prototypes) as supervision.


I have collaborated with Diana MacLean, Sanjay Kairam, and Jason Chuang on data analysis of medical forums, building effective automated and manual text annotation tools, and evaluation of topic models, respectively. For my Master's thesis at UT Austin, I worked on combining NLP and computer vision with Ray Mooney and Kristen Grauman.
没有近两年的
### Distributed Representations of Words to Guide Bootstrapped Entity Classifiers NAACL

Abstract
Bootstrapped classifiers iteratively generalize
from a few seed examples or prototypes to
other examples of target labels.  However,
sparseness of language and limited supervi-
sion make the task difficult. We address this
problem by using distributed vector represen-
tations of words to aid the generalization. We
use the word vectors to expand entity sets
used for training classifiers in a bootstrapped
pattern-based entity extraction system.  Our
experiments show that the classifiers trained
with the expanded sets perform better on en-
tity extraction from four online forums, with
30% F1 improvement on one forum. The re-
sults suggest that distributed representations
can provide good directions for generalization
in a bootstrapping system.

## Angel Xuan Chang
这个人是搞text 2 3D的
http://angelxuanchang.github.io/

### Cross-modal Attribute Transfer for Rescaling 3D Models
Abstract
We  present  an  algorithm  for  transferring  physical  at-
tributes between webpages and 3D shapes. We crawl prod-
uct catalogues and other webpages with structured meta-
data containing physical attributes such as dimensions and
weights.
Then  we  transfer  physical  attributes  between
shapes and real-world objects using a joint embedding of
images and 3D shapes and a view-based weighting and as-
pect ratio filtering scheme for instance-level linking of 3D
models  and  real-world  counterpart  objects.   We  evaluate
our approach on a large-scale dataset of unscaled 3D mod-
els, and show that we outperform prior work on rescaling
3D models that considers only category-level size priors.

### Matterport3D: Learning from RGB-D Data in Indoor Environments 
Abstract
Access to large, diverse RGB-D datasets is critical for
training RGB-D scene understanding algorithms. However,
existing datasets still cover only a limited number of views
or  a  restricted  scale  of  spaces.   In  this  paper,  we  intro-
duce Matterport3D, a large-scale RGB-D dataset contain-
ing 10,800 panoramic views from 194,400 RGB-D images
of 90 building-scale scenes.  Annotations are provided with
surface reconstructions, camera poses, and 2D and 3D se-
mantic  segmentations.   The  precise  global  alignment  and
comprehensive, diverse panoramic set of views over entire
buildings enable a variety of supervised and self-supervised
computer  vision  tasks,  including  keypoint  matching,  view
overlap prediction, normal prediction from color, semantic
segmentation, and region classification.

### Learning Where to Look: Data-Driven Viewpoint Set Selection for 3D Scenes 
Abstract
The  use  of  rendered  images,  whether  from  completely
synthetic datasets or from 3D reconstructions,  is increas-
ingly prevalent in vision tasks. However, little attention has
been given to how the selection of viewpoints affects the per-
formance of rendered training sets.  In this paper, we pro-
pose a data-driven approach to view set selection. Given a
set of example images, we extract statistics describing their
contents and generate a set of views matching the distribu-
tion of those statistics. Motivated by semantic segmentation
tasks,  we  model  the  spatial  distribution  of  each  semantic
object category within an image view volume. We provide a
search algorithm that generates a sampling of likely candi-
date views according to the example distribution, and a set
selection algorithm that chooses a subset of the candidates
that jointly cover the example distribution. Results of exper-
iments with these algorithms on SUNCG indicate that they
are indeed able to produce view distributions similar to an
example set from NYUDv2 according to the earth mover’s
distance.  Furthermore, the selected views improve perfor-
mance on semantic segmentation compared to alternative
view selection algorithms.

### ScanNet: Richly-annotated 3D Reconstructions of Indoor Scenes CVPR
Abstract
A key requirement for leveraging supervised deep learn-
ing  methods  is  the  availability  of  large,  labeled  datasets.
Unfortunately, in the context of RGB-D scene understand-
ing, very little data is available – current datasets cover a
small range of scene views and have limited semantic an-
notations.  To address this issue, we introduce ScanNet, an
RGB-D video dataset containing 2.5M views in 1513 scenes
annotated with 3D camera poses, surface reconstructions,
and semantic segmentations.   To collect this data,  we de-
signed an easy-to-use and scalable RGB-D capture system
that includes automated surface reconstruction and crowd-
sourced semantic annotation. We show that using this data
helps  achieve  state-of-the-art  performance  on  several  3D
scene understanding tasks, including 3D object classifica-
tion, semantic voxel labeling, and CAD model retrieval.

### Semantic Scene Completion from a Single Depth Image  CVPR
Abstract
This paper focuses on semantic scene completion, a task
for producing a complete 3D voxel representation of vol-
umetric  occupancy  and  semantic  labels  for  a  scene  from
a single-view depth map observation.   Previous work has
considered scene completion and semantic labeling of depth
maps separately. However, we observe that these two prob-
lems are tightly intertwined.   To leverage the coupled na-
ture  of  these  two  tasks,  we  introduce  the  semantic  scene
completion network (
SSCNet
), an end-to-end 3D convolu-
tional network that takes a single depth image as input and
simultaneously outputs occupancy and semantic labels for
all voxels in the camera view frustum.  Our network uses a
dilation-based 3D context module to efficiently expand the
receptive field and enable 3D context learning. To train our
network, we construct SUNCG - a manually created large-
scale  dataset  of  synthetic  3D  scenes  with  dense  volumet-
ric annotations. Our experiments demonstrate that the joint
model outperforms methods addressing each task in isola-
tion and outperforms alternative approaches on the seman-
tic scene completion task. The dataset, code and pretrained
model will be available online upon acceptance.

### SceneSuggest: Context-driven 3D Scene Design 
We present SceneSuggest: an interactive 3D scene design system providing context-driven suggestions for 3D model retrieval and placement. Using a point-and-click metaphor we specify regions in a scene in which to automatically place and orient relevant 3D models. Candidate models are ranked using a set of static support, position, and orientation priors learned from 3D scenes. We show that our suggestions enable rapid assembly of indoor scenes. We perform a user study comparing suggestions to manual search and selection, as well as to suggestions with no automatic orientation. We find that suggestions reduce total modeling time by 32%, that orientation priors reduce time spent re-orienting objects by 27%, and that context-driven suggestions reduce the number of text queries by 50%. 

### SceneSeer: 3D Scene Design with Natural Language 
Designing 3D scenes is currently a creative task that requires significant expertise and effort in using complex 3D design interfaces. This effortful design process starts in stark contrast to the easiness with which people can use language to describe real and imaginary environments. We present SceneSeer: an interactive text to 3D scene generation system that allows a user to design 3D scenes using natural language. A user provides input text from which we extract explicit constraints on the objects that should appear in the scene. Given these explicit constraints, the system then uses a spatial knowledge base learned from an existing database of 3D scenes and 3D object models to infer an arrangement of the objects forming a natural scene matching the input description. Using textual commands the user can then iteratively refine the created scene by adding, removing, replacing, and manipulating objects. We evaluate the quality of 3D scenes generated by SceneSeer in a perceptual evaluation experiment where we compare against manually designed scenes and simpler baselines for 3D scene generation. We demonstrate how the generated scenes can be iteratively refined through simple natural language commands. 

### Eviza: A Natural Language Interface for Visual Analysis  UIST
ABSTRACT
Natural language interfaces for visualizations have emerged as a
promising new way of interacting with data and performing ana-
lytics. Many of these systems have fundamental limitations. Most
return minimally interactive visualizations in response to queries
and often require experts to perform modeling for a set of predicted
user queries before the systems are effective.   Eviza provides a
natural language interface for an interactive query
dialog with an existing visualization rather than starting from a blank sheet and asking closed-ended questions that return a single text answer or static visualization. The system employs a probabilistic grammar based
approach with predefined rules that are dynamically updated based
on the data from the visualization, as opposed to computationally
intensive deep learning or knowledge based approaches

###  PiGraphs: Learning Interaction Snapshots from Observations SIGGRAPH
Abstract

We learn a probabilistic model connecting human poses and arrangements of object geometry from real-world observations of interactions collected with commodity RGB-D sensors. This model is encoded as a set of prototypical interaction graphs (PiGraphs), a human-centric representation capturing physical contact and visual attention linkages between 3D geometry and human body parts. We use this encoding of the joint probability distribution over pose and geometry during everyday interactions to generate interaction snapshots, which are static depictions of human poses and relevant objects during human-object interactions. We demonstrate that our model enables a novel human-centric understanding of 3D content and allows for jointly generating 3D scenes and interaction poses given terse high-level specifications, natural language, or reconstructed real-world scene constraints. 

### Evaluating the word-expert approach for Named-Entity Disambiguation 

Abstract
Named Entity Disambiguation (NED) is the task of linking a named-entity men-
tion to an instance in a knowledge-base, typically Wikipedia.  This task is closely
related to word-sense disambiguation (WSD), where the supervised word-expert
approach has prevailed.  In this work we present, for the first time, the results of
the word-expert approach to NED, where one classifier is built for each target en-
tity mention string.  The resources necessary to build the system, a dictionary and
a set of training instances, have been automatically derived from Wikipedia.  We
provide empirical evidence of the value of this approach, as well as a study of the
differences between WSD and NED, including ambiguity and synonymy statistics.


## Gabor Angeli 
http://cs.stanford.edu/~angeli/

### Position-aware Attention and Supervised Data Improve Slot Filling EMNLP
Organized relational knowledge in the form of “knowledge graphs” is important for many applications. However, the ability to populate knowledge bases with facts automatically extracted from documents has improved frustratingly slowly. This paper simultaneously addresses two issues that have held back prior work. We first propose an effective new model, which combines an LSTM sequence model with a form of entity position-aware attention that is better suited to relation extraction. Then we build TACRED, a large (119,474 examples) supervised relation extraction dataset, obtained via crowdsourcing and targeted towards TAC KBP relations. The combination of better supervised data and a more appropriate high-capacity model enables much better relation extraction performance. When the model trained on this new dataset replaces the previous relation extraction component of the best TAC KBP 2015 slot filling system, its F1 score increases markedly from 22.2% to 26.7%. 

### Learning Open Domain Knowledge From Text
The increasing availability of large text corpora holds the promise of acquiring an unprecedented amount of knowledge from this text. However, current techniques are either special- ized to particular domains or do not scale to large corpora. This dissertation develops a new technique for learning open-domain knowledge from unstructured web-scale text corpora. A first application aims to capture common sense facts: given a candidate statement about the world and a large corpus of known facts, is the statement likely to be true? We appeal to a probabilistic relaxation of natural logic – a logic which uses the syntax of natural language as its logical formalism – to define a search problem from the query statement to its appropriate support in the knowledge base over valid (or approximately valid) logical inference steps. We show a 4x improvement in recall over lemmatized lookup for querying common sense facts, while maintaining above 90% precision. This approach is extended to handle longer, more complex premises by segmenting these utterances into a set of atomic statements entailed through natural logic. We evaluate this system in isolation by using it as the main component in an Open Information Extrac- tion system, and show that it achieves a 3% absolute improvement in F1 compared to prior work on a competitive knowledge base population task. A remaining challenge is elegantly handling cases where we could not find a supporting premise for our query. To address this, we create an analogue of an evaluation function in gameplaying search: a shallow lexical classifier is folded into the search program to serve as a heuristic function to assess how likely we would have been to find a premise. Results on answering 4thgrade science questions show that this method improves over both the classifier in isolation and a strong IR baseline, and outperforms prior work on the task. 

### Combining Natural Logic and Shallow Reasoning for Question Answering.
Broad domain question answering is often difficult in the absence of structured knowledge bases, and can benefit from shallow lexical methods (broad coverage) and logical reasoning (high precision). We propose an approach for incorporating both of these signals in a unified framework based on natural logic. We extend the breadth of inferences afforded by natural logic to include relational entailment (e.g., buy → own) and meronymy (e.g., a person born in a city is born the city’s country). Furthermore, we train an evaluation function – akin to gameplaying – to evaluate the expected truth of candidate premises on the fly. We evaluate our approach on answering multiple choice science questions, , achieving strong results on the dataset. 

### Evaluating Word Embeddings Using a Representative Suite of Practical Tasks
Word embeddings are now widely used in natural language understanding tasks requiring sophisticated semantic information. However, the quality of new embedding methods is usually evaluated based on relatively simple word similarity benchmarks. We propose evaluating word embeddings by using them as features in simple models for a suite of popular downstream tasks. This gives a realistic view of the utility of the embeddings in realworld settings. The selection of diverse set of tasks, including both semantic and syntactic tasks, facilitates qualitative analysis of the strengths and weaknesses of the embeddings. The use of simple models allows us to format this evaluation as a standardized script that can be made available publicly, and which can be run in a few hours. 

## Sam Bowman
https://www.nyu.edu/projects/bowman/



2016–
Assistant Professor
Department of Linguistics & Center for Data Science (joint)
Department of Computer Science, Courant Institute (affiliate)
ML² Group/CILVR Lab (primary research groups)
Semantics Group (informal research group/seminar)
New York University

2011–2016
PhD Student
NLP Group & Department of Linguistics
Stanford University
Advisors: Chris Manning and Chris Potts

I study artificial neural network models for natural language understanding. You can reach me at bowman@nyu.edu.

### Adina Williams, Andrew Drozdov, and Samuel R. Bowman. Learning to parse from a semantic objective: It works. Is it syntax? Unpublished manuscript. 2017.
Recent work on reinforcement learning and other gradient estimators for latent tree learning has made it possible to train neural networks that learn to both parse a sentence and use the resulting parse to interpret the sentence, all without exposure to ground-truth parse trees at training time. Surprisingly, these models often perform better at sentence understanding tasks than models that use parse trees from conventional parsers. This paper aims to investigate what these latent tree learning models learn. We replicate two such models in a shared codebase and find that (i) they do outperform baselines on sentence classification, but that (ii) their parsing strategies are not especially consistent across random restarts, (iii) the parses they produce tend to be shallower than PTB parses, and (iv) these do not resemble those of PTB or of any other recognizable semantic or syntactic grammar formalism. 

### Nikita Nangia, Adina Williams, Angeliki Lazaridou, and Samuel R. Bowman. The RepEval 2017 Shared Task: Multi-Genre Natural Language Inference with Sentence Representations. Proceedings of RepEval 2017: The Second Workshop on Evaluating Vector Space Representations for NLP. 2017.
Abstract
This  paper  presents  the  results  of  the
RepEval  2017  Shared  Task,  which  eval-
uated  neural  network  sentence  represen-
tation   learning   models   on   the   Multi-
Genre  Natural  Language  Inference  cor-
pus  (MultiNLI)  recently  introduced  by
Williams  et  al.  (2017).    All  of  the  five
participating  teams  beat  the  bidirectional
LSTM   (BiLSTM)   and   continuous   bag
of  words  baselines  reported  in  Williams
et al..  The best single model used stacked
BiLSTMs with residual connections to ex-
tract sentence features and reached 74.5%
accuracy  on  the  genre-matched  test  set.
Surprisingly, the results of the competition
were  fairly  consistent  across  the  genre-
matched  and  genre-mismatched  test  sets,
and  across  subsets  of  the  test  data  rep-
resenting  a  variety  of  linguistic  phenom-
ena,  suggesting  that  all  of  the  submit-
ted  systems  learned  reasonably  domain-
independent  representations  for  sentence
meaning.

###Yichen Gong and Samuel R. Bowman. Ruminating Reader: Reasoning with Gated Multi-Hop Attention. Unpublished manuscript. 2017.
To answer the question in machine comprehension (MC) task, the models need to establish the interaction between the question and the context. To tackle the problem that the single-pass model cannot reflect on and correct its answer, we present Ruminating Reader. Ruminating Reader adds a second pass of attention and a novel information fusion component to the Bi-Directional Attention Flow model (BiDAF). We propose novel layer structures that construct an query-aware context vector representation and fuse encoding representation with intermediate representation on top of BiDAF model. We show that a multi-hop attention mechanism can be applied to a bi-directional attention structure. In experiments on SQuAD, we find that the Reader outperforms the BiDAF baseline by a substantial margin, and matches or surpasses the performance of all other published systems. 

###Yacine Jernite, Samuel R. Bowman, and David Sontag. Discourse-Based Objectives for Fast Unsupervised Sentence Representation Learning. Unpublished manuscript. 2017.
This work presents a novel objective function for the unsupervised training of neural network sentence encoders. It exploits signals from paragraph-level discourse coherence to train these models to understand text. Our objective is purely discriminative, allowing us to train models many times faster than was possible under prior methods, and it yields models which perform well in extrinsic evaluations. 

###Adina Williams, Nikita Nangia, and Samuel R. Bowman. A Broad-Coverage Challenge Corpus for Sentence Understanding through Inference (corpus page). Unpublished manuscript. 2017.
Abstract
This   paper   introduces   the   Multi-Genre
Natural  Language  Inference  (MultiNLI)
corpus,  a  dataset  designed  for  use  in  the
development  and  evaluation  of  machine
learning models for sentence understand-
ing. In addition to being one of the largest
corpora  available  for  the  task  of  NLI,  at
433k examples, this corpus improves upon
available resources in its coverage;  it of-
fers data from ten distinct genres of written
and spoken English—making it possible to
evaluate  systems  on  nearly  the  full  com-
plexity of the language—and it offers an
explicit setting for the evaluation of cross-
genre domain adaptation.

###{Samuel R. Bowman, Luke Vilnis}, Oriol Vinyals, Andrew M. Dai, Rafal Jozefowicz, and Samy Bengio. Generating Sentences from a Continuous Space. Proceedings of CoNLL. 2016.
Abstract
The  standard  recurrent  neural  network
language  model  (
rnnlm
)  generates  sen-
tences  one  word  at  a  time  and  does  not
work from an explicit global sentence rep-
resentation.    In  this  work,  we  introduce
and  study  an
rnn
-based  variational  au-
toencoder  generative  model  that  incorpo-
rates distributed latent representations of
entire  sentences.
This  factorization  al-
lows  it  to  explicitly  model  holistic  prop-
erties  of  sentences  such  as  style,  topic,
and high-level syntactic features.  Samples
from  the  prior  over  these  sentence  repre-
sentations remarkably produce diverse and
well-formed  sentences  through  simple  de-
terministic decoding.  By examining paths
through  this  latent  space,  we  are  able  to
generate coherent novel sentences that in-
terpolate  between  known  sentences.    We
present techniques for solving the difficult
learning problem presented by this model,
demonstrate  its  effectiveness  in  imputing
missing  words,  explore  many  interesting
properties  of  the  model’s  latent  sentence
space, and present negative results on the
use of the model in language modeling.

###Samuel R. Bowman, Jon Gauthier}, Abhinav Rastogi, Raghav Gupta, Christopher D. Manning, and Christopher Potts. A Fast Unified Model for Parsing and Sentence Understanding (code). Proceedings of ACL. 2016.
Abstract
Tree-structured neural networks exploit
valuable syntactic parse information as
they interpret the meanings of sentences.
However, they suffer from two key techni-
cal problems that make them slow and un-
wieldy for large-scale NLP tasks: they usu-
ally operate on parsed sentences and they
do not directly support batched computa-
tion. We address these issues by introduc-
ing the Stack-augmented Parser-Interpreter
Neural Network (SPINN), which combines
parsing and interpretation within a single
tree-sequence hybrid model by integrating
tree-structured sentence interpretation into
the linear sequential structure of a shift-
reduce parser. Our model supports batched
computation for a speedup of up to 25
×
over other tree-structured models, and its
integrated parser can operate on unparsed
data with little loss in accuracy. We evalu-
ate it on the Stanford NLI entailment task
and show that it significantly outperforms
other sentence-encoding models


## Natalia
http://web.stanford.edu/~natalias/
 I'm a Ph.D. student in the Linguistics Department at Stanford University. I work in the Natural Language Processing Group, advised by Chris Manning. I'm a member of the team that designed the Universal Dependencies standard and released the EWT dependency corpus. My dissertation is about different ways in which design choices we make in UD can affect its usefulness in NLP applications.

Email: [first name+s]@stanford.edu 

### Does UD need a parsing representation? An investigation of English
Abstract
This  paper  investigates  the  potential  of
defining  a  parsing  representation  for  En-
glish  data  in  Universal  Dependencies,  a
crosslingual dependency scheme.  We in-
vestigate  structural  transformations  that
change  the  choices  of  headedness  in  the
dependency  tree.
The  transformations
make   auxiliaries,   copulas,   subordinat-
ing  conjunctions  and  prepositions  heads,
while  in  UD  they  are  dependents  of  a
lexical  head.   We  show  experimental  re-
sults  for  the  performance  of  MaltParser,
a  data-driven  transition-based  parser,  on
the product of each transformation. While
some  transformed  representations  favor
performance,   inverting   the   transforma-
tions  to  obtain  UD  for  the  final  product
propagates errors, in part due to the nature
of lexical-head representations.  This pre-
vents the transformations from being prof-
itably used to improve parser performance
in that representation.

### A Gold Standard Dependency Corpus for English LREC
Abstract
We present a gold standard annotation of syntactic dependencies in the English Web Treebank corpus using the Stanford Dependencies
standard.   This  resource  addresses  the  lack  of  a  gold  standard  dependency  treebank  for  English,  as  well  as  the  limited  availability
of gold standard syntactic annotations for informal genres of English text.  We also present experiments on the use of this resource,
both for training dependency parsers and for evaluating dependency parsers like the one included as part of the Stanford Parser.  We
show that training a dependency parser on a mix of newswire and web data improves performance on that type of data without greatly
hurting performance on newswire text, and therefore gold standard annotations for non-canonical text can be valuable for parsing in
general.   Furthermore,  the systematic annotation effort has informed both the SD formalism and its implementation in the Stanford
Parser’s dependency converter. In response to the challenges encountered by annotators in the EWT corpus, we revised and extended the
Stanford Dependencies standard, and improved the Stanford Parser’s dependency converter.

### Universal Stanford dependencies: A cross-linguistics typology

Abstract
Revisiting the now de facto standard Stanford dependency representation, we propose an improved taxonomy to capture grammatical
relations  across  languages,  including  morphologically  rich  ones.    We  suggest  a  two-layered  taxonomy:   a  set  of  broadly  attested
universal grammatical relations, to which language-specific relations can be added.  We emphasize the lexicalist stance of the Stanford
Dependencies,  which  leads  to  a  particular,  partially  new  treatment  of  compounding,  prepositions,  and  morphology.   We  show  how
existing dependency schemes for several languages map onto the universal taxonomy proposed here and close with consideration of
practical implications of dependency representation choices for NLP applications, in particular parsing








