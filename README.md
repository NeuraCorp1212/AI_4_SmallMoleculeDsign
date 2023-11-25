# AI_for_SmallMoleculeDesign
Welcome to the AI_for_SmallMoleculeDesign repository! Here, we explore the synergy between artificial intelligence and pharmaceutical science, focusing on the screening and design of small molecules. Our goal is to share innovative AI algorithms that contribute to the advancement of drug discovery.

## About
In this section, we provide an overview of the repository's purpose and the exciting intersection of AI and small molecule drug design. Learn about the potential impact of AI algorithms on revolutionizing the pharmaceutical landscape.

## Algorithms —— Case 1
FeatNN
Discover a collection of state-of-the-art AI algorithms specifically tailored for small molecule design. From molecular docking simulations to machine learning models, explore the tools that are reshaping how we approach drug discovery.

Highly improved precision of binding affinity prediction with evolutionary strategy and deep GCN block(addressing the over-smoothing problem).

![alt text](https://github.com/StarLight1212/FeatNN/blob/main/meta/Fig1.jpg "FeatNN Architecture")

FeatNN achieves the SOTA performances in general datasets.
![alt text](https://github.com/StarLight1212/FeatNN/blob/main/meta/Fig2.jpg "SOTA Results")


FeatNN could effectively used in drug discovery and drug screening.

![alt text](https://github.com/StarLight1212/FeatNN/blob/main/meta/Fig6.jpg "Drug Screening Results")

Note: The scripts were encrypted with the encoded algorthm. If you want know the detail of the project, please contact us with email: ansehen@163.com. If you have special needs or are interested in the data set construction process, please contact us, and we will upload and open source the code of the data set construction part in succession. The code of the model part is prohibited from commercial use. If you need the source code for the purpose of learning and education, please contact us. After verification, or you will be sent the model source code by email.
___  

## Required python packages
- python 3.6-3.8
- pytorch torch-deploy-1.8 (GPU 3090, CUDA 11.2)
- torch = 1.10.1+cu113
- torchvision = 0.11.2+cu113
- rdkit (2021.09.4)
- bio = 1.3.3
- biopython = 1.79
- sklearn = 1.0.2
- numpy = 1.21.5
- pandas = 0.24.2
- scipy = 1.7.1
- openbabel = 3.1.1
- argparse


**News:**    
```yaml
The improvement directions of FeatNN mainly include the following 5 points:  
```  
- [x] 1. On a dataset constructed from PDBbind, our model greatly outperforms the SOTA models in CPA prediction tasks. FeatNN considerably outperforms the SOTA baselines in CPA prediction, with R2, root mean square error (RMSE) and Pearson coefficient values that are highly elevated  
- [x] 2. An Evo-Updating block is employed in the protein encoding module to interactively update the sequence and structure information of proteins so that the high-quality features of proteins are extracted and presented, enabling FeatNN to outperform various SOTA models.  
- [x] 3. In FeatNN, the distance matrices of protein residues were discretized into one dimension, and a word embedding strategy was applied to encode protein structure information and significantly reduce the computational cost of the proposed method; however, it still effectively represented the structure information of proteins. 
- [x] 4. With respect to the extraction of compound features, a specific residual connection is applied to represent the molecular graph, in which the features of the initial nodes are added onto each layer of the GCN, such that the graph features representation limitation caused by the notorious oversmoothing problem in traditional deep GCNs is solved.
- [x] 5. With the pretraining and fine-tuning strategy, both the generalization and R2 performance of the optimized model, FeatNNoptm, further increases compared to that of FeatNN.
- [x] 6. FeatNN has excellent generalization in the affinity prediction task, which is vital and pivotal in the drug screening domain. Targeting severe acute respiratory syndrome coronavirus 2 (SARS-CoV-2) 3-chymotrypsin (3C)-like protease and Akt-1, the generalization of FeatNN vastly outperforms the SOTA baseline in the affinity value prediction task.
- [x] 7. The prediction results of FeatNN with different conformations of the same protein are robust when 3D structure information is directly introduced in the model while neglecting the molecular dynamics of the protein.

------

## Usage
Get started on incorporating these AI algorithms into your own research and projects. This section includes guides, tutorials, and examples to help you leverage the power of AI for small molecule design effectively.

## Contributions
We welcome contributions from the community! Whether you have developed a new algorithm or want to share your experiences applying AI to drug discovery, find out how you can contribute to the growth of this repository.

## Resources
Explore additional resources, including research papers, articles, and links to relevant conferences and events. Stay updated on the latest advancements in AI-driven small molecule drug discovery.

Join us on this journey at the intersection of AI and pharmaceuticals, as we strive to revolutionize the process of small molecule design and contribute to the future of medicine!
