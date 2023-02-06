# Projects

The projects are listed below. It is worth mentioning that there are possible intersections concerning methods, data, and supervisors.


# Undergraduate - Scientific Initiation [IC] and Honours thesis [TCC]


## Network science / Complex networks / Complex systems

1) **Front-end for the TSAPI and the generation/analysis of functional networks**
> Professor: Vander L. S. Freitas
>
> The former student involved: Vinicius Silva (http://www.monografias.ufop.br/handle/35400000/4934) 
>
> Description: The TSAPI is a distributed API that compares sets of time series against each other, producing similarity matrices as output. This project aims to build a front end that consumes the TSAPI and generates functional networks from the similarity matrices, analyze the networks, and shows plots with metrics and distributions. 

2) **Experiment design with the TSAPI for time series generation and analysis**
> Professor: Vander L. S. Freitas 
> 
> The former student involved: Vinicius Silva (http://www.monografias.ufop.br/handle/35400000/4934)
> 
> Description: ...

3) **Generating and storing temporal collaboration networks**
> Professor: Vander L. S. Freitas
>
> Description: OpenAlex (https://openalex.org/) is An open and comprehensive catalog of scholarly papers, authors, and institutions. One has to generate and store temporal collaboration networks from the OpenAlex dataset, based on specific queries.

4) **Community detection in temporal networks**
> Professor: Vander L. S. Freitas
> 
> Description: Implement community detection algorithms for temporal networks

5) **Robustness analysis in oscillator networks**
> Professor: Vander L. S. Freitas
> 
> Previous students: Vinicius Fonseca, Suleimane Ducure, Douglas Barbosa
> 
> Description: The aim is to seek attack strategies that best destroy or keep synchronization.

6) **Simulation of spreading models on top of networks**
> Professor: Vander L. S. Freitas
> 
> Students: Gabriel F. da Costa
> 
> Description: 
> Possibilities w.r.t. model: 
>- metapopulation on each node.
>- contact networks.
Possibilities w.r.t. development:
>- create a website that allows the user to upload his network;
>- create a NetLogo project to run the model on top of synthetic networks
>- implementation of spreading models on top of multilayer networks; temporal networks

7) **Development of a QGIS add-on to generate road networks from shape files**
> Professor: Vander L. S. Freitas
> 
> Description: From a shape file with the roads of a region, one generates the road network, in which the nodes are roads and the connections occur when pairs of roads intersect.

8) **Correspondences between the structure of mobility networks and the spreading of COVID-19**
> Professor: Vander L. S. Freitas
> 
> Previous students: Suleimane Ducure
>
> Ref: https://doi.org/10.1590/0102-311X00184820


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

2) **Pattern recognition and computer vision techniques applied to biometrics problems** 
> Professors: Eduardo J. S. Luz, Pedro H. L. Silva 
> 
> Students: Adriano Figueiredo
> 
> Description: Biometrics consists of identifying or verifying an individual through a physical/behavioral trait, which is also known as a biometric modality. We are studying some specific modalities, such as ocular biometrics and through biometric signals (ECG, EEG). Currently, we explore deep learning techniques for the task.

> Results: Our group has been working on this topic for over 10 years and has some contributions published in the literature, whether in ocular/periocular biometrics ([paper](https://scholar.google.com.br/citations?user=20pViLEAAAAJ&hl=pt-BR#:~:text=Deep%20periocular%20representation%20aiming%20video%20surveillance)), ECG signal [paper](https://scholar.google.com.br/citations?user=20pViLEAAAAJ&hl=pt-BR#:~:text=Learning%20deep%20off%2Dthe%2Dperson%20heart%20biometrics%20representations), EEG [paper](https://scholar.google.com.br/citations?user=20pViLEAAAAJ&hl=pt-BR#:~:text=Convolutional%20network%20for%20EEG%2Dbased%20biometric), among others (see [paper](https://link.springer.com/article/10.1007/s10462-021-10028-w) and [paper](https://www.mdpi.com/1424-8220/19/13/2968)). Currently, we are building a database to extract signals through cameras using the Eulerian Video Magnification (EVM) method. We are also working to improve a loss function (D-loss - proposed by Prof. Pedro) for biometrics purposes (see [paper](https://ieeexplore.ieee.org/abstract/document/9891934)).


3) **Deep Face Recognition**
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

> Description: Application and development of deep learning techniques for problems related to medical imaging. Study of techniques for feature extraction, segmentation, and classification of artifacts in medical images

6) **Natural Language Processing (NLP) and Speech Recognition**
> Professor: Eduardo Luz

> Students: João Paulo R. Alvarenga, Amanda Oliveira

> Description: Recent advances in Automatic Speech Recognition have made it possible to achieve a quality never seen before in the literature, both for languages with abundant data, such as English, which has a large number of studies and for the Portuguese language, which has a more limited amount of resources and studies. This research project explores state-of-the-art techniques for the Portuguese.
> 
## Data Science
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
