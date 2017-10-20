# [Christopher Manning](https://nlp.stanford.edu/manning/ "Christopher Manning")
email:manning@cs.stanford.edu

## publication
sort by time

### CoNLL 2017 Shared Task: Multilingual Parsing from Raw Text to Universal Dependencies

Abstract
The  Conference  on  Computational  Natu-
ral Language Learning (CoNLL) features
a shared task,  in which participants train
and test their learning systems on the same
data sets.   In 2017,  the task was devoted
to learning **dependency parsers** for a large
number of languages, in a real-world set-
ting without any gold-standard annotation
on input.  All test sets followed a unified
annotation scheme, namely that of Univer-
sal Dependencies. In this paper, we define
the task and evaluation methodology, de-
scribe how the data sets were prepared, re-
port and analyze the main results, and pro-
vide a brief categorization of the different
approaches of the participating systems.

### ACL Get To The Point: Summarization with Pointer-Generator Networks
Abstract
Neural sequence-to-sequence models have
provided  a  viable  new  approach  for
abstractive text   summarization   (meaning
they are not restricted to simply selecting
and  rearranging  passages  from  the  origi-
nal text). However, these models have two
shortcomings: they are liable to **reproduce
factual details inaccurately**, and they tend
to repeat themselves. In this work we pro-
pose a novel architecture that augments the
standard sequence-to-sequence attentional
model  in  two  orthogonal  ways.
First, we use a **hybrid pointer-generator network** that can copy words from the source text
via pointing,  which  aids  accurate  reproduction of information, while retaining theability to produce novel words through thegenerator.   Second,  we  use coverage to keep track of what has been summarized, which  discourages  repetition.   We  apply our model to the CNN / Daily Mail sum-marization task, outperforming the current abstractive  state-of-the-art  by  at  least  2
ROUGE points

### ACL Naturalizing a Programming Language via Interactive Learning
Abstract
Our  goal  is  to  create  a  convenient  natu-
ral language interface for performing well-
specified but complex actions such as ana-
lyzing data, manipulating text, and query-
ing  databases.
However,  existing  natu-
ral language interfaces for such tasks are
quite primitive compared to the **power one
wields with a programming language**.  To
bridge this gap, we start with a core pro-
gramming  language  and  allow  users  to
“naturalize” the core language incremen-
tally by defining alternative, more natural
syntax and increasingly complex concepts
in terms of compositions of simpler ones.
In  a  voxel  world,  we  show  that  a  com-
munity of users can simultaneously teach
a common system a diverse language and
use it to build hundreds of complex voxel
structures.  Over the course of three days,
these users went from using only the core
language to using the naturalized language
in 85.9% of the last 10K utterances.

### EACL A Copy-Augmented Sequence-to-Sequence Architecture Gives Good Performance on Task-Oriented Dialogue

Abstract
**Task-oriented  dialogue**  focuses  on  con-
versational  agents  that  participate  in  dia-
logues with user goals on domain-specific
topics. In contrast to chatbots, which sim-
ply seek to **sustain open-ended meaning-
ful discourse**, existing task-oriented agents
usually  explicitly  model  user  intent  and
belief states. This paper examines bypass-
ing such an explicit representation by de-
pending on a latent neural embedding of
state and learning selective attention to di-
alogue history together with copying to in-
corporate relevant prior context. We com-
plement recent work by showing the effec-
tiveness  of  simple  sequence-to-sequence
neural  architectures  with  a  copy  mecha-
nism.  Our model outperforms more com-
plex memory-augmented models by 7% in
per-response generation and is on par with
the  current  state-of-the-art  on  DSTC2,  a
real-world task-oriented dialogue dataset.

### Gapping Constructions in Universal Dependencies v2
Abstract
In  this  paper,  we  provide  a  detailed  ac-
count  of  sentences  with  gapping  such  as
“John likes tea,  and Mary coffee” within
the **Universal Dependencies** (UD) frame-
work.  We explain how common gapping
constructions as well as rare complex con-
structions can be analyzed on the basis of
examples  in  Dutch,  English,  Farsi,  Ger-
man,  Hindi,  Japanese,  and  Turkish.   We
further  argue  why  the  adopted  analysis
of these constructions in UD version 2 is
better suited for annotating treebanks and
parsing  than  previous  proposals,  and  we
discuss how **gapping constructions** can be
analyzed in the enhanced UD representa-
tion,  a  graph-based  semantic  representa-
tion for shallow computational semantics
tasks.

