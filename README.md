# masterthesis
As part of the master thesis "Hallucinations in Retrieval-Augmented Language Models", an NLI-based evaluation framework was developed, which analyses the influence factors of benchmark and model selection as well as hyperparameters in order to subsequently propose a final model for the evaluation of RAG models. 

. The framework was technically realised in the Python programming language and im-plemented in Google Colab using the Colab Pro+ subscription in order to meet the re-quirements of the deep learning algorithms. In this case, 62.8 GB of system RAM is available for calculating the models. If the ML algorithm in question offers a correspond-ing API, the training was carried out on an NVIDIA L4 GPU with 22.5 GB GPU RAM us-ing CUDA 12.2. The follorwing illustration visualises the methodological framework of this thesis. 

<img width="425" alt="image" src="https://github.com/maren-212/masterthesis/assets/104628466/dd6b8e2d-0267-48d4-b0bf-3f0a1dada898">


A total of 38 transformer models were trained, which differ in terms of the following parameters: 
			
![image](https://github.com/maren-212/masterthesis/assets/104628466/c5c3d8bd-5a31-4acc-a0fe-ad33cfcb027d)



The corresponding notebook for fine tuning is: Data_and_fine_tuning.ipynb

A statistical analysis was then carried out to analyse the influence of the selected parameters on the accuracy. The corresponding notebook is: Result Analysis.ipynb


