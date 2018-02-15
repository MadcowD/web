---
layout: paper
title: On Characterizing the Capacity of Neural Networks using Algebraic Topology
authors: [[William Guss, "http://wguss.ml", "1"], [Ruslan Salakhutdinov, "http://www.cs.cmu.edu/~rsalakhu/", "1"]]
institutions: ["<sup>1</sup> Carnegie Mellon University,<br/> Machine Learning Department"]
video_abstract: /public/video.webm
abstract: The learnability of different neural architectures can be characterized directly by computable measures of data complexity. In this paper, we reframe the problem of architecture selection as understanding how data determines the most expressive and generalizable architectures suited to that data, beyond inductive bias. After suggesting algebraic topology as a measure for data complexity, we show that the power of a network to express the topological complexity of a dataset in its decision region is a strictly limiting factor in its ability to generalize. We then provide the first empirical characterization of the topological capacity of neural networks. Our empirical analysis shows that at every level of dataset complexity, neural networks exhibit topological phase transitions. This observation allowed us to connect existing theory to empirically driven conjectures on the choice of architectures for fully-connected neural networks.
arxiv: "https://arxiv.org/abs/1802.04443"
---

## Paper

<table class="paper-link" style="border-style: none;border-radius: none;">
	 		
  <tbody>
  	<tr>
	  <td style="
		  border-radius: 0px;
		border-style: none;
		background:none;
	"><a href="https://arxiv.org/abs/1802.04443"><img class="layered-paper-big" style="height:175px;" src="/public/topcharfirst.png"></a></td>

	  <td style="
		  border-radius: 0px;
		border-style: none;
		background:none;
		padding-left: 3em;
	"><span style="font-size:12pt">W.H. Guss, R. Salakhutdinov</span><br>
	  <b><span style="font-size:12pt">{{ page.title }}</span></b><br>
	  <span style="font-size:12pt">Preprint 2018. (hosted on <a href="https://arxiv.org/abs/1802.04443">arXiv</a>)</span>
	  <span style="font-size:4pt"><a href=""><br></a>
	  </span>
	  </td>
	    
	</tr>
  </tbody>
</table>

## [Neural Homology Theory](/dev/nht)

This work is a part of a broader research topic called Neural Homology Theory. In particular, the empricial characterization given suggests lower bounds on the capacity for neural networks to express complex *topologies.* Neural homology theory provides a theoretical framework for deriving these lower bounds using simple algebraic equations:

<a href="/dev/nht/"><img src="/public/nhomologytheory.png" width="100%" /></a>
