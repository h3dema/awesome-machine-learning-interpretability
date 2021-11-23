# awesome-machine-learning-*interpretability* [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated, but probably biased and incomplete, list of awesome machine learning interpretability resources.

If you want to contribute to this list (*and please do!*) read over the [contribution guidelines](contributing.md), send a pull request, or contact me [@jpatrickhall](https://twitter.com/jpatrickhall).

**An incomplete, imperfect blueprint for a more human-centered, lower-risk machine learning.** The resources in this repository can be used to do many of these things today. *The resources in this repository should not be considered legal compliance advice.*
![alt-text](https://github.com/h2oai/mli-resources/blob/master/blueprint.png)
</br>Image credit: H2O.ai Machine Learning Interpretability team, https://github.com/h2oai/mli-resources.


## Table of Contents

* [Comprehensive Software Examples and Tutorials](https://github.com/jphall663/awesome-machine-learning-interpretability#comprehensive-software-examples-and-tutorials)
* Explainability- or Fairness-Enhancing Software Packages
  * [Browser](https://github.com/jphall663/awesome-machine-learning-interpretability#browser)
  * [Python](https://github.com/jphall663/awesome-machine-learning-interpretability#python)
  * [R](https://github.com/jphall663/awesome-machine-learning-interpretability#r)
* [Free Books](https://github.com/jphall663/awesome-machine-learning-interpretability#free-books)
* [Other Interpretability and Fairness Resources and Lists](https://github.com/jphall663/awesome-machine-learning-interpretability#other-interpretability-and-fairness-resources-and-lists)
* [Review and General Papers](https://github.com/jphall663/awesome-machine-learning-interpretability#review-and-general-papers)
* [Teaching Resources](https://github.com/jphall663/awesome-machine-learning-interpretability#teaching-resources)
* Interpretable ("Whitebox") or Fair Modeling Packages
  * [C/C++](https://github.com/jphall663/awesome-machine-learning-interpretability#cc)
  * [Python](https://github.com/jphall663/awesome-machine-learning-interpretability#python-1)
  * [R](https://github.com/jphall663/awesome-machine-learning-interpretability#r-1)

## Comprehensive Software Examples and Tutorials

* [Getting a Window into your Black Box Model](http://projects.rajivshah.com/inter/ReasonCode_NFL.html)
* [IML](https://mybinder.org/v2/gh/christophM/iml/master?filepath=./notebooks/tutorial-intro.ipynb)
* [Interpretable Machine Learning with Python](https://github.com/jphall663/interpretable_machine_learning_with_python)
* [Interpreting Machine Learning Models with the iml Package](http://uc-r.github.io/iml-pkg)
* [Interpretable Machine Learning using Counterfactuals](https://docs.seldon.io/projects/alibi/en/v0.2.0/examples/cf_mnist.html)
* [Machine Learning Explainability by Kaggle Learn](https://www.kaggle.com/learn/machine-learning-explainability)
* [Model Interpretability with DALEX](http://uc-r.github.io/dalex)
* Model Interpretation series by Dipanjan (DJ) Sarkar:
  * [The Importance of Human Interpretable Machine Learning](https://towardsdatascience.com/human-interpretable-machine-learning-part-1-the-need-and-importance-of-model-interpretation-2ed758f5f476)
  * [Model Interpretation Strategies](https://towardsdatascience.com/explainable-artificial-intelligence-part-2-model-interpretation-strategies-75d4afa6b739)
  * [Hands-on Machine Learning Model Interpretation](https://towardsdatascience.com/explainable-artificial-intelligence-part-3-hands-on-machine-learning-model-interpretation-e8ebe5afc608)
  * [Interpreting Deep Learning Models for Computer Vision](https://towardsdatascience.com/explainable-artificial-intelligence-part-3-hands-on-machine-learning-model-interpretation-e8ebe5afc608)
* [Partial Dependence Plots in R](https://journal.r-project.org/archive/2017/RJ-2017-016/)
* [Saliency Maps for Deep
  Learning](https://medium.com/@thelastalias/saliency-maps-for-deep-learning-part-1-vanilla-gradient-1d0665de3284)
* [Visualizing ML Models with LIME](http://uc-r.github.io/lime)
* [What does a CNN see?](https://colab.research.google.com/drive/1xM6UZ9OdpGDnHBljZ0RglHV_kBrZ4e-9)
* [Visualizing and debugging deep convolutional networks](https://rohitghosh.github.io/2018/01/05/visualising-debugging-deep-neural-networks/)

## Explainability- or Fairness-Enhancing Software Packages

### Browser

* [What-if Tool](https://pair-code.github.io/what-if-tool/index.html#about)
* [TensorBoard Projector](http://projector.tensorflow.org)

### Python

* [acd](https://github.com/csinva/hierarchical_dnn_interpretations)
* [aequitas](https://github.com/dssg/aequitas)
* [AI Fairness 360](http://aif360.mybluemix.net)
* [AI Explainability 360](https://github.com/IBM/AIX360)
* [algofairness](https://github.com/algofairness)
* [Alibi](https://github.com/SeldonIO/alibi)
* [anchor](https://github.com/marcotcr/anchor)
* [BlackBoxAuditing](https://github.com/algofairness/BlackBoxAuditing)
* [casme](https://github.com/kondiz/casme)
* [ContrastiveExplanation (Foil Trees)](https://github.com/MarcelRobeer/ContrastiveExplanation)
* [DALEXtra]()
* [DeepExplain](https://github.com/marcoancona/DeepExplain)
* [deeplift](https://github.com/kundajelab/deeplift)
* [deepvis](https://github.com/yosinski/deep-visualization-toolbox)
* [eli5](https://github.com/TeamHG-Memex/eli5)
* [fairml](https://github.com/adebayoj/fairml)
* [fairness](https://github.com/algofairness/fairness-comparison)
* [foolbox](https://github.com/bethgelab/foolbox)
* [Grad-CAM](https://github.com/topics/grad-cam)
* [iNNvestigate neural nets](https://github.com/albermax/innvestigate)
* [Integrated-Gradients](https://github.com/ankurtaly/Integrated-Gradients)
* [interpret_with_rules](https://github.com/clips/interpret_with_rules)
* [Keras-vis](https://github.com/raghakot/keras-vis)
* [keract](https://github.com/philipperemy/keract/)
* [lofo-importance](https://github.com/aerdem4/lofo-importance)
* [L2X](https://github.com/Jianbo-Lab/L2X)
* [lime](https://github.com/marcotcr/lime)
* [lrp_toolbox](https://github.com/sebastian-lapuschkin/lrp_toolbox)
* [microsoft/interpret](https://github.com/Microsoft/interpret)
* [MLextend](http://rasbt.github.io/mlxtend/)
* [PDPbox](https://github.com/SauceCat/PDPbox)
* [pyBreakDown](https://github.com/MI2DataLab/pyBreakDown)
* [PyCEbox](https://github.com/AustinRochford/PyCEbox)
* [rationale](https://github.com/taolei87/rcnn/tree/master/code/rationale)
* [robustness](https://github.com/MadryLab/robustness)
* [RISE](https://github.com/eclique/RISE) 
* [shap](https://github.com/slundberg/shap)
* [Skater](https://github.com/datascienceinc/Skater)
* [tensorfow/cleverhans](https://github.com/tensorflow/cleverhans)
* [tensorflow/lucid](https://github.com/tensorflow/lucid)
* [tensorflow/model-analysis](https://github.com/tensorflow/model-analysis)
* [tensorflow/privacy](https://github.com/tensorflow/privacy)
* [tensorfuzz](https://github.com/brain-research/tensorfuzz)
* [TensorWatch](https://github.com/microsoft/tensorwatch)
* [tf-explain](https://github.com/sicara/tf-explain)
* [Themis](https://github.com/LASER-UMASS/Themis)
* [themis-ml](https://github.com/cosmicBboy/themis-ml)
* [treeinterpreter](https://github.com/andosa/treeinterpreter)
* [woe](https://github.com/boredbird/woe)
* [xai](https://github.com/EthicalML/xai)
* [yellowbrick](https://github.com/DistrictDataLabs/yellowbrick)

### R

* [ALEPlot](https://cran.r-project.org/web/packages/ALEPlot/index.html)
* [breakDown](https://pbiecek.github.io/breakDown/index.html)
* [DrWhyAI](https://github.com/ModelOriented/DrWhy)
* [DALEX](https://github.com/pbiecek/DALEX)
* [DALEXtra](https://cran.r-project.org/web/packages/DALEXtra/index.html)
* [EloML](https://github.com/ModelOriented/EloML)
* [ExplainPrediction](https://github.com/rmarko/ExplainPrediction)
* [featureImportance](https://github.com/giuseppec/featureImportance)
* [forestmodel](https://cran.r-project.org/web/packages/forestmodel/index.html)
* [fscaret](https://cran.r-project.org/web/packages/fscaret/)
* [ICEbox](https://cran.r-project.org/web/packages/ICEbox/index.html)
* [iml](https://github.com/christophM/iml)
* [lightgbmExplainer](https://github.com/lantanacamara/lightgbmExplainer)
* [lime](https://github.com/thomasp85/lime)
* [live](https://cran.r-project.org/web/packages/live/index.html)
* [mcr](https://github.com/aaronjfisher/mcr)
* [modelDown](https://cran.r-project.org/web/packages/modelDown/index.html)
* [modelOriented](https://github.com/ModelOriented)
* [modelStudio](https://github.com/ModelOriented/modelStudio)
* [pdp](https://bgreenwell.github.io/pdp/index.html)
* [shapleyR](https://github.com/redichh/ShapleyR)
* [shapper](https://cran.r-project.org/web/packages/shapper/index.html)
* [smbinning](https://cran.r-project.org/web/packages/smbinning/index.html)
* [vip](https://github.com/koalaverse/vip)
* [xgboostExplainer](https://github.com/AppliedDataSciencePartners/xgboostExplainer)

## Free Books

* [An Introduction to Machine Learning Interpretability](https://www.h2o.ai/oreilly-mli-booklet-2019/)
* [Fairness and Machine Learning](http://fairmlbook.org/)
* [Interpretable Machine Learning](https://christophm.github.io/interpretable-ml-book/)


## Other Interpretability and Fairness Resources and Lists

* [8 Principles of Responsible ML](https://ethical.institute/principles.html)
* [ACM FAT* 2019 Youtube Playlist](https://www.youtube.com/playlist?list=PLXA0IWa3BpHk7fE8IH6wXNEfAZyr3A5Yb)
* [AI Ethics Guidelines Global Inventory](https://algorithmwatch.org/en/project/ai-ethics-guidelines-global-inventory/)
* [AllenNLP Interpret: A Framework for Explaining Predictions of NLP Models](http://sameersingh.org/files/papers/allennlp-interpret-demo-emnlp19.pdf)
* [Awesome interpretable machine learning](https://github.com/lopusz/awesome-interpretable-machine-learning) ;)
* [Awesome machine learning operations](https://github.com/EthicalML/awesome-machine-learning-operations)
* [algoaware](https://www.algoaware.eu/)
* [Beyond Explainability: A Practical Guide to Managing Risk in Machine Learning Models](https://go.immuta.com/beyond-explainability-white-paper)
* [criticalML](https://github.com/rockita/criticalML)
* [Debugging Machine Learning Models (ICLR workshop proceedings)](https://debug-ml-iclr2019.github.io/)
* [Deep Insights into Explainability and Interpretability of Machine Learning Algorithms and Applications to Risk Management](https://ww2.amstat.org/meetings/jsm/2019/onlineprogram/AbstractDetails.cfm?abstractid=303053)
* [Distill](https://distill.pub) 
* [Fairness, Accountability, and Transparency in Machine Learning (FAT/ML) Scholarship](https://www.fatml.org/resources/relevant-scholarship)
* [Machine Learning Ethics References](https://github.com/radames/Machine-Learning-Ethics-References)
* [Machine Learning Interpretability Resources](https://github.com/h2oai/mli-resources)
* [MIT AI Ethics Reading Group](https://mitaiethics.github.io/)
* [private-ai-resources](https://github.com/OpenMined/private-ai-resources)
* [Warning Signs: The Future of Privacy and Security in an Age of Machine Learning](https://fpf.org/wp-content/uploads/2019/09/FPF_WarningSigns_Report.pdf)
* [XAI Resources](https://github.com/pbiecek/xai_resources)
* [You Created A Machine Learning Application Now Make Sure It's Secure](https://www.oreilly.com/ideas/you-created-a-machine-learning-application-now-make-sure-its-secure)

## Review and General Papers

* [A Comparative Study of Fairness-Enhancing Interventions in Machine Learning](https://arxiv.org/pdf/1802.04422.pdf)
* [A Survey Of Methods For Explaining Black Box Models](https://arxiv.org/pdf/1802.01933.pdf)
* [A Marauder’s Map of Security and Privacy in Machine Learning](https://arxiv.org/pdf/1811.01134.pdf)
* [Challenges for Transparency](https://arxiv.org/pdf/1708.01870.pdf)
* [Explaining Explanations: An Overview of Interpretability of Machine Learning](https://arxiv.org/pdf/1806.00069.pdf)
* [Explanation in Human-AI Systems: A Literature Meta-Review, Synopsis of Key Ideas and Publications, and Bibliography for Explainable AI](https://arxiv.org/abs/1902.01876v1)
* [Interpretable Machine Learning: Definitions, Methods, and Applications](https://arxiv.org/abs/1901.04592)
* [Machine Learning Explainability in Finance](https://www.bankofengland.co.uk/-/media/boe/files/working-paper/2019/machine-learning-explainability-in-finance-an-application-to-default-risk-analysis)
* [On the Art and Science of Machine Learning Explanations](https://arxiv.org/pdf/1810.02909.pdf)
* [On the Responsibility of Technologists: A Prologue and Primer](https://algo-stats.info/2018/04/15/on-the-responsibility-of-technologists-a-prologue-and-primer/)
* [Please Stop Explaining Black Box Models for High-Stakes Decisions](https://arxiv.org/pdf/1811.10154.pdf)
* [The Mythos of Model Interpretability](https://arxiv.org/pdf/1606.03490.pdf)
* [Towards A Rigorous Science of Interpretable Machine Learning](https://arxiv.org/pdf/1702.08608.pdf)
* [The Security of Machine Learning](https://people.eecs.berkeley.edu/~adj/publications/paper-files/SecML-MLJ2010.pdf)
* [Techniques for Interpretable Machine Learning](https://arxiv.org/pdf/1808.00033.pdf)
* [Trends and Trajectories for Explainable, Accountable and Intelligible Systems: An HCI Research Agenda](https://dl.acm.org/citation.cfm?id=3174156)

## Teaching Resources

* [An Introduction to Data Ethics](https://www.scu.edu/ethics/focus-areas/technology-ethics/resources/an-introduction-to-data-ethics/)
* [Fairness in Machine Learning](https://fairmlclass.github.io/)
* [Human-Center Machine Learning](http://courses.mpi-sws.org/hcml-ws18/)
* [Practical Model Interpretability](https://github.com/jphall663/GWU_data_mining/blob/master/10_model_interpretability/10_model_interpretability.md)
* [Trustworthy Deep Learning](https://berkeley-deep-learning.github.io/cs294-131-s19/)

## Interpretable ("Whitebox") or Fair Modeling Packages

### C/C++

* [Certifiably Optimal RulE ListS](https://github.com/nlarusstone/corels)

### Python

* [Bayesian Case Model](https://users.cs.duke.edu/~cynthia/code/BCM.zip)
* [Bayesian Ors-Of-Ands](https://github.com/wangtongada/BOA)
* [Bayesian Rule List (BRL)](https://users.cs.duke.edu/~cynthia/code/BRL_supplement_code.zip)
* [Explainable Boosting Machine (EBM)](https://github.com/Microsoft/interpret)
* [fair-classification](https://github.com/mbilalzafar/fair-classification)
* [Falling Rule List (FRL)](https://users.cs.duke.edu/~cynthia/code/falling_rule_list.zip)
* H2O-3
  * [Penalized Generalized Linear Models](http://docs.h2o.ai/h2o/latest-stable/h2o-py/docs/modeling.html#h2ogeneralizedlinearestimator)
  * [Monotonic GBM](http://docs.h2o.ai/h2o/latest-stable/h2o-py/docs/modeling.html#h2ogradientboostingestimator)
  * [Sparse Principal Components (GLRM)](http://docs.h2o.ai/h2o/latest-stable/h2o-py/docs/modeling.html#h2ogeneralizedlowrankestimator)
* [Monotonic](http://xgboost.readthedocs.io/en/latest/tutorials/monotonic.html) [XGBoost](http://xgboost.readthedocs.io/en/latest/)
* [pyGAM](https://github.com/dswah/pyGAM)
* [Risk-SLIM](https://github.com/ustunb/risk-SLIM)
* Scikit-learn
  * [Decision Trees](http://scikit-learn.org/stable/modules/tree.html)
  * [Generalized Linear Models](http://scikit-learn.org/stable/modules/linear_model.html)
  * [Sparse Principal Components](http://scikit-learn.org/stable/modules/decomposition.html#sparse-principal-components-analysis-sparsepca-and-minibatchsparsepca)
* [sklearn-expertsys](https://github.com/tmadl/sklearn-expertsys)
* [skope-rules](https://github.com/scikit-learn-contrib/skope-rules)
* [Super-sparse Linear Integer models (SLIMs)](https://github.com/ustunb/slim-python)
* [tensorflow/lattice](https://github.com/tensorflow/lattice)
* [EconML: A Python Package for ML-Based Heterogeneous Treatment Effects Estimation](https://github.com/microsoft/EconML)

### R

* [arules](https://cran.r-project.org/web/packages/arules/index.html)
* [Causal SVM](https://github.com/shangtai/githubcausalsvm)
* [elasticnet](https://cran.r-project.org/web/packages/elasticnet/index.html)
* [gam](https://cran.r-project.org/web/packages/gam/index.html)
* [glm2](https://cran.r-project.org/web/packages/glm2/)
* [glmnet](https://cran.r-project.org/web/packages/glmnet/index.html)
* H2O-3
  * [Penalized Generalized Linear Models](http://docs.h2o.ai/h2o/latest-stable/h2o-r/docs/reference/h2o.glm.html)
  * [Monotonic GBM](http://docs.h2o.ai/h2o/latest-stable/h2o-r/docs/reference/h2o.gbm.html)
  * [Sparse Principal Components (GLRM)](http://docs.h2o.ai/h2o/latest-stable/h2o-r/docs/reference/h2o.glrm.html)
* [Monotonic](http://xgboost.readthedocs.io/en/latest/tutorials/monotonic.html) [XGBoost](http://xgboost.readthedocs.io/en/latest/)
* [quantreg](https://cran.r-project.org/web/packages/quantreg/index.html)
* [rpart](https://cran.r-project.org/web/packages/rpart/index.html)
* [RuleFit](http://statweb.stanford.edu/~jhf/R_RuleFit.html)
* [Scalable Bayesian Rule Lists (SBRL)](https://users.cs.duke.edu/~cynthia/code/sbrl_1.0.tar.gz)
