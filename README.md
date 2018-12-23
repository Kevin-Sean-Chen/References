# Welcome to the References wiki!
* These are selected papers I am currently reading. It would be updated when I finish reading/give up or find out/replace with new relevant references, hopefully.
## 1. Predictive coding
* [Predictive coding in the visual cortex: a functional interpretation of some extra-classical receptive-field effects](https://www.cs.utexas.edu/users/dana/nn.pdf)
* * an original paper on predictive coding in V1 RFs
* [The free-energy principle: a unified brain theory?](https://www.nature.com/articles/nrn2787)
* * a more general predictive scheme in brain activity
* [The hippocampus as a predictive map](https://www.nature.com/neuro/journal/v20/n11/full/nn.4650.html)
* * one of the newest publication from Deepmind on prediction
* [Primary Visual Cortex Represents the Difference Between Past and Present](https://academic.oup.com/cercor/article/25/6/1427/298681/Primary-Visual-Cortex-Represents-the-Difference)
* * early results in visual cortex with predictive bahavior

## 2. Cortical structure and circuits
* [General Cortical and Special Prefrontal Connections: Principles from Structure to Function](http://www.annualreviews.org/doi/full/10.1146/annurev-neuro-071714-033936?url_ver=Z39.88-2003&rfr_id=ori%3Arid%3Acrossref.org&rfr_dat=cr_pub%3Dpubmed)
* * anatomy, looking at the structure underlying computation, are extremely powerful and crucial
* [Distributed Hierarchical Processing in the Primate Cerebral Cortex](http://www.cns.nyu.edu/~tony/vns/readings/felleman-vanessen-1991.pdf)
* [Whose cortical column would that be?](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2904586/pdf/fnana-04-00016.pdf)
* [A Canonical Microcircuit for Neocortex](http://www.mitpressjournals.org/doi/abs/10.1162/neco.1989.1.4.480)
* * important hypothesis for canonical microcircuits

## 3. Visual system
* [Local Diversity and Fine-Scale Organization of Receptive Fields in Mouse Visual Cortex](http://www.jneurosci.org/content/31/50/18506)
* * an important reference for V1 mapping, dynamics, and local organization
* [Highly Selective Receptive Fields in Mouse Visual Cortex](http://www.jneurosci.org/content/28/30/7520)
* * important cell typing and RF properties
* [Traveling Waves in Visual Cortex](http://www.cell.com/neuron/pdf/S0896-6273(12)00591-0.pdf)
* * how do global effects like traveling waves relate to local computation in columns
* [Six principles of visual cortical dynamics](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2906257/)
* * reviewing some known principles in visual cortex activities

## 4. Models
#### Network models
* [Inhibitory Plasticity Balances Excitation and Inhibition in Sensory Pathways and Memory Networks](http://science.sciencemag.org/content/334/6062/1569)
* * I am currently implementing the results in this paper
* [Rich-Club Organization in Effective Connectivity among Cortical Neurons](http://www.jneurosci.org/content/36/3/670)
* * rank of functional connectivity in cortex, which is important to investigate in population coding
#### Dynamical systems
* [Self-Tuned Critical Anti-Hebbian Networks](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.102.258102)
* * influential theoretical paper that generalizes dynamics of anti-hebbian networks and links to critical dynamics
* [The Dynamic Brain: From Spiking Neurons to Neural Masses and Cortical Fields](http://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000092)
* * long review on various response models, linking discrete networks and field models
* [Is there chaos in the brain? II. Experimental evidence and related models](http://www.sciencedirect.com/science/article/pii/S1631069103002002)
* * nonlinear dynamic approach in neuroscience
* [Synaptic input sequence discrimination on behavioral timescales mediated by reaction-diffusion chemistry in dendrites](https://elifesciences.org/articles/25827)
* * a link from microscopic biophysics to macroscopic behavior

## 5. Machine learning
* [Why does deep and cheap learning work so well?](https://arxiv.org/abs/1608.08225)
* * theoretical paper that verifies ability of deep learning by locality, symmetry, and "flatness" theories 
* [Deep Predictive Coding Networks for Video Prediction and Unsupervised Learning](https://arxiv.org/abs/1605.08104)
* * the only deep learning project that finally includes predictive coding
* [Opening the Black Box of Deep Neural Networks via Information](https://arxiv.org/abs/1703.00810)
* * fascinating paper that applies information-bottleneck method to machine learning, revealing a noval way to verify representation and phase transition during learning process
* [Neuroscience-Inspired Artificial Intelligence](http://www.cell.com/neuron/abstract/S0896-6273(17)30509-3)
* * current review and opinion from Deepmind

## 6. Biophysics and systems bio
* [Perspectives on theory at the interface of physics and biology](https://arxiv.org/abs/1512.08954)
* * Dr. Bialek's review and opinion in biophysics
* [Physical limits to magnetogenetics](https://elifesciences.org/articles/17210)
* * Dr. Meister's debunk for another paper that claims to bioengineer magnetogenetics
* [Broken Detailed Balance of Filament Dynamics in Active Networks](https://arxiv.org/abs/1603.04783)
* * Application of statistics physics in biomolecule dynamics
* [Probabilistic models of individual and collective animal behavior](https://arxiv.org/abs/1708.00385)
* * Application of statistics physics in collective behavior

## 7. Information theory
* [Information processing in living systems](https://arxiv.org/abs/1412.8752)
* * Dr. Bialek's review and opinion in information theory in biology
* [Sparse low-order interaction network underlies a highly correlated and learnable neural population code](http://www.pnas.org/content/108/23/9679.abstract)
* * functional investigation of sparse and weakly correlated population neural codes
* [Local information transfer as a spatiotemporal filter for complex systems](https://arxiv.org/abs/0809.3275)
* * a nice method to characterise spatiotemporal dynamics via information theory
* [A universal tradeoff between power, precision and speed in physical communication](https://arxiv.org/abs/1603.07758)
* * optimization/trade-off/physical limit paper, this time considering power consumption

## 8. Statistic mechanics
* [Thermodynamics of information](http://jordanmhorowitz.mit.edu/sites/default/files/documents/natureInfo.pdf)
* * linking information measurements and the physical correspondents is extremely fundamental
* [Statistical physics of self-replication](http://www.englandlab.com/uploads/7/8/0/3/7803054/2013jcpsrep.pdf)
* * origin of life in statistical physics term
* [The thermodynamics of prediction](https://arxiv.org/abs/1203.3271)
* * prediction in thermodynamics term, Landauer's principle and physical bounds revisited
* [Learning in Neural Networks Based on a Generalized Fluctuation Theorem](https://arxiv.org/abs/1504.03132)

## 9. Techs
* [Whole-brain calcium imaging with cellular resolution in freely behaving Caenorhabditis elegans](http://www.pnas.org/content/113/8/E1074.full.pdf)
* [Advances in light microscopy for neuroscience](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2820375/)
* * reviewing recent advances in neural recording through optical methods
* [Nanotools for Neuroscience and Brain Activity Mapping](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3665747/)
* [Physical principles for scalable neural recording](https://arxiv.org/abs/1306.5709)
* * a nice paper that estimates physical limits for bioengineering goals, guiding developments and optimization

## 10. Others
* [Selectionist and evolutionary approaches to brain function: a critical appraisal](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3337445/)
* * in terms of "neural Darwinism", how can we really compare evolution in species and dynamics in neuroscience
* [Evaluating cell reprogramming, differentiation and conversion technologies in neuroscience](https://www.nature.com/articles/nrn.2016.46)
* [Consciousness as a State of Matter](https://arxiv.org/abs/1401.1219)
* [Scalar Timing in Memory](https://www.ncbi.nlm.nih.gov/pubmed/6588812)
* [￼￼￼Why do we age?](https://www.nature.com/nature/journal/v408/n6809/full/408233a0.html)
* * ageing and time perception has long been one of the final frontiers for me
* [Bee Foraging in Uncertain Environments Using Predictive Hebbian Learning](https://papers.cnl.salk.edu/PDFs/Bee%20Foraging%20in%20Uncertain%20Environments%20Using%20Predictive%20Hebbian%20Learning%201995-3013.pdf)
* * nothing in neuroscience makes sense except in the light of animal behavior
* [Musical rhythm spectra from Bach to Joplin obey a 1/f power law](http://www.pnas.org/content/109/10/3716)
* * mysterious structure of musics and how they reveal mechanisms of perception are fascinating 
