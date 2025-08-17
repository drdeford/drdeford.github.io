---
layout: archive
permalink: /Current_Research/
title: "Current Research Interests"
author_profile: true
redirect_from: 
  - /Current_Research.md
  - /Current_Research.html
---

<script type="text/javascript" async
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.2/MathJax.js?config=TeX-MML-AM_CHTML">
</script>


This page contains some brief descriptions of my current research interests. For my published papers related to this topics, see the <a href="../Research">Research</a> page. 

<bold><H3>Political Redistricting</H3></bold>

<img src="./images/LWAR.gif" width="24%"  title="A  Markov chain on Arkansas partitions. "  />

  <p> Political redistricting can be abstracted as a graph partitioning problem subject to a
 variety of legal constraints. My main research in this area focuses on developing methods for efficient 
sampling of graph partitions usiing Markov chain techniques. I am also interested in shape based analysis of districting plans and metrics defined on the space of permissible graph partitions. For more details, see my overview of related resources <a href="https://tinyurl.com/gerrytalk"> here</a>. </p>
<p>There are many interesting, open problems in this domain that are well suited for student research projects. 
I also maintain an active list of open mathematical problems related to
 redistricting <a href="../files/GerryProjects-5.pdf">here</a>, please feel free to <a href="mailto:ddeford@vassar.edu"> email me</a> for more
details if any of these catch your interest.                            

<bold><H3> Random Dot Product Graphs </H3></bold>

<img src="./images/EP_Networks.gif" width="24%"  title="RDPG models of European Parliament voting behavior. "  />

<p> The Random Dot Product Graph (RDPG) model is a latent space model for complex networks, where 
each node is associated to a vector in \(\mathbb{R}^d\) and nodes are connected with probability equal 
to the dot product of their respective vectors. The geometry of this relationship provides natural connections to notions of
 comunity assignment and centrality as well as allowing for the construction of multiresolution models with community structure. 
This model has proven useful theoretically, for proving 
consistency results about spectral embeddings, as well as practically, with recent applications to many
machine learning problems on graphs. I am particularly interested in methods for learning RDPG representations
from empirical networks as well as proving results relating the geometric properties of the embeddings to the combinatorial
structure of the associated graphs. </p>


<bold><H3>Entropy in Time Series</H3></bold>

<p align="center">
    <img src="./images/d3walk_colors.gif" width="24%" title="TS visualization with points colored by pattern." />
  <img src="./images/d3points.gif" width="24%"  title="Distribution of steps in 2d plane. "  />
  <img src="./images/d3hist.gif" width="24%" title="Corresponding histogram over patterns."/>
</p>


Time series data consists of real valued samples, indexed by a time parameter, such as daily stock returns or temperature values. I am particularly interested in probabilistic generative models for this
data and their relation to entropy measures. Current work with <a href="https://katherinemath.com">
 Kate Moore</a>  focuses on clustering and  detecting distributional changes using information-theoretic metrics
and Markov based null models.
 These null models represent a given time series by a Markov chain defined on permutations,
 whose transition probabilities are inferred from the data. This model allows for both theoretical results for known distributions as well as an empirical test for divergence between the steady state of the Markov chain and the observed distribution. 


<bold><H3>Pickleball Analytics</H3></bold>

<img src="./images/gifR6404.gif" width="24%"  title="Visualization of the shots in a pickleball point."  />

Motivated by a recent paper about <a href="https://hdsr.mitpress.mit.edu/pub/uy0zl4i1/release/4?readingCollection=40060419">tennis analytics</a> I have been increasingly interested in analyzing 
pickleball match data and in studying the bracket design problem for fair recreational and tournament play formats. More information can be found on my <a href="../Other"> Other Writing</a> page.  With S. Ethier we formulated a Markov chain representation of 
gameplay to evaluate win probabilities under different game models and there are several natural ways to extend that work. Additional current projects include: 
<ul>
<li> Analyzing shot distributions as a function of court position and  shot type.</li>
 <li>Determining game and point winning probabilities as a function of serving rates and player ratings</li>
 <li> Analyzing the fairness properties of King of the Court models compared to round robin or elimination brackets</li>
  <li> Developing complete brackets for mixed partner mixed doubles round robin formats</li>
</ul>

<bold><H3>Representations and Eigenvalues</H3></bold>

<img src="./images/multi_example.png" width="24%"  title="Regular Tree Eigenvalues. "  />


The connection between the Fourier transform on finite groups and eigenvalues of Cayley graphs leads to many 
natural questions, both in graph theory and representation theory.
 I am particularly interested in questions relating to the
 convergence of the spectral measures for sequences of these graphs. One way to formalize this
 quesion is to ask for a combinatorial characterization of
 increasing graph sequences that satisy for all \(\varepsilon > 0\)
 there exists a finite set \(\Lambda \subseteq \mathbb{R}\) and an integer \(N\)
 such that for all \(n > N\) we have
 \(\dfrac{|\{ \lambda \in \operatorname{spec}(G_n): \lambda \notin \Lambda\}|}{|\operatorname{spec}(G_n)|}  < \varepsilon \).
 The future work sections of the papers linked above provide sketches of additional current research questions. Addtionally, various bases for the dihedral groups lead to
families of interger spectra graphs,
 while others define a periodic spectral structure that appears
 to obey a well-defined limit law. Explaining these phenomena is an ongoing research project, see 
<a href="https://github.com/drdeford/Dihedral_Cayley_Reps"> here </a> and <a href="https://github.com/drdeford/Tree_Eigenvalues"> here </a> for related software and figures. 





    
<bold><H3> Multiplex Networks </H3></bold>

<img src="./images/100_d_go.gif" width="24%"  title="Forced Multiplex Diffusion."  />

<p>While standard network models consider a set of nodes an a binary relation between them, multiplex networks
allow for many different types of connections between the nodes. For example, we might consider a social multiplex whose nodes are people and where different types of edges represent 
familial ties, coworkers, and friendship relations.  
</p><p>
 I am particularly interested in dynamical models on these networks, such as information flow through our social network example, and the
properties of their associated operators. Current research includes developing clustering algorithms that 
respect multiplex structure and better understanding the effects of
 modeling choices in application domains, as well as machine learning approaches for inferring inter-layer edge weights.  

</p>




<bold><H3>Other Projects:</H3></bold>
<p>
This section contains links to brief descriptions of various research projects, outside of my main areas, that have also captured my interest.
 Each .pdf contains some background material, thoughts on possible approaches, and a bibliography. 
</p>

<ul>
<li> <a href="../files/Stirling_Summary.pdf">Computing Stirling numbers for families of graphs and graph products</a></li> 
<li> <a href="../files/LHCCRR_Summary.pdf">Finding a module-theoretic decomposition of LHCCRR space and high-order Lucas Bases.</a></li>
<li> <a href="../files/Division_Summary.pdf">Creating an efficient algorithm for finding minimal division chains</a></li>
<li> <a href="../files/Mod_forms_summary.pdf">Investigating the splitting behaviour of theta series lifted via spherical polynomials</a></li>
<li><a href="../files/CS_Networks_summary.pdf"> Applying SFC methods to develop efficient implementations for scientific computing </a>  </li>
</ul>
