<p><img alt="TigerGraph logo" height="45px" src="https://blobscdn.gitbook.com/v0/b/gitbook-28427.appspot.com/o/spaces%2F-LHvjxIN4__6bA0T-QmU%2Favatar.png?generation=1532158270801864&amp;alt=media" align="left" hspace="10px" vspace="0px"></p>

# Welcome to the TigerLab!
The aim of this **colabatory** is to provide an **Open-Source Educational Space** with the intention of allowing Data Sceintist, Developers, Engineers, and Big Data enthusist to experiment with graph databases using all free tools.
---

>[2020 Data Day Slides: Graph & ML](https://docs.google.com/presentation/d/1bhj3g-sVgBV8PpdHvgb9ZV00OUfb29zKHTzv6qFWvXs/edit?usp=sharing)

## Table of Content:
* [Resources](#resources)
* [Tool List](#tools-list)
* [Tiger Labs](#lab-1---provision-a-graph-playground)
  * [Lab 1 - Provision a Graph Playground](https://medium.com/@jon.herke/deploy-a-graph-database-in-3-steps-no-code-need-d903bd062dae)
  * [Lab 2 - Getting Familiar with GraphStudio](https://medium.com/@jon.herke/exploring-graphstudio-a-ui-for-tigergraph-ed0751a3ff49)
  * [Lab 2.5 - Create a Secret and Generate a Token](https://colab.research.google.com/drive/1sYv3Jvc6KYsqC4D-Rxkvjh4iPnrp4rg7)
  * [Lab 3 - Create and Execute aTensorFlow Model using Graph Features](https://colab.research.google.com/drive/1yXg1UTJynjLKmdCvVNm_ldvurTR6szGN)
  * [Lab 4 - Create and Execute a Graph Convolution Neural-Net](https://colab.research.google.com/drive/11tcL4KXXwY__TmUUTjOf6InFQMC-VsG6)

### Resources
* [**TigerLab**](https://drive.google.com/drive/u/0/folders/1EuL9tTyk_gfk9J76GNhU-DdEaC5I16K2) google drive with all artifacts used in the TigerLab included.
* [**TigerDocs**](https://docs.tigergraph.com/) comprehensive repository of all things TigerGraph. If you have a question this would be the recommended first place to go when searching for an answer.
* [**Community Chat**](https://discord.gg/F2c9b9v) a place to talk and meet other graph developers.
* [**Reddit Community**](https://www.reddit.com/r/tigergraph/) a place have discussions, post content you develop, or tools you build. 

### Tools List

* [**Colabatory**](https://colab.research.google.com/notebooks/welcome.ipynb) is a free web-based interactive development environment using Jupyter notebook that requires no setup and runs entirely in the cloud. 
* [**Jupyter Notebook**](https://jupyter.org/) is an open-source web application that allows you to create and share documents that contain live code, equations, visualizations and narrative text
* [**TigerGraph Cloud**](tgcloud.io) allows you to run TigerGraph without the hassle of running the operations. This is ran on top of AWS and has built-in monitoring using NetData. 
* [**Tensorflow**](https://www.tensorflow.org/) is an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries and community resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML powered applications.
* [**pyTigerGraph**](https://www.tigergraph.com/) is Python package that abstracts the details of calling to a TigerGraph database. This allows you to setup your server details and get started using TigerGraph with Python in single line of code.
* [**Deep Graph Library**](https://www.dgl.ai/) (DGL) is a Python package built for easy implementation of graph neural network model family, on top of existing DL frameworks (e.g. PyTorch, MXNet, Gluon etc.)
* [**Python**](https://www.python.org/) is an interpreted, high-level, general-purpose programming language.

----

### Lab 1 - Provision a Graph Playground

**What you will accomplish?**
- You will gain familiarity with the TigerGraph Cloud portal
- You will have learned to provision an graph instance
- You will have a graph database instance to play with

</br>

**Ready to get Started?**

For this lab we will be spinning up a graph using [tgCloud.io](http://tgcloud.io) portal. If you're reading this right now and not in a workshop, it recommended you checkout this [BLOG](https://medium.com/@jon.herke/deploy-a-graph-database-in-3-steps-no-code-need-d903bd062dae) that walks you through the steps of deploying a graph in minutes. Once you finish the blog come back here and move onto the next lab. 


----
### Lab 2 - Get Familiar with GraphStudio
**What you will accomplish?**

- You will have gained familiarty with GraphStudio a UI for graph
  - Schema Loading
  - Data Mapping
  - Data Loading
  - Graph Exploration
  - Query Builder
- You will have written, published and deployed a query that is exposed as a REST service
- You will have created a SECRET which can be used to generate tokens


**Ready to get Started?**

Let's get into exploring GraphStudio. If you're reading this and are not in a workshop, it's recomended you checkout this [BLOG](https://medium.com/@jon.herke/exploring-graphstudio-a-ui-for-tigergraph-ed0751a3ff49) that provides a basic overview of GraphStudio. Once you finish the blog come back here and move onto the next lab. 


----
### Lab 2.5 - Create a Secret and Generate a Token
**What you will accomplished?**

- You will have used pyTigerGraph a python package that interfaces with TigerGraph
- You will have used a "SECRET" to generate a "TOKEN" to use in the plaground
- You will have used your "TOKEN" to make a call to grab all built-in REST endpoints


**Ready to get Started?**

Let's explore how to do a REST call to your TigerGraph instance. What you will want to do is clone this notebook [connect2TigerGraph](https://colab.research.google.com/drive/1sYv3Jvc6KYsqC4D-Rxkvjh4iPnrp4rg7) by clicking "File > "Save to Drive" and the follow along. Once you finish the notebook come back here and move onto the next lab. 


----

### Lab 3 - Create and Execute a TensorFlow Model using Graph Features
**What you will accomplish?**
- You will have used pyTigerGraph a python package that interfaces with TigerGraph
- You will have used Pandas to convert JSON into DataFrames
- You will have structured your data for TensorFlow
- You will have created a TensorFlow model
- You will have tested your TensorFlow model

**Ready to get Started?**

Let's explore how to do a feature set extraction into a Juypter Notebook environment. To get started you will want to clone this notebook [TigerGraph2TensorFlow](https://colab.research.google.com/drive/1yXg1UTJynjLKmdCvVNm_ldvurTR6szGN) by clicking "File > "Save to Drive" and the follow along. Once you finish the notebook come back here and move onto the next lab.


----

### Lab 4 - Create and Execute a Graph Convolution Neural-Net (GCN)
**What will you accomplish?**

- You will have used pyTigerGraph a python package that interfaces with TigerGraph
* You will have extracted a simple graph structure for input into a GCN
* You will have used DGL to create a 2-layered GCN
* You will have classified a user movie preference based off relationships in a graph

**Ready to get Started?**

Let's explore how to do a graph structure extraction into a Juypter Notebook environment and run it through a GCN. To get started you will want to clone this notebook [MoviePredictionGCN](https://colab.research.google.com/drive/11tcL4KXXwY__TmUUTjOf6InFQMC-VsG6#scrollTo=_BNqh7fz0486) by clicking "File > "Save to Drive" and the follow along. Once you finish the notebook come back here and move onto the next lab.


----