---
layout: about
title: about
permalink: /
subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>555 your office number</p>
    <p>123 your address street</p>
    <p>Your City, State 12345</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---


I'm Binglin (Kevin) Ji, a second-year master's student in `Electrical Engineering` and `Computer Engineering` at [Washington University in St. Louis](https://washu.edu). I'm currently a member of [Stream Based Supercomputing Lab](https://sbs.wustl.edu), advised by Prof. [Roger Chamberlain](https://www.ccrc.wustl.edu/~roger/). My research interests lie in **Machine Learning** (Bayesian Inversion) and **Parallel Computing** (AI Inference Acceleration), as well as the intersection of these two areas. 

Before coming to WashU, I worked at [Lenovo Research](https://research.lenovo.com/webapp/view_English/home.html), Shanghai, China, where I developed deep learning algorithms to solve computer vision problems in industrial scenarios and built container-based systems to optimize machine learning workflows.

## Fast GNN Inference on Multi-Core Systems <br> ( in [IPDPS 2025 Workshops](https://www.ipdps.org/ipdps2025/2025-workshops.html) )

Existing standard Graph Neural Network (GNN) libraries face challenges in performance and scalability on modern multi-core systems, especially for large graphs (more than 100,000 vertices) with heavy embeddings. We optimized GCN inference with different parallel strategies according to the properties of input graphs, considering the design trends of multi-core architectures. As a result, we achieved up to **2.64x** inference speed compared to `DGL v2.4.0` (Deep Graph Library) and **3.36x** compared to `PyG v2.6.1` (PyTorch-Geometric), both of which used `PyTorch v2.3.1` as the backend.
