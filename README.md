Supplementary material for the manuscript: Examining Socio-Economic Isolation in Urban Spaces

Folder descriptions:

- Dataset description: 

- Networks: Global Exposure networks for October and December in csv format.
  A Global Exposure network G=(V, E, W) is a weighted undirected network that results from the union of the individual tract-specific networks G_c=(V_c, E_c, W_c) for each census tract $c$.
  In G_c, each node represents a distinct group defined by unique socio-economic attributes (gender, age-group, and social class). Let $v_i$ and $v_j$ denote the nodes for groups $i$ and $j$, respectively.
  An edge forms between $v_i$ and $v_j$ with probability $P_{ij}(t)$, defined as: $P_{ij}(t) = \frac{m_i^t \cdot m_j^t}{n_c}$, where $m_i^t$ and $m_j^t$ are the numbers of visitors from groups $i$ and $j$ during time $t$,
  and $n_c$ represents the number of POIs in the census tract $c$. The edge weights within the network capture the cumulative probabilities of interactions. I.e., $w_{ij} = \sum_k P_{ij}(t_k)$, where $k$ is the number of
  time blocks in the dataset. time block throughout the week, with each day segmented into four time blocks: 6:00-9:59, 10:00-13:59, 14:00-17:59, and 18:00-21:59.



