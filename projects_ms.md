# Projects

The projects are listed below. It is worth mentioning that there are possible intersections concerning methods, data, and supervisors.


## Index

- [Network science / Complex networks / Complex systems](#networks)
- [Multiobjective optimization](#moo)
- [Machine Learning / Deep Learning](#machine-learning)
- [Data Science](#data-science)


# Master's degree


## Network science / Complex networks / Complex systems <a name="networks"></a>


1) **Investigate which transport modes were more important during the COVID-19 pandemic** 
> Professor: Vander L. S. Freitas
> 
> Students: Suleimane Ducure
> 
> Description: This project aims to establish a correlation between the structure of mobility networks and the spread of COVID-19. Our hypothesis is that the transportation network can significantly influence the path of the disease, which has been confirmed for the terrestrial mode under certain conditions, as noted by [(Freitas et al, 2020)](http://dx.doi.org/10.1590/0102-311X00184820). However, we seek to determine the role of each transport mode in the spread of the pandemic during different phases.

2) **Characterize mobility networks from different countries, in different scales and topologies (temporal, multilayer)**
> Professor: Vander L. S. Freitas
> 
> Students: Diogo Nascimento
> 
> Description: We aim to create a comprehensive dataset of mobility networks from different regions of the world, encompassing various resolutions (intra-city, inter-city) and types (static, temporal, weighted, multilayer, etc.). The datasets will be downloaded, and the corresponding networks will be generated and stored in a consistent format. Descriptive statistics will be extracted from the networks, and a comparative analysis will be conducted to produce a survey of the different mobility networks. All data and code will be made publicly available, facilitating further research in this field.

3) **Graph Neural Networks for time series forecast**
> Professor: Vander L. S. Freitas
> 
> Students: Fernando Duarte (Ph.D candidate) and Carlos Oliveira
> 
> Description: The goal of this project is to develop a forecasting model for time series data that is contained within the nodes of a network/graph. Our hypothesis is that time series from neighboring nodes influence each other, and should therefore be taken into account when building a forecast model for each individual node. Graph Neural Networks (GNN) are a potentially useful tool for this task, as they can leverage the graph topology when training the model. Instead of simply inputting the time series data for a given node, the model would also take into consideration the time series data for neighboring nodes. We are currently testing this approach to predict the number of COVID-19 cases in a set of cities, taking into account the previous time series data of neighboring cities in a mobility network, as the flow of people between cities can have a direct impact on disease propagation. Another application involves predicting traffic congestion by considering attributes such as flooding, rain, accidents, and previous slowness recordings within a road network.


## Multiobjective optimization <a name="moo"></a>

1) **Surrogate-based Multi-objetive Optimization for Deep Neural Networks Compression**
> Professor: Rodrigo Silva

> Description: It aims to find a trade-off between multiple objectives, such as accuracy and computational efficiency, when compressing deep neural networks. The project will use surrogate models, such as Gaussian processes or decision trees, to efficiently search for optimal solutions that balance these conflicting objectives.

2) **Multi-objetive Feature Extraction for Tabular Data**

> Professor: Rodrigo Silva

> Descrition: It aims to develop approaches for multi-objective feature extraction, which will simultaneously optimize multiple objectives such as classification accuracy, feature compactness, and robustness. The proposed method may utilize evolutionary algorithms to efficiently explore the search space of feature subsets and identify the Pareto-optimal solutions.

3) **Multi-objetive Problem: Guiding under uniformity measure in the decision space**

> Professor: Gladston Moreira

> Student: Open selection process 