### EMNLP Position-aware Attention and Supervised Data Improve Slot Filling

Abstract
Organized relational knowledge in the
form of “**knowledge graphs**” is important
for many applications. However, the abil-
ity to populate knowledge bases with facts
automatically extracted from documents
has improved frustratingly slowly.  This
paper simultaneously addresses two issues
that have held back prior work. We first
propose an effective new model, which
combines an LSTM sequence model with
a form of entity position-aware attention
that is better suited to relation extraction.
Then we build TACRED, a large (119,474
examples) supervised relation extraction
dataset, obtained via crowdsourcing and
targeted towards TAC KBP relations. The
combination of better supervised data and
a more appropriate high-capacity model
enables much better relation extraction
performance. When the model trained on
this new dataset replaces the previous rela-
tion extraction component of the best TAC
KBP 2015 slot filling system, its F1 score
increases markedly from 22.2% to 26.7%.

### ACL Arc-swift: A Novel Transition System for Dependency Parsing
Abstract
Transition-based  dependency  parsers  of-
ten need sequences of local shift and re-
duce operations to produce certain attach-
ments. Correct individual decisions hence
require global information about the sen-
tence  context  and  mistakes  cause  **error
propagation**.  This paper proposes a novel
transition  system,arc-swift,  that  enables
direct attachments between tokens farther
apart  with  a  single  transition.
This  allows  the  parser  to  **leverage  lexical  infor-
mation**  more  directly  in  transition  deci-
sions.   Hence, arc-swift can  achieve  sig-
nificantly better performance with a very
small beam size.  Our parsers reduce error
by 3.7–7.6% relative to those using exist-
ing  transition  systems  on  the  Penn  Tree-
bank dependency parsing task and English
Universal Dependencies.

### Stanford at TAC KBP 2016: Sealing Pipeline Leaks and Understanding Chinese
Abstract
We  describe  Stanford’s  entries  in  the  TAC
KBP 2016 Cold Start Slot Filling and Knowl-
edge Base Population challenge.  Our biggest
contribution is an entirely new Chinese entity
detection  and  relation  extraction  system  for
the new Chinese and cross-lingual relation ex-
traction tracks.   This new system consists of
several  **ruled-based  relation  extractors**  and  a distantly  supervised  extractor.   We  also  ana-
lyze  errors  produced  by  our  existing  mature
English  **KBP  system**,  which  leads  to  several
fixes,  notably  improvements  to  our  patterns-
based  extractor  and  neural  network  model,
support for nested mentions and inferred rela-
tions.   Stanford’s 2016 English,  Chinese and
cross-lingual  submissions  achieved  an  over-
all (macro-averaged LDC-MEAN) F1 of 22.0,
14.2, and 11.2 respectively on the 2016 evalu-
ation data, performing well above the median
entries, at 7.5, 13.2 and 8.3 respectively.

### CoNLL Shared Task Stanford's Graph-based Neural Dependency Parser at the CoNLL 2017 Shared Task
Abstract
This  paper  describes  the  **neural  depen-
dency parser** submitted by Stanford to the
CoNLL 2017 Shared Task on parsing Uni-
versal  Dependencies.
Our  system  uses
relatively simple LSTM networks to pro-
duce  part  of  speech  tags  and  labeled  de-
pendency parses from segmented and tok-
enized sequences of words. In order to ad-
dress the rare word problem that abounds
in  languages  with ** complex  morphology**,
we  include  a  character-based  word  rep-
resentation  that  uses  an  LSTM  to  pro-
duce embeddings from sequences of char-
acters.   Our  system  was  ranked  first  ac-
cording to all five relevant metrics for the
system:  UPOS  tagging  (93.09%),  XPOS
tagging  (82.27%),  unlabeled  attachment
score (81.30%), labeled attachment score
(76.30%),  and  content  word  labeled  at-
tachment score (72.57%).

