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
| | LLMXRec | DASFAA 2024 | https://github.com/GodFire66666/LLM\_rec\_explanation |
| | RecExplainer | KDD 2024 | https://github.com/microsoft/RecAI |
| | G-Refer | WWW 2025 | https://github.com/Yuhan1i/G-Refer |
| **Hallucination** | TokenRec | TKDE 2024 | https://github.com/Quhaoh233/TokenRec |
| | LCFT | EMNLP 2025 | https://github.com/djf-web/LCFT |
| | QUD | WWW 2025 | https://github.com/WonbinKweon/UNC_LLM_REC_WWW2025 |

---

### Table 2: Commonly Used and Publicly Accessible Real-World Datasets for TLLMRSs

| Domain | Dataset | User | Item | Interaction | Density | Reference |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **E-commerce** | Amazon Baby Products | 3,400,000 | 217,700 | 6,000,000 | 0.0008% | [nie2024hybrid] |
| | Amazon Beauty and Personal Care | 11,300,000 | 1,000,000 | 23,900,000 | 0.0002% | [nie2024hybrid] |
| | Amazon Cell Phones and Accessories | 11,600,000 | 1,300,000 | 20,800,000 | 0.0001% | [nie2024hybrid] |
| | Amazon Clothing Shoes and Jewelry | 728,719 | 159,456 | 6,724,382 | 0.0058% | [nie2024hybrid] |
| **Entertainment** | MovieLens 10M | 72,000 | 10,682 | 10,000,054 | 1.3002% | [bao2025bi] |
| | Amazon Books | 10,300,000 | 4,400,000 | 29,500,000 | 0.0001% | [nie2024hybrid] |
| | MicroLens (Video) | 34,492,051 | 1,142,528 | 1,006,528,709 | 0.0026% | [ni2025content] |
| | Amazon Video Games | 2,800,000 | 137,200 | 4,600,000 | 0.0012% | [nie2024hybrid] |
| **Media** | Globo | 314,000 | 46,000 | 3,000,000 | 0.0208% | [wu2020mind] |
| | MIND | 1,000,000 | 161,013 | 24,155,470 | 0.0150% | [wu2020mind] |
| | Adressa | 3,083,438 | 48,486 | 27,223,576 | 0.0182% | [wu2020mind] |
| **Tourism** | SynthTRIPs(POI) | 200 | 200 | 4,604 | 11.5100% | [banerjee2025synthtrips] |
| **Finance** | FAR-Trans | 29,090 | 806 | 388,046 | 1.6550% | [sanz2024far] |
| **Healthcare** | MIMIC-IV | 8,916 | 125 | 877 | 0.0787% | [liu2024large] |
