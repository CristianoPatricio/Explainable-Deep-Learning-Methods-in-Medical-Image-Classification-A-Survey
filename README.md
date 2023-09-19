# Explainable Deep Learning Methods in Medical Image Classification: A Survey

## Table of Contents:
- [Survey Papers](#survey-papers)
- [XAI Methods in Medical Diagnosis](#xai-methods-in-medical-diagnosis)
  - [Explanation by Feature Attribution](#explanation-by-feature-attribution)
    - [Perturbation-based methods](#perturbation-based-methods)
    - [Saliency Methods](#saliency-methods)
  - Explanation by Text
    - Image Captioning
    - Concept Attribution
  - Explanation by Examples
    - Case-Based Reasoning
    - Counterfactual Explanations
    - Prototypes
  - Explanation by Concepts
  - Other Approaches
    - Bayesian Approaches
    - Adversarial Training

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

1. Rory Sayres, Ankur Taly, Ehsan Rahimy, Katy Blumer, David Coz, Naama Hammel, Jonathan Krause, Arunachalam Narayanaswamy,
Zahra Rastegar, Derek Wu, et al.<br>
<span style="font-size:15px; color:#bd5d38;">**Using a Deep Learning Algorithm and Integrated Gradients Explanation to Assist Grading for
Diabetic Retinopathy**</span> <br>
*Ophthalmology 126, 4 (2019), 552–564* <br>
<span style="font-size:15px;"><a href="https://www.sciencedirect.com/science/article/pii/S0161642018315756" target="blank">:page_facing_up: Paper</a></span>

<br>

1. Tsung-Chieh Lin and Hsi-Chieh Lee<br>
<span style="font-size:15px; color:#bd5d38;">**Covid-19 Chest Radiography Images Analysis Based on Integration of Image Preprocess, Guided Grad-CAM, Machine Learning and Risk Management**</span> <br>
*International Conference on Medical and Health
Informatics (ICMHI), 281-288, 2020* <br>
<span style="font-size:15px;"><a href="https://dl.acm.org/doi/10.1145/3418094.3418096" target="blank">:page_facing_up: Paper</a></span>

<br>

1. Alina Lopatina, Stefan Ropele, Renat Sibgatulin, Jürgen R Reichenbach, and Daniel Güllmar<br>
<span style="font-size:15px; color:#bd5d38;">**Investigation of Deep-Learning-
Driven Identification of Multiple Sclerosis Patients Based on Susceptibility-Weighted Images Using Relevance Analysis**</span> <br>
*Frontiers in Neuroscience (2020), 1356* <br>
<span style="font-size:15px;"><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7775402" target="blank">:page_facing_up: Paper</a></span>

<br>

1. Isabel Rio-Torto, Kelwin Fernandes, and Luís Teixeira<br>
<span style="font-size:15px; color:#bd5d38;">**Understanding the decisions of CNNs: An in-model approach**</span> <br>
*Pattern
Recognition Letters 133 (2020), 373–380* <br>
<span style="font-size:15px;"><a href="https://www.sciencedirect.com/science/article/pii/S0167865520301240" target="blank">:page_facing_up: Paper</a></span>

<br>