### Arxiv Key-Value Retrieval Networks for Task-Oriented Dialogue
Abstract
Neural task-oriented dialogue systems of-
ten struggle to smoothly interface with a
knowledge base.  In this work, we seek to
address this problem by proposing a new
neural dialogue agent that is able to effec-
tively **sustain grounded**, **multi-domain dis-
course** through a novel key-value retrieval
mechanism.  The model is end-to-end dif-
ferentiable and does not need to explicitly
model dialogue state or belief trackers. We
also  release  a  new  dataset  of  3,031  dia-
logues that are grounded through underly-
ing  knowledge  bases  and  span  three  dis-
tinct tasks in the in-car personal assistant
space: calendar scheduling, weather infor-
mation retrieval, and point-of-interest nav-
igation. Our architecture is simultaneously
trained on data from all domains and sig-
nificantly outperforms a competitive rule-
based system and other existing neural di-
alogue  architectures  on  the  provided  do-
mains according to both automatic and hu-
man evaluation metrics.

### Arxiv SceneSeer: 3D Scene Design with Natural Language
ABSTRACT
Designing 3D scenes is currently a creative task that requires significant expertise and effort in using complex 3D design interfaces.  This effortful design process starts in stark contrast to the easiness with which people can use language to describe real and imaginary environments.  We present SCENESEER
:  an interactive text to 3D scene generation system
that  allows  a  user  to  design  3D  scenes  using  natural  language.   A  user  provides  input  text  from  which  we  extract explicit constraints on the objects that should appear in the scene.  Given these explicit constraints, the system then uses
a spatial knowledge base learned from an existing database of 3D scenes and 3D object models to infer an arrangement of the objects forming a natural scene matching the input description.   Using textual commands the user can then itera-
tively refine the created scene by adding, removing, replacing,  and  manipulating  objects.   We  evaluate  the  quality  of 3D  scenes  generated  by  S
CENESEER in  a  perceptual  evaluation experiment where we compare against manually designed scenes and simpler baselines for 3D scene generation. We demonstrate how the generated scenes can be iteratively refined through simple natural language commands.

### Paris and Stanford at EPE 2017:Downstream Evaluation of Graph-based Dependency Representations
Abstract
We  describe  the STANFORD-PARIS and PARIS-STANFORD submissions to the
2017  Extrinsic  Parser  Evaluation  (EPE)
Shared Task.  The purpose of this shared
task  was  to  evaluate  dependency  graphs
on three downstream tasks.  Through our
submissions, we evaluated the usability of
several  representations  derived  from  En-
glish  Universal  Dependencies  (UD),  as
well as the Stanford Dependencies (SD),
Predicate Argument Structure (PAS), and
DM representations. We further compared
two parsing strategies: Directly parsing to
graph-based  dependency  representations
and  a  two-stage  process  of  **first  parsing
to  surface  syntax  trees**  and  then  apply-
ing **rule-based augmentations** to obtain the
final  graphs.    Overall,  our  systems  per-
formed  very  well  and  our  submissions
ranked  first  and  third.    In  our  analysis,
we find that the two-stage parsing process
leads  to  better  downstream  performance,
and that enhanced UD, a graph-based rep-
resentation,  consistently  outperforms
basic UD, a strict surface syntax representa-
tion, suggesting an advantage of enriched
representations for downstream tasks.

### EMNLP Importance sampling for unbiased on-demand evaluation of knowledge base population
Abstract
**Knowledge  base  population  (KBP**)  sys-
tems take in a large document corpus and
extract  entities  and  their  relations.   Thus
far,  KBP  evaluation  has  relied  on  judge-
ments on the pooled predictions of exist-
ing  systems.   We  show  that  this  evalua-
tion  is  problematic:  when  a  new  system
predicts a previously unseen relation, it is
penalized even if it is correct.  This leads
to  significant  bias  against  new  systems,
which counterproductively discourages in-
novation  in  the  field.   Our  first  contribu-
tion is a new importance-sampling based
evaluation which corrects for this bias by
annotating a new system's predictions on-
demand via crowdsourcing.  We show this
eliminates bias and reduces variance using
data from the 2015 TAC KBP task.   Our
second contribution is an implementation
of our method made publicly available as
an online KBP evaluation service.  We pi-
lot the service by testing diverse state-of-
the-art systems on the TAC KBP 2016 cor-
pus and obtain accurate scores in a cost ef-
fective manner.

