---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---
# William H. Guss 

<img src="/public/home_banner.jpg" width="100%" />
I am a computer scientist and mathematician from Salt Lake City, Utah. My doctoral research was in *deep learning theory* and *deep reinforcement learning* at [Carnegie Mellon University](http://ml.cmu.edu) under [Ruslan Salakhutdinov](http://www.cs.cmu.edu/~rsalakhu/). During my time at Carnegie Mellon, I founded the [MineRL](http://minerl.io) project with the broad goal of developing general AI in Minecraft using human priors. MineRL was acquired by OpenAI in 2020, where I served as a research scientist, [codeveloping](https://scholar.google.com/citations?view_op=view_citation&hl=en&user=5bB_sFcAAAAJ&citation_for_view=5bB_sFcAAAAJ:ULOm3_A8WrAC) [Github Copilot](https://copilot.github.com/) and [Codex](https://openai.com/blog/openai-codex/) in addition to developing algorithsm for imitation learning and reinforcement learning from human priors. Currently I spend most of my time running [lydian.ai], a machine learning and artificial intelligence consulting firm and research lab.

My goal is to understand human intelligence by creating artificial intelligence.

- [Neural Homology Theory](dev/nht)
- [Deep Function Machines](dev/dfm)
- [MineRL: Towards Open-world AGI](http://minerl.io) 
- [lydian.ai](https://lydian.ai)


## Recent Posts [[blog](/blog)]
{% for post in site.posts limit: 5 %}
{% unless post.categories contains 'unlisted' %}
- [{{ post.title }}]({{ post.url }}). {{ post.date | date_to_string }}
{% endunless %}
{% endfor %}

## Papers, Presentations, Posters [[google scholar](https://scholar.google.com/citations?user=5bB_sFcAAAAJ&hl=en)]
- [On Universal Approximation by Neural Networks with Uniform Guarantees on Approximation of Infinite Dimensional Maps](https://arxiv.org/abs/1910.01545) **William H. Guss**, Ruslan Salakhutdinov. Preprint. [[arXiv](https://arxiv.org/abs/1910.01545)]

- [MineRL: A large-scale dataset of Minecraft demonstrations](http://minerl.io/dataset).  **William H. Guss**, Brandon Houghton, Nicholay Topin, Phillip Wang, Cayden Codel, Manuela Veloso, Ruslan Salakhutdinov.  IJCAI, 2019. [[arXiv](https://arxiv.org/abs/1907.13440)]

- [The MineRL competition on sample efficient reinforcement learning using
human priors](http://minerl.io/competition). **William H. Guss**, Cayden Codel, Katja Hofmann, Brandon Houghton, Noboru Kuno, Stephanie Milani, Sharada Mohanty, Diego Perez Liebana, Ruslan Salakhutdinov, Nicholay Topin, Manuela Veloso, Phillip Wang. NeurIPS Competition Track, 2019. [[arXiv](https://arxiv.org/abs/1904.10079)]

- [Towards a theory of neural topology: The
homology of rectified units](/dev/nht). **William H. Guss and Ruslan Salakhutdinov.**  ICML 2018 GIML Workshlop. **Best
Contribution Award**. [[extended abstract](http://gimli.cc/2018/public_abstracts/gimli2018_guss_salakhutdinov.pdf)] 

- [On Characterizing the Capacity of Neural Networks using Algebraic Topology](/dev/nht/empirical). **William H. Guss**, Ruslan Salakhutdinov.  NIPS 2017, DLTP Workshop. [[arXiv](https://arxiv.org/abs/1802.04443)]  [[poster](/public/pdf/dltp2017.pdf)]

- [Towards Neural Homology Theory](/dev/nht). **William H. Guss**, Ruslan Salakhutdinov. Talk, Microsoft Research, 2018. [[slides](/public/pdf/towards_neural_homology_theory.pdf)] 

- Eigen: A Step Towards Conversational AI. **William H. Guss**, James Bartlett, Phillip Kuznetsov, Piyush Patil. Alexa Prize Proceedings 2017. [[proceedings](https://developer.amazon.com/alexaprize/proceedings)]

- [Deep Function Machines: Generalized Neural Networks for Topological Layer Expression](dev/dfm). **William H. Guss**. Preprint. [[arXiv](https://arxiv.org/abs/1612.04799)]  
![Wave Layer](https://github.com/MadcowD/madcowd.github.io/raw/master/public/movie_1.gif)

- [Universal Approximation of Nonlinear Operators on Banach Space](dev/dfm). **William H. Guss**. Machine Learning at Berkeley Research Symposium 2016.  [[pdf](/public/pdf/operator_approx.pdf)]

-  [Backpropagation-Free Parallel Deep Reinforcement Learning](/dev/openbrain). **William H. Guss**. James Bartlett, Noah Golmant, Phillip Kuznetsov, Max Johansen. Preprint (WIP). [[pdf](/public/pdf/nobackprop.pdf)]

- [Parameter Reduction using Operator Neural Networks](dev/dfm). **William H. Guss**. Microsoft Research Symposium 2016. *Best Poster Award.* [[poster](/public/pdf/param_reduc.pdf)]

- Functional Neural Networks Evaluated by Weierstrass Polynomials. **William H. Guss**, Phillip Kuznetsov, Patrick Chen. Intel ISEF 2015. Pittsburgh, Pennsylvania. [[AAAI' Honorable Mention](https://www.societyforscience.org/content/press-room/intel-isef-2015-special-awards-ceremony)] [[ASA' Honorable Mention](https://www.societyforscience.org/content/press-room/intel-isef-2015-special-awards-ceremony)] 
