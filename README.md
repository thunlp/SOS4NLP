# SOS4NLP
SOS4NLP: A survey list of surveys for natural language processing.

Mainly Contributed and Maintained by [Yuan Zang](https://github.com/zangy17). 

Reading the surveys is an efficient way to learn about an academic field. This repository provides a paperlist of surveys for different areas of natural language processing. 

Thanks for all great [contributors](#acknowledgements)! Everyone in Github is welcomed to make contribution to this repository.

### Contents

* [0. Surveys of Natural Language Processing](#0-surveys-of-natural-language-processing)
* [1. Language Parsing](#1-language-parsing)
  * [1.1 Semantic Parsing](#11-semantic-parsing)
  * [1.2 Text Segmentation](#12-text-segmentation)
  * [1.3 Part of Speech Tagging](#13-part-of-speech)
  * [1.4 Coreference Resolution](#14-coreference-resolution)
  * [1.5 Word Sense Disambiguation](#15-word-sense-disambiguation)
  * [1.6 Named Entity Recognization](#16-named-entity-recognization)
  * [1.7 Dependency Parsing](#17-dependency-parsing)
* [2. Natural Language Understanding and Generation](#2-natural-language-understanding-and-generation)
  * [2.1 Text Classification](#21-text-classification)
  * [2.2 Sentiment Analysis](#22-sentiment-analysis) 
  * [2.3 Natural Language Inference](#23-natural-language-inference)
  * [2.4 Reading Comprehension](#24-reading-comprehension)
  * [2.5 Natural Language Generation](#25-natural-language-generation)
  * [2.6 Machine Translation](#26-machine-translation)
  * [2.7 Text Summarization](#27-text-summarization)
* [3. Information Extraction](#3-information-extraction)
  * [3.1 Relation Extraction](#31-relation-extraction)
  * [3.2 Event Extration](#32-event-extraction)
  * [3.3 Open Information Extraction](#33-open-information-extraction)
* [4. Information Retrieval](#4-information-retrieval)
* [5. Dialogue and Question Answering](#5-dialogue-and-question-answering)
  * [5.1 Dialogue](#51-dialogue)
  * [5.2 Question Answering](#52-question-answering)
* [6. Representation Learning](#6-representation-learning)
  * [6.1 Representation Learning](#61-representation-learning)
  * [6.2 Knowledge Representation Learning](#62-knowledge-representation-learning)
  * [6.3 Word Representation Learning](#63-word-representation-learning)
  * [6.4 Network Representation Learning](#64-network-representation-learning)
* [7. Machine Learning for Natural Language Processing](#7-machine-learning-for-natural-language-processing)
  * [7.1 Deep Learning for Natural Language Processing](#71-deep-learning-for-natural-language-processing)
  * [7.2 Transformers and Pretrain Language Models](#transformers-and-pretrain-language-models)
  * [7.3 Graph Neural Networks](#73-graph-neural-networks)
  * [7.4 Reinforcement Learning](#74-reinforcement-learning)
  * [7.5 Data Augmentation](#75-data-augmentation)
  * [7.6 Few/Zero Shot Learning](#76-few/zero-shot-learning)
  * [7.7 Meta Learning](#77-meta-learning)
  * [7.8 Continual Learning](#78-continual-learning)
  * [7.9 Contrastive Learning](#79-contrastive-learning)
  * [7.10 Multi-Task Learning](#710-multi-task-learning)
  * [7.11 Intepretability and Analysis](#711-intepretability-and-analysis)
  * [7.12 Security Threats and Defense](#712-security-threats-and-defense)
* [8. Interdisciplinary Natural language Processing Application](#8-interdisciplinary-natural-language-processing-application)
  * [8.1 Legal Intelligence](#81-legal-intelligence)
  * [8.2 Bioinformation](#82-bioinformation)
  * [8.3 Financial Intelligence](#83-financial-intelligence)
* [Acknowledgements](#acknowledgements)


## 0. Surveys of Natural Language Processing

1. **Advances in natural language processing**.
   *Julia Hirschberg, Christopher D Manning*. Science 2015. [[pdf](https://nlp.stanford.edu/~manning/xyzzy/Hirschberg-Manning-Science-2015.pdf)]

1. **Jumping NLP Curves: A Review of Natural Language Processing Research**.

   *Erik Cambria, Bebo White*. IEEE Computational Intelligence Magazine 2014. [[pdf](https://www.gwern.net/docs/ai/2014-cambria.pdf)]

1. **Natural Language Processing: An Introduction**.
   *Prakash M Nadkarni,  Lucila Ohno-Machado,  Wendy W Chapman*. Journal of the American Medical Informatics Association 2011. [[pdf](https://watermark.silverchair.com/18-5-544.pdf?token=AQECAHi208BE49Ooan9kkhW_Ercy7Dm3ZL_9Cf3qfKAc485ysgAAAskwggLFBgkqhkiG9w0BBwagggK2MIICsgIBADCCAqsGCSqGSIb3DQEHATAeBglghkgBZQMEAS4wEQQMTbW0kBdq70u31A2pAgEQgIICfB9c_mxn3VbFBsTi1npJDFQeVGcPm4ColBNSaoe_IQi7mxDJx5DwD9mmYvdhOQf3CIcds_yDPpLJFP_9bvkf0mfQkKb3U9TSm-KMl_xwLjhkIi090ceKWUhQqcbihY4IWKJmapv0kADF73tPUl9yGhmjFe6Bn7wAKhBC0_XE_A1qpqgscRoyQ3rocVi6dklbHjFKBbIKO5790l6gJXijbVqwAJF3WBGWhP9v0uvXlRun--BG8BZYk2CA6aleWw4T_pCh0fh4ZA1zXNnkr3MiE3Z3YtSdNvDuNA19kekWt8WtRDJd33KRqqWIzk_t-Tekk87SpMLR3O59In65vBSUIBiuFB6xPXJu4-HkU6m5hb9NybU8iYT2oQNQQXdh3Xep4c8OfzCkhLO-CVGhIEOLmNgfKuOnxZW9KAQeZrauNHd-binadf6b5MKrtecCOvrdNgAZNSIyTlGUC_knXbGmMbI3ELTDvARIulZykTF0ZfPCFDDxCrWlpy2FzS_9yBwNc_h7qRC0MxINmxHlADF7efxm3L9XoM7v2bul5tqInTjmjGDZX8ZjSlBs0E2Nvq8YaBxaGJkYV7L-KSY81qgRVMfekEha7eRZFPAn6bFbfO3WulUpfD1veDasuwyIlRsql3EGx4VGmkSE7SpYPrMEVSdHU0Wo8LKKj1xCTzmIv_0Por_y4uAnjB7J3IToavjoanU6iOkg-rFyYw5Y8guFBDPJ9CyKLeBf3RjU1_KEOXW2IGaVIcKvQqFIL_Xnb8sBUSZfFJ3bpNpT4aqHyAKun8Ec6yYGd1hVuGg57nHbuDODtxoe-RB0f3BK3K-Lu698fCh-fpWhAAcziNHZhQ)]

1. **Natural Language Processing**. 
   *Gobinda G Chowdhury*. Annual Review of Information Science and Technology 2003. [[pdf](https://strathprints.strath.ac.uk/2611/1/strathprints002611.pdf)]

## 1. Language Parsing

### 1.1 Semantic Parsing 

1. **A Survey on Semantic Parsing**.

   *Aishwarya Kamath, Rajarshi Das*. AKBC 2018. [[pdf](https://arxiv.org/pdf/1812.00978)]

### 1.2 Text Segmentation

1. **Text Segmentation Techniques: A Critical Review**. 
   *Irina Pak, Phoey Lee Teh*. Innovative Computing, Optimization and Its Applications 2018. [[pdf](http://eprints.sunway.edu.my/840/1/Teh%20Phoey%20Lee%20Text%20Segmentation%20Techniques%20A%20Critical%20Review%20edited.pdf)]

### 1.3 Part of Speech Tagging

1. **Part‐of‐speech Tagging**.

   *Angel R Martinez*. Wiley Interdisciplinary Reviews: Computational Statistics 2012. [[pdf](https://wires.onlinelibrary.wiley.com/doi/epdf/10.1002/wics.195)]

### 1.4 Coreference Resolution

1. **Coreference Resolution: A Survey**.

   *Pradheep Elango*. University of Wisconsin, Madison, WI 2005. [[pdf](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.102.1565&rep=rep1&type=pdf)]

### 1.5 Word Sense Disambiguation

1. **Word Sense Disambiguation: A Survey**.

   *Alok Ranjan Pal*. Arxiv 2015. [[pdf](https://arxiv.org/pdf/1508.01346)]  

1. **Word Sense Disambiguation: A Survey**.

   *Roberto Navigli*. CSUR 2009. [[pdf](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.153.8457&rep=rep1&type=pdf)]

### 1.6 Named Entity Recognization

1. **A Survey on Deep Learning for Named Entity Recognition**.

   *Jing Li, Aixin Sun, Jianglei Han, Chenliang Li*. TKDE 2020. [[pdf](https://arxiv.org/pdf/1812.09449)]

1. **A Survey of Named Entity Recognition and Classification**.

   *David Nadeau, Satoshi Sekine*. Lingvisticae Investigationes 2007. [[pdf](https://www.time.mk/trajkovski/thesis/li07.pdf)]  

### 1.7 Dependency Parsing

1. **Dependency Parsing**.

   *Sandra Kubler, Ryan McDonald, Joakim Nivre*. Synthesis Lectures on Human Language Technologies 2009. [[pdf](https://www.linguisticsociety.org/sites/default/files/e-learning/dependencies.pdf)]

## 2. Natural Language Understanding and Generation

### 2.1 Text Classification

1. **Text Classification Algorithms: A Survey**. 
   *Kamran Kowsari, Kiana Jafari Meimandi, Mojtaba Heidarysafa, Sanjana Mendu, Laura Barnes, Donald Brown*. Information 2019. [[pdf](https://www.mdpi.com/2078-2489/10/4/150/pdf)]

1. **Semantic Text Classification: A Survey of Past and Recent Advances**.

   *Berna Altinel, Murat Can Ganiz*. Information Processing \& Management 2018. [[pdf](https://www.sciencedirect.com/science/article/abs/pii/S0306457317305757)]

### 2.2 Sentiment Analysis

1. **A Survey of Sentiment Analysis in Social Media**. 
   *Lin Yue, Weitong Chen, Xue Li, Wanli Zuo, Minghao Yin*. Knowledge and Information Systems 2019. [[pdf](http://cse.iitkgp.ac.in/~saptarshi/courses/socomp2020a/sentiment-analysis-survey-yue2019.pdf)]

1. **Deep Learning for Sentiment Analysis: A Survey**.

   *Lei Zhang, Shuai Wang, Bing Liu*. Wiley Interdisciplinary Reviews: Data Mining and Knowledge Discovery 2018. [[pdf](https://onlinelibrary.wiley.com/doi/am-pdf/10.1002/widm.1253)]

### 2.3 Natural Language Inference

1. **Recent Advances in Natural Language Inference: A Survey of Benchmarks, Resources, and Approaches**. 
   *Shane Storks, Qiaozi Gao, Joyce Y Chai*. Arxiv 2019. [[pdf](https://arxiv.org/pdf/1904.01172)]

### 2.4 Reading Comprehension

1. **A Survey on Machine Reading Comprehension—Tasks, Evaluation Metrics and Benchmark Datasets**. 
   *Changchang Zeng, Shaobo Li, Qin Li, Jie Hu, Jianjun Hu*. Applied Sciences 2020. [[pdf](https://www.mdpi.com/2076-3417/10/21/7640/pdf)]

1. **Neural Machine Reading Comprehension: Methods and Trends**.

   *Shanshan Liu, Xin Zhang, Sheng Zhang, Hui Wang, Weiming Zhang*. Applied Sciences 2019. [[pdf](https://www.mdpi.com/2076-3417/9/18/3698/pdf)]

### 2.5 Text Generation

1. **Pretrained Language Models for Text Generation: A Survey**.

   *Junyi Li, Tianyi Tang, Wayne Xin Zhao, Ji-Rong Wen*. Arxiv 2021. [[pdf](https://arxiv.org/pdf/2105.10311.pdf)]

1. **Survey of the State of the Art in Natural Language Generation: Core Tasks, Applications and Evaluation**. 
   *Albert Gatt, Emiel Krahmer*. Journal of Artificial Intelligence Research 2018. [[pdf](https://www.jair.org/index.php/jair/article/download/11173/26378)]

### 2.6 Machine Translation

1. **Neural Machine Translation: A Review of Methods, Resources, and Tools**.
   
*Zhixing Tan, Shuo Wang, Zonghan Yang, Gang Chen, Xuancheng Huang, Maosong Sun, YangLiu*. AI Open 2020. [[pdf](https://pdf.sciencedirectassets.com/777606/1-s2.0-S2666651020X00027/1-s2.0-S2666651020300024/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJGMEQCIEI%2Fd%2BRJ29itBNaq4DDn72X5y%2BvR4sUPQVYGkvCaOxSlAiBb9Jk8gNj2eRv5XzqU3MDZLcM9cNVYMk3bApmgOuKo5SqDBAjh%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAQaDDA1OTAwMzU0Njg2NSIMGBZpbHJaLTbA2IKlKtcDlKl3M%2FKoev68AxfA1LPWWUNURJZeL4opVifdAsIMyGUSQ0PEtmApxPZUw7VrdigGDkvaShDCCYh0Y0RJWXF9GXX%2BpJBuuv8eae1mGQ1OjjBgT2rmIVCx%2BcCpyBeTkz2BWEzf36ZBqIs96pGUGptZOruWn03TkrTIk9u7reHlD1dP3WAhEynkyAFu6ZYxhJ4i54R%2FDDPUvKhvHRe54QvYHciX%2BDUQr%2B8LqkhGPLs3%2F1fKkpbtbYKPaEd2Il2rJAG26xNhj2b6%2FZnHoA6cn%2B%2F3CszEXb6QhQHDB8g4ZhmJTivtVtRmWXexmpFo0%2FUpMXLLlojv9SoCME80T1skNCRqOWzWjN7T%2F4exLLxIHVn9YXDKHczyKkAY0F%2B8gcICr36m0y9joAsGo8cSj5afhzA1GalxsYdOiSV0rfZApSZ3giU74snMygiXsmYtI7o6G%2FpRGC%2FNuJfP0%2BZgviIhCXY2OtOcujYyj3dixk6AFMkAHmbJEG2XyqE6HdOxsv7pcBDe%2BBtkbMMriBdlARwyP13qdS%2BaP8NOuTwdF3ykM8dwsQXC7Bg1soovygfTiBYPr%2FBBewCVXlY%2BEWo1XTCF2rBh93od29atHRiaFnH16zU%2FeBHqFR%2FwIueOMMups4cGOqYBUMp8kSHbPS7itMjQoLFtUow0nDP1jtAKu7aZ0pc2575N2vF3ljE%2BOb4EOjRX38EC9s%2BoKu62gEeZPpIHXOuAlmMopPwkPOmAhgsS6SBm8GkkbUOsqiZYrkMMCaxBXLof7Hb0J%2FO%2BP5X0pfoxehoAhhA5kAsxgmYc%2BfOvhKaScNacloAs3j1fIq5yPXSz97%2B98GxPDNKE1%2BZ349rpPxYdOHMWLomZNw%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20210713T011505Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYXAOF4ABF%2F20210713%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=e7ed2a8e3a1864f8e8501ab7267e8fccb4063f50bede5feafa0b70ccab5b2521&hash=da1e8d310c84ee9994d7353a0f8bd6819053d8d02889f652f94641cbcfea9a19&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S2666651020300024&tid=spdf-def16018-cee7-4413-938c-6b22e9f94fdc&sid=27eca1f72344884dbe7913d4b18b564d6a85gxrqa&type=client)]
   
1. **A Survey of Machine Translation: Its History, Current Status and Future Prospects**.

   *Jonathan Slocum*. Computational Linguistics 1985. [[pdf](https://www.aclweb.org/anthology/J85-1001.pdf)]

### 2.7 Text Summarization

1. **A Survey on Dialogue Summarization: Recent Advances and New Frontiers**.

    *Xiachong Feng, Xiaocheng Feng, Bing Qin*. arxiv 2021. [[pdf](https://arxiv.org/pdf/2107.03175)]
    
1. **What Have We Achieved on Text Summarization?**

    *Dandan Huang, Leyang Cui, Sen Yang, Guangsheng Bao, Kun Wang, Jun Xie, Yue Zhang*. EMNLP 2020. [[pdf](https://aclanthology.org/2020.emnlp-main.33.pdf)]

1. **Recent Automatic Text Summarization Techniques: A Survey**. 
    *Mahak Gambhir, Vishal Gupta*. Artificial Intelligence Review 2017. [[pdf](https://link.springer.com/content/pdf/10.1007/s10462-016-9475-9.pdf)]

## 3. Information Extraction

### 3.1 Relation Extraction

1. **More Data, More Relations, More Context and More Openness: A Review and Outlook for Relation Extraction**.

   *Xu Han, Tianyu Gao, Yankai Lin, Hao Peng, Yaoliang Yang, Chaojun Xiao, Zhiyuan Liu, Peng Li, Maosong Sun, Jie Zhou*. AACL 2020. [[pdf](https://aclanthology.org/2020.aacl-main.75.pdf)]

1. **Relation extraction: a survey**.

   Sachin Pawar, Girish K. Palshikara, Pushpak Bhattacharyyab. Arxiv 2017. [[pdf](https://arxiv.org/pdf/1712.05191.pdf)]

### 3.2 Event Extration

1. **A Survey of Event Extraction from Text**. 
   *Wei Xiang, Bang Wang*. IEEE Access 2019. [[pdf](https://ieeexplore.ieee.org/iel7/6287639/8600701/08918013.pdf)]
   
2. **Extracting Events and Their Relations from Texts: A Survey on Recent Research Progress and Challenges**.

   *Kang Liu, Yubo Chen, Jian Liu, Xinyu Zuo, Jun Zhao*. AI Open 2020. [[pdf](https://www.sciencedirect.com/science/article/pii/S266665102100005X/pdfft?md5=3983861e9ae91ce7b45f0c5533071077&pid=1-s2.0-S266665102100005X-main.pdf)]

### 3.3 Open Information Extraction

1. **A Survey on Open Information Extraction**. 
   *Christina Niklaus, Matthias Cetto, Andre Freitas, Siegfried Handschuh*. COLING 2018. [[pdf](https://arxiv.org/pdf/1806.05599)]

## 4. Information Retrieval

1. **Data Mining and Information Retrieval in the 21st Century: A Bibliographic Review**.

   *Jiaying Liu, Xiangjie, Kong, Xinyu Zhou, Lei Wang, Da Zhang, Ivan Lee, Bo Xu, Feng Xia*. Science Review 2019. [[pdf](https://pdf.sciencedirectassets.com/276226/1-s2.0-S1574013719X00040/1-s2.0-S1574013719301297/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEOT%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJGMEQCICq5IyB56s6Und0UJRNRuwZ8moPqdExErZ0TtRQQLGUNAiAFqh%2FtINYbe%2BmWQnEo%2B4GbKrlum0q8IMz0DkqT4sB%2B1CqDBAjN%2F%2F%2F%2F%2F%2F%2F%2F%2F%2F8BEAQaDDA1OTAwMzU0Njg2NSIM5WDlAL%2BoE9iRKE4WKtcDlh9uPvVVjUQ9h8KwcYFwpbaEfF6xvjLl%2Fyzn4gGE3ARgGVsEJbi2kVc83hDhw03g%2BaKxGWSQr10OLGqG0nYTUrJdQZY6WcZpJRBDcdjfMe%2FVlGlQuG0Mu%2BZYZRO%2F96h%2BAiAXwDIuZyLRAftKyIrBLgqnZ0PBsC6lyOFdPH0RFW%2B19YFKHoNuof%2Fx%2BrmpL63bLK6EBPzjI6ZOQ7f3Hc%2Fo%2FiZGoAH2AAMsidgyBIBk%2FZx56S%2B%2FWv6hvkmZh%2BbUj%2FK9ElXqnIDgyokzOX4%2FR9SVPFP5lXslzU3BJmpS2LsMv9SI4xY92ISOdXGTw2eCgMnqvY4huM92tSJoNkaKuipZPU8Em61WcrCcjP2v%2Bubxaz0LCTwrnbB2jQYLf9%2BzIZf7DWrIaWVu8XuoPwMfj%2FY7IELkNdidCHErVp94D3%2Fcv%2FIHGcHIUxVuK2pvElHB85xF0hgsWRWbX9RusDU2S7KryloCMjkedsgSfiNh0uAaiuiL40S5olbAVuK00LgXEq9o1H3%2B%2BQekDo%2Bn0kzIolfMBPAWpf2Anmvfa0vGEIrtXqS7tqIGHvDNNpmE8gg9lB63QlKJu2Yt3jiUbcQJbuWhEz8OCqcngVgRVtQRT7Nstb8V1yMc43QcMNPzrocGOqYB3b0JzWmueBzXIGbAdfLifUj%2BGQm2Kx0Qi4LsuBnJEYaX0GfcWxtT%2BaIk%2By3PCP2H3vABGfO0bInuXflJBhpkW4pZ5i7d51ysfp%2FKXu4yEiZT2JhDFgi70p0roesXyHrD5z5pi2nYWXptCTD6oe6JWR02QtCr5IsQVMBTRa3RUwOjAf3VP58zT2dNSwLjUTOjNdAC3e2j1FA2cQn9f0C94pIrKjPt4g%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20210712T045217Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY74QVIXG7%2F20210712%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=f2f453778540f3e5bf0883461f74ac8314f34bee23d998cb46403e9eee9c23c2&hash=6e521d2013bcd4ebe81b93a081d055b01acebb5dbd35d82f8502f2de73ce799e&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S1574013719301297&tid=spdf-35941364-0392-4be0-b75e-20e00a183bf2&sid=27eca1f72344884dbe7913d4b18b564d6a85gxrqa&type=client)]

1. **Neural Models for Information Retrieval**.

   *Bhaskar Mitra, Nick Craswell*. Arxiv 2017. [[pdf](https://arxiv.org/pdf/1705.01509.pdf)]

## 5. Dialogue and Question Answering

### 5.1 Dialogue

1. **A Survey on Dialogue Systems: Recent Advances and New Frontiers**.

   *Hongshen Chen, Xiaorui Liu, Dawei Yin, Jiliang Tang*. Acm SIGKDD Explorations Newsletter 2017. [[pdf](https://arxiv.org/pdf/1711.01731)]

### 5.2 Question Answering

1. **Core Techniques of Question Answering Systems over Knowledge Bases: A Survey**. 
   *Dennis Diefenbach, Vanessa Lopez, Kamal Singh, Pierre Maret*. Knowledge and Information Systems 2018. [[pdf](https://hal.archives-ouvertes.fr/hal-01637143/document)]

1. **Question Answering Systems: Survey and Trends**.

   *Abdelghani Bouziane, Djelloul Bouchiha, Noureddine Doumi, Mimoun Malki*. Procedia Computer Science 2015. [[pdf](https://www.sciencedirect.com/science/article/pii/S1877050915034663/pdf?md5=e483aabf699b13dd1fdb74c8e95b5100&pid=1-s2.0-S1877050915034663-main.pdf&_valck=1)]

1. **A Survey on Question Answering Technology from an Information Retrieval Perspective**.

   *Oleksandr Kolomiyets, Marie-Francine Moens*. Information Science 2011. [[pdf](http://wtlab1.um.ac.ir/images/e-library/Question_Answering/A%20survey%20on%20question%20answering%20technology%20from%20an%20information%20retrieval%20perspective.pdf)]

1. **Retrieving and Reading: A Comprehensive Survey on Open-domain Question Answering**.

    *Fengbin Zhu, Wenqiang Lei, Chao Wang, Jianming Zheng, Soujanya Poria, Tat-Seng Chua*. arxiv 2021. [[pdf](https://arxiv.org/pdf/2101.00774)]

## 6. Representation Learning

### 6.1 Representation Learning

1. **Representation Learning: A Review and New Perspectives.** 

   *Yoshua Bengio, Aaron Courville, and Pascal Vincent.* TPAMI 2013. [[pdf](https://arxiv.org/pdf/1206.5538)]

### 6.2 Knowledge Representation Learning 

1. **Sememe Knowledge Computation: A Review of Recent Advances in Application and Expansion of Sememe Knowledge Bases**.

   *Fanchao Qi, Ruobing Xie, Yuan Zang, Zhiyuan Liu, Maosong Sun*. Frontiers of Computer Science 2021. [[pdf](https://link.springer.com/article/10.1007/s11704-020-0002-4)]

1. **Knowledge Graph Embedding: A Survey of Approaches and Applications**.

   *Quan Wang, Zhendong Mao, Bin Wang, Li Guo*. TKDE 2017. [[pdf](http://ieeexplore.ieee.org/abstract/document/8047276/)]

1. **Knowledge Representation Learning: A Review**.

   *Zhiyuan Liu, Maosong Sun, Yankai Lin, Ruobing Xie*. Journal of Computer Research and Development 2016. [[pdf](https://crad.ict.ac.cn/EN/article/downloadArticleFile.do?attachType=PDF&id=3099)]

1. **A Review of Relational Machine Learning for Knowledge Graphs**.

   *Maximilian Nickel, Kevin Murphy, Volker Tresp, Evgeniy Gabrilovich*. Proceedings of the IEEE 2015. [[pdf](https://arxiv.org/pdf/1503.00759)]

### 6.3 Word Representation Learning

1. **From Word to Sense Embeddings: A Survey on Vector Representations of Meaning**.

   *Jose Camacho-Collados, Mohammad Taher Pilehvar*. JAIR 2018. [[pdf](https://www.jair.org/index.php/jair/article/download/11259/26454/)]

### 6.4 Network Representation Learning

1. **Network Representation Learning: A Macro and Micro View**.

   *Xueyi Liu, Jie Tang*. AI Open 2021. [[pdf](https://pdf.sciencedirectassets.com/777606/1-s2.0-S2666651021X00022/1-s2.0-S2666651021000024/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEPj%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEaCXVzLWVhc3QtMSJIMEYCIQDF4AZ3X%2BNSkwIYrQFjT5J2NmWQoHmxcdnZ%2FcUedLywSgIhAII%2FNrzVTGMN1PMuzFJn%2FSKD4UfyWdV3w2K6wuGU8GSJKoMECOH%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FwEQBBoMMDU5MDAzNTQ2ODY1Igx4dtx3R0qAisPhSuAq1wO%2FfY2wuQ6oZ9%2FyuJoq4P7j2zbMRSxFWEdIFt%2BInUKHuKOR6Z2QolCfx10s7ool05vvnLgkwesm4G5TIbFdq9AyaKtnGB2fIkRL872m94O9RRUYvWONG6UxFcMCmEbXhvQPWBsz1ypEsJkTeZ7S9oVZaWXaJeNr90BrHWxSdoOQ2U%2Fy%2Bo7OCY4cExwbBzRGVpQQ%2BhwEjUpzBmhHRa3ITiZJZrIedCZE7tL%2FuQ2AxM963t9GOX0dl3fx2aF4u89FLnXjSUwS8kSII37OmEoOoqU8GalrGQSqbLfVX3jCh4LJucC76fZNXB7Ueu%2Bn%2FY%2BpYSn71iAFnSpsVYoxL2zx%2BqyTq8twGK70%2BU9bRtCHoAV26Z8Z7IRqiMZm5wLdvuaUDt%2B79izGneQ4dfPymy5Z50RWxhHDupoYYuCcl53EwHS5DJ8eOoQ6mjOszngrVwZsnohHIw0v1kOwH8zAmwUFuYvar543JI1HfXIPLndTFsKXhxnN%2BppqrW5Myxf06NvQgZ9QJPYcnFlcgCn3pN0QbjgZx%2FNkwqYvp3qFe6ASVZzON694ufdsBnzCfKK4W7kczivEsmd83%2Fd5nC8P18I3EMeGK%2FqI34SpBpJqGB0Me3Fc6nhQQM8eW3Yw6a%2BzhwY6pAGtEmsONGDApmnuJDw06%2FP5MqunMCAPmOCm5j4p%2BqWbtDyaACe9vPmBt4RPgRA4B7Axxi05VzhjJ525wrThobJ86%2BFIHHyfXcipLDY3Z5wz1wIdv%2FL6qvXR%2B1A05XULV2BMQVEEGzFrFTr%2BFSLx%2BStedvTrwlS8s22mBg6Y4U6yoH7XrI28KcIpMaIfbTscy34E3aqKqCE%2FLcdl19JYgwg46dUebw%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20210713T011759Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTY4MKE7SXL%2F20210713%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=b475442910cb1cbe2893d7a57cb204012ba3fb1c4038481a79775f88eaf78ec9&hash=b0aee28209890c3e40e3b1fca16a70a0d6f7c8ed6c36846912b65f7811a8d480&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S2666651021000024&tid=spdf-69cab0cb-463d-46df-b673-08b0dc37a6fa&sid=27eca1f72344884dbe7913d4b18b564d6a85gxrqa&type=client)]

1. **A Survey on Network Embedding**.

   *Peng Cui, Xiao Wang, Jian Pei, Wenwu Zhu*. TKDE 2018. [[pdf](https://arxiv.org/pdf/1711.08752)]

1. **Network Representation Learning: A Survey**.

   *Daokun Zhang, Jie Yin, Xingquan Zhu, Chengqi Zhang*. IEEE Transactions on Big Data 2018. [[pdf](https://arxiv.org/pdf/1801.05852.pdf)]

1. **Network Representation Learning: An Overview**.

   *Cunchao Tu, Cheng Yang, Zhiyuan Liu, Maosong Sun*. Scientia Sinica Informationis 2017. [[pdf](http://engine.scichina.com/publisher/scp/journal/SSI/47/8/10.1360/N112017-00145)]

## 7. Machine Learning for Natural Language Processing

### 7.1 Deep Learning for Natural Language Processing

1. **A Survey of the Usages of Deep Learning for Natural Language Processing**.

   *Daniel W. Otter, Julian R. Medina, Jugal K. Kalita*. IEEE Transactions on Neural Networks and Learning Systems 2021. [[pdf](https://arxiv.org/pdf/1807.10854)]

1. **Recent Trends in Deep Learning Based Natural Language Processing**.

   *Tom Young, Devamanyu Hazarika, Soujanya Poria, Erik Cambria*. IEEE Computational Intelligence Magazine 2018. [[pdf](https://arxiv.org/pdf/1708.02709.pdf%C2%A0)]

### 7.2 Transformers and Pretrain Language Models

1. **A Survey of Transformers**.

   *Tianyang Lin, Yuxin Wang, Xiangyang Liu, Xipeng Qiu*. Arxiv 2021. [[pdf](https://arxiv.org/pdf/2106.04554)]

1. **Pre-Trained Models: Past, Present and Future**.

   *Xu Han, Zhengyan Zhang, Ning Ding, Yuxian Gu, Xiao Liu, Yuqi Huo, Jiezhong Qiu, Liang Zhang, Wentao Han, Minlie Huang, Qin Jin, Yanyan Lan, Yang Liu, Zhiyuan Liu, Zhiwu Lu, Xipeng Qiu, Ruihua Song, Jie Tang, Ji-Rong Wen, Jinhui Yuan, Wayne Xin Zhao, Jun Zhu*. Arxiv 2021. [[pdf](https://arxiv.org/abs/2106.07139)]

1. **Pre-trained models for natural language processing: A survey**.

   *XiPeng Qiu, TianXiang Sun, YiGe Xu, YunFan Shao, Ning Dai, XuanJing Huang*. Science China Technological Sciences 2020. [[pdf](https://link.springer.com/content/pdf/10.1007/s11431-020-1647-3.pdf)]

1. **Efficient Transformers: A Survey**.

   *Yi Tay, Mostafa Dehghani, Dara Bahri, Donald Metzler*. Arxiv 2020. [[pdf](https://arxiv.org/pdf/2009.06732)]

### 7.3 Graph Neural Networks

1. **Graph Neural Networks for Natural Language Processing: A Survey**.

   *Lingfei Wu, Yu Chen, Kai Shen, Xiaojie Guo, Hanning Gao, Shucheng Li, Jian Pei, Bo Long*. Arxiv 2021. [[pdf](https://arxiv.org/pdf/2106.04554)]

1. **Robustness of Deep Learning Models on Graphs: A Survey**.

   *Jiarong Xu, Junru Chen, Siqi You, Zhiqing Xiao, Yang Yang, Jiangang Lu*. AI Open 2021. [[pdf](https://pdf.sciencedirectassets.com/777606/1-s2.0-S2666651021X00022/1-s2.0-S2666651021000139/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEBEaCXVzLWVhc3QtMSJHMEUCIQDmcB9h7dKn3wvTXbv0mGpCRs2zxb7v0oNAoEYfK65lXAIgWbqRSd0Dcxz1EoKSYxbMQb0Iazt1HZAUteMHhXvc2F0qgwQI%2Bf%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAEGgwwNTkwMDM1NDY4NjUiDMMC3gpvzxTpfbscwyrXAzesgUHaJWjNaP29to2qfBQFPC6lwNAHbcRwVgCWfdvccX%2BQi%2BX0hgSkVMDLB3F5nfKwG05JfDE3ZsfVttAZ2djvytUk3%2F8R9UszAqjBWKFeNsuWKK0Ogh3N6acYe7w7bBkMJ9vdFgf%2BjAPnIvsDCX6hmDeZQQe4RokCv1oCM4M01T5%2FTmVzZS2f9AukdAZ%2BvwXH2ATXMB27n9vhN01kTbcci9IK2F2wpbRr2%2Bbuebs1yYHE0SP3EuAsyuDdbSCpZxxB%2BnEGBt%2FBnVm7LHR%2ByHDHgXtY1K7co6oHwM0AQHK8b5IjSd7OjRFnHBYjuOGWe3hCE0N7MixhK7kh4rV1DPb8FgOYxTZgwZ8f0upRvdK9cOGx3aoyxXVGpMO%2B5ScgkXn3i6wDbwX5FLFb%2FbHtBIvEWj1MQ9KbhYzfrc2kTfqTacN9uRxGw8wc8NS%2BsBus9U7oyjvvpgknJ5je7guaCXgotoXmvOdeIlXEywP7XnBzMz1oxvdeIXteNc8k%2Fq9kKLe6EMiGz0dKwu3lSxS0N9jBvDAup8yoT%2BnHE6zWxyGFiOy720aKS%2FH0HS8TFpX648TTjG2Kv6bcE9%2FHsHD9Fea3ydeGLRscRAx02asRcerDARdGjCuzWzC91biHBjqlAenPBD5BQFVYcnENsDGaZCqFDGVju%2BLTSvkglhMraDbXEKEGNiOMcDNt321b%2FEbsNFjB7r7sfJYAp8PizoFiR9mVds2oM2KQYW5YKrq252dWYS7SP%2BNi6nvnmKRBBLs%2F4r59bk3SHemKj%2FxbLucRMzd9qB9mPSIzzfOudBeACQ%2BEHQ1Fmc6CaY109NGRayIkfOtE6iM0XOW%2BQX07crvRWo%2FHlw%2F%2FvQ%3D%3D&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20210714T020215Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYV7YMI542%2F20210714%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=dcaf351d4a7f1c1818f4d436fd3c522460839dd98c69809aecf7466c4c9debed&hash=c51537b014f1d20d25cd8553fa5586fab12f731df76eee3dabbcc0b342f0048a&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S2666651021000139&tid=spdf-90eddceb-73c9-4b80-878d-65985d4a175a&sid=80948377662c7948732be96-54885b4a3c51gxrqa&type=client)]

1. **Graph Neural Networks: A Review of Methods and Applications**.

   *Jie Zhou, Ganqu Cui, Shengding Hu, Zhengyan Zhang, Cheng Yang, Zhiyuan Liu, Lifeng Wang, Changcheng Li, Maosong Sun*. AI Open 2020. [[pdf](https://www.sciencedirect.com/science/article/pii/S2666651021000012)]

1. **A Comprehensive Survey on Graph Neural Networks**.

   *Zonghan Wu, Shirui Pan, Fengwen Chen, Guodong Long, Chengqi Zhang, Philip S. Yu*. IEEE transactions on neural networks and learning systems 2020. [[pdf](https://arxiv.org/pdf/1901.00596.pdf)]
   
   

### 7.4 Reinforcement Learning

1. **A Survey of Reinforcement Learning Informed by Natural Language**.

   *Jelena Luketina, Nantas Nardelli, Gregory Farquhar, Jakob Foerster, Jacob Andreas, Edward Grefenstette, Shimon Whiteson, Tim Rocktäschel*. IJCAI 2019. [[pdf](https://arxiv.org/pdf/1906.03926)]

### 7.5 Data Augmentation

1. **A Survey of Text Data Augmentation**.

   *Pei Liu, Xuemin Wang, Chao Xiang, Weiye Meng*. CCNS 2020. [[pdf](https://www.computer.org/csdl/proceedings-article/ccns/2020/434900a191/1oqKQDVrQOY)]

2. **A Survey of Data Augmentation Approaches for NLP**.

    *Steven Y. Feng, Varun Gangal, Jason Wei, Sarath Chandar, Soroush Vosoughi, Teruko Mitamura, Eduard Hovy*. ACL Finings 2021. [[pdf](https://arxiv.org/pdf/2105.03075)]

3. **An Empirical Survey of Data Augmentation for Limited Data Learning in NLP**. 

    *Jiaao Chen, Derek Tam, Colin Raffel, Mohit Bansal, Diyi Yang*. arxiv 2021. [[pdf](https://arxiv.org/pdf/2106.07499)]

### 7.6 Few/Zero Shot Learning

1. **Generalizing from a Few Examples: A Survey on Few-Shot Learning**.

   *Yaqing Wang, Quanming Yao, James Kwok, Lionel M. Ni*. CSUR 2020. [[pdf](https://arxiv.org/pdf/1904.05046)]

1. **A Survey of Zero-Shot Learning: Settings, Methods, and Applications**.

   *Wei Wang, Vincent W. Zheng, Han Yu, Chunyan Miao*. ACM Transactions on Intelligent Systems and Technology 2019. [[pdf](https://www.ntulily.org/wp-content/uploads/journal/A_Survey_of_Zero-Shot_Learning_Settings_Methods_and_Applications_accepted.pdf)]

### 7.7 Meta Learning

1. **Meta-Learning in Neural Networks: A Survey**.

   *Timothy Hospedales, Antreas Antoniou, Paul Micaelli, Amos Storkey*. PAMI 2020. [[pdf](https://arxiv.org/pdf/2004.05439)]

1. **Meta-Learning: A Survey**.

   *Joaquin Vanschoren*. Arxiv 2018. [[pdf](https://arxiv.org/pdf/1810.03548)]

### 7.8 Continual Learning

1. **A Continual Learning Survey: Defying Forgetting in Classification Tasks**.

   *Matthias Delange, Rahaf Aljundi, Marc Masana, Sarah Parisot, Xu Jia, Ales Leonardis, Greg Slabaugh, Tinne Tuytelaars*. PAMI 2021. [[pdf](https://arxiv.org/pdf/1909.08383)]

### 7.9 Contrastive Learning

1. **A Survey on Contrastive Self-Supervised Learning**.

   *Ashish Jaiswal, Ashwin Ramesh Babu, Mohammad Zaki Zadeh, Debapriya Banerjee, Fillia Makedon*. Technologies 2021. [[pdf](https://www.mdpi.com/2227-7080/9/1/2/pdf)]

1. **Contrastive Representation Learning: A Framework and Review**.

   *Phuc H. Le-Khac, Graham Healy, Alan F. Smeaton*. IEEE Access 2020. [[pdf](https://ieeexplore.ieee.org/iel7/6287639/8948470/09226466.pdf)]

### 7.10 Multi-Task Learning

1. **Multi-task learning for natural language processing in the 2020s: Where are we going?**

   *Joseph Worsham, Jugal Kalita*. Pattern Recognition Letters 2020. [[pdf](https://arxiv.org/pdf/2007.16008)]

1. **An Overview of Multi-Task Learning in Deep Neural Networks**.

   *Sebastian Ruder*. Arxiv 2017. [[pdf](https://arxiv.org/pdf/1706.05098)]

### 7.11 Intepretability and Analysis

1. **On Interpretability of Artificial Neural Networks: A Survey**.

   *Feng-Lei Fan, Jinjun Xiong, Mengzhou Li, Ge Wang*. IEEE Transactions on Radiation and Plasma Medical Sciences 2021. [[pdf](https://arxiv.org/pdf/2001.02522)]

1. **A Survey of the State of Explainable AI for Natural Language Processing**.

   *Marina Danilevsky, Kun Qian, Ranit Aharonov, Yannis Katsis, Ban Kawas, Prithviraj Sen*. AACL 2020. [[pdf](https://arxiv.org/pdf/2010.00711)].

1. **Machine Learning Interpretability: A Survey on Methods and Metrics**.

   *Diogo V. Carvalho, Eduardo M. Pereira, Jaime S. Cardoso*. Electronics 2019. [[pdf](https://www.mdpi.com/2079-9292/8/8/832/pdf)]

1. **Analysis Methods in Neural Language Processing: A Survey**.

   *Yonatan Belinkov, James Glass*. TACL 2019. [[pdf](https://direct.mit.edu/tacl/article-pdf/doi/10.1162/tacl_a_00254/1923061/tacl_a_00254.pdf)]

1. **Teach Me to Explain: A Review of Datasets for Explainable NLP**. 

    *Sarah Wiegreffe, Ana Marasović*. arxiv 2021. [[pdf](https://arxiv.org/pdf/2102.12060)]

### 7.12 Security Threats and Defense

1. **Adversarial Attacks on Deep Learning Models in Natural Language Processing: A Survey**. 

   *Wei Emma Zhang, Quan Z. Sheng, Ahoud Alhazmi, Chenliang Li*. ACM TIST 2020. [[pdf](https://dl.acm.org/doi/pdf/10.1145/3374217)]

1. **Backdoor Learning: A Survey**.

   *Yiming Li, Baoyuan Wu, Yong Jiang, Zhifeng Li, Shu-Tao Xia*. Arxiv 2020. [[pdf](https://arxiv.org/pdf/2007.08745.pdf)].

1. **A Survey of Privacy Attacks in Machine Learning**.

   *Maria Rigaki, Sebastian Garcia*. Arxiv 2020. [[pdf](https://arxiv.org/pdf/2007.07646)]

## 8. Interdisciplinary Natural language Processing Application

### 8.1 Legal Intelligence

1. **How Does NLP Benefit Legal System: A Summary of Legal Artificial Intelligence**.

   *Haoxi Zhong, Chaojun Xiao, Cunchao Tu, Tianyang Zhang, Zhiyuan Liu, Maosong Sun*. ACL 2020. [[pdf](https://arxiv.org/pdf/2004.12158)]

### 8.2 Bioinformation

1. **Survey of Natural Language Processing Techniques in Bioinformatics**.

   *Zhiqiang Zeng, Hua Shi, Yun Wu, Zhiling Hong*. Computational and Mathematical Methods in Medicine 2015. [[pdf](https://pdfs.semanticscholar.org/7013/479be7dda124750aa22fb6231eea2671f630.pdf)].

### 8.3 Financial Intelligence

1. **Natural Language Based Financial Forecasting: A Survey**.

   *Frank Z. Xing, Erik Cambria, Roy E. Welsch*. Artificial Intelligence Review 2018. [[pdf](https://dspace.mit.edu/bitstream/handle/1721.1/116314/10462_2017_9588_ReferencePDF.pdf?sequence=2&isAllowed=y)].

## Acknowledgements

Great thanks to other contributor [Shengding Hu](https://github.com/ShengdingHu), [Chenglei Si](https://github.com/NoviScl) and [Han-Gil Kim](https://github.com/uoneway)! (names are not listed in particular order)

Please contact us if we miss your names in this list, we will add you back ASAP!