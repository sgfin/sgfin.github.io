---
layout: post
title: ML Resources
permalink: /learning-resources/
---


<style>
table {
  border-collapse: collapse;
}
th, td {
    border: 1px solid #999;
}

p {
    width: 100%;
}

</style>


<h3>Outline:</h3>

<div style="padding-top: 10px; font-size:large">

<a href="#Start">-Where Should I Start?</a><br>

<a href="#CS">-Computer Science</a><br>

<a href="#realA">-Real Analysis</a><br>

<a href="#LA">-Linear Algebra</a><br>

<a href="#prob">-Probability</a><br>

<a href="#stat">-Statistics</a><br>

<a href="#causal">-Causal Inference</a><br>

<a href="#opt">-Optimization</a><br>

<a href="#info">-Information Theory</a><br>

<a href="#ml">-Classic Machine Learning</a><br>

<a href="#bayesML">-Bayesian Machine Learning</a><br>

<a href="#DL">-Deep Learning</a><br>

<a href="#NLP">-Natural Language Processing</a><br>

<a href="#RL">-Reinforcement Learning</a><br>

<a href="#bio">-Applications in Biology and Medicine</a><br>

<a href="#misc">-Favorite Websites</a>

</div>

### <a name="Start"></a> Where should I start (in ML)?

If you're here looking for a general introduction to machine learning, I would proceed in the following order:

