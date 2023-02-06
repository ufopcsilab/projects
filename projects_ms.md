# Projects

The projects are listed below. It is worth mentioning that there are possible intersections concerning methods, data, and supervisors.



# Master's degree


## Network science / Complex networks / Complex systems


1) **Investigate which transport modes were more important during the COVID-19 pandemic** 
> Professor: Vander L. S. Freitas
> 
> Students: Suleimane Ducure
> 
> Description: ...

2) **Assess similarity metrics/algorithms for time series concerning different kinds of series (chaotic, periódic, chaotic+periodic, noisy)**
> Professor: Vander L. S. Freitas
> 
> Students: Iuri Diniz, Vinicius Silva
> 
> Description: ...

3) **Characterize mobility networks from different countries, in different scales and topologies (temporal, multilayer)**
> Professor: Vander L. S. Freitas
> 
> Students: Diogo Nascimento
> 
> Description: ...

4) **Reservoir computing for time series forecast**
> Professor: Vander L. S. Freitas
> 
> Description: ...

5) **Graph Neural Networks for time series forecast**
> Professor: Vander L. S. Freitas
> 
> Students: Fernando Duarte, Carlos Oliveira
> 
> Description: ...



## Multiobjective optimization


## Machine Learning / Deep Learning
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

## Data Science
> Professors: Eduardo Luz and Gladston Moreira

>Students: 

>Description: All financial institutions are adapting to function almost exclusively online. However, the ease of opening digital accounts has brought enormous challenges to the sector. One of the challenges is the ease with which customers move between banks and financial companies, making retention difficult. The ease of opening accounts has also led to an increase in cases of account creation used for fraud. And the uncontrolled explosion in the increase of customers makes credit management virtually impossible to be done manually. In order to assist financial analysts, some form of automation is mandatory. Solutions based on artificial intelligence (AI) and machine learning (ML) techniques, especially artificial neural network models, are powerful tools when there is a good volume of historical data. The project aims to study and develop AI and ML models for fraud detection, credit analysis and customer management.

>Results: This research arose from a partnership between the PPGCC/UFOP and Gerencianet (now Efí).Preliminar results can be found in [article 1](https://sol.sbc.org.br/index.php/eniac/article/download/22791/22614/) and [article 2](https://sol.sbc.org.br/index.php/eniac/article/download/22772/22595). 
