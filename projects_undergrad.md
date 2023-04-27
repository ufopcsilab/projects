# Projects

The projects are listed below. It is worth mentioning that there are possible intersections concerning methods, data, and supervisors.


# Undergraduate - Scientific Initiation [IC] and Honours thesis [TCC]


## Index

- [Network science / Complex networks / Complex systems](#networks)
- [Multiobjective optimization](#moo)
- [Machine Learning / Deep Learning](#machine-learning)
- [Data Science](#data-science)


## Network science / Complex networks / Complex systems <a name="networks"></a>

1) **Front-end for the TSAPI and the generation/analysis of functional networks**
> Professor: Vander L. S. Freitas
>
> The former student involved: Vinicius Silva (http://www.monografias.ufop.br/handle/35400000/4934) 
>
> Description: The TSAPI is a distributed API designed to compare sets of time series and produce similarity matrices as output. In this project, we aim to create a front-end interface that can consume the TSAPI and generate functional networks from the produced similarity matrices. Additionally, we will analyze the networks and display plots that visualize the metrics and distributions.

2) **Assess similarity metrics/algorithms for time series concerning different kinds of series (chaotic, periodic, chaotic+periodic, noisy)**
> Professor: Vander L. S. Freitas
> 
> Students: Iuri Diniz, Vinicius Silva
> 
> Description: The generation of functional networks, as described by [(Ferreira et al., 2021)](https://doi.org/10.1140/epjs/s11734-021-00274-y), is an interesting research topic. These networks are formed from nodes that are connected when their properties or attributes are similar. However, a critical challenge in this area is to identify a suitable similarity metric or algorithm, which can be difficult depending on the type of data being compared. Therefore, this project aims to compare various types of temporal series (including chaotic, periodic, chaotic+periodic, noisy, and both real and synthetic data) and evaluate different similarity metrics and algorithms for constructing functional networks. 

3) **Generating and storing temporal collaboration networks**
> Professor: Vander L. S. Freitas
>
> Description: [OpenAlex](https://openalex.org/) is a comprehensive and open catalog of scholarly papers, authors, and institutions. Our objective is qury the database and create temporal networks in standard formats. Currently, there is an API (https://github.com/filipinascimento/openalexnet) available to generate static networks, which could be adapted to the temporal context.

4) **Community detection in temporal networks**
> Professor: Vander L. S. Freitas
> 
> Description: The objective of this project is to implement and compare different community detection algorithms for temporal networks. The [OpenAlex](https://openalex.org/) dataset could serve as a case study for this investigation.
> 
> Literature: [Fortunato (2010)](https://doi.org/10.1016/j.physrep.2009.11.002), [Rossetti and Cazabet (2018)](https://doi.org/10.1145/3172867).

5) **Robustness analysis in oscillator networks**
> Professor: Vander L. S. Freitas
> 
> Previous students: Vinicius Fonseca, Suleimane Ducure, Douglas Barbosa
> 
> Description: The aim is to seek attack strategies that best destroy or keep synchronization. 
> 
> Literature: [Barabasi (2016)](http://networksciencebook.com/chapter/8), [Strogatz and Stewart (1993)](https://www.jstor.org/stable/24941731), [Mallada and Tang (2013)](https://doi.org/10.1088/1751-8113/46/50/505101).

6) **Simulation of spreading models on top of networks**
> Professor: Vander L. S. Freitas
> 
> Students: Gabriel F. da Costa
> 
> Description: Our focus is on simulating spreading models on networks, and there are several options for choosing the model. One possibility is to simulate a metapopulation on each node, or to use contact networks where each node represents an individual. Additionally, we're interested in exploring the development of platforms to facilitate this work. For instance, we could create a website that allows users to upload their own network, select a specific model, simulate it, and visualize/download the results. Another option is to develop a [NetLogo](https://ccl.northwestern.edu/netlogo/) project that can run the model on both synthetic and real networks. Finally, we're also interested in implementing spreading models on multilayer and temporal networks. We are interested in simulating spreading models on top of networks. 
> 
> Literature: [Harko et al. (2014)](https://doi.org/10.1016/j.amc.2014.03.030), [Lamosa et al (2021)](https://doi.org/10.1371/journal.pone.0248126).

7) **Development of a QGIS add-on to generate road networks from shape files**
> Professor: Vander L. S. Freitas
> 
> Description: The objective of this project is to develop a QGIS add-on that can take a shapefile containing road data for a particular region as input and generate a corresponding road network. The resulting network will feature roads as nodes, and connections between these nodes will be created wherever pairs of roads intersect.

8) **Investigate which transport modes were more important during the COVID-19 pandemic** 
> Professor: Vander L. S. Freitas
> 
> Students: Suleimane Ducure
> 
> Description: This project aims to establish a correlation between the structure of mobility networks and the spread of COVID-19. Our hypothesis is that the transportation network can significantly influence the path of the disease, which has been confirmed for the terrestrial mode under certain conditions, as noted by [(Freitas et al, 2020)](http://dx.doi.org/10.1590/0102-311X00184820). However, we seek to determine the role of each transport mode in the spread of the pandemic during different phases.


9) **Characterize mobility networks from different countries, in different scales and topologies (temporal, multilayer)**
> Professor: Vander L. S. Freitas
> 
> Students: Diogo Nascimento
> 
> Description: We aim to create a comprehensive dataset of mobility networks from different regions of the world, encompassing various resolutions (intra-city, inter-city) and types (static, temporal, weighted, multilayer, etc.). The datasets will be downloaded, and the corresponding networks will be generated and stored in a consistent format. Descriptive statistics will be extracted from the networks, and a comparative analysis will be conducted to produce a survey of the different mobility networks. All data and code will be made publicly available, facilitating further research in this field.


## Multiobjective optimization <a name="moo"></a>

1) **Surrogate-based Multi-objetive Optimization for Deep Neural Networks Compression**
> Professor: Rodrigo Silva

> Description: It aims to find a trade-off between multiple objectives, such as accuracy and computational efficiency, when compressing deep neural networks. The project will use surrogate models, such as Gaussian processes or decision trees, to efficiently search for optimal solutions that balance these conflicting objectives.

2) **A Multi-Objective Approach to the Menu Planning Problem Focused on Primary Schools in Minas Gerais**
> Professor: Pedro Silva

> Description: This work had the objective of generating a set of meal plans for primary schools (6th to 9th grade) from Minas Gerais State, using the Multi-objective diet Problem, the Non-Dominated Genetic Algorithm - II ( NSGA-II) and the $\epsilon$-Constraint strategy, in order to minimize the cost and the nutritional error of meals, besides meeting the nutritional needs of teenagers from 11 to 15 years old. To achieve this objective, tests were performed using a database comprehending 97 foods, obtained from the booklet of the \textit{Cardápios da Alimentação Escolar of the Secretaria de Estado de Educação de Minas Gerais} and their nutritional values were obtained from the table \textit{Tabela Brasileira de Composição dos Alimentos (TBCA)}. The cost values of each food were calculated accounting the medium price charged for brazilian retail supermarkets. The proposed methodology was able to generate sets of non-dominated solutions to the problem, where each point represents a solution among the considered objectives. Each non-dominated solution obtained represents a possible set of meal plans for the schools. Moreover, the generated diets match every nutritional value recommended by the consulted references.  

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

2) **Pattern recognition and computer vision techniques applied to biometrics problems** 
> Professors: Eduardo J. S. Luz, Pedro H. L. Silva 
> 
> Students: Adriano Figueiredo
> 
> Description: Biometrics consists of identifying or verifying an individual through a physical/behavioral trait, which is also known as a biometric modality. We are studying some specific modalities, such as ocular biometrics and through biometric signals (ECG, EEG). Currently, we explore deep learning techniques for the task.

