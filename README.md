# TLLMRS_Survey
This repository provides the collection of representative open-source algorithms and public datasets for evaluating trustworthy LLM-based recommender systems. It is associated with our comprehensive survey paper "A Survey on Trustworthy LLM-based Recommender Systems"..




### Table 1: Representative Open-Source TLLM4Rec Algorithms

| Aspect | Algorithm | Venue | Link |
| :--- | :--- | :--- | :--- |
| **Fairness** | UP5 | EACL 2024 | https://github.com/agiresearch/UP5 |
| | IFairLRS | WWW 2024 | https://github.com/JiangM-C/IFairLRS.git |
| | $D^3$ | EMNLP 2024 | https://github.com/SAI990323/DecodingMatters |
| | SPRec | WWW 2025 | https://github.com/RegionCh/SPRec |
| | FUDLR | WWW 2026 | https://github.com/JinLi-i/FUDLR |
| **Robustness** | LoRec | SIGIR 2024 | https://github.com/Kaike-Zhang/LoRec |
| | RLMRec | WWW 2024 | https://github.com/HKUDS/RLMRec |
| | LLM4DSR | TOIS 2025 | https://github.com/WANGBohaO-jpg/LLM4DSR |
| | LLM4RSR | AAAI 2025 | https://github.com/AlchemistYT/LLM4RSR |
| | LLM-AGR | KBS 2025 | https://github.com/zhaxinji/LLM-AGR |
| | LLaRD | WWW 2025 | https://github.com/shuyao-wang/LLaRD |
| | DALR | TOIS 2025 | https://github.com/pengyingtao/DALR |
| | IADSR | CIKM 2025 | https://github.com/Applied-Machine-Learning-Lab/IADSR |
| **Privacy** | E2URec | FCS 2024 | https://github.com/justarter/E2URec |
| | FELLRec | NAACL 2025 | https://github.com/Polaris-JZ/FELLRec |
| | EmojiCrypt | NAACL 2026 | https://github.com/agiresearch/EmojiCrypt |
| **Explainability** | ReXPlug | SIGIR 2021 | https://github.com/deepeshhada/ReXPlug |
| | PEPLER | TOIS 2023 | https://github.com/lileipisces/PEPLER |
| | Xrec | EMNLP 2024 | https://github.com/HKUDS/Xrec |
| | LLMXRec | DASFAA 2024 | https://github.com/GodFire66666/LLM_rec_explanation |
| | RecExplainer | KDD 2024 | https://github.com/microsoft/RecAI |
| | G-Refer | WWW 2025 | https://github.com/Yuhan1i/G-Refer |
| **Hallucination** | TokenRec | TKDE 2024 | https://github.com/Quhaoh233/TokenRec |
| | LCFT | EMNLP 2025 | https://github.com/djf-web/LCFT |
| | QUD | WWW 2025 | https://github.com/WonbinKweon/UNC_LLM_REC_WWW2025 |

---

### Table 2: Commonly Used and Publicly Accessible Real-World Datasets for TLLMRSs

| Domain | Dataset | User | Item | Interaction(/rating) | Density(=1-Sparsity) | Reference |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **E-commerce** | Amazon Baby_Products | 3,400,000 | 217,700 | 6,000,000 | 0.0008% | Bridging Language and Items for Retrieval and Recommendation |
| | Amazon Beauty_and_Personal_Care | 11,300,000 | 1,000,000 | 23,900,000 | 0.0002% | Bridging Language and Items for Retrieval and Recommendation |
| | Amazon Cell_Phones_and_Accessories | 11,600,000 | 1,300,000 | 20,800,000 | 0.0001% | Bridging Language and Items for Retrieval and Recommendation |
| | Amazon Clothing_Shoes_and_Jewelry | 728,719 | 159,456 | 6,724,382 | 0.0058% | Bridging Language and Items for Retrieval and Recommendation |
| | Amazon Grocery_and_Gourmet_Food | 7,000,000 | 603,200 | 14,300,000 | 0.0003% | Bridging Language and Items for Retrieval and Recommendation |
| **Entertainment** | MovieLens 10M | 72,000 | 10,682 | 10,000,054 | 1.3002% | A Bi-Step Grounding Paradigm for Large Language Models in Recommendation Systems |
| | MovieLens 1M | 6,040 | 3,952 | 1,000,209 | 4.1902% | Item-side Fairness of Large Language Model-based Recommendation System |
| | Amazon Books | 10,300,000 | 4,400,000 | 29,500,000 | 0.0001% | Bridging Language and Items for Retrieval and Recommendation |
| | Amazon Digital_Music | 101,000 | 70,500 | 130,400 | 0.0018% | Bridging Language and Items for Retrieval and Recommendation |
| | MicroLens(Video) | 34,492,051 | 1,142,528 | 1,006,528,709 | 0.0026% | A Content-Driven Micro-Video Recommendation Dataset at Scale |
| | Amazon Video_Games | 2,800,000 | 137,200 | 4,600,000 | 0.0012% | Bridging Language and Items for Retrieval and Recommendation |
| **Media** | Globo | 314,000 | 46,000 | 3,000,000 | 0.0208% | MIND: A Large-scale Dataset for News Recommendation |
| | MIND | 1,000,000 | 161,013 | 24,155,470 | 0.0150% | MIND: A Large-scale Dataset for News Recommendation |
| | Adressa | 3,083,438 | 48,486 | 27,223,576 | 0.0182% | MIND: A Large-scale Dataset for News Recommendation |
| **Tourism** | TourismQA(POI) | - | 216,033 | 47,124 | - | Answering POI-Recommendation Questions using TourismReviews |
| | SynthTRIPs(POI) | 200 | 200 | 4,604 | 11.5100% | SynthTRIPs: A Knowledge-Grounded Framework for Benchmark Query Generation for Personalized Tourism Recommenders |
| | TravelPlanner | - | 3,860,000 | 1,225 | - | TravelPlanner: A Benchmark for Real-World Planning with Language Agents |
| **Finance** | FAR-Trans | 29,090 | 806 | 388,046 | 1.6550% | FAR-Trans: An Investment Dataset for Financial Asset Recommendation |
| **Healthcare** | MIMIC-IV | 8,916 | 125 | 877 | 0.0787% | Large Language Model Distilling Medication Recommendation Model |
| **Recruitment** | Job_Recommendation analysis | 3,790 | 84,090 | 12,371 | 0.0039% | Job_Recommendation analysis, https://www.kaggle.com/datasets/kandij/job-recommendation-datasets |
| **Education** | University Student Enrollment Data(Course) | 9,351 | 1,851 | 9,315 | 0.0538% | University Student Enrollment Data, https://www.kaggle.com/datasets/thedevastator/university-student-enrollment-data |