### ACL A Thorough Examination of the CNN/Daily Mail Reading Comprehension Task
Abstract
Enabling a computer to understand a docu-
ment so that it can answer comprehension
questions is a central,  yet unsolved goal
of NLP.  A key factor impeding its solu-
tion by machine learned systems is the lim-
ited availability of **human-annotated data**.
Hermann et al. (2015) seek to solve this
problem by creating over a million training
examples by pairing CNN and Daily Mail
news articles with their summarized bullet
points, and show that a neural network can
then be trained to give good performance
on this task.  In this paper, we conduct a
thorough examination of this new reading
comprehension task. Our primary aim is to
understand what depth of language under-
standing is required to do well on this task.
We approach this from one side by doing a
careful hand-analysis of a small subset of
the problems and from the other by show-
ing that simple, carefully designed systems
can obtain accuracies of 72.4% and 75.8%
on these two datasets, exceeding current
state-of-the-art results by over 5% and ap-
proaching what we believe is the ceiling
for performance on this task.

### LREC Universal Dependencies v1: A Multilingual Treebank Collection
Abstract
**Cross-linguistically** consistent annotation is necessary for sound comparative evaluation and cross-lingual learning experiments. It is also
useful for multilingual system development and comparative linguistic studies. Universal Dependencies is an open community effort to
create cross-linguistically consistent treebank annotation for many languages within a dependency-based lexicalist framework.  In this
paper, we describe v1 of the universal guidelines, the underlying design principles, and the currently available **treebanks** for 33 languages.

### ACL A Fast Unified Model for Parsing and Sentence Understanding
Abstract
**Tree-structured neural networks** exploit
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
computation for a speedup of up to 25×
over other tree-structured models, and its
integrated parser can operate on unparsed
data with little loss in accuracy. We evalu-
ate it on the Stanford NLI entailment task
and show that it significantly outperforms
other sentence-encoding models.

### ACL Achieving Open Vocabulary Neural Machine Translation with Hybrid Word-Character Models
Abstract
Nearly all previous work on neural ma-
chine translation (NMT) has used quite
restricted vocabularies,  perhaps with a
subsequent method to patch in unknown
words. This paper presents a novel word-
character solution to achieving open vo-
cabulary NMT. We build hybrid systems
that translate mostly at the word level
and consult the **character components** for
rare words.  Our character-level recur-
rent neural networks compute source word
representations and recover unknown tar-
get words when needed.  The twofold
advantage of such a hybrid approach is
that it is much faster and easier to train
than character-based ones; at the same
time, it never produces unknown words
as in the case of word-based models. On
the WMT’15 English to Czech translation
task, this hybrid approach offers an ad-
dition boost of +2.1−11.4 BLEU points
over models that already handle unknown
words.  Our best system achieves a new
state-of-the-art result with 20.7 BLEU
score. We demonstrate that our character
models can successfully learn to not only
generate well-formed words for Czech,
a highly-inflected language with a very
complex vocabulary, but also build correct
representations for English source words.

### Arxiv Deep Biaffine Attention for Neural Dependency Parsing
ABSTRACT
This paper builds off recent work from Kiperwasser & Goldberg (2016) using neural attention in a simple graph-based dependency parser. We
use a larger but more thoroughly regularized parser than other recent **BiLSTM-based** approaches, with biaffine classifiers to predict arcs and labels. Our parser gets state of the art or near state of the art performance on standard treebanks for six different languages, achieving 95.7% UAS and 94.1% LAS on the most popular English PTB dataset.
This makes it the highest-performing graph-based parser on this benchmark—outperforming Kiperwasser & Goldberg (2016) by 1.8% and 2.2
%—and comparable to the highest performing transition-based parser (Kuncoro et al., 2016),
which achieves 95.8% UAS and 94.6% LAS. We also show which hyperparameter choices had a significant effect on parsing accuracy, allowing us to achieve large gains over other graph-based approaches

