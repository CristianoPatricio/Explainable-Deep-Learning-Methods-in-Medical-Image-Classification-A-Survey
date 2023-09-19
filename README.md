# Explainable Deep Learning Methods in Medical Image Classification: A Survey

![XAI Categorization](https://github.com/CristianoPatricio/Explainable-Deep-Learning-Methods-in-Medical-Image-Classification-A-Survey/blob/main/xai_categorization.png)

For an interactive version of the table of the survey, allowing sorting by *year*, *interpretability method*, and *dataset*, <a href="http://socia-lab.di.ubi.pt/~cristiano_patricio/survey/" target="blank">click here</a>. 

![Interactive Table](https://github.com/CristianoPatricio/Explainable-Deep-Learning-Methods-in-Medical-Image-Classification-A-Survey/blob/main/table.gif)

## Table of Contents:
- [Survey Papers](#survey-papers)
- [XAI Methods in Medical Diagnosis](#xai-methods-in-medical-diagnosis)
  - [Explanation by Feature Attribution](#explanation-by-feature-attribution)
    - [Perturbation-based methods](#perturbation-based-methods)
    - [Saliency Methods](#saliency-methods)
  - [Explanation by Text](#explanation-by-text)
    - [Image Captioning](#image-captioning)
    - [Concept Attribution](#concept-attribution)
  - [Explanation by Examples](#explanation-by-examples)
    - [Case-Based Reasoning](#case-based-reasoning)
    - [Counterfactual Explanations](#counterfactual-explanations)
    - [Prototypes](#prototypes)
  - [Explanation by Concepts](#explanation-by-concepts)
  - [Other Approaches](#other-approaches)
    - [Bayesian Approaches](#bayesian-approaches)
    - [Adversarial Training](#adversarial-training)

## Survey Papers

1. Milda Pocevičiute, Gabriel Eilertsen, and Claes Lundström <br>
<span style="font-size:15px; color:#bd5d38;">**Survey of XAI in Digital Pathology**</span> <br>
*Artificial Intelligence and Machine Learning for Digital Pathology: State-of-the-Art and Future Challenges, 56–88, 2020* <br>
<span style="font-size:15px;"><a href="https://arxiv.org/pdf/2008.06353.pdf" target="blank">:page_facing_up: Paper</a></span> 

<br>

2. Erico Tjoa and Cuntai Guan <br>
<span style="font-size:15px; color:#bd5d38;">**A Survey on Explainable Artificial Intelligence (XAI): Towards Medical XAI**</span> <br>
*IEEE Transactions on
Neural Networks and Learning Systems 32, 11 (2020), 4793–4813* <br>
<span style="font-size:15px;"><a href="https://arxiv.org/pdf/1907.07374.pdf" target="blank">:page_facing_up: Paper</a></span> 

<br>

3. Amitojdeep Singh, Sourya Sengupta, and Vasudevan Lakshminarayanan <br>
<span style="font-size:15px; color:#bd5d38;">**Explainable Deep Learning Models in Medical Image
Analysis**</span> <br>
*Journal of Imaging 6, 6 (2020), 52* <br>
<span style="font-size:15px;"><a href="https://arxiv.org/pdf/2005.13799.pdf" target="blank">:page_facing_up: Paper</a></span> 

<br>

4. Mehmet A Gulum, Christopher M Trombley, and Mehmed Kantardzic <br>
<span style="font-size:15px; color:#bd5d38;">**A Review of Explainable Deep Learning Cancer Detection
Models in Medical Imaging**</span> <br>
*Applied Sciences 11, 10 (2021), 4573* <br>
<span style="font-size:15px;"><a href="https://www.mdpi.com/2076-3417/11/10/4573" target="blank">:page_facing_up: Paper</a></span>

<br>

5. Hareem Ayesha, Sajid Iqbal, Mehreen Tariq, Muhammad Abrar, Muhammad Sanaullah, Ishaq Abbas, Amjad Rehman, Muhammad
Farooq Khan Niazi, and Shafiq Hussain <br>
<span style="font-size:15px; color:#bd5d38;">**Automatic medical image interpretation: State of the art and future directions**</span> <br>
*Pattern
Recognition 114 (2021), 107856* <br>
<span style="font-size:15px;"><a href="https://www.sciencedirect.com/science/article/pii/S0031320321000431" target="blank">:page_facing_up: Paper</a></span>

<br>

6. Zohaib Salahuddin, Henry C. Woodruff, Avishek Chatterjee, and Philippe Lambin <br>
<span style="font-size:15px; color:#bd5d38;">**Transparency of Deep Neural Networks for
Medical Image Analysis: A Review of Interpretability Methods**</span> <br>
*Computers in Biology and Medicine 140 (2022), 105111* <br>
<span style="font-size:15px;"><a href="https://www.sciencedirect.com/science/article/pii/S0010482521009057" target="blank">:page_facing_up: Paper</a></span>


<br>

7. Pablo Messina, Pablo Pino, Denis Parra, Alvaro Soto, Cecilia Besa, Sergio Uribe, Marcelo Andía, Cristian Tejos, Claudia Prieto, and
Daniel Capurro <br>
<span style="font-size:15px; color:#bd5d38;">**A survey on deep learning and explainability for automatic report generation from medical images**</span> <br>
*ACM
Computing Surveys (CSUR) 54, 10s (2022), 1–40* <br>
<span style="font-size:15px;"><a href="https://arxiv.org/pdf/2010.10563.pdf" target="blank">:page_facing_up: Paper</a></span>

<br>
<br>

## XAI Methods in Medical Diagnosis

### Explanation by Feature Attribution

#### Perturbation-based methods

1. Avleen Malhi, Timotheus Kampik, Husanbir Pannu, Manik Madhikermi, and Kary Främling<br>
<span style="font-size:15px; color:#bd5d38;">**Explaining Machine Learning-Based
Classifications of In-Vivo Gastral Images**</span> <br>
*Digital Image Computing: Techniques and Applications (DICTA), 1–7, 2019* <br>
<span style="font-size:15px;"><a href="https://ieeexplore.ieee.org/document/8945986" target="blank">:page_facing_up:  Paper</a></span>

<br>

2. Kyle Young, Gareth Booth, Becks Simpson, Reuben Dutton, and Sally Shrapnel<br>
<span style="font-size:15px; color:#bd5d38;">**Deep Neural Network or Dermatologist?**</span> <br>
*Interpretability of Machine Intelligence in Medical Image Computing and Multimodal Learning for Clinical Decision Support, 48–55, 2019* <br>
<span style="font-size:15px;"><a href="https://arxiv.org/abs/1908.06612" target="blank">:page_facing_up:  Paper</a></span>

<br>

3. Fabian Eitel and Kerstin Ritter for the Alzheimer’s Disease Neuroimaging Initiative (ADNI)<br>
<span style="font-size:15px; color:#bd5d38;">**Testing the Robustness of Attribution
Methods for Convolutional Neural Networks in MRI-Based Alzheimer’s Disease Classification**</span> <br>
*Medical Image Computing and Multimodal Learning for Clinical Decision Support (IMIMIC), 3–11, 2019* <br>
<span style="font-size:15px;"><a href="https://arxiv.org/abs/1909.08856" target="blank">:page_facing_up:  Paper</a></span>

<br>

4. Pavan Rajkumar Magesh, Richard Delwin Myloth, and Rijo Jackson Tom<br>
<span style="font-size:15px; color:#bd5d38;">**An Explainable Machine Learning Model for Early
Detection of Parkinson’s Disease using LIME on DaTscan Imagery**</span> <br>
*Computers in Biology and Medicine 126 (2020), 104041* <br>
<span style="font-size:15px;"><a href="https://www.sciencedirect.com/science/article/pii/S0010482520303723" target="blank">:page_facing_up:  Paper</a></span>

<br>

5. Narinder Singh Punn and Sonali Agarwal<br>
<span style="font-size:15px; color:#bd5d38;">**Automated diagnosis of COVID-19 with limited posteroanterior chest X-ray images
using fine-tuned deep neural networks**</span> <br>
*Applied Intelligence 51, 5 (2021), 2689–2702* <br>
<span style="font-size:15px;"><a href="https://link.springer.com/article/10.1007/s10489-020-01900-3" target="blank">:page_facing_up:  Paper</a></span>

<br>

6. Sutong Wang, Yunqiang Yin, Dujuan Wang, Yanzhang Wang, and Yaochu Jin<br>
<span style="font-size:15px; color:#bd5d38;">**Interpretability-Based Multimodal Convolutional
Neural Networks for Skin Lesion Diagnosis**</span> <br>
*IEEE Transactions on Cybernetics (2021)* <br>
<span style="font-size:15px;"><a href="https://pubmed.ncbi.nlm.nih.gov/34546933/" target="blank">:page_facing_up:  Paper</a></span>

<br>

#### Saliency Methods

1. Pranav Rajpurkar, Jeremy Irvin, Robyn L Ball, Kaylie Zhu, Brandon Yang, Hershel Mehta, Tony Duan, Daisy Ding, Aarti Bagul, et al . <br>
<span style="font-size:15px; color:#bd5d38;">**Deep learning for chest radiograph diagnosis: A retrospective comparison of the CheXNeXt algorithm to practicing radiologists**</span> <br>
*PLoS Medicine 15, 11 (2018)* <br>
<span style="font-size:15px;"><a href="https://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.1002686" target="blank">:page_facing_up: Paper</a></span>

<br>

2. Rory Sayres, Ankur Taly, Ehsan Rahimy, Katy Blumer, David Coz, Naama Hammel, Jonathan Krause, Arunachalam Narayanaswamy,
Zahra Rastegar, Derek Wu, et al.<br>
<span style="font-size:15px; color:#bd5d38;">**Using a Deep Learning Algorithm and Integrated Gradients Explanation to Assist Grading for
Diabetic Retinopathy**</span> <br>
*Ophthalmology 126, 4 (2019), 552–564* <br>
<span style="font-size:15px;"><a href="https://www.sciencedirect.com/science/article/pii/S0161642018315756" target="blank">:page_facing_up: Paper</a></span>

<br>

3. Tsung-Chieh Lin and Hsi-Chieh Lee<br>
<span style="font-size:15px; color:#bd5d38;">**Covid-19 Chest Radiography Images Analysis Based on Integration of Image Preprocess, Guided Grad-CAM, Machine Learning and Risk Management**</span> <br>
*International Conference on Medical and Health
Informatics (ICMHI), 281-288, 2020* <br>
<span style="font-size:15px;"><a href="https://dl.acm.org/doi/10.1145/3418094.3418096" target="blank">:page_facing_up: Paper</a></span>

<br>

4. Alina Lopatina, Stefan Ropele, Renat Sibgatulin, Jürgen R Reichenbach, and Daniel Güllmar<br>
<span style="font-size:15px; color:#bd5d38;">**Investigation of Deep-Learning-
Driven Identification of Multiple Sclerosis Patients Based on Susceptibility-Weighted Images Using Relevance Analysis**</span> <br>
*Frontiers in Neuroscience (2020), 1356* <br>
<span style="font-size:15px;"><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7775402" target="blank">:page_facing_up: Paper</a></span>

<br>

5. Isabel Rio-Torto, Kelwin Fernandes, and Luís Teixeira<br>
<span style="font-size:15px; color:#bd5d38;">**Understanding the decisions of CNNs: An in-model approach**</span> <br>
*Pattern
Recognition Letters 133 (2020), 373–380* <br>
<span style="font-size:15px;"><a href="https://www.sciencedirect.com/science/article/pii/S0167865520301240" target="blank">:page_facing_up: Paper</a></span>

<br>

### Explanation by Text

#### Image Captioning

1. Zizhao Zhang, Yuanpu Xie, Fuyong Xing, Mason McGough, and Lin Yang <br>
<span style="font-size:15px; color:#bd5d38;">**MDNet: A Semantically and Visually Interpretable
Medical Image Diagnosis Network**</span> <br>
*IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 6428–6436, 2017* <br>
<span style="font-size:15px;"><a href="https://arxiv.org/abs/1707.02485" target="blank">:page_facing_up: Paper</a></span>

<br>

2. Baoyu Jing, Pengtao Xie, and Eric Xing <br>
<span style="font-size:15px; color:#bd5d38;">**On the Automatic Generation of Medical Imaging Reports**</span> <br>
*56th
Annual Meeting of the Association for Computational Linguistics (ACL), 2018* <br>
<span style="font-size:15px;"><a href="https://arxiv.org/abs/1711.08195" target="blank">:page_facing_up: Paper</a></span>

<br>

3. Xiaosong Wang, Yifan Peng, Le Lu, Zhiyong Lu, and Ronald Summers<br>
<span style="font-size:15px; color:#bd5d38;">**TieNet: Text-Image Embedding Network for Common
Thorax Disease Classification and Reporting in Chest X-rays**</span> <br>
*IEEE Conference on Computer Vision and Pattern
Recognition (CVPR), 9049–9058, 2018* <br>
<span style="font-size:15px;"><a href="https://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_TieNet_Text-Image_Embedding_CVPR_2018_paper.pdf" target="blank">:page_facing_up: Paper</a></span>

<br>

4. Christy Y Li, Xiaodan Liang, Zhiting Hu, and Eric P Xing<br>
<span style="font-size:15px; color:#bd5d38;">**Hybrid Retrieval-Generation Reinforced Agent for Medical Image
Report Generation**</span> <br>
*International Conference on Neural Information Processing Systems (NIPS), 1537–1547, 2018* <br>
<span style="font-size:15px;"><a href="https://proceedings.neurips.cc/paper_files/paper/2018/file/e07413354875be01a996dc560274708e-Paper.pdf" target="blank">:page_facing_up: Paper</a></span>

<br>

5. Li Sun, Weipeng Wang, Jiyun Li, and Jingsheng Lin<br>
<span style="font-size:15px; color:#bd5d38;">**Study on Medical Image Report Generation Based on Improved Encoding-Decoding Method**</span> <br>
*Intelligent Computing Theories and Application, 686–696, 2019* <br>
<span style="font-size:15px;"><a href="https://link.springer.com/chapter/10.1007/978-3-030-26763-6_66" target="blank">:page_facing_up: Paper</a></span>

<br>

6. Catarina Barata, Jorge S Marques, and M Emre Celebi<br>
<span style="font-size:15px; color:#bd5d38;">**Deep Attention Model for the Hierarchical Diagnosis of Skin Lesions**</span> <br>
*IEEE Conference on Computer Vision and Pattern Recognition Workshops (CVPRW), 2757–2765, 2019* <br>
<span style="font-size:15px;"><a href="https://openaccess.thecvf.com/content_CVPRW_2019/papers/ISIC/Barata_Deep_Attention_Model_for_the_Hierarchical_Diagnosis_of_Skin_Lesions_CVPRW_2019_paper.pdf" target="blank">:page_facing_up: Paper</a></span>

<br>

7. Sonit Singh, Sarvnaz Karimi, Kevin Ho-Shon, and Len Hamey<br>
<span style="font-size:15px; color:#bd5d38;">**From Chest X-Rays to Radiology Reports: A Multimodal Machine
Learning Approach**</span> <br>
*Digital Image Computing: Techniques and Applications (DICTA), 1–8, 2019* <br>
<span style="font-size:15px;"><a href="https://ieeexplore.ieee.org/document/8945819" target="blank">:page_facing_up: Paper</a></span>

<br>

8. Hyebin Lee, Seong Tae Kim, and Yong Man Ro<br>
<span style="font-size:15px; color:#bd5d38;">**Generation of Multimodal Justification Using Visual Word Constraint Model
for Explainable Computer-Aided Diagnosis**</span> <br>
*Interpretability of Machine Intelligence in Medical Image Computing and Multimodal
Learning for Clinical Decision Support, 21–29, 2019* <br>
<span style="font-size:15px;"><a href="https://arxiv.org/abs/1906.03922" target="blank">:page_facing_up: Paper</a></span>

<br>

9. William Gale, Luke Oakden-Rayner, Gustavo Carneiro, Andrew P Bradley, and Lyle J Palmer<br>
<span style="font-size:15px; color:#bd5d38;">**Producing Radiologist-Quality
Reports for Interpretable Deep Learning**</span> <br>
*IEEE International Symposium on Biomedical Imaging (ISBI), 1275–1279, 2019* <br>
<span style="font-size:15px;"><a href="https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8759236" target="blank">:page_facing_up: Paper</a></span>

<br>

10. Changchang Yin, Buyue Qian, Jishang Wei, Xiaoyu Li, Xianli Zhang, Yang Li, and Qinghua Zheng<br>
<span style="font-size:15px; color:#bd5d38;">**Automatic Generation of
Medical Imaging Diagnostic Report with Hierarchical Recurrent Neural Network**</span> <br>
*IEEE International Conference on Data Mining (ICDM), 728–737, 2019* <br>
<span style="font-size:15px;"><a href="https://ieeexplore.ieee.org/document/8970668" target="blank">:page_facing_up: Paper</a></span>

<br>

11. Guanxiong Liu, Tzu-Ming Harry Hsu, Matthew McDermott, Willie Boag, Wei-Hung Weng, Peter Szolovits, and Marzyeh Ghassemi <br>
<span style="font-size:15px; color:#bd5d38;">**Clinically Accurate Chest X-Ray Report Generation**</span> <br>
*Machine Learning for Healthcare Conference, 249–269, 2019* <br>
<span style="font-size:15px;"><a href="http://proceedings.mlr.press/v106/liu19a/liu19a.pdf" target="blank">:page_facing_up: Paper</a></span>

<br>

12. Zhihong Chen, Yan Song, Tsung-Hui Chang, and Xiang Wan <br>
<span style="font-size:15px; color:#bd5d38;">**Generating Radiology Reports via Memory-driven Transformer**</span> <br>
*Conference on Empirical Methods in Natural Language Processing (EMNLP), 1439–1449, 2020* <br>
<span style="font-size:15px;"><a href="https://aclanthology.org/2020.emnlp-main.112/" target="blank">:page_facing_up: Paper</a></span>

<br>

13. Fenglin Liu, Xian Wu, Shen Ge, Wei Fan, and Yuexian Zou<br>
<span style="font-size:15px; color:#bd5d38;">**Exploring and Distilling Posterior and Prior Knowledge for Radiology
Report Generation**</span> <br>
*IEEE/CVF Conference on Computer Vision and Pattern Recognition, 13753–13762, 2021* <br>
<span style="font-size:15px;"><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Liu_Exploring_and_Distilling_Posterior_and_Prior_Knowledge_for_Radiology_Report_CVPR_2021_paper.pdf" target="blank">:page_facing_up: Paper</a></span>

<br>

14. Fenglin Liu, Changchang Yin, Xian Wu, Shen Ge, Ping Zhang, and Xu Sun<br>
<span style="font-size:15px; color:#bd5d38;">**Contrastive Attention for Automatic Chest X-ray
Report Generation**</span> <br>
*Findings of the Association for Computational Linguistics: ACL-IJCNLP, 269–280, 2021* <br>
<span style="font-size:15px;"><a href="https://arxiv.org/abs/2106.06965" target="blank">:page_facing_up: Paper</a></span>

<br>

15. Zhanyu Wang, Mingkang Tang, Lei Wang, Xiu Li, and Luping Zhou<br>
<span style="font-size:15px; color:#bd5d38;">**A Medical Semantic-Assisted Transformer for Radiographic
Report Generation**</span> <br>
*Medical Image Computing and Computer Assisted Intervention–MICCAI 2022: 25th International Conference,
Singapore, September 18–22, 2022, Proceedings, Part III. 655–664* <br>
<span style="font-size:15px;"><a href="https://arxiv.org/abs/2208.10358" target="blank">:page_facing_up: Paper</a></span>

<br>

16. Zhanyu Wang, Lingqiao Liu, Lei Wang, and Luping Zhou<br>
<span style="font-size:15px; color:#bd5d38;">**METransformer: Radiology Report Generation by Transformer with
Multiple Learnable Expert Tokens**</span> <br>
*IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR),
11558–11567, 2023* <br>
<span style="font-size:15px;"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_METransformer_Radiology_Report_Generation_by_Transformer_With_Multiple_Learnable_Expert_CVPR_2023_paper.pdf" target="blank">:page_facing_up: Paper</a></span>

<br>

17. Zhanyu Wang, Lingqiao Liu, Lei Wang, and Luping Zhou<br>
<span style="font-size:15px; color:#bd5d38;">**METransformer: Radiology Report Generation by Transformer with
Multiple Learnable Expert Tokens**</span> <br>
*IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR),
11558–11567, 2023* <br>
<span style="font-size:15px;"><a href="https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_METransformer_Radiology_Report_Generation_by_Transformer_With_Multiple_Learnable_Expert_CVPR_2023_paper.pdf" target="blank">:page_facing_up: Paper</a></span>

<br>

18. Alexander Selivanov, Oleg Y Rogov, Daniil Chesakov, Artem Shelmanov, Irina Fedulova, and Dmitry V Dylov<br>
<span style="font-size:15px; color:#bd5d38;">**Medical image
captioning via generative pretrained transformers**</span> <br>
*Scientific Reports 13, 1 (2023), 4171* <br>
<span style="font-size:15px;"><a href="https://www.nature.com/articles/s41598-023-31223-5" target="blank">:page_facing_up: &nbsp; Paper</a></span>

<br>

#### Concept Attribution

1. Mara Graziani, Vincent Andrearczyk, Stéphane Marchand-Maillet, and Henning Müller<br>
<span style="font-size:15px; color:#bd5d38;">**Concept attribution: Explaining CNN
decisions to physicians**</span> <br>
*Computers in Biology and Medicine 123 (2020), 103865* <br>
<span style="font-size:15px;"><a href="https://www.sciencedirect.com/science/article/pii/S0010482520302225" target="blank">:page_facing_up: Paper</a></span>

<br>

2. Adriano Lucieri, Muhammad Naseer Bajwa, Stephan Alexander Braun, Muhammad Imran Malik, Andreas Dengel, and Sheraz Ahmed<br>
<span style="font-size:15px; color:#bd5d38;">**ExAID: A Multimodal Explanation Framework for Computer-Aided Diagnosis of Skin Lesions**</span> <br>
*Computer Methods and Programs in Biomedicine (2022), 106620* <br>
<span style="font-size:15px;"><a href="https://www.sciencedirect.com/science/article/pii/S0169260722000050" target="blank">:page_facing_up: Paper</a></span>

<br>

### Explanation by Examples

#### Case-Based Reasoning

1. Philipp Tschandl, Giuseppe Argenziano, Majid Razmara, and Jordan Yap<br>
<span style="font-size:15px; color:#bd5d38;">**Diagnostic Accuracy of Content Based Dermatoscopic
Image Retrieval with Deep Classification Features**</span> <br>
*British Journal of Dermatology 181, 1 (2019), 155–165* <br>
<span style="font-size:15px;"><a href="https://pubmed.ncbi.nlm.nih.gov/30207594/" target="blank">:page_facing_up: Paper</a></span>

<br>

2. Jean-Baptiste Lamy, Boomadevi Sekar, Gilles Guezennec, Jacques Bouaud, and Brigitte Séroussi<br>
<span style="font-size:15px; color:#bd5d38;">**Explainable artificial intelligence
for breast cancer: A visual case-based reasoning approach**</span> <br>
*Artificial Intelligence in Medicine 94 (2019), 42–53* <br>
<span style="font-size:15px;"><a href="https://www.sciencedirect.com/science/article/pii/S0933365718304846" target="blank">:page_facing_up: Paper</a></span>

<br>

3. Alina Jade Barnett, Fides Regina Schwartz, Chaofan Tao, Chaofan Chen, Yinhao Ren, Joseph Y Lo, and Cynthia Rudin<br>
<span style="font-size:15px; color:#bd5d38;">**Interpretable
Mammographic Image Classification using Case-Based Reasoning and Deep Learning**</span> <br>
*Workshop on Deep Learning, Case-Based
Reasoning, and AutoML: Present and Future Synergies - IJCAI, 2021* <br>
<span style="font-size:15px;"><a href="https://arxiv.org/abs/2107.05605" target="blank">:page_facing_up: Paper</a></span>

<br>

4. Catarina Barata and Carlos Santiago<br>
<span style="font-size:15px; color:#bd5d38;">**Improving the Explainability of Skin Cancer Diagnosis Using CBIR**</span> <br>
*International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI), 550–559, 2021* <br>
<span style="font-size:15px;"><a href="https://link.springer.com/chapter/10.1007/978-3-030-87199-4_52" target="blank">:page_facing_up: Paper</a></span>

<br>

#### Counterfactual Explanations

1. Junho Kim, Minsu Kim, and Yong Man Ro<br>
<span style="font-size:15px; color:#bd5d38;">**Interpretation of Lesional Detection via Counterfactual Generation**</span> <br>
*IEEE International Conference on Image Processing (ICIP), 96–100, 2021* <br>
<span style="font-size:15px;"><a href="https://ieeexplore.ieee.org/document/9506282" target="blank">:page_facing_up: Paper</a></span>

<br>

2. Kathryn Schutte, Olivier Moindrot, Paul Hérent, Jean-Baptiste Schiratti, and Simon Jégou<br>
<span style="font-size:15px; color:#bd5d38;">**Using StyleGAN for Visual Interpretability of Deep Learning Models on Medical Images**</span> <br>
*Medical Imaging Meets NeurIPS Workshop, 2021* <br>
<span style="font-size:15px;"><a href="https://arxiv.org/abs/2101.07563" target="blank">:page_facing_up: Paper</a></span>

<br>

3. Sumedha Singla, Brian Pollack, Stephen Wallace, and Kayhan Batmanghelich<br>
<span style="font-size:15px; color:#bd5d38;">**Explaining the Black-box Smoothly - A Counterfactual Approach**</span> <br>
*Medical Image Analysis 84 (2023), 102721* <br>
<span style="font-size:15px;"><a href="https://arxiv.org/abs/2101.04230" target="blank">:page_facing_up: Paper</a></span>

<br>

#### Prototypes

1. Eunji Kim, Siwon Kim, Minji Seo, and Sungroh Yoon<br>
<span style="font-size:15px; color:#bd5d38;">**XProtoNet: Diagnosis in Chest Radiography with Global and Local
Explanations**</span> <br>
*IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 15719–15728, 2021* <br>
<span style="font-size:15px;"><a href="https://openaccess.thecvf.com/content/CVPR2021/papers/Kim_XProtoNet_Diagnosis_in_Chest_Radiography_With_Global_and_Local_Explanations_CVPR_2021_paper.pdf" target="blank">:page_facing_up: Paper</a></span>

<br>

2. Gurmail Singh and Kin-Choong Yow<br>
<span style="font-size:15px; color:#bd5d38;">**An Interpretable Deep Learning Model For Covid-19 Detection With Chest X-ray Images**</span> <br>
*IEEE Access 9 (2021), 85198–85208* <br>
<span style="font-size:15px;"><a href="https://ieeexplore.ieee.org/document/9448270" target="blank">:page_facing_up: Paper</a></span>

<br>

### Explanation by Concepts

1. Zhengqing Fang, Kun Kuang, Yuxiao Lin, Fei Wu, and Yu-Feng Yao<br>
<span style="font-size:15px; color:#bd5d38;">**Concept-based Explanation for Fine-grained Images and Its
Application in Infectious Keratitis Classification**</span> <br>
*ACM International Conference on Multimedia, 700–708, 2020* <br>
<span style="font-size:15px;"><a href="https://dl.acm.org/doi/10.1145/3394171.3413557" target="blank">:page_facing_up: Paper</a></span>

<br>

2. Mert Yuksekgonul, Maggie Wang, and James Zou<br>
<span style="font-size:15px; color:#bd5d38;">**Post-hoc concept bottleneck models**</span> <br>
*arXiv preprint arXiv:2205.15480 (2022)* <br>
<span style="font-size:15px;"><a href="https://arxiv.org/abs/2205.15480" target="blank">:page_facing_up: Paper</a></span>

<br>

3. Siyuan Yan, Zhen Yu, Xuelin Zhang, Dwarikanath Mahapatra, Shekhar S Chandra, Monika Janda, Peter Soyer, and Zongyuan Ge<br>
<span style="font-size:15px; color:#bd5d38;">**Towards Trustable Skin Cancer Diagnosis via Rewriting Model’s Decision**</span> <br>
*IEEE/CVF Conference on Computer
Vision and Pattern Recognition (CVPR), 11568–11577, 2023* <br>
<span style="font-size:15px;"><a href="https://arxiv.org/abs/2303.00885" target="blank">:page_facing_up: Paper</a></span>

<br>

4. Cristiano Patrício, João C. Neves, and Luis F. Teixeira<br>
<span style="font-size:15px; color:#bd5d38;">**Coherent Concept-based Explanations in Medical Image and Its Application
to Skin Lesion Diagnosis**</span> <br>
*IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW),
3799–3808, 2023* <br>
<span style="font-size:15px;"><a href="https://openaccess.thecvf.com/content/CVPR2023W/SAIAD/papers/Patricio_Coherent_Concept-Based_Explanations_in_Medical_Image_and_Its_Application_to_CVPRW_2023_paper.pdf" target="blank">:page_facing_up: Paper</a></span>

<br>

### Other Approaches

#### Bayesian Approaches

1. Ponkrshnan Thiagarajan, Pushkar Khairnar, and Susanta Ghosh<br>
<span style="font-size:15px; color:#bd5d38;">**Explanation and Use of Uncertainty Obtained by Bayesian
Neural Network Classifiers for Breast Histopathology Images**</span> <br>
*IEEE Transactions on Medical Imaging 41, 4 (2021), 815–825* <br>
<span style="font-size:15px;"><a href="https://ieeexplore.ieee.org/document/9585450" target="blank">:page_facing_up: Paper</a></span>

<br>

2. Mohammad Ehtasham Billah and Farrukh Javed <br>
<span style="font-size:15px; color:#bd5d38;">**Bayesian Convolutional Neural Network-based Models for Diagnosis of Blood
Cancer**</span> <br>
*Applied Artificial Intelligence (2022), 1–22* <br>
<span style="font-size:15px;"><a href="https://www.tandfonline.com/doi/full/10.1080/08839514.2021.2011688" target="blank">:page_facing_up: Paper</a></span>

<br>

3. Mahesh Gour and Sweta Jain<br>
<span style="font-size:15px; color:#bd5d38;">**Uncertainty-aware convolutional neural network for COVID-19 X-ray images classification**</span> <br>
*Computers in Biology and Medicine 140 (2022), 105047* <br>
<span style="font-size:15px;"><a href="https://www.sciencedirect.com/science/article/pii/S0010482521008416" target="blank">:page_facing_up: &nbsp; Paper</a></span>

<br>

#### Adversarial Training

1. Andrei Margeloiu, Nikola Simidjievski, Mateja Jamnik, and Adrian Weller<br>
<span style="font-size:15px; color:#bd5d38;">**Improving Interpretability in Medical Imaging
Diagnosis using Adversarial Training**</span> <br>
*Medical Imaging Meets NeurIPS Workshop, 2020* <br>
<span style="font-size:15px;"><a href="https://arxiv.org/abs/2012.01166" target="blank">:page_facing_up: &nbsp; Paper</a></span>

<br>




