---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---

# William H. Guss 

I am a computer scientist and mathematician from Salt Lake City, Utah. I'm currently doing my PhD in *deep learning theory* and *deep reinforcement learning* at Carnegie Mellon University under [Ruslan Salakhutdinov](http://www.cs.cmu.edu/~rsalakhu/). A large amount of my time is spent at [Infoplay AI](http://infoplay.ai), a cryptocurrency hedgefund I cofounded that uses AI to interact with financial markets. [[bio](/bio)]

My goal is to understand human intelligence by creating artificial intelligence.

- [Neural Homology Theory](dev/nht)
- [Deep Function Machines](dev/dfm)





## Recent Posts [[blog](/blog)]
{% for post in site.posts limit: 5 %}
{% unless post.categories contains 'unlisted' %}
- [{{ post.title }}]({{ post.url }}). {{ post.date | date_to_string }}
{% endunless %}
{% endfor %}

## Papers, Presentations, Posters

- [On Characterizing the Capacity of Neural Networks using Algebraic Topology](dev/nht). **William H. Guss**, Ruslan Salakhutdinov. ICML 2018 (Submitted). NIPS 2017, DLTP Workshop. [[poster](public/dltp2017.pdf)]

- Eigen: A Step Towards Conversational AI. **William H. Guss**, James Bartlett, Phillip Kuznetsov, Piyush Patil. Alexa Prize Proceedings 2017. [[proceedings](https://developer.amazon.com/alexaprize/proceedings)]

- [Deep Function Machines: Generalized Neural Networks for Topological Layer Expression](dev/dfm). **William H. Guss**. Preprint. [[arXiv](https://arxiv.org/abs/1612.04799)]  
![Wave Layer](public/movie_1.gif)

- [Universal Approximation of Nonlinear Operators on Banach Space](dev/dfm). **William H. Guss**. Machine Learning at Berkeley Research Symposium 2016.  [[pdf](public/pdf/operator_approx.pdf)]

-  [Backpropagation-Free Parallel Deep Reinforcement Learning](/dev/openbrain). **William H. Guss**. James Bartlett, Noah Golmant, Phillip Kuznetsov, Max Johansen. Preprint (WIP). [[pdf](public/pdf/nobackprop.pdf)]

- [Parameter Reduction using Operator Neural Networks](dev/dfm). **William H. Guss**. Microsoft Research Symposium 2016. *Best Poster Award.* [[poster](public/pdf/param_reduc.pdf)]

- Functional Neural Networks Evaluated by Weierstrass Polynomials. **William H. Guss**, Phillip Kuznetsov, Patrick Chen. Intel ISEF 2015. Pittsburgh, Pennsylvania. [[AAAI' Honorable Mention](https://www.societyforscience.org/content/press-room/intel-isef-2015-special-awards-ceremony)] [[ASA' Honorable Mention](https://www.societyforscience.org/content/press-room/intel-isef-2015-special-awards-ceremony)] 