# Must-read papers on LegalAI with LLMs

## Role-Based Schema of LLMs in LegalAI

We adopt a **role-based schema** to categorize the applications of LLMs in LegalAI research. This schema is organized into three perspectives: `Data`, `Modeling`, and `Evaluation`, each involving specific `Objects` and corresponding `Roles`.

| **Perspective** | **Objects**         | **Roles**                                                                 |
|-----------------|---------------------|---------------------------------------------------------------------------|
| Data            | Samples              | Data Augmentation, Data Reconstruction, Data Cleaning                     |
|                 | Labels               | Label Generation, Label Correction, Label Reconstruction                  |
| Modeling        | LLM Enhancement      | Fine-tuning, In-context Learning                                          |
|                 | LLM-for-SM           | Data Sources, Supervision Signals, Evaluation Feedback                    |
|                 | Frameworks           | Task Workflow Reshaping, Explainability                                   |
| Evaluation      | Dimensions           | Expanded Evaluation Objectives                                            |
|                 | Methods              | LLM Scoring, Human-LLM, Output Reconstruction                             |
> This schema is from our paper: *"LegalAI Research in LLM Era: Data, Method and Evaluation".*

## Surveys of LegalAI with LLMs

#### &nbsp;&nbsp;&nbsp;2025 ####

1. **Exploring LLMs Applications in Law: A Literature Review on Current Legal NLP Approaches**.

   *Siino M, Falco M, Croce D, et al*. IEEE Access [J]. [[pdf](<https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10850911>)]