> Results: Our group has been working on this topic for over 10 years and has some contributions published in the literature, whether in ocular/periocular biometrics ([paper](https://scholar.google.com.br/citations?user=20pViLEAAAAJ&hl=pt-BR#:~:text=Deep%20periocular%20representation%20aiming%20video%20surveillance)), ECG signal [paper](https://scholar.google.com.br/citations?user=20pViLEAAAAJ&hl=pt-BR#:~:text=Learning%20deep%20off%2Dthe%2Dperson%20heart%20biometrics%20representations), EEG [paper](https://scholar.google.com.br/citations?user=20pViLEAAAAJ&hl=pt-BR#:~:text=Convolutional%20network%20for%20EEG%2Dbased%20biometric), among others (see [paper](https://link.springer.com/article/10.1007/s10462-021-10028-w) and [paper](https://www.mdpi.com/1424-8220/19/13/2968)). Currently, we are building a database to extract signals through cameras using the Eulerian Video Magnification (EVM) method. We are also working to improve a loss function (D-loss - proposed by Prof. Pedro) for biometrics purposes (see [paper](https://ieeexplore.ieee.org/abstract/document/9891934)).


3) **DeepFake Face Recognition**
> Professor: Eduardo J. S. Luz
> 
> Students:
> 
> Description: See this [paper](https://www.sciencedirect.com/science/article/pii/S0925231220316945?casa_token=75SJbD-z5hoAAAAA:-mEJFB2i2y9GmPgHsL9EY-fhU7kCAhLZuOHOJyV6ss_QtrBsQfBA4MOD-NeZmSNPPTRsk4oh0Q) and this [paper](https://dl.acm.org/doi/full/10.1145/3507902?casa_token=Fh1IKv7N-7UAAAAA%3AXUDkj1hYzJbapY8v9xhN6vGkMReFcjwZD6KicXRATIA-GoJTP2CBUWu4eUEWI-aT14BwT_BzL9Ky) for better understanding of the project.

4) **Plant species recognition**
> Professors: Eduardo Luz and Gladston Moreira

> Students: Pedro Castro (Ph.D. candidate)

> Description: Plant species can be recognized by its leaf, flower, fruit, etc. The aim of this project is to investigate deep learning methods in the context of plant species recognition via images.

> Results: We have interesting contributions so far. See this [paper](https://scholar.google.com.br/citations?hl=pt-BR&user=20pViLEAAAAJ&view_op=list_works&sortby=pubdate#:~:text=An%20End%2Dto%2DEnd%20Deep%20Learning%20System%20for%20Hop%20Classification) and this [paper](https://scholar.google.com.br/citations?hl=pt-BR&user=20pViLEAAAAJ&view_op=list_works&sortby=pubdate#:~:text=Dataset%20for%20Hop%20varieties%20classification) for more information.

5) **Deep learning aplied to medical imagens**
> Professors: Eduardo Luz, Gladston Moreira, Pedro Silva and Rodrigo Silva

> Students: Jean Pinheiro

> Description: Application and development of deep learning techniques for problems related to medical imaging. Study of techniques for feature extraction, segmentation, and classification of artifacts in medical images. For reference, see [Luz et at, 2022](https://link.springer.com/article/10.1007/s42600-021-00151-6) and [Silva et al, 2020](https://www.sciencedirect.com/science/article/pii/S2352914820305773)

6) **Natural Language Processing (NLP) and Speech Recognition**
> Professor: Eduardo Luz

> Students: João Paulo R. Alvarenga, Amanda Oliveira

> Description: Recent advances in Automatic Speech Recognition have made it possible to achieve a quality never seen before in the literature, both for languages with abundant data, such as English, which has a large number of studies and for the Portuguese language, which has a more limited amount of resources and studies. This research project explores state-of-the-art techniques for the Portuguese. For reference see [Alvarenga at al.](https://latamt.ieeer9.org/index.php/transactions/article/view/7464) - [Link for video abstract](https://www.youtube.com/watch?v=yJ8FygAPvqw) 
> 
7) **Statistical Tests of Hypotheses Applied to Hyper-parameter Optimization**
> Professor: Rodrigo Silva
 
> Description: This project aims to develop a rigorous and systematic approach for hyper-parameter optimization. It will use statistical testing methods to test hypotheses about the quality of different hyper-parameter configurations and determine the best set of hyper-parameters for a given task.

8) **Interpretable Feature Extraction for tabular data**
> Professor: Rodrigo Silva
 
> Description: This project aims to identify the most important variables in a dataset while also providing insights into why these variables are significant. It may investigate techniques such as LIME, SHAP, and decision trees to understand and explain the feature extraction process.

9) **Surrogate-based Multi-objetive Optimization for Deep Neural Networks Compression**
> Professor: Rodrigo Silva

> Description: It aims to find a trade-off between multiple objectives, such as accuracy and computational efficiency, when compressing deep neural networks. The project will use surrogate models, such as Gaussian processes or decision trees, to efficiently search for optimal solutions that balance these conflicting objectives.

10) **A specialized ChatGPT for a UFOP context**
> Professor: Pedro Silva

> Description: In this project, a chatbot based on ChatGPT is created for the UFOP context. The objective is to respond to the student's questions about the context of the UFOP. Besides, a different approach is to automatically generate content about the CSILab and UFOP.
 

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