- [Introduction to Statistical Learning](http://faculty.marshall.usc.edu/gareth-james/ISL/) by James, Witten, Hastie, and Tibshirani. This textbook is a fantastic introduction to the field, written by some of its leading experts. It is short and well-written enough to be read cover-to-cover, high-level enough to be accessible to people from various backgrounds, yet rigorous in the sense that it teaches you to think about the problems rather than just giving you a cookbook.  The textbook is free as a PDF at the book website, and the authors have also provided a collection of excellent videos that accompany the text on Youtube (the videos are nicely organized into a collection [here](https://www.r-bloggers.com/in-depth-introduction-to-machine-learning-in-15-hours-of-expert-videos/)). Note that this textbook also has a "big sister", the classic [Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/), which covers the same content at much more mathematical depth. However, I would start with ISL and then move to ESL from there as your interest directs.  Note that the code in this book and class is in R and covers most of the classical ML toolkit but doesn't cover deep learning.

- [Fast.ai](https://course.fast.ai/) by Jeremy Howard and Rachel Thomas. This course provides an accessible but extremely effective introduction to deep learning, the most popular branch of modern machine learning. The course is hands-on and immensely practical, but each lesson will equip you with the tools to build a very effective model for some new branch of ML (computer vision, NLP, etc.). The course is taught in Python using Pytorch and their own library.

Once you make your way through ISL and fast.ai, you will have a solid handle on all the most commonly used techniques in ML (classic and cutting edge). You will have a decent intuition for which methods can work when, and an ability to at least understand and modify code for ML analysis in both R and Python. From there, you should be prepared to jump at greater depth into any subarea of the field that you fancy.

Depending on background and bandwidth, a motivated student could probably work through the above material in 1-4 months. Go get 'em! :)


### <a name="CS"></a> Computer Science

#### Theory

| File | Description   |
| :-----------: |:-------------:|
|  [CS Theory Cheatsheet](/files/cheatsheets/CS_theory_cheat_sheet.pdf)  |  CS theory cheat sheet, originally accessed [here](https://www.tug.org/texshowcase/cheat.pdf)|
|Tim Roughgarden's [Lectures on Algorithms](https://theory.stanford.edu/~tim/notes.html) and [Algorithms Illuminated](http://www.algorithmsilluminated.org/)| Tim Roughgarden is one of most natural teachers I've ever seen. The first link is to lecture notes in PDF form from many classes. Videos for his Algorithms 2 class (CS 261) are [here](https://www.youtube.com/playlist?list=PLEGCF-WLh2RJh2yDxlJJjnKswWdoO8gAc). The second is a link to his page for his new textbook, but that page also has links out to all the youtube videos from his coursera version of CS 161 (Algorithms 1).|

#### Programming cheatsheets

| File | Description   |
| :-----------: |:-------------:|
|  [R dplyr cheatsheet](/files/cheatsheets/R_cheatsheet_dplyr.pdf)  |  Cheatsheet for Hadley's amazing data wrangling package, dplyr. One of many from [RStudio](https://www.rstudio.com/resources/cheatsheets/) |
| [R dplyr and data.table side by side](https://atrebas.github.io/post/2019-03-03-datatable-dplyr/) | Nice side-by-side comparison of dplyr and data.table by Atrebas.|
|  [R ggplot2 cheatsheet](/files/cheatsheets/R_cheatsheet_ggplot2.pdf)  |  Cheatsheet for Hadley's amazing plotting package, ggplot2. One of many from [RStudio](https://www.rstudio.com/resources/cheatsheets/)|
|  [SQL Joins cheatsheet](/files/cheatsheets/SQL_joins.png)  |  Graphical description of classic SQL joins w/ toy code  |
|  [Python pandas cheatsheet](/files/cheatsheets/Python_cheatsheet_pandas.pdf)  |  Cheatsheet for python's data wrangling package, pandas. Downloaded from [here](https://pandas.pydata.org/Pandas_Cheat_Sheet.pdf)|
|  [Python numpy cheatsheet](/files/cheatsheets/Python_cheatsheet_numpy.pdf)  |  Cheatsheet for python's numerical package, numpy. Downloaded from [Datacamp](https://www.datacamp.com)|
|  [Python keras cheatsheet](/files/cheatsheets/Python_Keras_Cheat_Sheet.pdf)  |  Cheatsheet for python's NN package, keras. Downloaded from [Datacamp](https://www.datacamp.com).|
|  [Python scikit-learn cheatsheet](/files/cheatsheets/Python_cheatsheet_scikit.pdf)  |  Cheatsheet for python's ML package, scikit-learn. Downloaded from [Datacamp](https://www.datacamp.com).|
|  [Python seaborn tutorial](https://seaborn.pydata.org/tutorial.html)  |  Tutorial for python's plotting system, seaborn. Haven't found a great one yet for matplotlib. |
|  [Graphic Design cheatsheet](/files/cheatsheets/graphic_design.pdf)  |  Cute little graphic design cheatsheet downloaded from [here](https://www.psiweb.org/docs/default-source/2018-psi-conference-posters/48-julie-jones.pdf) |
| Pytorch [cheat sheet](https://pytorch.org/tutorials/beginner/ptcheat.html) and [tutorials](https://pytorch.org/tutorials/) and [docs](https://pytorch.org/docs/stable/index.html)| The pytorch team has some world class docs and tutorials.|

### <a name="realA"></a> Real Analysis

| File | Description   |
| :-----------: |:-------------:|
|  [Measure, Integration, and Real Analysis](http://measure.axler.net/MIRA.pdf)  |  Sheldon Axler's textbook-under-development on measure theory and real analysis. ([Website](http://measure.axler.net)). |

### <a name="LA"></a> Linear Algebra

| File | Description   |
| :-----------: |:-------------:|
|  [Boyd Applied Linear Algebra](http://vmls-book.stanford.edu/vmls.pdf)  |  Freely available book from Boyd and Vandenberghe on Applied LA ([website](http://vmls-book.stanford.edu/)). |
| [Fast.ai Computational Linear Algebra](https://github.com/fastai/numerical-linear-algebra/blob/master/README.md) | Rachel Thomas has put together this great online textbook for computational linear algebra with accompanying [youtube videos](https://www.youtube.com/playlist?list=PLtmWHNX-gukIc92m1K0P6bIOnZb-mg0hY). |
|  [CS 229 Linear Algebra Notes](/files/notes/CS229_Linear_Algebra.pdf)  |  Linear algebra reference from Stanford's Machine Learning [Course](http://cs229.stanford.edu/materials.html). |
|  [Matrix Calc for DL](https://explained.ai/matrix-calculus/index.html) [(pdf here)](/files/notes/Matrix_Calc_for_DL.pdf)  |  Really nice overview of matrix calculus for deep learning from Parr/Howard.  Citable on on [arxiv](https://arxiv.org/abs/1802.01528). |
| [Strang: Matrix methods for Data, Signals, and ML](https://ocw.mit.edu/courses/mathematics/18-065-matrix-methods-in-data-analysis-signal-processing-and-machine-learning-spring-2018/) | Gil Strang's newer linear algebra course, focusing on the linear algebra relevant to data and ML.  Youtube videos [here](https://www.youtube.com/playlist?list=PLUl4u3cNGP63oMNUHXqIUcrkS2PivhN3k). |
| [Linear Algebra Done Right, Abridged](http://linear.axler.net/LinearAbridged.pdf) | This is a free version of Sheldon Axler's texbook Linear Algebra Done Right, which is a nice intro treatment of the subject that is accessible but more pure-mathy in flavor than the above. |


### <a name="prob"></a>  Probability

| File | Description   |
| :-----------: |:-------------:|
|  [Probability Cheatsheet](/files/cheatsheets/probability_cheatsheet_blackwhite.pdf) |  Probability cheat sheet, from William Chen's [github](https://github.com/wzchen/probability_cheatsheet)|
| [MIT 6.041 Intro Probability](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-041-probabilistic-systems-analysis-and-applied-probability-fall-2010/) | John Tsitsiklis et al have put together some great resources. Their classic MIT intro to probability has been archived on [OCW](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-041-probabilistic-systems-analysis-and-applied-probability-fall-2010/) and also offered on Edx ([Part 1](https://www.edx.org/course/introduction-probability-part-1-mitx-6-041-1x), [Part 2](https://www.edx.org/course/introduction-to-probability-part-2-inference-processes)). The [textbook](https://www.amazon.com/Introduction-Probability-2nd-Dimitri-Bertsekas/dp/188652923X) is also excellent. |
| [Joe Blitzstein's Stat110](https://projects.iq.harvard.edu/stat110/about) | Joe Blitzstein's undergrad probability course has a high overlap in content with 6.041. Like 6.041, it also has a great [textbook](https://drive.google.com/file/d/1VmkAAGOYCTORq1wxSQqy255qLJjTNvBI/view), [youtube](https://projects.iq.harvard.edu/stat110/youtube) videos, and an [edx](https://www.edx.org/course/introduction-to-probability-0) offering. It's a bit more playful, as well.|
|[MathematicalMonk](https://www.youtube.com/user/mathematicalmonk)| This guy is amazing. Some 250 youtube tutorials on ML, Probability, and Information Theory. |
| [Trouble in high-dimensional Land](https://dibyaghosh.com/blog/probability/highdimensionalgeometry.html) | Fun little blog post going through intro high-dimensional geometry and its relevance to probability. |


### <a name="stat"></a>  Statistics

| File | Description   |
| :-----------: |:-------------:|
| [Common statistical tests are linear models (or: how to teach stats)](https://lindeloev.github.io/tests-as-linear/) and [Statistical Test Cheatsheet](/files/cheatsheets/linear_tests_cheat_sheet.pdf)| This little blog post does an incredible job explaining how a whole bunch of common statistical tests can be intuitively unified under a single framework (linear models)|
| Russell Poldracks' [Statistical Thinking for the 21st Century](http://statsthinking21.org/index.html) | This appears to be a pretty fantastic (albeit rather elementary) textbook for a one-quarter intro to statistics class (stat 60 at stanford). Despite assuming little, it touches upon a lot of great topics. |
|  [Doug Sparks' Stats 200](/files/notes/Stat200_2014_Merged_Sparks.pdf)  |  Nice course notes on Statistical Inference from Doug Sparks 2014 offering of [stats 200](http://stats200.stanford.edu/) |
|  [Modern Statistics for Modern Biology](https://www-huber.embl.de/msmb/)  |  This online textbook is from Susan Holmes and Wolfgang Huber, and provides a nice and accessible intro to the parts of modern data science revelant to computational biologists.  It also happens to be a piece of typographic *art*, created with [bookdown](https://bookdown.org/yihui/bookdown/).  |
|  [Statistical Rethinking](https://xcelab.net/rm/statistical-rethinking/)  |  Lecture Videos on [youtube](https://www.youtube.com/playlist?list=PLDcUM9US4XdM9_N6XUUFrhghGJ4K25bFc) accompany this fantastic introductory textbook. |
| [Seeing Theory Frequentist Inference](https://seeing-theory.brown.edu/frequentist-inference/index.html) | This is a really beautiful visual presentation of the basic ideas of frequentist inference, from the Seeing Theory textbook.  I love it.|
| [Estadística Multivariada](https://est-mult.netlify.com) | Beautiful note set on multivariate stats from María Teresa Ortiz and Felipe González. Covers bayesian networks, gaussian models, missing data, latent variable models, and baysian methods.|
| [Estadística Computacional](https://tereom.github.io/est-computacional-2019/) | Beautiful note set on computational stats from María Teresa Ortiz. Covers basic probability, simulation, visualization, inference, and some basic bayesian methods.|


### <a name="causal"></a> Causal Inference

| File | Description   |
| :-----------: |:-------------:|
|  [Hernan and Robbins Causal Inference Book](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book/)  |  Long-upcoming textbook on causal inference (from the epidemiology perspective), with drafts fairly frequently updated on the web page. |
| [All the DAGs from the Causal Inference Book](https://sgfin.github.io/2019/06/19/Causal-Inference-Book-All-DAGs/) and [Glossary and Notes](https://sgfin.github.io/2019/06/19/Causal-Inference-Book-Glossary-and-Notes/)| In the first post, I'm compiling all the DAGs from Hernan and Robbins book into one place for easier use. In the second, I have some additional notes to accompany part one of the book. |
|  [Robert Osazuwa Causal Modeling in ML Book](https://github.com/robertness/causalML)  |  Looks to be a nice course in development on causal and generative modeling. Lecture notes are being produced in a bookdown [here](https://bookdown.org/connect/#/apps/2584/access) |
| [Causal Inference Papers](https://github.com/logangraham/arXausality) | Nice Github repo that compiles a bunch of Arxiv papers on Causal Machine Learning |
|  [Hernan Selection Bias](/files/notes/structured_approach_selection_bias_Hernan.pdf)  |  Nice summary of selection bias via DAGs by Hernan et al. |


### <a name="opt"></a>  Optimization

| File | Description   |
| :-----------: |:-------------:|
|[Boyd Convex Optimization Book](http://web.stanford.edu/~boyd/cvxbook/bv_cvxbook.pdf)| Famous and freely available textbook from Boyd and Vandenberghe, accompanied by [slides](https://web.stanford.edu/class/ee364a/lectures.html) and Youtube videos. More advanced follow-up class [here](https://web.stanford.edu/class/ee364b/lectures.html)|
|  NYU Optimization-based Data Analysis [2016](/files/notes/NYU_Optimization_2016.pdf) and [2017](/files/notes/NYU_Optimization_2017.pdf) |  Fantastic course notes on Optimization-based data analysis from NYU [2016 website](https://cims.nyu.edu/~cfgranda/pages/OBDA_spring16/notes.html) and [2017 website](https://cims.nyu.edu/~cfgranda/pages/OBDA_fall17/schedule.html). |
| [Ruder Gradient Descent Overview](http://ruder.io/optimizing-gradient-descent/index.html) [(PDF here)](/files/notes/ruder_gradient.pdf) |  Great overview of gradient descent algorithms. |
|  [Bottou Large-Scale Optimization](/files/notes/bottou_optimization.pdf) |  Notes on Optimization from Bottou, Curtis, and Nocedal. Downloaded from [arxiv](https://arxiv.org/abs/1606.04838). |


### <a name="info"></a>  Information Theory

| File | Description   |
| :-----------: |:-------------:|
|[Chris Olah Visual Information Theory](http://colah.github.io/posts/2015-09-Visual-Information/)| As always, Chris Olah creates an amazing presentation both in words and images.  Goal is to visualize key information theory concepts.|
|[Cover and Thomas Ch2 - Entropy and Information](/files/notes/Cover_and_Thomas_ch2_entropy.pdf)| The extremely well-written introductory chapter from the classic information theory textbook.|
|[Cover and Thomas Ch11 - Info Theory and Statistics](/files/notes/Cover_and_Thomas_ch11_info_and_stats.pdf)| The information theory and statistics chapter from the classic information theory textbook.|
|[Deriving Probability Distributions from Maximum Entropy Principle](https://sgfin.github.io/2017/03/16/Deriving-probability-distributions-using-the-Principle-of-Maximum-Entropy/)| It feels slimey and self-serving to include this, but I wrote this post to better understand how information theory can be used to understand/derive common probability distributions from first principles.|
|[Deriving the information entropy of the multivariate gaussian](https://sgfin.github.io/2017/03/11/Deriving-the-information-entropy-of-the-multivariate-gaussian/)| Another blog post I wrote to try to understand information theory + statistics.|


### <a name="ml"></a>  Classic Machine Learning

#### Textbooks, Lectures, and Course Notes

| File | Description   |
| :-----------: |:-------------:|
|  [Math for ML Book](/files/notes/mml-book.pdf)  |  Math-first but highly accessible intro textbook for machine learning by Faisal and Ong, available on [github](https://mml-book.github.io/). |
| [Learning from Data](https://work.caltech.edu/telecourse.html) by Abu Mostafa | "A short course. Not a hurried course." on machine learning. A nice first treatment that is concise but fairly rigorous.  Also has [videos organized by topic](https://work.caltech.edu/library/). |
| Bishop's [Pattern Recognition and Machine Learning](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf) | This is a classic ML text, and has now been finally released (legally) for free online. |
|  [CS 229 Lecture Notes](/files/notes/CS229_Lecture_Notes.pdf)  |  Classic note set from Andrew Ng's amazing grad-level intro to ML: [CS229](http://cs229.stanford.edu/syllabus.html). |
|  [CS 229 TA Cheatsheet 2018](/files/cheatsheets/cs229_2018_cheatsheet.pdf)  |  TA cheatsheet from the 2018 offering of Stanford's Machine Learning [Course](http://cs229.stanford.edu/materials.html), Github repo [here](https://github.com/afshinea/stanford-cs-229-machine-learning). |
|  [ESL](https://web.stanford.edu/~hastie/ElemStatLearn/printings/ESLII_print12.pdf) and [ISL](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20Seventh%20Printing.pdf) from Hastie et al |  Beginner (ISL) and Advanced (ESL) presentation to classic machine learning from world-class stats professors. Slides and video for a MOOC on ISL is available [here](https://www.dataschool.io/15-hours-of-expert-machine-learning-videos/). |
| Foundations of Data Science [textbook](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/11/book-June-14-2017pdf.pdf) and [videos](https://www.youtube.com/playlist?list=PLD7HFcN7LXRcvobbHq_8zMyWq_tKwtebc) | This mini-course appears to have developed out of CMU's "CS Theory for the Information Age" [2012 site](https://www.cs.cmu.edu/~venkatg/teaching/CStheory-infoage/), which I think is a better name for this.  It's a strong upper-undergrad or intro-grad student math class covering foundations for high-dimensional data algorithms. Another class using the textbook is [here](http://grigory.us/data-science-class.html). High-dimensional probability section is cool. |
|Tim Roughgarden's [Modern Algorithmic Toolbox](https://theory.stanford.edu/~tim/notes.html) | CS 168: Modern Algorithmic Toolbox has fantastic coverage of PCA, SVD, Compressive Sensing, Tensors, and other core ML tools.|


#### Special Topics and Blog Posts

| File | Description   |
| :-----------: |:-------------:|
|  [Roughgarden SVD Notes](/files/notes/CS168_Roughgarden_SVD.pdf)  |  Really great presentation of SVD from [Tim Rougharden's CS168](https://web.stanford.edu/class/cs168/index.html) at Stanford. |
|  [Roughgarden PCA Notes](/files/notes/CS168_Roughgarden_PCA.pdf)  |  Really great presentaiton of PCA from [Tim Rougharden's CS168](https://web.stanford.edu/class/cs168/index.html) at Stanford. |


### <a name="bayesML"></a>  Bayesian Machine Learning

| File | Description   |
| :-----------: |:-------------:|
|  [CS 228 PGM Notes](https://ermongroup.github.io/cs228-notes/)  |  Really great course notes on Probabilistic Graphical Models from at Stanford. PDF export wasn't ideal so linking only to website.|
| CMU PGM Course [2019](https://sailinglab.github.io/pgm-spring-2019/lectures/) and [2014](http://www.cs.cmu.edu/~epxing/Class/10708/lecture.html) | Nice course from CMU (10-708) that covers PGMs and -- in newer offerings -- relevant parts of DL, too.  Has videos, scribe notes, and slides. |
|  [Blei Foundations of Graphical Models Course](http://www.cs.columbia.edu/~blei/fogm/2016F/index.html)  |  2016 course notes on Foundations of Graphical Models from David Blei 2016 website|
[Blei Exponential Familes/Variational Inference](/files/notes/blei_exponFam_varInf.pdf)| A couple of the course notes I particularly like from Blei's [2011 Probabilistic Modeling Course](https://www.cs.princeton.edu/courses/archive/fall11/cos597C/) )
|  [Blei Variational Inference Review](/files/notes/blei_variational_review.pdf) |  Overview on Variational Inference from David Blei available on [arxiv](https://arxiv.org/abs/1601.00670)|
| [Visual Exploration of Gaussian Processes](https://www.google.com/search?q=distill+gaussian+processes&rlz=1C5CHFA_enUS735US735&oq=distill+gaussian+processes&aqs=chrome..69i57j69i60l2j69i61j69i60l2.3173j0j1&sourceid=chrome&ie=UTF-8) | Masterclass exposition on Gaussian Processes from the always-amazing Distill. |


### <a name="DL"></a>  Deep Learning 

#### Textbooks, Lectures, and Course Notes

| File | Description   |
| :-----------: |:-------------:|
| [Roger Grosse's CSC321 Notes](/files/notes/CS321_Grosse_Lecture_Notes.pdf)  |  Notes from Roger Grosse's CSC 321 [full website here](http://www.cs.toronto.edu/~rgrosse/courses/csc321_2018/). Probably the single best intro to DL course I've found from any university. Notes and slides are gorgeous.|
|  [Fast.Ai](https://www.fast.ai/)  |  Wonderful set of intro lectures + notebooks from Jeremy Howard and Rachel Thomas. In addition, Hiromi Suenaga has released excellent and self-contained notes of the whole series with timestamp links back to videos: [FastAI DL Part 1](https://www.kdnuggets.com/2018/07/fast-ai-deep-learning-part-1-notes.html), [FastAI DL Part 2](https://www.kdnuggets.com/2018/07/fast-ai-deep-learning-part-2-notes.html), and [FastAI ML](https://www.kdnuggets.com/2018/07/suenaga-fast-ai-machine-learning-notes.html). |
|  [CS231N DL for Vision](http://cs231n.github.io/)  |  Amazing notes from Andrej Karapthy, with lectures on Youtube as well. |
| [Deep Learning Book](https://www.deeplearningbook.org) | This textbook by Ian Goodfellow, Yoshua Bengio, and Aaron Courville is probably the closest we have to a de facto standard textbook for DL. |
| [CS294-158 Deep Unsupervised Learning](https://sites.google.com/view/berkeley-cs294-158-sp19/home) | Open course on deep unsupervised learning from Berkeley.  Looks fantastic.|


#### Special Topics and Blog Posts

| File | Description   |
| :-----------: |:-------------:|
|Karpathy's [Recipe for Training NNs](https://karpathy.github.io/2019/04/25/recipe/) | A great blog post that contains a bunch of little tricks for training deep neural networks |
| Troubleshooting Deep Neural Networks [video](https://www.youtube.com/watch?v=XtCNNwDi9xg) and [slides](http://josh-tobin.com/assets/pdf/troubleshooting-deep-neural-networks-01-19.pdf?utm_campaign=NLP%20News&utm_medium=email&utm_source=Revue%20newsletter) by Josh Tobin | "A field gudie to fixing your model," which has some nice tips. |
| [Different types of convolutions](https://towardsdatascience.com/a-comprehensive-introduction-to-different-types-of-convolutions-in-deep-learning-669281e58215) by Kunlun Bai | Nice blg post providing an overview of many different types of convolutions used in deep learning. |
|Adversarial Examples/Robust ML [Part 1](http://people.csail.mit.edu/madry/lab/blog/adversarial/2018/07/06/adversarial_intro/), [Part 2](http://people.csail.mit.edu/madry/lab/blog/adversarial/2018/07/11/robust_optimization_part1/), and [Part 3](http://people.csail.mit.edu/madry/lab/blog/adversarial/2018/08/10/robust_optimization_part2/) | The [Madry lab](https://people.csail.mit.edu/madry/lab/) is one of the top research groups in robust deep learning research. They put together a fantastic intro to these topics on their blog. I hope they keep making posts... |
|[Distill Attention](https://distill.pub/2016/augmented-rnns/)| Amazingly clear presentation of the attention mechanism and its (early) variants |
| [Lilian Weng Attention post](https://lilianweng.github.io/lil-log/2018/06/24/attention-attention.html) | Nice blog post on attention, self-attention, trasnformers, etc |
|[Distill Building Interpretability](https://distill.pub/2018/building-blocks/)| Coolest visualizations of NN internals I've ever seen|
|[Distill Feature Visualization](https://distill.pub/2017/feature-visualization/)| Running theme: If it's only distill.pub, read it. |
|[Chris Olah Understanding LSTMs](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)| Chris Olah is a master of his craft, and here offers a fantastic overview of LSTMs and GRUs.|
| [Intro to Federated Learning](https://github.com/OpenMined/PySyft/tree/master/examples/tutorials) | Intro to federated learning and PySyft from Andrew Trask and others using PyTorch.|
| [Triplet Loss and Online triplet mining blog post](https://omoindrot.github.io/triplet-loss) | Nice exposition on Olivier Moindrot's blog |
| [Graph Convolutional Neural Networks](https://tkipf.github.io/graph-convolutional-networks/) | Blog post on GCNNs by Thomas Kipf | 

#### Instructive Codebases

| File | Description   |
| :-----------: |:-------------:|
| Sebastian Raschka's [Deep Learning Models Github](https://github.com/rasbt/deeplearning-models)| An impressively comprehensive set of TensorFlow and Pytorch models, annotated and perusable in 80+ Jupyter Notebooks. |
|[Pytorch Tutorials](https://pytorch.org/tutorials/) | The tutorials put out by the pytorch developers are really fantastic. Easy to see why the community is growing so fast. |
| Wiseodd's [Website](https://wiseodd.github.io/) and [Deep Generative Models Github](https://github.com/wiseodd/generative-models) and | An amazing collection of deep learning implementations. | 


### <a name="NLP"></a>  Natural Language Processing

#### Textbooks, Lectures, and Course Notes

| File | Description   |
| :-----------: |:-------------:|
| [Fast.ai Intro to NLP](https://www.fast.ai/2019/07/08/fastai-nlp/) | Code-first intro to NLP from the excellent folks at fast.ai. |
|  [CS224W Deep Learning for NLP 2017](/files/notes/cs224n-2017-merged.pdf)  |  Fantastic course notes on Deep Learning for NLP from Stanford's [CS224](http://web.stanford.edu/class/cs224n/). Updated noteset appears to live [here](https://web.stanford.edu/class/cs224n/readings/). |
|  [CMU CS 11-747 Deep Learning for NLP](http://www.phontron.com/class/nn4nlp2018/schedule.html)  |  Fantastic course on Deep Learning for NLP from CMU's Graham Neubig. Really great lecture videos on Youtube [here](https://www.youtube.com/playlist?list=PLbdKUKMAnh9Qqs5uwEBDfRb_L3YaLbRKq) |
|  [CS224U Natural Language Understanding 2019](/http://web.stanford.edu/class/cs224u/)  |  Another DL+NLP course at Stanford.  Also has accompanying [Youtube videos](https://www.youtube.com/watch?v=tZ_Jrc_nRJY&list=PLoROMvodv4rObpMCir6rNNUlFAn56Js20) and a [Github repo](https://github.com/cgpotts/cs224u/) |

#### Special Topics and Blog Posts

| File | Description   |
| :-----------: |:-------------:|
|[Chris Olah on Word Embeddings](http://colah.github.io/posts/2014-07-NLP-RNNs-Representations/)| Chris Olah explaining world embeddings and the like.|
| [Transformers from Scratch by Peter Bloem](http://www.peterbloem.nl/blog/transformers) | Nice overview of transformer architecures with some great diagrams and code. | 
| [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/) | Nice visualization of how transformer networks work by Jay Alammar. |
|[The Annotated Transformer](http://nlp.seas.harvard.edu/2018/04/03/attention.html)| Harvard's Sasha Rush created a line-by-line annotation of "Attention is All You Need" that also serves as a working notebook. Pedagogical brilliance, and it would be awesome to do this for a couple papers per year.|
|  [Goldberg's Primer on NNs for NLP](/files/notes/Goldber_Primer_Neural_Nets_NLP.pdf)  |  Overview of Deep Learning for NLP from Yoav Goldberg [downloaded from here](http://u.cs.biu.ac.il/~yogo/nnlp.pdf). |
|  [Neubig's Tutorial on NNs for NLP](/files/notes/neubig_nmt_seq2seq.pdf)  |  Overview of Deep Learning for NLP from Graham Neubig. Downloaded from [arxiv](https://arxiv.org/pdf/1703.01619.pdf) and pairs nicely with his course and videos. |


### <a name="RL"></a> Reinforcement Learning 

#### Textbooks, Lectures, and Course Notes

| File | Description   |
| :-----------: |:-------------:|
|[Sutton and Barto Open RL Book](http://incompleteideas.net/book/the-book-2nd.html)| De-facto standard intro to RL, even though the textbook is only now about to be published!|
|[Stanford Reinforcement Learning Course ](http://web.stanford.edu/class/cs234/index.html) by Emma Brunskill| A really great RL class from Stanford. The website has a really nice note set. Also, lecture videos are on [Youtube](https://www.youtube.com/watch?v=FgzM3zpZ55o&list=PLoROMvodv4rOSOPzutgyCTapiGlY2Nd8u).|
|[Berkeley Deep Reinforcement Learning](http://rll.berkeley.edu/deeprlcourse/)| RL class from Berkeley taught by top dogs in the field, lectures posted to Youtube.|

#### Special Topics and Blog Posts

| File | Description   |
| :-----------: |:-------------:|
|[Karpathy's Pong From Pixels](http://karpathy.github.io/2016/05/31/rl/)| Andrej Karpathy has a real gift for didactics. This is a self-contained explanation of deep reinforcement learning sufficient to understand a basic atari agent. |
|[Weng's A (Long) Peek into RL](https://lilianweng.github.io/lil-log/2018/02/19/a-long-peek-into-reinforcement-learning.html)| A nice blog post covering the foundations of reinforcement learning|
|[OpenAI's Intro to RL](https://spinningup.openai.com/en/latest/spinningup/rl_intro.html)| The introductory tutorial for OpenAIs new ["Spinning Up in Deep RL" website](https://blog.openai.com/spinning-up-in-deep-rl/) |

### <a name="bio"></a> Applications in Biology and Medicine

| File | Description   |
| :-----------: |:-------------:|
| [Medical ML Datasets github](https://github.com/beamandrew/medical-data) | Github repo of a bunch of medical ML datasets, compiled by Andrew Beam. |
|[ML for protein design github](https://github.com/yangkky/Machine-learning-for-proteins)| Nice github repo put together by Kevin Yang, covering a bunch of ground in the ML for proteins space.|
|[Best Practices in Single-Cell RNA-Seq Tutorial](https://www.embopress.org/doi/10.15252/msb.20188746)| Excelllent tutorial on single-cell RNA-seq, walking through current best practices at every stage of scRNA-seq analysis.|


### <a name="misc"></a> Miscellaneous websites

| File | Description   |
| :-----------: |:-------------:|
| [Chris Olah's Blog](http://colah.github.io/) | Essentially everything on here is gold. I am so grateful for the hours he must put into these posts.|
|[distill.pub](https://distill.pub)| Distill navigates a really interesting gap between super-blog and research journal. I wish that we had more publications like this. |
| [Sebastian Ruder's blog](http://ruder.io/) | Sebastian has produced a lot of really great explanations, like the one on gradient descent methods I linked to above. He also maintains a [website tracking progress on NLP benchmarks](https://nlpprogress.com/)| 
| [Lillian Weng's Blog](https://lilianweng.github.io/lil-log/)| Great blog on RL, meta-learning, and other topics |
| [ShortScience](http://www.shortscience.org/) | This website contains public summaries/discussions of machine learning, CS, and biology papers. |
| [Berkeley AI Research (BAIR) Blog](https://bair.berkeley.edu/blog/) | BAIR produces a lot of great research, and uses this blog to release more accessible presentations of their papers. | 
| [Off the Convex Path](https://www.offconvex.org/) | Nice blog on machine learning and optimization. | 
| [Ferenc Huszár's blog](https://www.inference.vc/) | Pretty popular blog that has a lot of explorations/musings on ML from an author with a rigorous mathematical perspective | 
|  [Thibaut Lienart's Blog](https://tlienart.github.io/pub/csml.html)  |  This website has some notes on math and optimization that seem interesting.  |



