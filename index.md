---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---

# William H. Guss 

I am a computer scientist and mathematician from Salt Lake City, Utah. I currently study at UC Berkeley and work part-time at [Bonsai AI](http://bons.ai) making AI that use other AI to solve problems. A large part of my time is devoted to Machine Learning at Berkeley ([ML@B](http://ml.berkeley.edu/)), a research/consulting organizaton I cofounded in 2015. [[bio](bio)]

My goal is to understand human intelligence by creating artificial intelligence.


## Recent Posts [[blog](/blog)]
{% for post in site.posts limit: 5 %}
{% unless post.categories contains 'unlisted' %}
- [{{ post.title }}]({{ post.url }}). {{ post.date | date_to_string }}
{% endunless %}
{% endfor %}


## Selected Projects [[projects](/dev)]

## Papers, Presentations, Posters

- [Deep Function Machines: Generalized Neural Networks for Topological Layer Expression](dev/dfm). **William H. Guss**. COLT 2017 (Submitting). [[arXiv](https://arxiv.org/abs/1612.04799)]  
![Wave Layer](public/movie_1.gif)



- [Universal Approximation of Nonlinear Operators on Banach Space](dev/dfm). **William H. Guss**. Machine Learning at Berkeley Research Symposium 2016.  [[pdf](public/pdf/operator_approx.pdf)]

-  [Backpropagation-Free Parallel Deep Reinforcement Learning](/dev/openbrain). **William H. Guss**. James Bartlett, Noah Golmant, Phillip Kuznetsov, Max Johansen. NIPS 2017 (WIP). [[pdf](public/pdf/nobackprop.pdf)]

- [Parameter Reduction using Operator Neural Networks](dev/dfm). **William H. Guss**. Microsoft Research Symposium 2016. *Best Poster Award.* [[pdf](public/pdf/param_reduc.pdf)]

- Functional Neural Networks Evaluated by Weierstrass Polynomials. **William H. Guss**, Phillip Kuznetsov, Patrick Chen. Intel ISEF 2015. Pittsburgh, Pennsylvania. [[AAAI' Honorable Mention](https://www.societyforscience.org/content/press-room/intel-isef-2015-special-awards-ceremony)] [[ASA' Honorable Mention](https://www.societyforscience.org/content/press-room/intel-isef-2015-special-awards-ceremony)] 