### ACL Improving Coreference Resolution by Learning Entity-Level Distributed Representations
Abstract
A long-standing challenge in coreference
resolution  has  been  the  incorporation  of
entity-level information – features defined
over clusters of mentions instead of men-
tion  pairs.
We  present  a  neural  net-
work  based  coreference  system  that  pro-
duces  high-dimensional  vector  represen-
tations  for  pairs  of  **coreference  clusters**.
Using  these  representations,  our  system
learns  when  combining  clusters  is  de-
sirable.
We   train   the   system   with   a
learning-to-search  algorithm  that  teaches
it  which  local  decisions  (cluster  merges)
will  lead  to  a  high-scoring  final  corefer-
ence  partition.   The  system  substantially
outperforms the current state-of-the-art on
the  English  and  Chinese  portions  of  the
CoNLL 2012 Shared Task dataset despite
using few hand-engineered features.

### EMNLP Deep Reinforcement Learning for Mention-Ranking Coreference Models
Abstract
Coreference  resolution  systems  are  typically
trained  with  **heuristic  loss  functions**  that  re-
quire  careful  tuning.
In  this  paper  we  instead apply **reinforcement learning** to directly optimize a neural mention-ranking model for coreference  evaluation  metrics.    We  experiment  with  two  approaches:  the
REINFORCE policy   gradient   algorithm   and   a   reward rescaled  max-margin  objective.   We  find  the latter to be more effective, resulting in a sig-
nificant  improvement  over  the  current  state-
of-the-art on the English and Chinese portions
of the CoNLL 2012 Shared Task

### LREC Enhanced English Universal Dependencies: An Improved Representation for Natural Language Understanding Tasks
Abstract
Many  shallow  natural  language  understanding  tasks  use  dependency  trees  to  extract  relations  between  content  words.    However,
strict surface-structure dependency trees tend to follow the linguistic structure of sentences too closely and frequently fail to provide
direct relations between content words.  To mitigate this problem, the original Stanford Dependencies representation also defines two
dependency graph representations which contain additional and augmented relations that explicitly capture otherwise implicit relations
between content words.  In this paper, we revisit and extend these dependency graph representations in light of the recent Universal
Dependencies (UD) initiative and provide a detailed account of an enhanced and an enhanced++
English UD representation. We further
present a converter from constituency to
basic, i.e., strict surface structure, **UD trees**, and a converter from basic UD trees to enhanced and
enhanced++ English UD graphs. We release both converters as part of Stanford CoreNLP and the Stanford Parser.

### ACL Learning Language Games through Interaction
Abstract
We  introduce  a  new  language  learning
setting  relevant  to  building  adaptive  nat-
ural  language  interfaces.
It  is  inspired 
by Wittgenstein’s language games:  a hu-
man   wishes   to   accomplish   some   task
(e.g., achieving a certain configuration of
blocks), but can only communicate with a
computer, who performs the actual actions
(e.g., removing all red blocks).  The com-
puter  initially  knows  nothing  about  lan-
guage  and  therefore  must  learn  it  from
scratch through interaction, while the hu-
man adapts to the computer’s capabilities.
We created a game called SHRDLURN in
a blocks world and collected interactions
from 100 people playing it.  First, we an-
alyze the humans’ strategies, showing that
using compositionality and avoiding syn-
onyms correlates positively with task per-
formance.  Second, we compare computer
strategies,  showing  that  modeling  prag-
matics on a semantic parsing model accel-
erates learning for more strategic players.

### CoNLL Compression of Neural Machine Translation Models via Pruning
Abstract
Neural  Machine  Translation  (NMT),  like
many  other  deep  learning  domains,  typ-
ically suffers from over-parameterization,
resulting in large storage sizes. This paper
examines  three  simple  magnitude-based
pruning schemes to compress NMT mod-
els,   namely class-blind, class-uniform, and
class-distribution,   which   differ   in
terms of how pruning thresholds are com-
puted for the different classes of weights in
the NMT architecture. We demonstrate the
efficacy of weight pruning as a compres-
sion technique for a state-of-the-art NMT
system. We show that an NMT model with
over 200 million parameters can be pruned
by 40% with very little performance loss
as  measured  on  the  WMT’14  English-
German translation task.  This sheds light
on  the  distribution  of  redundancy  in  the
NMT architecture.  Our main result is that
with retraining, we can recover and even
surpass the original performance with an
80%-pruned model.