> Descrition: It aims to develop approaches for multi-objective optimization that integrates a guiding criterion to promote the uniformity of solutions in the decision variable space into the search procedure. A good representation of solutions in the decision space is also important from the point of view of the decision-making process. See this [paper](https://ieeexplore.ieee.org/document/9037034).


## Machine Learning / Deep Learning <a name="machine-learning"></a>
1) **Automatic Classification of Arrhythmias: Approach Based on Temporal Vectorcardiogram and Graph Neural Networks** 
> Professors: Eduardo J. S. Luz and Vander L. S. Freitas
> 
> Students: Rafael Oliveira, Guilherme L. Silva, Gabriel Garcia, Vinícius Queiroz
> 
> Description: In this project, we propose the classification of heartbeats through graph neural networks in order to extract features simultaneously from two ECG leads plus one temporal component. The premise is that by relating two ECG derivatives in time, new information can be detected and thus enhance the extraction of a more robust feature vector. Additionally, we aim to investigate ways of reducing computational and memory cost, in order to facilitate integration with medical equipment through hardware accelerators.
> 
> Results: In previous works, we investigated the impact of considering more than one ECG lead on arrhythmia classification [article 1](https://ieeexplore.ieee.org/abstract/document/7319564), and we even proposed a new representation of a heartbeat with three dimensions, which we called the temporal vectorcardiogram (TVCG) [article 2](https://www.nature.com/articles/s41598-017-09837-3). We explored complex network techniques to extract features and performed table classification. In current work, we are exploring feature extraction directly from raw data through graph neural networks [article 3](https://sol.sbc.org.br/index.php/sbcas/article/download/21630/21454/), [article 4](https://sol.sbc.org.br/index.php/sbcas/article/download/21630/21454/). Currently, we are exploring the techniques on two databases, the MITDB and the database explored in [article 5](https://sol.sbc.org.br/index.php/sbcas/article/download/21616/21440). The most current code, maintained by the Master's student Rafael Oliveira, can be found at [link]. For a good understanding of the problem, we recommend reading our survey at [link](https://www.sciencedirect.com/science/article/pii/S0169260715003314).
> 
> Work to be done: Current results show that the approach via Graph Convolutional Network (GCN) is promising [article 3, article 4], however, there is still much to be done to make it feasible for clinical use, especially in terms of computational cost. Currently, we need (1) to find/develop more efficient implementations of the visibility graph technique (used to transform a heartbeat into a graph) and (2) to employ the visibility graph on two ECG derivatives at the same time (visibility graph in 2 dimensions). Another research path is (3) to study other ways of mapping a heartbeat (which is a one-dimensional signal) into a graph.

2) **Automatic Classification of Arrhythmias: Approach Based on Self-Supervised Learning** 
> Professors: Eduardo J. S. Luz, Pedro H. L. Silva 
> 
> Students: Guilherme L. Silva
> 
> Description: In this project, we propose the classification of heartbeats using deep learning (convolutional and recurrent networks, attention mechanism) and self-supervised learning. We believe that to make the use of such models more feasible in the field (considering the generalization aspect), self-supervised learning along with the human in the loop could be the right path. 
> 
> Results: So far, we have presented a new pretext task for ECG. Guilherme Silva (MSc candidate), achieved promising results with that pretext task and his thesis will be published soon. For a good understanding of the problem, we recommend reading the survey at [link](https://www.sciencedirect.com/science/article/pii/S0169260715003314).
> 
> Work to be done: (1) Investigate aspects of fairness and unbalance (see [article](https://arxiv.org/abs/2206.02792)), (2) Investigate aspects of uncertainty and impact of distribution shift ([article1](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w42/Combalia_Uncertainty_Estimation_in_Deep_Neural_Networks_for_Dermoscopic_Image_Classification_CVPRW_2020_paper.pdf), [article2](https://openreview.net/pdf?id=LK8bvVSw6rn), [article3](https://vitalab.github.io/blog/2021/06/17/uncertainty.html), [article4](https://arxiv.org/pdf/2206.08871.pdf)), (3) Evaluate computational cost and hardware acceleration (perhaps via FPGA?), Investigate energy-based representation methods, (4) we believe there is room for a survey regarding explainability such as presented in this [paper](https://www.researchgate.net/publication/367881677_A_Short_Survey_on_Machine_Learning_Explainability_An_Application_to_Periocular_Recognition).

3) **Pattern recognition and computer vision techniques applied to biometrics problems** 
> Professors: Eduardo J. S. Luz, Pedro H. L. Silva 
> 
> Students: Adriano Figueiredo
> 
> Description: Biometrics consists of identifying or verifying an individual through a physical/behavioral trait, which is also known as a biometric modality. We are studying some specific modalities, such as ocular biometrics and through biometric signals (ECG, EEG). Currently, we explore deep learning techniques for the task.

> Results: Our group has been working on this topic for over 10 years and has some contributions published in the literature, whether in ocular/periocular biometrics ([paper](https://scholar.google.com.br/citations?user=20pViLEAAAAJ&hl=pt-BR#:~:text=Deep%20periocular%20representation%20aiming%20video%20surveillance)), ECG signal [paper](https://scholar.google.com.br/citations?user=20pViLEAAAAJ&hl=pt-BR#:~:text=Learning%20deep%20off%2Dthe%2Dperson%20heart%20biometrics%20representations), EEG [paper](https://scholar.google.com.br/citations?user=20pViLEAAAAJ&hl=pt-BR#:~:text=Convolutional%20network%20for%20EEG%2Dbased%20biometric), among others (see [paper](https://link.springer.com/article/10.1007/s10462-021-10028-w) and [paper](https://www.mdpi.com/1424-8220/19/13/2968)). Currently, we are building a database to extract signals through cameras using the Eulerian Video Magnification (EVM) method. We are also working to improve a loss function (D-loss - proposed by Prof. Pedro) for biometrics purposes (see [paper](https://ieeexplore.ieee.org/abstract/document/9891934)).


4) **DeepFake Face Recognition**
> Professor: Eduardo J. S. Luz
> 
> Students:
> 
> Description: See this [paper](https://www.sciencedirect.com/science/article/pii/S0925231220316945?casa_token=75SJbD-z5hoAAAAA:-mEJFB2i2y9GmPgHsL9EY-fhU7kCAhLZuOHOJyV6ss_QtrBsQfBA4MOD-NeZmSNPPTRsk4oh0Q) and this [paper](https://dl.acm.org/doi/full/10.1145/3507902?casa_token=Fh1IKv7N-7UAAAAA%3AXUDkj1hYzJbapY8v9xhN6vGkMReFcjwZD6KicXRATIA-GoJTP2CBUWu4eUEWI-aT14BwT_BzL9Ky) for better understanding of the project.

5) **Plant species recognition**
> Professors: Eduardo Luz and Gladston Moreira

> Students: Pedro Castro (Ph.D. candidate)

> Description: Plant species can be recognized by its leaf, flower, fruit, etc. The aim of this project is to investigate deep learning methods in the context of plant species recognition via images. See this [paper](https://ieeexplore.ieee.org/abstract/document/9667141/) for more information. Dataset available within the [paper](https://www.sciencedirect.com/science/article/pii/S2352340921005965).

6) **Deep learning aplied to medical imagens**
> Professors: Eduardo Luz, Gladston Moreira, Pedro Silva and Rodrigo Silva

> Students: Jean Pinheiro

> Description: Application and development of deep learning techniques for problems related to medical imaging. Study of techniques for feature extraction, segmentation, and classification of artifacts in medical images

7) **Natural Language Processing (NLP) and Speech Recognition**
> Professor: Eduardo Luz

> Students: João Paulo R. Alvarenga, Amanda Oliveira

> Description: Recent advances in Automatic Speech Recognition have made it possible to achieve a quality never seen before in the literature, both for languages with abundant data, such as English, which has a large number of studies and for the Portuguese language, which has a more limited amount of resources and studies. This research project explores state-of-the-art techniques for the Portuguese.

## Data Science <a name="data-science"></a>
1) **Pattern recognition and machine learning techniques applied to financial problems**
> Professors: Eduardo Luz and Gladston Moreira

>Students: Marcus Almeira, Mariana Mota, Luisa Cizilio, Andressa Souza

>Description: All financial institutions are adapting to function almost exclusively online. However, the ease of opening digital accounts has brought enormous challenges to the sector. One of the challenges is the ease with which customers move between banks and financial companies, making retention difficult. The ease of opening accounts has also led to an increase in cases of account creation used for fraud. And the uncontrolled explosion in the increase of customers makes credit management virtually impossible to be done manually. In order to assist financial analysts, some form of automation is mandatory. Solutions based on artificial intelligence (AI) and machine learning (ML) techniques, especially artificial neural network models, are powerful tools when there is a good volume of historical data. The project aims to study and develop AI and ML models for fraud detection, credit analysis and customer management.

>Results: This research came from a partnership between the PPGCC/UFOP and Gerencianet (now Efí). See preliminary results in [paper 1](https://sol.sbc.org.br/index.php/eniac/article/download/22791/22614/) and [paper 2](https://sol.sbc.org.br/index.php/eniac/article/download/22772/22595). 

2) **Data Science Applied to Cybersecurity** 
> Professor: Eduardo J. S. Luz 
> 
> Students: 
> 
> Description: Applying machine learning techniques to detect serious threats in the network (with a focus on the industry). See the [link](https://analyticsindiamag.com/top-8-cybersecurity-datasets-for-your-next-machine-learning-project/) for a better idea and datasets.

3) **Dataset distilation**
> Professor: Eduardo Luz

> Students:

> Description:  Dataset distillation aims to derive a smaller dataset from a large one, using synthetic samples, to train models that yield performance comparable with those trained on the original dataset. With this project, we plan to investigate dataset distillation on several tasks in different domains. For a more detailed information see the [paper](https://arxiv.org/abs/2301.07014).

4) **Surrogate-based Multi-objetive Optimization for Deep Neural Networks Compression**
> Professor: Rodrigo Silva

> Description: It aims to find a trade-off between multiple objectives, such as accuracy and computational efficiency, when compressing deep neural networks. The project will use surrogate models, such as Gaussian processes or decision trees, to efficiently search for optimal solutions that balance these conflicting objectives.

5) **Multi-objetive Feature Extraction for Tabular Data**

> Professor: Rodrigo Silva

> Descrition: It aims to develop approaches for multi-objective feature extraction, which will simultaneously optimize multiple objectives such as classification accuracy, feature compactness, and robustness. The proposed method may utilize evolutionary algorithms to efficiently explore the search space of feature subsets and identify the Pareto-optimal solutions.