2. **Exploring the use of LLMs in the Italian legal domain: A survey on recent applications**.

   *Siino M*. Computer Law & Security Review [J]. [[pdf](<https://www.sciencedirect.com/science/article/pii/S2212473X25000379>)]

#### &nbsp;&nbsp;&nbsp;2024 ####

1. **A survey on llm-as-a-judge**.

   *Gu J, Jiang X, Shi Z, et al*. arXiv [EB/OL]. [[pdf](<https://arxiv.org/pdf/2411.15594?>)]

2. **To what extent have llms reshaped the legal domain so far? a scoping literature review**.

   *Padiu B, Iacob R, Rebedea T, et al*. Information [J]. [[pdf](<https://www.mdpi.com/2078-2489/15/11/662/pdf?version=1729576128>)]

3. **Large language models for automated q\&a involving legal documents: a survey on algorithms, frameworks and applicationse**.

   *Yang X, Wang Z, Wang Q, et al*. International Journal of Web Information Systems [J]. [[pdf](<https://www.emerald.com/ijwis/article-abstract/20/4/413/1216712/Large-language-models-for-automated-Q-amp-A?redirectedFrom=fulltext>)]



#### &nbsp;&nbsp;&nbsp;2023 ####

1. **A short survey of viewing large language models in legal aspect**.

   *Sun Z*. arXiv [EB/OL]. [[pdf](<https://arxiv.org/pdf/2303.09136>)]


## Legal Classification

### &nbsp;&nbsp;&nbsp;Data ###
  
#### &nbsp;&nbsp;&nbsp;Samples ####

1. **Harnessing GPT-3.5-turbo for Rhetorical Role Prediction in Legal Cases**.

   *Belfathi A, Hernandez N, Monceaux L*. JURIX 2023 [C]. [[pdf](<https://arxiv.org/pdf/2310.17413>)][[dataset](<https://github.com/Legal-NLP-EkStep/rhetorical-role-baseline>)]

2. **Neural Data Augmentation for Legal Overruling Task: Small Deep Learning Models vs. Large Language Models**.

   *Sheik R, Siva Sundara K P, Nirmala S J*. Neural Processing Letters [J]. [[pdf](<https://link.springer.com/content/pdf/10.1007/s11063-024-11574-4.pdf>)]

3. **GOLDCOIN: Grounding Large Language Models in Privacy Laws via Contextual Integrity Theory**.

   *Fan W, Li H, Deng Z*. IEEE Access [J]. [[pdf](<https://aclanthology.org/2024.emnlp-main.195.pdf>)][[dataset](https://github.com/HKUST-KnowComp/GoldCoin)]
   
4. **Enabling Discriminative Reasoning in LLMs for Legal Judgment Prediction**.

   *Deng C, Mao K, Zhang Y, et al*. EMNLP (Findings) 2024 [C]. [[pdf](<https://arxiv.org/pdf/2407.01964>)][[dataset1](<https://cail.oss-cn-qingdao.aliyuncs.com/CAIL2018_ALL_DATA.zip)][[dataset2](https://github.com/CURRENTF/HRN>)]

5. **An LLMs‐based neuro‐symbolic legal judgment prediction framework for civil cases**.

   *Wei B, Yu Y, Gan L, et al*. Artificial Intelligence and Law [J]. [[pdf](<https://link.springer.com/content/pdf/10.1007/s10506-025-09433-1.pdf>)][[dataset](<https://github.com/mly-nlp/LJP-MSJudge>)]

6. **CADLRA: A multi-charge prediction method based on the Criminal Act-Driven Law Retrieval Augmentation**.

   *Feng J, Zhao L, Qin H, et al*. Engineering Applications of Artificial Intelligence [J]. [[pdf](<https://www.sciencedirect.com/science/article/pii/S0952197624007772/pdfft?md5=d5b552ed042378bf0aec6d04ab08cd6d&pid=1-s2.0-S0952197624007772-main.pdf>)][[dataset](<https://cail.oss-cn-qingdao.aliyuncs.com/CAIL2018_ALL_DATA.zip>)]

7. **Precedent-Enhanced Legal Judgment Prediction with LLM and Domain-Model Collaboration**.

   *Wu Y, Zhou S, Liu Y, et al*. EMNLP 2023 [C]. [[pdf](<https://arxiv.org/pdf/2310.09241>)][[dataset](<https://github.com/wuyiquan/PLJP>)]

8. **Using LLMs to Discover Legal Factors**.

   *Gray M, Savelka J, Oliver W, et al*. JURIX 2024 [C]. [[pdf](<https://ebooks.iospress.nl/pdf/doi/10.3233/FAIA241234>)]

#### &nbsp;&nbsp;&nbsp;Labels ####

1. **GOLDCOIN: Grounding Large Language Models in Privacy Laws via Contextual Integrity Theory**.

   *Fan W, Li H, Deng Z*. IEEE Access [J]. [[pdf](<https://aclanthology.org/2024.emnlp-main.195.pdf>)][[dataset](<https://github.com/HKUST-KnowComp/GoldCoin>)]

2. **An LLMs‐based neuro‐symbolic legal judgment prediction framework for civil cases**.

   *Wei B, Yu Y, Gan L, et al*. Artificial Intelligence and Law [J]. [[pdf](<https://link.springer.com/content/pdf/10.1007/s10506-025-09433-1.pdf>)][[dataset](<https://github.com/mly-nlp/LJP-MSJudge>)]

3. **CADLRA: A multi-charge prediction method based on the Criminal Act-Driven Law Retrieval Augmentation**.

   *Feng J, Zhao L, Qin H, et al*. Engineering Applications of Artificial Intelligence [J]. [[pdf](<https://www.sciencedirect.com/science/article/pii/S0952197624007772/pdfft?md5=d5b552ed042378bf0aec6d04ab08cd6d&pid=1-s2.0-S0952197624007772-main.pdf>)][[dataset](<https://cail.oss-cn-qingdao.aliyuncs.com/CAIL2018_ALL_DATA.zip>)]

4. **Using LLMs to Discover Legal Factors**.

   *Gray M, Savelka J, Oliver W, et al*. JURIX 2024 [C]. [[pdf](<https://ebooks.iospress.nl/pdf/doi/10.3233/FAIA241234>)]

5. **Syllogistic Reasoning for Legal Judgment Analysis**.

   *Deng W, Pei J, Kong K, et al*. EMNLP 2023 [C]. [[pdf](<https://aclanthology.org/2023.emnlp-main.864.pdf>)][[dataset](<https://share.weiyun.com/KpNPqFtt>)]

7. **The unreasonable effectiveness of large language models in zero-shot semantic annotation of legal texts**.

   *Savelka J, Ashley K D*. Frontiers in Artificial Intelligence [J]. [[pdf](<https://www.frontiersin.org/journals/artificial-intelligence/articles/10.3389/frai.2023.1279794/pdf>)][[dataset1](<https://github.com/LLTLab/VetClaims-JSON>)][[dataset2](<https://www.atticusprojectai.org/cuad>)][[dataset3](<https://www.phasys.pitt.edu/contact.html>)]

8. **Using Large Language Models to Support Thematic Analysis in Empirical Legal Studies**.

   *Drápal J, Westermann H, Savelka J*. JURIX 2023 [C]. [[pdf](<https://arxiv.org/pdf/2310.18729>)]

9. **Courtroom-LLM: A Legal-Inspired Multi-LLM Framework for Resolving Ambiguous Text Classifications**.

   *Jung S, Jung J*. COLING 2025 [C]. [[pdf](<https://aclanthology.org/2025.coling-main.493.pdf>)]

### &nbsp;&nbsp;&nbsp;Modeling ###

#### &nbsp;&nbsp;&nbsp;LLM Enhancement ####

1. **GOLDCOIN: Grounding Large Language Models in Privacy Laws via Contextual Integrity Theory**.

   *Fan W, Li H, Deng Z*. IEEE Access [J]. [[pdf](<https://aclanthology.org/2024.emnlp-main.195.pdf>)][[dataset](<https://github.com/HKUST-KnowComp/GoldCoin>)]

2. **Enabling Discriminative Reasoning in LLMs for Legal Judgment Prediction**.

   *Deng C, Mao K, Zhang Y, et al*. EMNLP (Findings) 2024 [C]. [[pdf](<https://arxiv.org/pdf/2407.01964>)][[dataset1](<https://cail.oss-cn-qingdao.aliyuncs.com/CAIL2018_ALL_DATA.zip>)][[dataset2](<https://github.com/CURRENTF/HRN>)]

3. **CADLRA: A multi-charge prediction method based on the Criminal Act-Driven Law Retrieval Augmentation**.

   *Feng J, Zhao L, Qin H, et al*. Engineering Applications of Artificial Intelligence [J]. [[pdf](<https://www.sciencedirect.com/science/article/pii/S0952197624007772/pdfft?md5=d5b552ed042378bf0aec6d04ab08cd6d&pid=1-s2.0-S0952197624007772-main.pdf>)][[dataset](<https://cail.oss-cn-qingdao.aliyuncs.com/CAIL2018_ALL_DATA.zip>)]

4. **Fine-tuning GPT-3 for legal rule classification**.

   *Liga D, Robaldo L*. Computer Law & Security Review [J]. [[pdf](<https://www.sciencedirect.com/science/article/pii/S0267364923000742/pdfft?md5=f53d2a0a4355c818ac8112a1101c35e9&pid=1-s2.0-S0267364923000742-main.pdf>)][[dataset](<https://github.com/dapreco/daprecokb/blob/master/gdpr/rioKB_GDPR.xml>)]

5. **LegalReasoner: A Multi-Stage Framework for Legal Judgment Prediction via Large Language Models and Knowledge Integration**.

   *Prasad N, Boughanem M, Dkaki T, et al*. IEEE Access [J]. [[pdf](<https://ieeexplore.ieee.org/iel8/6287639/6514899/10750819.pdf>)][[dataset1](<https://cail.oss-cn-qingdao.aliyuncs.com/CAIL2018_ALL_DATA.zip>)][[dataset2](<https://archive.org/details/ECHR-ACL2019>)]

6. **Rethinking the Development of Large Language Models from the Causal Perspective: A Legal Text Prediction Case Study**.

   *Chen H, Zhang L, Liu Y, et al*. AAAI 2024 [C]. [[pdf](<https://ojs.aaai.org/index.php/AAAI/article/download/30086/31914>)][[dataset1](<https://archive.org/details/ECHR-ACL2019>)][[dataset2](<https://huggingface.co/datasets/ecthr_cases>)][[dataset3](<https://drive.switch.ch/index.php/s/j9S0GRMAbGZKa1A>)]

7. **DPFSI: A legal judgment prediction method based on deontic logic prompt and fusion of law article statistical information**.

   *Meng C, Todo Y, Tang C, et al*. Expert Systems with Applications [J]. [[pdf](<https://www.sciencedirect.com/science/article/pii/S0957417425003446/pdfft?casa_token=s-aXCUxzV4EAAAAA:JbP8fAmTWHcbOs7rQQpbGLqkIJemmk__QzcyyNQyetYhpoAMkmVI4gEyvehBciBK_UNCCCg9Ww&md5=833d695d44a83d97aca2fbeac295a91d&pid=1-s2.0-S0957417425003446-main.pdf>)][[dataset](<https://cail.oss-cn-qingdao.aliyuncs.com/CAIL2018_ALL_DATA.zip>)]

8. **NYAYAANUMANA and INLEGALLLAMA: The Largest Indian Legal Judgment Prediction Dataset and Specialized Language Model for Enhanced Decision Analysis**.

   *Nigam S K, Patnaik B D, Mishra S*. COLING 2025 [C]. [[pdf](<https://arxiv.org/pdf/2412.08385>)][[dataset](<https://github.com/ShubhamKumarNigam/NyayaAnumana-and-INLegalLlama>)]

9. **An LLMs‐based neuro‐symbolic legal judgment prediction framework for civil cases**.

   *Wei B, Yu Y, Gan L, et al*. Artificial Intelligence and Law [J]. [[pdf](<https://link.springer.com/content/pdf/10.1007/s10506-025-09433-1.pdf>)][[dataset](<https://github.com/mly-nlp/LJP-MSJudge>)]

10. **Precedent-Enhanced Legal Judgment Prediction with LLM and Domain-Model Collaboration**.
     
     *Wu Y, Zhou S, Liu Y, et al*. EMNLP 2023 [C]. [[pdf](https://arxiv.org/pdf/2310.09241)][[dataset](<https://github.com/wuyiquan/PLJP>)]

11. **Courtroom-LLM: A Legal-Inspired Multi-LLM Framework for Resolving Ambiguous Text Classifications**.

     *Jung S, Jung J*. COLING 2025 [C]. [[pdf](<https://aclanthology.org/2025.coling-main.493.pdf>)]

12. **Harnessing GPT-3.5-turbo for Rhetorical Role Prediction in Legal Cases**.

     *Belfathi A, Hernandez N, Monceaux L*. JURIX 2023 [C]. [[pdf](<https://arxiv.org/pdf/2310.17413>)][[dataset](<https://github.com/Legal-NLP-EkStep/rhetorical-role-baseline>)]

13. **Legal Syllogism Prompting: Teaching Large Language Models for Legal Judgment Predictions**.

     *Jiang C, Yang X*. ICAIL 2023 [C]. [[pdf](<https://dl.acm.org/doi/pdf/10.1145/3594536.3595170?casa_token=EyP_LqQK7kIAAAAA:loANkbImAXC8PDXafXgu0AsRqZkEY4BHx82eKq3aaVn1weHPtUSGIx5k0xGdugAAw4294k-kyRtW>)][[dataset](<https://cail.oss-cn-qingdao.aliyuncs.com/CAIL2018_ALL_DATA.zip>)]

14. **LLMs – the Good, the Bad or the Indispensable?: A Use Case on Legal Statute Prediction and Legal Judgment Prediction on Indian Court Cases**.

     *Vats S, Zope A, De S, et al*. EMNLP (Findings) 2023 [C]. [[pdf](<https://aclanthology.org/2023.findings-emnlp.831.pdf>)][[dataset](<https://github.com/somsubhra04/LLM_Legal_Prompt_Generation>)]

15. **Experimental Study of In-Context Learning for Text Classification and Its Application to Legal Document Review in Construction Delay Disputes**.

     *Huber-Fliflet N, Zhang J, Gronvall P*. IEEE Big Data 2024 [C]. [[pdf](<https://ieeexplore.ieee.org/iel8/10824975/10824942/10826061.pdf?casa_token=s7AlN8_ORVYAAAAA:XzADl2pWde8Um6Lso5GmAo5maoZsbh42zMRkQ4tgq_CeX_-INAnV3hTalrm7LTBtxV8E6gWaIHcQXA>)]

16. **Legal Judgment Prediction with LLM and Graph Contrastive Learning Networks**.

     *Xia Y, Luo X*. CSAI 2024 [C]. [[pdf](<https://dl.acm.org/doi/pdf/10.1145/3709026.3709068?casa_token=Rl1sIKwQF58AAAAA:TxZbQp4bKQnNpxzLEDpnKztm6EiOwVqtbDtwEBIagqX2ttU0vqp8W8j_36x16GAbz6lqnEXw5U_wjg>)][[dataset1](<https:%20//huggingface.co/datasets/coastalcph/fairlex/viewer/ecthr>)][[dataset2](<https:%20//huggingface.co/datasets/AUEB-NLP/ecthr_cases>)]

17. **Neural Data Augmentation for Legal Overruling Task: Small Deep Learning Models vs. Large Language Models**.

     *Sheik R, Siva Sundara K P, Nirmala S J*. Neural Processing Letters [J]. [[pdf](<https://link.springer.com/content/pdf/10.1007/s11063-024-11574-4.pdf>)]

#### &nbsp;&nbsp;&nbsp;LLM-for-SM ####

1. **Neural Data Augmentation for Legal Overruling Task: Small Deep Learning Models vs. Large Language Models**.

   *Sheik R, Siva Sundara K P, Nirmala S J*. Neural Processing Letters [J]. [[pdf](<https://link.springer.com/content/pdf/10.1007/s11063-024-11574-4.pdf>)]

2. **An LLMs‐based neuro‐symbolic legal judgment prediction framework for civil cases**.

   *Wei B, Yu Y, Gan L, et al*. Artificial Intelligence and Law [J]. [[pdf](<https://link.springer.com/content/pdf/10.1007/s10506-025-09433-1.pdf>)][[dataset](<https://github.com/mly-nlp/LJP-MSJudge>)]

3. **Legal Judgment Prediction with LLM and Graph Contrastive Learning Networks**.

   *Xia Y, Luo X*. CSAI 2024 [C]. [[pdf](<https://dl.acm.org/doi/pdf/10.1145/3709026.3709068?casa_token=Rl1sIKwQF58AAAAA:TxZbQp4bKQnNpxzLEDpnKztm6EiOwVqtbDtwEBIagqX2ttU0vqp8W8j_36x16GAbz6lqnEXw5U_wjg>)][[dataset1](<https:%20//huggingface.co/datasets/coastalcph/fairlex/viewer/ecthr>)][[dataset2](<https:%20//huggingface.co/datasets/AUEB-NLP/ecthr_cases>)]

#### &nbsp;&nbsp;&nbsp;Frameworks ####

1. **GOLDCOIN: Grounding Large Language Models in Privacy Laws via Contextual Integrity Theory**.

   *Fan W, Li H, Deng Z*. IEEE Access [J]. [[pdf](<https://aclanthology.org/2024.emnlp-main.195.pdf>)][[dataset](<https://github.com/HKUST-KnowComp/GoldCoin>)]

2. **Enabling Discriminative Reasoning in LLMs for Legal Judgment Prediction**.

   *Deng C, Mao K, Zhang Y, et al*. EMNLP (Findings) 2024 [C]. [[pdf](<https://arxiv.org/pdf/2407.01964>)][[dataset1](<https://cail.oss-cn-qingdao.aliyuncs.com/CAIL2018_ALL_DATA.zip>)][[dataset2](<https://github.com/CURRENTF/HRN>)]

3. **An LLMs‐based neuro‐symbolic legal judgment prediction framework for civil cases**.

   *Wei B, Yu Y, Gan L, et al*. Artificial Intelligence and Law [J]. [[pdf](<https://link.springer.com/content/pdf/10.1007/s10506-025-09433-1.pdf>)][[dataset](<https://github.com/mly-nlp/LJP-MSJudge>)]

4. **CADLRA: A multi-charge prediction method based on the Criminal Act-Driven Law Retrieval Augmentation**.

   *Feng J, Zhao L, Qin H, et al*. Engineering Applications of Artificial Intelligence [J]. [[pdf](<https://www.sciencedirect.com/science/article/pii/S0952197624007772/pdfft?md5=d5b552ed042378bf0aec6d04ab08cd6d&pid=1-s2.0-S0952197624007772-main.pdf>)][[dataset](<https://cail.oss-cn-qingdao.aliyuncs.com/CAIL2018_ALL_DATA.zip>)]

5. **Precedent-Enhanced Legal Judgment Prediction with LLM and Domain-Model Collaboration**.

   *Wu Y, Zhou S, Liu Y, et al*. EMNLP 2023 [C]. [[pdf](<https://arxiv.org/pdf/2310.09241>)][[dataset](<https://github.com/wuyiquan/PLJP>)]

6. **Syllogistic Reasoning for Legal Judgment Analysis**.

   *Deng W, Pei J, Kong K, et al*. EMNLP 2023 [C]. [[pdf](<https://aclanthology.org/2023.emnlp-main.864.pdf>)][[dataset](<https://share.weiyun.com/KpNPqFtt>)]

7. **Using Large Language Models to Support Thematic Analysis in Empirical Legal Studies**.

   *Drápal J, Westermann H, Savelka J*. JURIX 2023 [C]. [[pdf](<https://arxiv.org/pdf/2310.18729>)]

8. **Courtroom-LLM: A Legal-Inspired Multi-LLM Framework for Resolving Ambiguous Text Classifications**.

   *Jung S, Jung J*. COLING 2025 [C]. [[pdf](<https://aclanthology.org/2025.coling-main.493.pdf>)]

9. **LegalReasoner: A Multi-Stage Framework for Legal Judgment Prediction via Large Language Models and Knowledge Integration**.

   *Wang X, Zhang X, Hoo V, et al*. IEEE Access [J]. [[pdf](<https://ieeexplore.ieee.org/iel8/6287639/6514899/10750819.pdf>)][[dataset1](<https://cail.oss-cn-qingdao.aliyuncs.com/CAIL2018_ALL_DATA.zip>)][[dataset2](<https://archive.org/details/ECHR-ACL2019>)]

10. **Rethinking the Development of Large Language Models from the Causal Perspective: A Legal Text Prediction Case Study**.

    *Chen H, Zhang L, Liu Y, et al*. AAAI 2024 [C]. [[pdf](<https://ojs.aaai.org/index.php/AAAI/article/download/30086/31914>)][[dataset1](<https://archive.org/details/ECHR-ACL2019>)][[dataset2](<https://huggingface.co/datasets/ecthr_cases>)][[dataset3](<https://drive.switch.ch/index.php/s/j9S0GRMAbGZKa1A>)]

11. **Legal Syllogism Prompting: Teaching Large Language Models for Legal Judgment Predictions**.

    *Jiang C, Yang X*. ICAIL 2023 [C]. [[pdf](<https://dl.acm.org/doi/pdf/10.1145/3594536.3595170?casa_token=EyP_LqQK7kIAAAAA:loANkbImAXC8PDXafXgu0AsRqZkEY4BHx82eKq3aaVn1weHPtUSGIx5k0xGdugAAw4294k-kyRtW>)][[dataset](<https://cail.oss-cn-qingdao.aliyuncs.com/CAIL2018_ALL_DATA.zip>)]

12. **Legal Judgment Prediction with LLM and Graph Contrastive Learning Networks**.

    *Xia Y, Luo X*. CSAI 2024 [C]. [[pdf](<https://dl.acm.org/doi/pdf/10.1145/3709026.3709068?casa_token=Rl1sIKwQF58AAAAA:TxZbQp4bKQnNpxzLEDpnKztm6EiOwVqtbDtwEBIagqX2ttU0vqp8W8j_36x16GAbz6lqnEXw5U_wjg>)][[dataset1](<https:%20//huggingface.co/datasets/coastalcph/fairlex/viewer/ecthr>)][[dataset2](<https:%20//huggingface.co/datasets/AUEB-NLP/ecthr_cases>)]

13. **Chinese legal judgment prediction via knowledgeable prompt learning**.

    *Sun J, Huang S, Wei C*. Expert Systems with Applications [J]. [[pdf](<https://www.sciencedirect.com/science/article/pii/S0957417423026799/pdfft?md5=d162260aeff07804848c7eabaaff25f9&pid=1-s2.0-S0957417423026799-main.pdf>)][[dataset](<https://cail.oss-cn-qingdao.aliyuncs.com/CAIL2018_ALL_DATA.zip>)]

14. **Harnessing GPT-3.5-turbo for Rhetorical Role Prediction in Legal Cases**.

    *Belfathi A, Hernandez N, Monceaux L*. JURIX 2023 [C]. [[pdf](<https://arxiv.org/pdf/2310.17413>)][[dataset](<https://github.com/Legal-NLP-EkStep/rhetorical-role-baseline>)]

15. **NYAYAANUMANA and INLEGALLLAMA: The Largest Indian Legal Judgment Prediction Dataset and Specialized Language Model for Enhanced Decision Analysis**.

    *Nigam S K, Patnaik B D, Mishra S*. COLING 2025 [C]. [[pdf](<https://arxiv.org/pdf/2412.08385>)][[dataset](<https://github.com/ShubhamKumarNigam/NyayaAnumana-and-INLegalLlama>)]

16. **Topic classification of case law using a large language model and a new taxonomy for UK law: AI insights into summary judgment**.

    *Sargeant H, Izzidien A, Steffek F*. Artificial Intelligence and Law [J]. [[pdf](<https://link.springer.com/content/pdf/10.1007/s10506-025-09434-0.pdf>)][[dataset](<https://www.cst.cam.ac.uk/research/srg/projects/law>)] 

18. **LLMs–the Good, the Bad or the Indispensable?: A Use Case on Legal Statute Prediction and Legal Judgment Prediction on Indian Court Cases**.

    *Vats S, Zope A, De S, et al*. EMNLP (Findings) 2023 [C]. [[pdf](<https://aclanthology.org/2023.findings-emnlp.831.pdf>)][[dataset](<https://github.com/somsubhra04/LLM_Legal_Prompt_Generation>)]

### &nbsp;&nbsp;&nbsp;Evaluation ###

#### &nbsp;&nbsp;&nbsp;Dimensions  ####

1. **GOLDCOIN: Grounding Large Language Models in Privacy Laws via Contextual Integrity Theory**.

   *Fan W, Li H, Deng Z*. IEEE Access [J]. [[pdf](<https://aclanthology.org/2024.emnlp-main.195.pdf>)][[dataset](<https://github.com/HKUST-KnowComp/GoldCoin>)]

2. **Syllogistic Reasoning for Legal Judgment Analysis**.

   *Deng W, Pei J, Kong K, et al*. EMNLP 2023 [C]. [[pdf](<https://aclanthology.org/2023.emnlp-main.864.pdf>)][[dataset](<https://share.weiyun.com/KpNPqFtt>)]

3. **The unreasonable effectiveness of large language models in zero-shot semantic annotation of legal texts**.

   *Savelka J, Ashley K D*. Frontiers in Artificial Intelligence [J]. [[pdf](<https://www.frontiersin.org/journals/artificial-intelligence/articles/10.3389/frai.2023.1279794/pdf>)][[dataset1](<https://github.com/LLTLab/VetClaims-JSON>)][[dataset2](<https://www.atticusprojectai.org/cuad>)][[dataset3](<https://www.phasys.pitt.edu/contact.html>)]

4. **Courtroom-LLM: A Legal-Inspired Multi-LLM Framework for Resolving Ambiguous Text Classifications**.

   *Jung S, Jung J*. COLING 2025 [C]. [[pdf](<https://aclanthology.org/2025.coling-main.493.pdf>)]

5. **Fine-tuning GPT-3 for legal rule classification**.

   *Liga D, Robaldo L*. Computer Law & Security Review [J]. [[pdf](<https://www.sciencedirect.com/science/article/pii/S0267364923000742/pdfft?md5=f53d2a0a4355c818ac8112a1101c35e9&pid=1-s2.0-S0267364923000742-main.pdf>)][[dataset](<https://github.com/dapreco/daprecokb/blob/master/gdpr/rioKB_GDPR.xml>)]

6. **NYAYAANUMANA and INLEGALLLAMA: The Largest Indian Legal Judgment Prediction Dataset and Specialized Language Model for Enhanced Decision Analysis**.

   *Nigam S K, Patnaik B D, Mishra S*. COLING 2025 [C]. [[pdf](<https://arxiv.org/pdf/2412.08385>)][[dataset](<https://github.com/ShubhamKumarNigam/NyayaAnumana-and-INLegalLlama>)]

7. **Experimental Study of In-Context Learning for Text Classification and Its Application to Legal Document Review in Construction Delay Disputes**.

   *Huber-Fliflet N, Zhang J, Gronvall P*. IEEE Big Data 2024 [C]. [[pdf](<https://ieeexplore.ieee.org/iel8/10824975/10824942/10826061.pdf?casa_token=s7AlN8_ORVYAAAAA:XzADl2pWde8Um6Lso5GmAo5maoZsbh42zMRkQ4tgq_CeX_-INAnV3hTalrm7LTBtxV8E6gWaIHcQXA>)]

8. **Using LLMs to Discover Legal Factors**.

   *Gray M, Savelka J, Oliver W, et al*. JURIX 2024 [C]. [[pdf](<https://ebooks.iospress.nl/pdf/doi/10.3233/FAIA241234>)]

#### &nbsp;&nbsp;&nbsp;Methods ####

1. **GOLDCOIN: Grounding Large Language Models in Privacy Laws via Contextual Integrity Theory**.

   *Fan W, Li H, Deng Z*. IEEE Access [J]. [[pdf](<https://aclanthology.org/2024.emnlp-main.195.pdf>)][[dataset](<https://github.com/HKUST-KnowComp/GoldCoin>)]

## Legal Retrieval

### &nbsp;&nbsp;&nbsp;Data ###

#### &nbsp;&nbsp;&nbsp;Samples ####

1. **CAPTAIN at COLIEE 2024: Large Language Model for Legal Text Retrieval and Entailment**.

   *Nguyen P, Nguyen C, Nguyen H, et al*. JSAI-isAI 2024 [C]. [[pdf](<https://link.springer.com/content/pdf/10.1007/978-981-97-3076-6.pdf>)][[dataset](<https://coliee.org/application>)]

2. **Explicitly Integrating Judgment Prediction with Legal Document Retrieval A Law-Guided Generative Approach**.

   *Qin W, Cao Z, Yu W, et al*. SIGIR 2024 [C]. [[pdf](<https://arxiv.org/pdf/2312.09591>)][[dataset1](<https://github.com/ruc-wjyu/OPT-Match>)][[dataset2](<https://github.com/THUIR/LeCaRDv2>)][[dataset3](<https://huggingface.co/datasets/maastrichtlawtech/bsard>)]

3. **Exploiting LLMs' Reasoning Capability to Infer Implicit Concepts in Legal Information Retrieval**.

   *Nguyen H L, Nguyen T M, Nguyen D M, et al*. NeLaMKRR 2024 [C]. [[pdf](<https://arxiv.org/pdf/2410.12154>)][[dataset](<https://coliee.org/application>)]

4. **LawLLM: Law Large Language Model for the US Legal System**.

   *Shu D, Zhao H, Liu X, et al*. CIKM 2024 [C]. [[pdf](<https://dl.acm.org/doi/pdf/10.1145/3627673.3680020>)][[dataset](<https://case.law>)]

5. **Legal Query RAG**.

   *Wahidur R S, Kim S, Choi H, et al*. IEEE Access [J]. [[pdf](<https://ieeexplore.ieee.org/iel8/6287639/6514899/10887211.pdf>)][[dataset](<https://huggingface.co/datasets/ibunescu/qa_legal_dataset_train>)]

6. **AIIR Lab at COLIEE 2025: Exploring Applications of Large Language Models for Legal Text Retrieval and Entailment**.

   *Wu D, Lawrence S, Mansouri B*. COLIEE 2025 Workshop [C]. [[pdf](<https://www.researchgate.net/profile/Behrooz-Mansouri/publication/393924641_AIIR_Lab_at_COLIEE_2025_Exploring_Applications_of_Large_Language_Models_for_Legal_Text_Retrieval_and_Entailment/links/689acfd1659b52652cdf3dd2/AIIR-Lab-at-COLIEE-2025-Exploring-Applications-of-Large-Language-Models-for-Legal-Text-Retrieval-and-Entailment.pdf>)][[dataset](<https://coliee.org/application>)]

7. **Learning Interpretable Legal Case Retrieval via Knowledge-Guided Case Reformulation**.

   *Deng C, Mao K, Dou Z*. EMNLP 2024 [C]. [[pdf](<https://arxiv.org/pdf/2406.19760>)][[dataset1](<https://github.com/myx666/LeCaRD>)][[dataset2](<https://github.com/THUIR/LeCaRDv2>)]

#### &nbsp;&nbsp;&nbsp;Labels ####

1. **LawLLM: Law Large Language Model for the US Legal System**.

   *Shu D, Zhao H, Liu X, et al*. CIKM 2024 [C]. [[pdf](<https://dl.acm.org/doi/pdf/10.1145/3627673.3680020>)][[dataset](<https://case.law>)]

2. **Leveraging Large Language Models for Relevance Judgments in Legal Case Retrieval**.

   *Ma S, Chen C, Chu Q, et al*. arXiv [EB/OL]. [[pdf](<https://arxiv.org/pdf/2403.18405?>)][[dataset](<https://github.com/myx666/LeCaRD>)]

3. **LeDQA: A Chinese Legal Case Document-based Question Answering Dataset**.

   *Liu B, Zhu Z, Ai Q, et al*. CIKM 2024 [C]. [[pdf](<https://dl.acm.org/doi/pdf/10.1145/3627673.3679154>)][[dataset](<https://github.com/BulouLiu/LeDQA>)]

### &nbsp;&nbsp;&nbsp;Modeling ###

#### &nbsp;&nbsp;&nbsp;LLM Enhancement ####

1. **CAPTAIN at COLIEE 2024: Large Language Model for Legal Text Retrieval and Entailment**.

   *Nguyen P, Nguyen C, Nguyen H, et al*. JSAI-isAI 2024 [C]. [[pdf](<https://link.springer.com/content/pdf/10.1007/978-981-97-3076-6.pdf>)][[dataset](<https://coliee.org/application>)]

2. **LawLLM: Law Large Language Model for the US Legal System**.

   *Shu D, Zhao H, Liu X, et al*. CIKM 2024 [C]. [[pdf](<https://dl.acm.org/doi/pdf/10.1145/3627673.3680020>)][[dataset](<https://case.law>)]

3. **Legal Query RAG**.

   *Wahidur R S, Kim S, Choi H, et al*. IEEE Access [J]. [[pdf](<https://ieeexplore.ieee.org/iel8/6287639/6514899/10887211.pdf>)][[dataset](<https://huggingface.co/datasets/ibunescu/qa_legal_dataset_train>)]

4. **CAPTAIN at COLIEE 2025: Enhancing Legal Text Processing and Structural Analysis with Large Language Models**.

   *Nguyen D, Nguyen M-P , Chu Q-H, et al*. COLIEE 2025 Workshop [C]. [[pdf](<https://coliee.org/documents/Proceedings/2025-Proceedings.pdf>)][[dataset](<https://coliee.org/application>)]

5. **Jnlp at COLIEE 2025: Hybrid large language model-based framework for legal information retrieval and entailment**.

   *Nguyen H, Nguyen H, Pham T, et al*. COLIEE 2025 Workshop [C]. [[pdf](<https://coliee.org/documents/Proceedings/2025-Proceedings.pdf>)][[dataset](<https://coliee.org/application>)]

6. **Exploiting LLMs' Reasoning Capability to Infer Implicit Concepts in Legal Information Retrieval**.

   *Nguyen H-L, Nguyen T-M, Nguyen D-M, et al*. NeLaMKRR 2024 [C]. [[pdf](<https://arxiv.org/pdf/2410.12154>)][[dataset](<https://coliee.org/application>)]

7. **Learning Interpretable Legal Case Retrieval via Knowledge-Guided Case Reformulation**.

   *Deng C, Mao K, Dou Z*. EMNLP 2024 [C]. [[pdf](<https://arxiv.org/pdf/2406.19760>)][[dataset1](<https://github.com/myx666/LeCaRD>)][[dataset2](<https://github.com/THUIR/LeCaRDv2>)]

8. **Leveraging Natural Language Processing and Large Language Models for Assisting Due Diligence in the Legal Domain**.

   *Jang M, Stikkel G*. NAACL 2024 [C]. [[pdf](<https://aclanthology.org/2024.naacl-industry.14.pdf>)][[dataset](<https://science.kirasystems.com/>)]

9. **Pushing the Boundaries of Legal Information Processing with Integration of Large Language Models**.

   *Nguyen C, Tran T, Le K, et al*. JSAI-isAI 2024 [C]. [[pdf](<https://link.springer.com/content/pdf/10.1007/978-981-97-3076-6.pdf>)][[dataset](<https://coliee.org/application>)]

10. **Leveraging Large Language Models for Relevance Judgments in Legal Case Retrieval**.

     *Ma S, Chen C, Chu Q, et al*. arXiv [EB/OL]. [[pdf](<https://arxiv.org/pdf/2403.18405?>)][[dataset](<https://github.com/myx666/LeCaRD>)]

11. **NOWJ@COLIEE 2025: A Multi-stage Framework Integrating Embedding Models and Large Language Models for Legal Retrieval and Entailment**.

     *Nguyen H-T, Nguyen T-M, Le X-B, et al*. COLIEE 2025 Workshop [C]. [[pdf](<https://coliee.org/documents/Proceedings/2025-Proceedings.pdf>)][[dataset](<https://coliee.org/application>)]

#### &nbsp;&nbsp;&nbsp;LLM-for-SM ####

1. **CAPTAIN at COLIEE 2024: Large Language Model for Legal Text Retrieval and Entailment**.

   *Nguyen P, Nguyen C, Nguyen H, et al*. JSAI-isAI 2024 [C]. [[pdf](<https://link.springer.com/content/pdf/10.1007/978-981-97-3076-6.pdf>)][[dataset](<https://coliee.org/application>)]

2. **Pushing the Boundaries of Legal Information Processing with Integration of Large Language Models**.

   *Nguyen C, Tran T, Le K, et al*. JSAI-isAI 2024 [C]. [[pdf](<https://link.springer.com/content/pdf/10.1007/978-981-97-3076-6.pdf>)][[dataset](<https://coliee.org/application>)]

3. **LeDQA: A Chinese Legal Case Document-based Question Answering Dataset**.

   *Liu B, Zhu Z, Ai Q, et al*. CIKM 2024 [C]. [[pdf](<https://dl.acm.org/doi/pdf/10.1145/3627673.3679154>)][[dataset](<https://github.com/BulouLiu/LeDQA>)]

4. **UQLegalAI@COLIEE2025: Advancing Legal Case Retrieval with Large Language Models and Graph Neural Networks**.

   *Tang Y, Qiu R, Huang Z*. COLIEE 2025 Workshop [C]. [[pdf](<https://coliee.org/documents/Proceedings/2025-Proceedings.pdf>)][[dataset](<https://coliee.org/application>)]

5. **IRNLPUI at COLIEE 2025: Utilization of LLMs for Statute Law Retrieval and Legal Entailment Task**.

   *Tjandra B, Negara M S N , Wicaksono A F*. COLIEE 2025 Workshop [C]. [[pdf](<https://coliee.org/documents/Proceedings/2025-Proceedings.pdf>)][[dataset](<https://coliee.org/application>)]

#### &nbsp;&nbsp;&nbsp;Frameworks ####

1. **CAPTAIN at COLIEE 2024: Large Language Model for Legal Text Retrieval and Entailment**.

   *Nguyen P, Nguyen C, Nguyen H, et al*. JSAI-isAI 2024 [C]. [[pdf](<https://link.springer.com/content/pdf/10.1007/978-981-97-3076-6.pdf>)][[dataset](<https://coliee.org/application>)]

2. **Explicitly Integrating Judgment Prediction with Legal Document Retrieval A Law-Guided Generative Approach**.

   *Qin W, Cao Z, Yu W, et al*. SIGIR 2024 [C]. [[pdf](<https://arxiv.org/pdf/2312.09591>)][[dataset1](<https://github.com/ruc-wjyu/OPT-Match>)][[dataset2](<https://github.com/THUIR/LeCaRDv2>)][[dataset3](<https://huggingface.co/datasets/maastrichtlawtech/bsard>)]

3. **Exploiting LLMs' Reasoning Capability to Infer Implicit Concepts in Legal Information Retrieval**.

   *Nguyen H-L, Nguyen T-M, Nguyen D-M, et al*. NeLaMKRR 2024 [C]. [[pdf](<https://arxiv.org/pdf/2410.12154>)][[dataset](<https://coliee.org/application>)]

4. **LawLLM: Law Large Language Model for the US Legal System**.

   *Shu D, Zhao H, Liu X, et al*. CIKM 2024 [C]. [[pdf](<https://dl.acm.org/doi/pdf/10.1145/3627673.3680020>)][[dataset](<https://case.law>)]

5. **Learning Interpretable Legal Case Retrieval via Knowledge-Guided Case Reformulation**.

   *Deng C, Mao K, Dou Z*. EMNLP 2024 [C]. [[pdf](<https://arxiv.org/pdf/2406.19760>)][[dataset1](<https://github.com/myx666/LeCaRD>)][[dataset2](<https://github.com/THUIR/LeCaRDv2>)]

6. **Legal Query RAG**.

   *Wahidur R S, Kim S, Choi H, et al*. IEEE Access [J]. [[pdf](<https://ieeexplore.ieee.org/iel8/6287639/6514899/10887211.pdf>)][[dataset](<https://huggingface.co/datasets/ibunescu/qa_legal_dataset_train>)]

7. **Leveraging Natural Language Processing and Large Language Models for Assisting Due Diligence in the Legal Domain**.

   *Jang M, Stikkel G*. NAACL 2024 [C]. [[pdf](<https://aclanthology.org/2024.naacl-industry.14.pdf>)][[dataset](<https://science.kirasystems.com/>)]

8. **Pushing the Boundaries of Legal Information Processing with Integration of Large Language Models**.

   *Nguyen C, Tran T, Le K, et al*. JSAI-isAI 2024 [C]. [[pdf](<https://link.springer.com/content/pdf/10.1007/978-981-97-3076-6.pdf>)][[dataset](<https://coliee.org/application>)]

9. **LLMs, Knowledge Graphs, and Hybrid Search: Task-Specific Approaches to Legal AI in COLIEE**.

   *Wehnert S, Valappil B, Luca E*. COLIEE 2025 Workshop [C]. [[pdf](<https://coliee.org/documents/Proceedings/2025-Proceedings.pdf>)][[dataset](<https://coliee.org/application>)]

### &nbsp;&nbsp;&nbsp;Evaluation ###

#### &nbsp;&nbsp;&nbsp;Dimensions  ####

1. **Exploiting LLMs' Reasoning Capability to Infer Implicit Concepts in Legal Information Retrieval**.

   *Nguyen H L, Nguyen T M, Nguyen D M, et al*. NeLaMKRR 2024 [C]. [[pdf](<https://arxiv.org/pdf/2410.12154>)][[dataset](<https://coliee.org/application>)]

2. **Legal Query RAG**.

   *Wahidur R S, Kim S, Choi H, et al*. IEEE Access [J]. [[pdf](<https://ieeexplore.ieee.org/iel8/6287639/6514899/10887211.pdf>)][[dataset](<https://huggingface.co/datasets/ibunescu/qa_legal_dataset_train>)]

3. **Leveraging Natural Language Processing and Large Language Models for Assisting Due Diligence in the Legal Domain**.

   *Jang M, Stikkel G*. NAACL 2024 [C]. [[pdf](<https://aclanthology.org/2024.naacl-industry.14.pdf>)][[dataset](<https://science.kirasystems.com/>)]

4. **Pushing the Boundaries of Legal Information Processing with Integration of Large Language Models**.

   *Nguyen C, Tran T, Le K, et al*. JSAI-isAI 2024 [C]. [[pdf](<https://link.springer.com/content/pdf/10.1007/978-981-97-3076-6.pdf>)][[dataset](<https://coliee.org/application>)]

#### &nbsp;&nbsp;&nbsp;Methods ####

1. **Legal Query RAG**.

   *Wahidur R S, Kim S, Choi H, et al*. IEEE Access [J]. [[pdf](<https://ieeexplore.ieee.org/iel8/6287639/6514899/10887211.pdf>)][[dataset](<https://huggingface.co/datasets/ibunescu/qa_legal_dataset_train>)]

2. **Leveraging Natural Language Processing and Large Language Models for Assisting Due Diligence in the Legal Domain**.

   *Jang M, Stikkel G*. NAACL 2024 [C]. [[pdf](<https://aclanthology.org/2024.naacl-industry.14.pdf>)][[dataset](<https://science.kirasystems.com/>)]

3. **Pushing the Boundaries of Legal Information Processing with Integration of Large Language Models**.

   *Nguyen C, Tran T, Le K, et al*. JSAI-isAI 2024 [C]. [[pdf](<https://link.springer.com/content/pdf/10.1007/978-981-97-3076-6.pdf>)][[dataset](<https://coliee.org/application>)]

## Legal Generation

### &nbsp;&nbsp;&nbsp;Data ###

#### &nbsp;&nbsp;&nbsp;Samples ####

1. **Unleashing the Power of LLMs in Court View Generation by Stimulating Internal Knowledge and Incorporating External Knowledge**.

   *Liu Y, Wu Y, Li A, et al*. NAACL (Findings) 2024 [C]. [[pdf](<https://aclanthology.org/2024.findings-naacl.177.pdf>)][[dataset](<https://data.court.gov.cn/pages/laic2021.html>)]

2. **Bringing legal knowledge to the public by constructing a legal question bank using large-scale pre-trained language model**.

   *Yuan M, Kao B, Wu T H, et al*. Artif. Intell. Law [J]. [[pdf](<https://link.springer.com/content/pdf/10.1007/s10506-023-09367-6.pdf>)]
   
3. **CBR-RAG: Case-Based Reasoning for Retrieval Augmented Generation in LLMs for Legal Question Answering**.

   *Wiratunga N, Abeyratne R, Jayawardena L, et al*. ICCBR 2024 [C]. [[pdf](<https://arxiv.org/pdf/2404.04302>)][[dataset](<https://huggingface.co/datasets/umarbutler/open-australian-legal-qa>)]

4. **Fine-tuning Large Language Models for Improving Factuality in Legal Question Answering**.

   *Hu Y, Gan L, Xiao W, et al*. COLING 2025 [C]. [[pdf](<https://arxiv.org/pdf/2501.06521>)][[dataset](<https://github.com/YinghaoHu/LegalHalBench>)]

5. **Legal Query RAG**.

   *Wahidur R S, Kim S, Choi H, et al*. IEEE Access [J]. [[pdf](<https://ieeexplore.ieee.org/iel8/6287639/6514899/10887211.pdf>)][[dataset](<https://huggingface.co/datasets/ibunescu/qa_legal_dataset_train>)]

6. **Event Extraction and Semantic Representation from Spanish Workers’ Statute Using Large Language Models**.

   *Argüelles Terrón G, Martín Chozas P, Rodríguez Doncel V*. JURIX 2023 [C]. [[pdf](<https://ebooks.iospress.nl/pdf/doi/10.3233/FAIA230983>)][[dataset](< https://zenodo.org/records/8143596>)]

7. **Fighting the Knowledge Representation Bottleneck with Large Language Models**.

    *Billi M, Pisano G, Sanchi M*. JURIX 2024 [C]. [[pdf](<https://ebooks.iospress.nl/pdf/doi/10.3233/FAIA241230>)]

8. **From text to structure: Using large language models to support the development of legal expert systems**.

    *Janatian S, Westermann H, Tan J, et al*. JURIX 2023 [C]. [[pdf](<https://ebooks.iospress.nl/pdf/doi/10.3233/FAIA230962>)]

#### &nbsp;&nbsp;&nbsp;Labels ####

1. **Agenda-Driven Question Generation: A Case Study in the Courtroom Domain**.

   *Fung Y, Kumar A, Galstyan A, et al*.  NAACL (Findings) 2024 [C]. [[pdf](<https://aclanthology.org/2024.lrec-main.49.pdf>)]

2. **Interpretable Long-Form Legal Question Answering with Retrieval-Augmented Large Language Models**.

   *Louis A, van Dijck G, Spanakis G*. NAACL 2024 [C]. [[pdf](<https://arxiv.org/pdf/2309.17050>)][[dataset](<https://github.com/maastrichtlawtech/lleqa>)]

3. **Enhancing legal assistance with AI: a comprehensive approach to intent classification and domain specific model tuning**.

   *Bhatnagar M, Huchhanavar S*. Artif. Intell. Law [J]. [[pdf](<https://link.springer.com/content/pdf/10.1007/s10506-025-09441-1.pdf>)]

### &nbsp;&nbsp;&nbsp;Modeling ###

#### &nbsp;&nbsp;&nbsp;LLM Enhancement ####

1. **Divide and Conquer: Legal Concept-guided Criminal Court View Generation**.

   *Xu Q, Wei X, Yu H, Liu Q, Fei H*. EMNLP (Findings) 2024 [C]. [[pdf](<https://aclanthology.org/2024.findings-emnlp.194.pdf>)][[dataset](<https://github.com/xuqi220/LeGen>)]

2. **Agenda-Driven Question Generation: A Case Study in the Courtroom Domain**.

   *Fung Y, Kumar A, Galstyan A, et al*.  NAACL (Findings) 2024 [C]. [[pdf](<https://aclanthology.org/2024.lrec-main.49.pdf>)]

3. **Interpretable Long-Form Legal Question Answering with Retrieval-Augmented Large Language Models**.

   *Louis A, van Dijck G, Spanakis G*. NAACL 2024 [C]. [[pdf](<https://arxiv.org/pdf/2309.17050>)][[dataset](<https://github.com/maastrichtlawtech/lleqa>)]

4. **Enhancing legal assistance with AI: a comprehensive approach to intent classification and domain specific model tuning**.

   *Bhatnagar M, Huchhanavar S*. Artif. Intell. Law [J]. [[pdf](<https://link.springer.com/content/pdf/10.1007/s10506-025-09441-1.pdf>)]

5. **From text to structure: Using large language models to support the development of legal expert systems**.

   *Janatian S, Westermann H, Tan J, et al*. JURIX 2023 [C]. [[pdf](<https://ebooks.iospress.nl/pdf/doi/10.3233/FAIA230962>)]

6. **Legal Query RAG**.

   *Wahidur R S, Kim S, Choi H, et al*. IEEE Access [J]. [[pdf](<https://ieeexplore.ieee.org/iel8/6287639/6514899/10887211.pdf>)][[dataset](<https://huggingface.co/datasets/ibunescu/qa_legal_dataset_train>)]

7. **Unleashing the Power of LLMs in Court View Generation by Stimulating Internal Knowledge and Incorporating External Knowledge**.

   *Liu Y, Wu Y, Li A, et al*. NAACL (Findings) 2024 [C]. [[pdf](<https://aclanthology.org/2024.findings-naacl.177.pdf>)][[dataset](<https://data.court.gov.cn/pages/laic2021.html>)]

8. **AgentsCourt: Building Judicial Decision-Making Agents with Court Debate Simulation and Legal Knowledge Augmentation**.

   *He Z, Cao P, Wang C, et al*. EMNLP (Findings) 2024 [C]. [[pdf](<https://arxiv.org/pdf/2403.02959>)]

9. **Bringing legal knowledge to the public by constructing a legal question bank using large-scale pre-trained language model**.

   *Yuan M, Kao B, Wu T H, et al*. Artif. Intell. Law [J]. [[pdf](<https://link.springer.com/content/pdf/10.1007/s10506-023-09367-6.pdf>)]

10. **Event Extraction and Semantic Representation from Spanish Workers’ Statute Using Large Language Models**.

     *Argüelles Terrón G, Martín Chozas P, Rodríguez Doncel V*. JURIX 2023 [C]. [[pdf](<https://ebooks.iospress.nl/pdf/doi/10.3233/FAIA230983>)][[dataset](< https://zenodo.org/records/8143596>)]

11. **Fighting the Knowledge Representation Bottleneck with Large Language Models**.

     *Billi M, Pisano G, Sanchi M*. JURIX 2024 [C]. [[pdf](<https://ebooks.iospress.nl/pdf/doi/10.3233/FAIA241230>)]

12. **From text to structure: Using large language models to support the development of legal expert systems**.

    *Janatian S, Westermann H, Tan J, et al*. JURIX 2023 [C]. [[pdf](<https://ebooks.iospress.nl/pdf/doi/10.3233/FAIA230962>)]

13. **CBR-RAG: Case-Based Reasoning for Retrieval Augmented Generation in LLMs for Legal Question Answering**.

     *Wiratunga N, Abeyratne R, Jayawardena L, et al*. ICCBR 2024 [C]. [[pdf](<https://arxiv.org/pdf/2404.04302>)][[dataset](<https://huggingface.co/datasets/umarbutler/open-australian-legal-qa>)]

#### &nbsp;&nbsp;&nbsp;Frameworks ####

1. **Divide and Conquer: Legal Concept-guided Criminal Court View Generation**.

   *Xu Q, Wei X, Yu H, Liu Q, Fei H*. EMNLP (Findings) 2024 [C]. [[pdf](<https://aclanthology.org/2024.findings-emnlp.194.pdf>)][[dataset](<https://github.com/xuqi220/LeGen>)]

2. **AgentsCourt: Building Judicial Decision-Making Agents with Court Debate Simulation and Legal Knowledge Augmentation**.

   *He Z, Cao P, Wang C, et al*. EMNLP (Findings) 2024 [C]. [[pdf](<https://arxiv.org/pdf/2403.02959>)]

3. **Bringing legal knowledge to the public by constructing a legal question bank using large-scale pre-trained language model**.

   *Yuan M, Kao B, Wu T H, et al*. Artif. Intell. Law [J]. [[pdf](<https://link.springer.com/content/pdf/10.1007/s10506-023-09367-6.pdf>)]

4. **Enhancing legal assistance with AI: a comprehensive approach to intent classification and domain specific model tuning**.

   *Bhatnagar M, Huchhanavar S*. Artif. Intell. Law [J]. [[pdf](<https://link.springer.com/content/pdf/10.1007/s10506-025-09441-1.pdf>)]

5. **Legal Query RAG**.

   *Wahidur R S, Kim S, Choi H, et al*. IEEE Access [J]. [[pdf](<https://ieeexplore.ieee.org/iel8/6287639/6514899/10887211.pdf>)][[dataset](<https://huggingface.co/datasets/ibunescu/qa_legal_dataset_train>)]

6. **Event Extraction and Semantic Representation from Spanish Workers’ Statute Using Large Language Models**.

   *Argüelles Terrón G, Martín Chozas P, Rodríguez Doncel V*. JURIX 2023 [C]. [[pdf](<https://ebooks.iospress.nl/pdf/doi/10.3233/FAIA230983>)][[dataset](< https://zenodo.org/records/8143596>)]

### &nbsp;&nbsp;&nbsp;Evaluation ###

#### &nbsp;&nbsp;&nbsp;Dimensions  ####

1. **From text to structure: Using large language models to support the development of legal expert systems**.

   *Janatian S, Westermann H, Tan J, et al*. JURIX 2023 [C]. [[pdf](<https://ebooks.iospress.nl/pdf/doi/10.3233/FAIA230962>)]

2. **Legal Query RAG**.

   *Wahidur R S, Kim S, Choi H, et al*. IEEE Access [J]. [[pdf](<https://ieeexplore.ieee.org/iel8/6287639/6514899/10887211.pdf>)][[dataset](<https://huggingface.co/datasets/ibunescu/qa_legal_dataset_train>)]

#### &nbsp;&nbsp;&nbsp;Methods ####

1. **Adapting Abstractive Summarization to Court Examinations in a Zero-Shot Setting: A Short Technical Paper**.

   *Epps M, Njoo L, Willey C, Forney A*. ICAIL 2023 [C]. [[pdf](<https://ceur-ws.org/Vol-3435/short3.pdf>)]

2. **Divide and Conquer: Legal Concept-guided Criminal Court View Generation**.

   *Xu Q, Wei X, Yu H, Liu Q, Fei H*. EMNLP (Findings) 2024 [C]. [[pdf](<https://aclanthology.org/2024.findings-emnlp.194.pdf>)][[dataset](<https://github.com/xuqi220/LeGen>)]

3. **AgentsCourt: Building Judicial Decision-Making Agents with Court Debate Simulation and Legal Knowledge Augmentation**.

   *He Z, Cao P, Wang C, et al*. EMNLP (Findings) 2024 [C]. [[pdf](<https://arxiv.org/pdf/2403.02959>)]

4. **Agenda-Driven Question Generation: A Case Study in the Courtroom Domain**.

   *Fung Y, Kumar A, Galstyan A, et al*.  NAACL (Findings) 2024 [C]. [[pdf](<https://aclanthology.org/2024.lrec-main.49.pdf>)]

5. **CBR-RAG: Case-Based Reasoning for Retrieval Augmented Generation in LLMs for Legal Question Answering**.

   *Wiratunga N, Abeyratne R, Jayawardena L, et al*. ICCBR 2024 [C]. [[pdf](<https://arxiv.org/pdf/2404.04302>)][[dataset](<https://huggingface.co/datasets/umarbutler/open-australian-legal-qa>)]

6. **Fine-tuning Large Language Models for Improving Factuality in Legal Question Answering**.

   *Hu Y, Gan L, Xiao W, et al*. COLING 2025 [C]. [[pdf](<https://arxiv.org/pdf/2501.06521>)][[dataset](<https://github.com/YinghaoHu/LegalHalBench>)]

7. **Legal Query RAG**.

   *Wahidur R S, Kim S, Choi H, et al*. IEEE Access [J]. [[pdf](<https://ieeexplore.ieee.org/iel8/6287639/6514899/10887211.pdf>)][[dataset](<https://huggingface.co/datasets/ibunescu/qa_legal_dataset_train>)]

8. **From text to structure: Using large language models to support the development of legal expert systems**.

   *Janatian S, Westermann H, Tan J, et al*. JURIX 2023 [C]. [[pdf](<https://ebooks.iospress.nl/pdf/doi/10.3233/FAIA230962>)]

9. **Enhancing legal assistance with AI: a comprehensive approach to intent classification and domain specific model tuning**.

   *Bhatnagar M, Huchhanavar S*. Artif. Intell. Law [J]. [[pdf](<https://link.springer.com/content/pdf/10.1007/s10506-025-09441-1.pdf>)]

   