### LREC A comparison of Named-Entity Disambiguation and Word Sense Disambiguation
Abstract
Named  Entity  Disambiguation  (NED)  is  the  task  of  linking  a  named-entity  mention  to  an  instance  in  a  knowledge-base,  typically
Wikipedia-derived resources like DBpedia.  This task is closely related to word-sense disambiguation (WSD), where the mention of an
open-class word is linked to a concept in a knowledge-base, typically WordNet. This paper analyzes the relation between two annotated
datasets on NED and WSD, highlighting the commonalities and differences. We detail the methods to construct a NED system following
the WSD word-expert approach, where we need a dictionary and one classifier is built for each target entity mention string. Constructing
a dictionary for NED proved challenging, and although similarity and ambiguity are higher for NED, the results are also higher due to
the larger number of training data, and the more crisp and skewed meaning differences.

### ACL Evaluating Word Embeddings Using a Representative Suite of Practical Tasks
Abstract
Word  embeddings  are  increasingly  used
in  natural  language  understanding  tasks
requiring sophisticated semantic informa-
tion.  However, the quality of new embed-
ding  methods  is  usually  evaluated  based
on  simple  word  similarity  benchmarks.
We propose evaluating word embeddings
in vivo
by  evaluating  them  on  a  suite  of
popular downstream tasks.  To ensure the
ease of use of the evaluation, we take care
to find a good point in the tradeoff space
between  (1)  creating  a  thorough  evalua-
tion  –  i.e.,  we  evaluate  on  a  diverse  set
of tasks; and (2) ensuring an easy and fast
evaluation – by using simple models with
few  tuned  hyperparameters.   This  allows
us to release this evaluation as a standard-
ized script and online evaluation, available
at http://veceval.com/ .

### Arxiv Evaluating the word-expert approach for Named-Entity Disambiguation
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

### ACL Combining Natural Logic and Shallow Reasoning for Question Answering
Abstract
Broad  domain  question  answering  is  of-
ten  difficult  in  the  absence  of  structured
knowledge  bases,  and  can  benefit  from
shallow lexical methods (broad coverage)
and  logical  reasoning  (high  precision).
We propose an approach for incorporating
both  of  these  signals  in  a  unified  frame-
work  based  on  natural  logic.   We  extend
the breadth of inferences afforded by nat-
ural logic to include relational entailment
(e.g.,buy→own)  and  meronymy  (e.g.,
a person born in a city is born the city’s
country).   Furthermore,  we train an
evaluation  function–  akin  to  gameplaying  –
to evaluate the expected truth of candidate
premises on the fly.  We evaluate our ap-
proach on answering multiple choice sci-
ence questions, achieving strong results on
the dataset.

### SIGIR Understanding Human Language: Can NLP and Deep Learning Help?
There is a lot of overlap between the core problems of information retrieval (IR) and natural language processing (NLP). An IR system gains from understanding a user need and from understanding documents, and hence being able to determine whether a document has information that satisfies the user need. Much of NLP is about the same thing: Natural language understanding aims to understand the meaning of questions and documents and meaning relationships. The exciting recent application of deep learning approaches in NLP has brought new tools for effectively understanding language semantics. In principle, there should be a lot of synergy, though in practice the concerns of IR on large systems and macro-scale understanding have tended to contrast with the emphasis in NLP on language structure and micro-scale understanding. My talk will emphasize the two topics of how NLP can contribute to understanding textual relationships and how deep learning approaches substantially aid in this goal. One basic -- and very successful tool -- has been the new generation of distributed word representations: neural word embeddings. However, beyond just word meanings, we need to understand how to compose the meanings of larger pieces of text. Two requirements for that are good ways to understand the structure of human language utterances and ways to compose their meanings. Deep learning methods can help for both tasks. Finally, we need to understand relationships between pieces of text, to be able to do tasks such as Natural Language Inference (or Recognizing Textual Entailment) and Question Answering, and I will look at some of our recent work in these areas, both with and without the help of neural networks



