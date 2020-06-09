# Learning from data on networks

Modern societies increasingly depend on complex networked systems to support our daily routines. Electrical energy is delivered by the power grid; the Internet enables almost instantaneous world-wide interactions; our economies rest upon a complex network of inter-dependencies spanning the globe. Networks are ubiquitous in complex biological, social, engineering, and physical systems. 
Understanding structures and dynamics defined over such networks has thus become a prevalent challenge across many disciplines. A recurring question which appears in a wide variety of problems is how one can exploit the interplay between the topological structure of the system and available measurements at the nodes (or edges) of the networks. 
The goal of this minisymposium is to bring together researchers from different mathematical communities -- from network science, machine learning, statistics, signal processing and optimization -- to discuss and highlight novel approaches to understand and learn from data defined on networks. 

## Organized by    

[Michael Schaub](https://michaelschaub.github.io/)    (RWTH Aachen University - Germany)   
[Santiago Segarra](https://segarra.rice.edu/)     (Rice University - USA)   
[Francesco Tudisco](https://ftudisco.gitlab.io/)     (Gran Sasso Science Institute - Italy)   


## Session date and time   

June 30, 2020   
Starting at 10:00 am Eastern time (Boston)   
\[7am California, 9am Texas, 3pm UK, 4pm EU, 10pm China\]


## Schedule (tentative)   


| Time (ET)     | Speaker                              | Title                                                                         |
| ------------- | ------------------------------------ | ---------------------------------------------------------------------------- |
| 10:00 - 10:30 | Michael Schaub         | Learning from graphs and data on networks — overview and outlook             |
| 10:30 - 11:00 | Caterina De Bacco      | Incorporating node attributes in community detection for multilayer networks |
| 11:00 - 11:30 | Danai Koutra           | The Power of Summarization in Network Representation Learning (and beyond)   |
| 11:30 - 12:00 | Ekaterina Rapinchuk    | Applications of Auction Dynamics to Data Defined on Networks                 |
| 12:00 - 12:30 | David Gleich           | Nonlinear processes on networks                                              |


See also the conference's [virtual program](https://siam9-my.sharepoint.com/:x:/g/personal/moore_siam_org/EYTLcxWB41NJs2SqNhuHv4UB9SGkLksNw5_3jt-pJP1biw?rtime=RcpDmJML2Eg)  

## Zoom link  
TBA


# Speakers and abstracts

### [Michael Schaub](https://michaelschaub.github.io/)   
RWTH Aachen University (Germany)  
**Learning from graphs and data on networks: overview and outlook**  
Abstract. *Many problems in data science can be framed in terms of analyzing graphs.
In some cases, these graphs are constructed from point-cloud data in order to reveal certain underlying features of the data, e.g., as done in manifold learning.
In other cases, the graphs themselves are the data we would like to understand. A canonical example here is social network network analysis.
A third category are problems in which the data of interest is defined on top of a graph and we would like to leverage the graph structure to understand those data better --- think for instance of dynamical systems such as the flow of traffic or human mobility patterns defined on top of a graph.*

*In this talk we will give a brief overview of these various learning perspectives associated to graphs and data analysis and highlight differences, similarities and challenges among these.
We will particularly focus on the latter perspective: how to learn from data defined on networks? In this context we will discuss the problem of 'topological inference' in more detail, in which we aim to learn a graph from dynamical observations on its nodes.*


### [Caterina De Bacco](https://cdebacco.com/)   
Max Planck Institute for Intelligent Systems (Germany)   
**Incorporating node attributes in community detection for multilayer networks**    
Abstract. *In this work, we propose a new approach for community detection in multilayer and attributed networks. The goal is to assign each network node to clusters by incorporating both the information carried by nodes' attributes and the connectivity patterns in each layer. This is a challenging inference task as one needs to properly combine two types of information and thus leverage the extent to which topological and attribute information contribute to the network's partition. We present an extension of the existing MultiTensor model which was recently developed as a generative model to perform overlapping community detection on multilayer networks by taking into account different types of interactions. Specifically, we incorporate nodes' attributes into the probabilistic framework to uncover groups of nodes that are structurally close but also share some common characteristics. We illustrate its behavior on synthetic and real data.*


### [Danai Koutra](https://web.eecs.umich.edu/~dkoutra/)   
University of Michigan (USA)  
**The Power of Summarization in Network Representation Learning (and beyond)**    
Abstract. *Networks naturally capture a host of real-world interactions, from social interactions and email communication to web browsing to brain activity. Over the past few years, representation learning over networks has been shown to be successful in a variety of downstream tasks, such as classification and link prediction. Most existing approaches seek to learn node representations that capture node proximity. In this talk, I will discuss our recent work on a different class of node representations that aim to preserve the structural similarity between the nodes, which is related to roles and positions in sociology. I will present the lessons learned from designing efficient structural embedding methods for large-scale heterogeneous data, with focus on how we can leverage summarization to overcome the computational challenges and massive storage requirements that many existing techniques face, as well as to gain interpretability. Throughout the talk, I will point out applications to entity linking across data sources (i.e., network alignment), network comparison and classification, professional role discovery, entity resolution, and more.*


### [Ekaterina Rapinchuk](https://users.math.msu.edu/users/merkurje/)   
Michigan State University (USA)  
**Applications of Auction Dynamics to Data Defined on Networks**  
Abstract. *The task of classifying data, where the goal is to divide the data into a number of classes, is a fundamental problem in machine learning. In fact, data classification is an integral part of many practical applications, including classification of 3D point clouds representing 3D objects and scenes. In this paper, we present a new graph-based data classification method, which can be applied to both unsupervised and semi-supervised learning. The graph-based algorithm is derived by optimizing an energy formed using both region-based and boundary-based terms; a gradient flow of the energy is performed using an intuitive auction dynamics technique. The new method is unconditionally stable, able to incorporate class size information and very efficient. The accuracy and efficiency of the procedure is demonstrated by experiments on unsupervised classification of 3D point clouds; in fact, the algorithm is able to classify a point cloud of more than a million points in just over a minute.*



### [David Gleich](https://www.cs.purdue.edu/homes/dgleich/)   
Purdue University (USA)  
**Nonlinear processes on networks**    
Abstract. *We discuss various opportunities and challenges using nonlinear processes on graph data. In particular, we focus on how the lack of linearity opens up an interesting possibility in problems related to semi-supervised learning and seeded clustering where the result of multiple seeds does not combine linearly.*    


