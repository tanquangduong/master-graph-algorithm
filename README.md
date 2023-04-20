# master-graph-algorithm
Master Graph Algorithm

## ✅ Setup Env
- Create Python environment\
`conda create -n env_name python=3.10`\
`conda activate env_name`
- Create Python environment\
`pip install -r .\path_to_requirements\requirements.txt`

## Graph
- Type of graphs:
  - Undirected graphs. E.g:
    - Mike and Amine know each other
  - Directed graphs. E.g:
    - Mike and his house (Mike lives in a house, but his house does not live in Mike).
    - John manages Paul (John is the manager of Paul).
  - Undirected multigraphs. E.g:
    - Mike and John are classmates are well as co-workers.
  - Directed multigraphs. E.g.
    - Mike reports to John in the office, and John teaches Mike the Python programming language.
- Special types of edges
  - Self-edge. E.g:
    - John transfers money from his business account to his personal account. Such a special relationship can be represented by a self-directed edge.
  - Hyperedge. E.g:
    - Mike, John, and Sarah are working on one specific project
## Social Network Analysis(SNA)
- Network graph analysis is considered social network analysis if the following apply:
  - The vertices of the graph represent people.
  - The edges between them represent social relationships between them, such as a friendship, a common hobby, kinship, a sexual relationship, dislikes, and so on. 
  - The business question that we are trying to answer through graph analysis has some strong social aspect to it.
- SNA can be used for the following:
  - Understanding a users's actions on social media platforms, such as Facebook, Twitter, or LinkedIn
  - Understanding fraud
  - Understanding society's criminal behavior
## Network Analysis Theory
Some important notions, as follows:
- The shortest path
- A neighborhood
- Triangles
- Density
- Centrality measures
- Degree
- Betweenness
- Fairness and closeness
- Eigenvector centrality
- 