# recommendation-reference-paper-list

## Collaborative Filtering Based Model
|Title|Structure|Dataset|Baseline|Metric|
|:---:|:---:|:---:|:---:|:---:|
|Atentive Collaborative Filtering: Multimedia Recommendation with Item- and Component-Level Attention </br> **(ACF)**</br> [2017 SIGIR(ACM)\*\*] </br>[[paper]][1]|![image](https://user-images.githubusercontent.com/67678405/120065206-1178c480-c0ab-11eb-8357-2097d3b3ff5c.png)|Pinterest</br>Vine|**[CF-based]**</br>UCF</br>itemKNN</br>BPR</br>SVD++</br>**[Content-based]**</br>CBF</br>**[Hybrid]**</br>SVDFeature</br>Deep Hybrid|HR</br>NDCG</br>(L-O-O\*)</br>(K=10~100)</br>(dim=32,64,128)|
|Deep Matrix Factorization Models for Recommender Systems </br> **(DMF)** </br> [2017 IJCAI\*\*] </br> [[paper]][2]|![image](https://user-images.githubusercontent.com/67678405/121487195-d19bd080-ca0c-11eb-81b0-9f6fcbe6bf0b.png)|ML 100K</br>ML 1m</br>Amusic</br>Amovie|itemPOP</br>itemKNN</br>eALS</br>NeuMF-p|HR</br>NDCG</br>(L-O-O\*)</br>(K=10)|
|Neural Collaborative Filtering </br> **(NeuMF)** </br> [2017 WWW\*\*] </br> [[paper]][3] |![image](https://user-images.githubusercontent.com/67678405/121765576-d5ebf900-cb86-11eb-8c77-59cb37adf873.png)|ML 1m</br>Pinterest|itemPOP</br>itemKNN</br>BPR</br>eALS|HR</br>NDCG</br>(L-O-O\*)</br>(K=1~10)</br>(dim=8,16,32,64)|
|A Neural Collaborative Filtering Model with Interaction-based Neighborhood</br>**(NNCF)**</br>[2017 CIKM(ACM)\*\*]</br>[[paper]][4]|![image](https://user-images.githubusercontent.com/67678405/121795239-def1ce80-cc49-11eb-95ac-c415624f21cd.png)|Delicious</br>ML 1m</br>Rossmann|itemPOP</br>itemKNN</br>BPR</br>NeuMF|HR</br>NDCG</br>(L-O-O\*)</br>(K=5,10)</br>(dim=32)|
|NAIS: Neural Attentive Item Similarity Model for Recommendation</br>**(NAIS)**</br>[2018 IEEE]</br>[[paper]][5]|![image](https://user-images.githubusercontent.com/67678405/121794784-22e2d480-cc46-11eb-9d56-4e46e7c9bde9.png)|ML 1m</br>Pinterest</br>(same set as NCF)|itemPOP</br>itemKNN</br>FISM</br>MF-BPR</br>MF-eALS</br>MLP|HR</br>NDCG</br>(L-O-O\*)</br>(K=10)</br>(dim=8,16,32,64)|
|Outer Product-based Neural Collaborative Filtering</br>**(ConvNCF)**</br>[2018 arXiv]</br>[[paper]][6]|![image](https://user-images.githubusercontent.com/67678405/121985122-18077b80-cdcf-11eb-9973-ed2e81e65be9.png)|Yelp</br>Gowalla|itemPOP</br>MF-BPR</br>MLP</br>JRL</br>NeuMF|HR</br>NDCG</br>(L-O-O-1000)</br>(K=10)</br>(dim=64)|
|Deep Item-based Collaborative Filtering for Top-N Recommendation </br> **(DeepICF)**</br>[2019 ACM]</br>[[paper]][7]|![image](https://user-images.githubusercontent.com/67678405/121867715-36bc3280-cd3b-11eb-9f8d-e96b24aaaebd.png)|ML 1m</br>Pinterest|itemPOP</br>itemKNN</br>HOSLIM</br>BPR</br>eALS</br>MLP</br>FISM|HR</br>NDCG</br>(L-O-O\*)</br>(K=10)</br>(dim=8,16,32,64)|
|Matching User with Item Set: Collaborative Bundle Recommendation with Deep Attention Network</br>**(DAM)**</br>[2019 IJCAI\*\*]</br>[[paper]][8]|![image](https://user-images.githubusercontent.com/67678405/122144133-cd990400-ce8d-11eb-9799-444ea40708f2.png)|Netease</br>Youshu|BPR</br>NCF</br>BR</br>EFM|</br>Recall</br>MAP</br>(L-O-O\*)</br>(K=5)</br>(dim=5,10)|
|Neural Graph Collaborative Filtering</br> **(NGCF)**</br> [2019 SIGIR(ACM)\*\*] </br>[[paper]][9]|![image](https://user-images.githubusercontent.com/67678405/122313880-013d6200-cf52-11eb-8417-7cf993f5f4ff.png)|Gowalla</br>Yelp2018</br>Amazon-Book|MF</br>NeuMF</br>CMN</br>HOP-Rec</br>PinSage</br>GC-MC|Recall</br>NDCG</br>(tt-split, 8:2)</br>(K=20)|
|Reinforced Negative Sampling for Recommendation with Exposure Data</br>**(RNS)**</br>[2019 IJCAI\*\*]</br>[[paper]][10]|![image](https://user-images.githubusercontent.com/67678405/122630344-d4c64900-d0fd-11eb-8f4c-8b3a10d6661c.png)|Beibei</br>Zhihu|[common]</br>itemPOP</br>BPR-GMF</br>[adversarial sampler]</br>BPR-DNS</br>KBGAN</br>IRGAN</br>[exposure-enhanced samplers]</br>BPE-EN</br>EBPR|AUC</br>NDCG</br>(L-O-O\*)</br>(K=10)</br>(dim=32)|
|Efficient Neural Matrix Factorization without Sampling for Recommendation</br>**(ENMF)**</br>[2020 ACM]</br>[[paper]][11]|![image](https://user-images.githubusercontent.com/67678405/122664764-4fff2c00-d1de-11eb-8523-0065eee54f8b.png)|Ciao</br>Epinion</br>ML 1m|itemPOP</br>itemKNN</br>BPR</br>WMF</br>ExpoMF</br>GMF</br>NCF</br>ConvNCF|HR</br>NDCG</br>(L-O-O-all)</br>(K=50,100,200)</br>(dim=8,16,32,64)|


\* : L-O-O : Leave-one-Out

\*\* : Conference Proceedings Paper

## Factorization Machine Based Model

|Title|Structure|Dataset|Baseline|Metric|
|:---:|:---:|:---:|:---:|:---:|
|Deep Learning over Multi-field Categorical Data</br>**(FNN,SNN)**</br>[2016 ECIR\*\*]</br>[[paper]][12]|![image](https://user-images.githubusercontent.com/67678405/122694402-2d215600-d278-11eb-84dd-8aa10bdbc57d.png)|iPinYou|LR</br>FM</br>FNN(ours)</br>SNN(ours)|AUC-ROC|
|Deep Crossing: Web-Scale Modeling without Manually Crafted Combinatorial Features</br>**(DC)**</br>[2016 KDD\*\*]</br>[[paper]][13]|![image](https://user-images.githubusercontent.com/67678405/122695222-c2254e80-d27a-11eb-93c6-d689f11ac906.png)|text_cp1_tn_s</br>text_cp1_tn_b|DSSM|Logloss|
|Wide & Deep Learning for Recommender Systems</br>**(W&D)**</br>[2016 DLRS\*\*]</br>[[paper]][14]|![image](https://user-images.githubusercontent.com/67678405/122695204-b5085f80-d27a-11eb-9ebc-11a5f1bf4844.png)|-|wide</br>deep</br>wide&deep|offline AUC|
|Deep & Cross Network for Ad Click Predictions</br>**(DCN)**</br>[2017 ADKDD\*\*]</br>[[paper]][15]|![image](https://user-images.githubusercontent.com/67678405/122695017-3c090800-d27a-11eb-9df9-9b7b4a75fe5a.png)|Criteo Display Ads2|DNN</br>LR</br>FM</br>W&D</br>DC|Logloss|
|Neural Factorization Machines for Sparse Predictive Analytics</br>**(NFM)**</br>[2017 SIGIR\*\*]</br>[[paper]][16]|![image](https://user-images.githubusercontent.com/67678405/123054687-0f065200-d440-11eb-978d-2338cf284cbd.png)|Frappe</br>ML-(2017)|LibFM</br>HOFM</br>Wide&Deep</br>DeepCross|RMSE</br>(tt-split, 7:2:1)|
|DeepFM: A Factorization-Machine based Neural Network for CTR Prediction</br>**(DeepFM)**</br>[2017 arXiv]</br>[[paper]][17]|![image](https://user-images.githubusercontent.com/67678405/123188753-8804b880-d4d7-11eb-81cc-8bdf6691dc24.png)|Criteo</br>Company*|LR,FM</br>FNN</br>IPNN,OPNN,PNN*</br>LR&DNN</br>FM&DNN|AUC-ROC</br>Logloss|
|xDeepFM: Combining Explicit and Implicit Feature Interactions for Recommender Systems</br>**(xDeepFM)**</br>[2018 SIGKDD\*\*]</br>[[paper]][18]|![image](https://user-images.githubusercontent.com/67678405/123188788-981c9800-d4d7-11eb-9a54-776d67c335b9.png)|Criteo</br>Dianping</br>Bing News|LR,FM</br>DNN,DCN</br>W&D</br>PNN</br>DeepFM|AUC-ROC</br>Logloss|
|CFM: Convolutional Factorization Machines for Context-Aware Recommendation</br>**(CFM)**</br>[2019 IJCAI]</br>[[paper]][19]|![image](https://user-images.githubusercontent.com/67678405/123367849-aa6d0380-d5b5-11eb-80ee-9dab965b0a4f.png)|Frappe</br>Last FM</br>ML 1m|itemPOP</br>FM</br>NFM</br>DeepFM</br>ONCF|HR</br>NDCG</br>L-O-O-all</br>(K=5,10,20)|
|HoAFM: A High-order Attentive Factorization Machine for CTR Prediction</br>**(HoAFM)**</br>[2020 IP&M]</br>[[paper]][20]|![image](https://user-images.githubusercontent.com/67678405/123367916-c375b480-d5b5-11eb-9326-0af646e9f9d9.png)|Criteo</br>Avazu|GBDT+LR</br>FM</br>W&D</br>NFM</br>CIN</br>xDeepFM|AUC-ROC</br>Logloss</br>(tt-split,8:1:1)|

</br>

\* : L-O-O : Leave-one-Out (100)

\*\* : Conference Proceedings Paper


## Graph Convolution Based Model
|Title|Structure|Dataset|Baseline|Metric|
|:---:|:---:|:---:|:---:|:---:|
|KGAT: Knowledge Graph Attention Network for Recommendation</br>**(KGAT)**</br>[2019 SIGKDD\*\*]</br>[[paper]][21]|![image](https://user-images.githubusercontent.com/67678405/123726485-080d9280-d8cb-11eb-9443-4f0a54c168b8.png)||||
|Unifying Knowledge Graph Learning and Recommendation: Towards a Better Understanding of User Preferences</br>**(KTUP)**</br>[2019 WWW\*\*]</br>[[paper]][22]|![image](https://user-images.githubusercontent.com/67678405/123726648-528f0f00-d8cb-11eb-9863-97e7feabf865.png)||||

</br>

\* : L-O-O : Leave-one-Out (100)

\*\* : Conference Proceedings Paper


## Knowledge Graph Based Model



[1]:https://dl.acm.org/doi/abs/10.1145/3077136.3080797
[2]:https://www.ijcai.org/Proceedings/2017/0447.pdf
[3]:https://dl.acm.org/doi/abs/10.1145/3038912.3052569
[4]:https://dl.acm.org/doi/abs/10.1145/3132847.3133083
[5]:https://ieeexplore.ieee.org/abstract/document/8352808
[6]:https://arxiv.org/abs/1808.03912
[7]:https://dl.acm.org/doi/abs/10.1145/3314578
[8]:https://www.ijcai.org/Proceedings/2019/0290.pdf
[9]:https://dl.acm.org/doi/abs/10.1145/3331184.3331267
[10]:https://www.ijcai.org/Proceedings/2019/0309.pdf
[11]:https://dl.acm.org/doi/abs/10.1145/3373807
[12]:https://link.springer.com/chapter/10.1007/978-3-319-30671-1_4
[13]:https://dl.acm.org/doi/abs/10.1145/2939672.2939704
[14]:https://dl.acm.org/doi/abs/10.1145/2988450.2988454
[15]:https://dl.acm.org/doi/abs/10.1145/3124749.3124754
[16]:https://dl.acm.org/doi/abs/10.1145/3077136.3080777
[17]:https://dl.acm.org/doi/abs/10.1145/3219819.3220023
[18]:https://arxiv.org/abs/1703.04247
[19]:http://staff.ustc.edu.cn/~hexn/papers/ijcai19-cfm.pdf
[20]:https://www.sciencedirect.com/science/article/pii/S0306457319302389
[21]:https://dl.acm.org/doi/abs/10.1145/3292500.3330989
[22]:https://dl.acm.org/doi/abs/10.1145/3308558.3313705
