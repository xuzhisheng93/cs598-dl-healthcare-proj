# cs598-dl-healthcare-proj

- Paper: [SEMI-SUPERVISED CLASSIFICATION WITH GRAPH CONVOLUTIONAL NETWORKS](https://arxiv.org/pdf/1609.02907.pdf)
  - link: https://arxiv.org/abs/1609.02907
  - link to the original code: https://github.com/tkipf/gcn
- Project Proposal (03/26/2023)
  - up to 4 pages + unlimited references
  - template: https://www.overleaf.com/project/63a77466f9ce7b6ffce27a3b
  1) Cite the original paper.
  2) State the general problem the paper aims to solve. Do not use the same language as the paper.
     - The paper aims to solve the problem of semi-supervised classification, which occurs when only a small portion of the data is labeled, while the rest is unlabeled. The objective is to leverage the information contained in the unlabeled data to improve classification accuracy by learning representations of the data points that capture the underlying structure of the data. The paper proposes a new approach using graph convolutional networks to learn these representations and improve both the accuracy and efficiency of semi-supervised classification.
  3) Describe the new and specific approach taken by the paper. Discuss why it is interesting or innovative.
     - The new approach improved the performance (efficiency) of existing graph-based semi-supervised learning by avoiding explicitly graph-based regularization in the loss function.
     - Existing models usually have assumption that connected nodes in the graph are likely to share the same label. This assumption might have restricted modeling capacity. The method introduced 
  4) Identify the specific hypotheses you plan to verify in your reproduction study.
     - To confirm the complexity is linear while keeping the accuracy high.
  5) Outline any additional ablations you plan to do and explain why they are interesting.
     - Play with different propagation model:
       - memory usage
       - training time
  6) Explain how you have access to the necessary data.
     - The data is preprocessed and stored in the github repository
  7) Discuss the computational feasibility of your proposed work.
     - According to the original paper, the machine used for training contained an Nvidia's Titan graphic card. We have a machine with similar performance and should be able to replicate the implementation.
  8) Specify if you will be re-using existing code and provide a link to it, or if you will implement the code yourself.

- Project Draft (04/16/2023)
- Final Submission (PDF + Presentation + Code) (05/08/2023)
- 
