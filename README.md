# BrainDead 🧠

<img src="https://github.com/Revelation-24/BrainDead2k24/assets/165821528/c6327ea6-5cd9-4185-a8ce-4246e80743a3" style="width: 100%; height: auto;">


## Data Analysis and Machine Learning Competition

Exciting news! 🎉 Revelation 2K24 is back, proudly presented by the Department of Computer Science and Technology, IIEST Shibpur. This year, we're thrilled to announce our collaboration with multiple leading product-based companies who are eager to recruit top talent from our main technical events. Don't miss out on this unparalleled chance to shine and secure your future in the tech world! See you at Revelation 24! 🚀 #Revelation24 #TechFest #IIESTS #CareerOpportunities

---

Get ready for the ultimate challenge in data analysis and machine learning at Revelation '24 with BrainDead! 🚀

We're excited to present two compelling problem statements for this flagship competition, both of which are compulsory. Whether you can solve one or both, or even just a part of the problems, we encourage you to make a submission and showcase your skills! We believe in your potential to tackle these challenges head-on and demonstrate your expertise in data analysis and machine learning. On behalf of Team Revelation, we wish you all the best! 💻🔍 #BrainDead #Revelation24 #DataAnalysis #MachineLearning

---

**Contact Us**
- 📧 Email: [braindead2k24@gmail.com](mailto:braindead2k24@gmail.com)
- 📲 Join WhatsApp Group: [Link](#)

**Submission Requirements**
- For Problem Statement 1 and Problem Statement 2, prepare a concise report in .pptx or .pdf format and append it with the report you prepared in Problem Statement 1.
- Upload your .iPython notebook to Github and share the link of your repository via UnStop. Ensure that the repository is public.

**Remember:**
- Both the problem statements are **compulsory**.
- You can submit whichever question you can solve. However, your score for the unsolved problem will be 0.
- If you submit the report for a problem statement but not the .iPython notebook, your score for that problem will be 0 (Aryabhatta to be blamed).

**Long story short, create a single concise report covering both the problem statements (if you have solved both), and upload the code for Problems 1 and 2 to Github.**

---

## Problem Statement 1: Analyze Rice Production Data In India and Predict Rice Production in Indian States/Union Territories


<div align="right"> <b> Marks = 40 </b></div>


***Problem Statement:***

In this challenge, participants are tasked with predicting the production of rice on a state-wise or union territory-wise basis. The dataset provided spans from the agricultural sessions of 2004-2005 to 2022-2023, detailing the quantity of rice produced annually.

***Analysis Goals:***

Analyze the dataset and derive meaningful insights from the data. Here are some examples that you might consider for your analysis:
- How does production vary from state to state (through bar charts, pie charts, etc.)?
- What is the state-wise rate of production?
- For which provinces there is a need to improve their production of rice.
- You can use other instances, such as state-wise and year-wise rainfall in India. (Data link must be provided if including any instance)
- Present your analysis in a report. You can use charts, tables, and graphs to elaborate your analysis.
- **In the end, any prediction model should be used to predict the state-wise/union territory-wise production of rice for the next 5 years.**

***Tools for Analysis:***
Participants may use the following tools for analysis:
- MS Excel
- Tableau/PowerBI
- Jupyter Notebook/Google Colab with Matplotlib

***Dataset Link:*** [BrainDead Rice Production Data in India](https://www.kaggle.com/datasets/braindead2k24/brain-dead-rice-production-data-in-india)

***Dataset Description:***

The dataset is divided into three tables, from which Table 1 contains 34 rows and 10 columns, Table 2 contains 34 rows and 11 columns and Table 3 contains the source of the data (actually for data analysis and prediction there is no need of Table 3).

- The first row of both Table 1 and Table 2 contains the title of the dataset. 
- From the second row, the dataset’s first column contains the name of the State/Union Territory, and the other columns contain the year-wise production of rice. 
- The last row contains the year-wise all-over rice production in India.



***Deliverables:***

- A complete report of the analysis of the dataset and methodology employed in your work. The report should be concise. This report might include references, tables, figures, and results. **The methodology used for prediction must be clear**. If you are using tools like Excel, also mention the Excel formulas that you used for the analysis.
- Also submit the **source code** for the production of rice for the **next 5 years**.

***Marking Criteria:***

Participants will be evaluated based on the following criteria:
- ***Writing style, references, and presentation of findings.***
- ***Dataset exploration.***
- ***Methodologies employed for analysis and prediction.***
- ***Source Code***
- ***Results and discussion.***

---

## Problem Statement 2: Detecting Multimodal Hate Speech in Internet Memes


<div align="right"> <b> Marks = 60 </b></div>

***Problem Statement:***

This competition aims to develop a **novel multimodal machine learning model** for classifying harmful internet memes that surpasses existing benchmark models while requiring less computation power. Internet memes, combining images and text, are pervasive online, but some carry harmful messages, necessitating effective detection methods. The challenge lies in creating a model that efficiently leverages **both image and text data** to identify **harmful content accurately**. Participants will be provided with a **dataset** containing labeled memes and tasked with training a model capable of achieving superior **performance compared to existing benchmarks while optimizing computational efficiency.**

***Dataset Link:*** [BrainDead Multimodal Data for Hateful Meme](https://www.kaggle.com/datasets/braindead2k24/brain-dead-multimodal-data-for-hateful-meme)

***Dataset Description:***

The dataset provided for this competition comprises **10,000 data points**, each representing an internet meme and containing both image and text data. The image data is stored in a folder named "**img**," housing a diverse collection of meme images. Meanwhile, the text data is organized within a **CSV** file, where each row corresponds to a meme and includes the meme's ID, associated text, and class label denoting **harmful (1)** or **non-harmful (0)**. To facilitate multimodal analysis, participants will integrate both image and text data during model development, associating each meme's text with its corresponding image using the provided meme ID. This dataset serves as a foundation for training and evaluating advanced multimodal **machine learning models aimed at accurately classifying harmful memes** while optimizing computational efficiency.


***Deliverables:***

- A **novel multimodal machine learning model designed** for classifying **multimodal harmful internet memes that can handle images and text together.**
- Trained model(s) demonstrating superior performance compared to existing **benchmark models. (a few best classification benchmarks are given below).**
  | Rank | Model                | ROC AUC |
  |------|----------------------|---------|
  | 1    | Pali-X-VPD           | 0.892   |
  | 2    | RGCL - HateCLIPper   | 0.867   |
  | 3    | HateCLIPper - Align  | 0.858   |
  | 4    | ISSUES               | 0.855   |
  | 5    | Vilio                | 0.825   |
  | 6    | HateDetectron27      | 0.811   |
  | 7    | SEER                 | 0.734   |
  | 8    | Flamingo             | 0.700   |
  | 9    | CLIP                 | 0.661   |

- Documentation outlining the architecture, training methodology, and key insights behind the developed model(s).
- Predictions for a **separate test set of memes**, showcasing the model's effectiveness in real-world scenarios.
- Analysis of the model's performance metrics, including accuracy, precision, recall, F1 score, area under the ROC curve (AUC), and confusion matrix analysis.
- Insights into optimization strategies aimed at **reducing computational overhead** while maintaining model efficacy.
- Division of the dataset into training (80%) and test (20%) sets, ensuring proper evaluation and validation of the model's performance.
- **Comparative results** of the proposed model with **similar datasets A and B**, including performance metrics and insights gained from the comparison. This will show that your proposed model is not dependent on the dataset
  
**Data Set A Link:** [brain_dead_harmful_data_for_covid19](https://www.kaggle.com/datasets/braindead2k24/brain-dead-harmful-data-for-covid19)

**Data Set B Link:** [brain_dead_harmful_data_for_politics](https://www.kaggle.com/datasets/braindead2k24/brain-dead-harmful-data-for-politics)

---

***Environment for Coding:***
Everyone should use the mentioned environments for coding. Google Colab Or Your System, Jupyter Notebook, TensorFlow, Keras, Python, PyTorch, etc. Your notebook name should be in this (team_name_brain_dead_2k24.ipynb) format.

***Submission Guideline:***
- Submission via UnStop.
- If there is an issue, You can Contact Us at [braindead2k24@gmail.com](mailto:braindead2k24@gmail.com).
- Join WhatsApp Group: [Link](#)
- A complete report of the methodology employed in your work and the source code of your best pipelines for each selected dataset. The report should be concise. This report might include references, tables, figures, and results. Everyone should submit their code between 04/04/2024 at 10 AM to 06/04/2024 at 10 AM.

***Marking Criteria:***
Upload your code to Github. Create an account if you don’t have one. Make sure your repository is public. Your report should have most of these: Writing Style, references, figures, etc. Dataset exploration Methodology Results of analysis Comparative study Pipeline architecture you used Conclusion

**N.B. - Plagiarism Must be Checked During Evaluation:**
All submissions will be subject to thorough plagiarism checks during the evaluation process to ensure originality and integrity.

---

**Dataset Credits:**
- **Problem Statement 1:** Ministry of Agriculture and Farmers’ Welfare, Government of India.
- **Problem Statement 2:** Kiela, Douwe, Hamed Firooz, Aravind Mohan, Vedanuj Goswami, Amanpreet Singh, Pratik Ringshia, and Davide Testuggine. "The hateful memes challenge: Detecting hate speech in multimodal memes." Advances in neural information processing systems 33 (2020): 2611-2624. Pramanick, Shraman, Dimitar Dimitrov, Rituparna Mukherjee, Shivam Sharma, Md Shad Akhtar, Preslav Nakov, and Tanmoy Chakraborty. "Detecting harmful memes and their targets." arXiv preprint arXiv:2110.00413 (2021).

**Submission Format:**
- Table of Contents
- Introduction
- Dataset Prepossing
- Model Architecture and Training Methodology
- Performance Evaluation
- Results and Discussion
- Summary of model performance on the test set
- Optimization Strategies
- Conclusion
- References


















<!--# [BrainDead](https://unstop.com/hackathons/braindead-revelation-24-indian-institute-of-engineering-science-and-technology-iiest-shibpur-938823) 🧠
<h1>Data Analysis and Machine Learning Competition:</h1>
<h3>Exciting news! 🎉 Revelation 2K24 is back, proudly presented by the Department of Computer Science and Technology, IIEST Shibpur. This year, we're thrilled to announce our collaboration with multiple leading product-based companies who are eager to recruit top talent from our main technical events.
Don't miss out on this unparalleled chance to shine and secure your future in the tech world! See you at Revelation 24!
 🚀 #Revelation24 #TechFest #IIESTS #CareerOpportunities



Get ready for the ultimate challenge in data analysis and machine learning at Revelation '24 with BrainDead! 🚀

We're excited to present two compelling problem statements for this flagship competition, both of which are compulsory. Whether you can solve one or both, or even just a part of the problems, we encourage you to make a submission and showcase your skills!
We believe in your potential to tackle these challenges head-on and demonstrate your expertise in data analysis and machine learning. On behalf of Team Revelation, we wish you all the best! 💻🔍 #BrainDead #Revelation24 #DataAnalysis #MachineLearning



</h3>



<h2>

**Contact Us**:

📧 Email: [braindead2k24@gmail.com](mailto:braindead2k24@gmail.com)  
📲 Join WhatsApp Group: [Link](#)


<!-- For Problem Statement 1 and  Problem Statement 2, prepare a concise report in .pptx or .pdf format and append it with the report you prepared in Problem Statement 1. 

Upload your .iPython notebook to Github and share the link with your repository via UnStop. 

Ensure that the repository is public.

Long story short, create a single concise report covering both the problem statements (if you have solved both), and upload the code for Problems 1 and 2 to Github.

Remember:

Both problem statements are compulsory.

You can submit whichever question you can solve. However, your score for the unsolved problem will be 0.

If you submit the report for Problem Statement 1 but not the .iPython notebook for Problem Statement 1 (or vice versa), your score for that problem will be 0. 

**Submission Guidelines:**

- Prepare a concise report in .pptx or .pdf format covering both problem statements
- Upload your .iPython notebook to GitHub and share the link with your repository via UnStop, ensure that the repository is public.
- You need to submit both the .iPython notebook and the report for each of the problem, missing any of these will lead to no marks for the particular problem statement.
- We encourage you to submit whichever question you can solve. However, your score for the unsolved problem will be 0.

  
Long story short, create a single concise report covering both the problem statements (if you have solved both), and upload the code for Problems 1 and 2 to Github

</h2>

<hr>

# Problem Statement 1: Analyze Rice Production Data In India and Predict Rice Production in Indian States/Union Territories. (Marks- 40)

<h3> Challenge Description:
In this challenge, participants are tasked with predicting the production of rice on a state-wise or union territory-wise basis. 

The dataset provided spans from the agricultural sessions of 2004-2005 to 2022-2023, detailing the quantity of rice produced annually.

Analysis Goals:
Analyze the dataset and derive meaningful insights from the data.

Here are some examples that you might consider for your analysis:

- How does production vary from state to state (through bar charts, pie charts, etc.)?
- What is the state-wise rate of production?
- For which provinces there is need to improve their production of rice.
- You can use other instances, such as state-wise and year-wise rainfall in India. (Data link must be provided if including any instance)
- Present your analysis in a report. You can use charts, tables, and graphs to elaborate your analysis.
- In the end, any prediction model should be used to predict the state-wise/union territory-wise production of rice for the next 5 years.

Tools for Analysis:

Participants may use the following tools for analysis:
- MS Excel
- Tableau/PowerBI
- Jupyter Notebook/Google Colab with Matplotlib

Dataset Link:  ([brain-dead-rice-production-data-in-india](http://www.kaggle.com/datasets/braindead2k24/brain-dead-rice-production-data-in-india))
<!--https://www.kaggle.com/datasets/braindead2k24/brain-dead-rice-production-data-in-india 

Dataset Description:
The dataset is divided into three tables, from which Table 1 contains 34 rows and 10 columns, 

Table 2 contains 34 rows and 11 columns and 

Table 3 contains the source of the data (actually for data analysis and prediction there is no need of Table 3).

- The first row of both Table 1 and Table 2 contains the title of the dataset.
- From the second row, the dataset’s first column contains the name of the State/Union Territory, and the other columns contain the year-wise production of rice. 
- The last row contains the year-wise all-over rice production in India.

Deliverables:
A complete report of the analysis of the dataset and methodology employed in your work. The report should be concise. This report might include references, tables, figures, and results. The methodology used for prediction must be clear. The file format should be either a ppt or a pdf. If you are using tools like Excel, also mention the Excel formulas that you used for the analysis.
Will also submit the source code for the production of rice for the next 5 years. 

Marking Criteria:
Participants will be evaluated based on the following criteria:
- Writing style, references, and presentation of findings.
- Dataset exploration.
- Methodologies employed for analysis and prediction.
- Source Code
- Results and discussion.

</h3>


# Problem Statement 2: Detecting Multimodal Hate Speech in Internet Memes. (Marks 60)

<h3>
 Problem Statement:
 
This competition aims to develop a novel multimodal machine learning model for classifying harmful internet memes that surpasses existing benchmark models while requiring less computation power. Internet memes, combining images and text, are pervasive online, but some carry harmful messages, necessitating effective detection methods. The challenge lies in creating a model that efficiently leverages both image and text data to identify harmful content accurately. Participants will be provided with a dataset containing labeled memes and tasked with training a model capable of achieving superior performance compared to existing benchmarks while optimizing computational efficiency.

Dataset Link: ([brain_dead_multimodal_data_for_hateful_meme](https://www.kaggle.com/datasets/braindead2k24/brain-dead-multimodal-data-for-hateful-meme))
<!---https://www.kaggle.com/datasets/braindead2k24/brain-dead-multimodal-data-for-hateful-meme 

Dataset Description:

The dataset provided for this competition comprises 10,000 data points, each representing an internet meme and containing both image and text data. The image data is stored in a folder named "img," housing a diverse collection of meme images. Meanwhile, the text data is organized within a CSV file, where each row corresponds to a meme and includes the meme's ID, associated text, and class label denoting harmful (1) or non-harmful (0). To facilitate multimodal analysis, participants will integrate both image and text data during model development, associating each meme's text with its corresponding image using the provided meme ID. This dataset serves as a foundation for training and evaluating advanced multimodal machine learning models aimed at accurately classifying harmful memes while optimizing computational efficiency.

Deliverables:

- A novel multimodal machine learning model is designed for classifying multimodal harmful internet memes that can handle images and text together.
- Trained model(s) demonstrating superior performance compared to existing benchmark models (a few best classification benchmarks are given below).
  
  | Rank | Model | ROC AUC |
  | ---- | ----- | ------- |
  | 1    | Pali-X-VPD | 0.892 |
  | 2    | RGCL - HateCLIPper | 0.867 |
  | 3    | HateCLIPper - Align | 0.858 |
  | 4    | ISSUES | 0.855 |
  | 5    | Vilio | 0.825 |
  | 6    | HateDetectron27 | 0.811 |
  | 7    | SEER | 0.734 |
  | 8    | Flamingo | 0.700 |
  | 9    | CLIP | 0.661 |

- Documentation outlining the architecture, training methodology, and key insights behind the developed model(s).
- Predictions for a separate test set of memes, showcasing the model's effectiveness in real-world scenarios.
- Analysis of the model's performance metrics, including accuracy, precision, recall, F1 score, area under the ROC curve (AUC), and confusion matrix analysis.
- Insights into optimization strategies aimed at reducing computational overhead while maintaining model efficacy.
- Division of the dataset into training (80%) and test (20%) sets, ensuring proper evaluation and validation of the model's performance.
- Comparative results of the proposed model with similar datasets A and B, including performance metrics and insights gained from the comparison. This will show that your proposed model is not dependent on the dataset.
- Data Set A Link: [brain_dead_harmful_data_for_covid19](https://www.kaggle.com/datasets/braindead2k24/brain-dead-harmful-data-for-covid19)
https://www.kaggle.com/datasets/braindead2k24/brain-dead-harmful-data-for-covid19
- Data Set B Link: [brain_dead_harmful_data_for_politics](https://www.kaggle.com/datasets/braindead2k24/brain-dead-harmful-data-for-politics)
https://www.kaggle.com/datasets/braindead2k24/brain-dead-harmful-data-for-politics

Environment for coding:

Everyone should use the mentioned environments for coding. Google Colab Or Your System, Jupyter Notebook, TensorFlow, Keras, Python, PyTorch, etc. Your notebook name should be in this (team_name_brain_dead_2k24.ipynb) format.


Submission Guideline:
- Submit your files and GitHub link via UnStop.
- If there is an issue, You can contact us at braindead2k24@gmail.com.
Join WhatsApp Group: Link

A complete report of the methodology employed in your work and the source code of your best pipelines for each selected dataset. The report should be concise. This report might include references, tables, figures, and results.

Everyone should submit their code between 04/04/2024 at 10 AM to 06/04/2024 at 10 AM.

Marking criteria:
- Upload your code to Github. Create an account if you don’t have one. Make sure your repository is public. Your report should have most of these:
- Writing Style, references, figures, etc.
- Dataset exploration
- Methodology
- Results of analysis
- Comparative study
- Pipeline architecture you used
Conclusion
N.B. - Plagiarism Must be Checked During Evaluation:

All submissions will be subject to thorough plagiarism checks during the evaluation process to ensure originality and integrity 


Dataset credits
* Problem Statement 1: 
Ministry of Agriculture and Farmers’ Welfare, Government of India.
** Problem Statement 2:
 Kiela, Douwe, Hamed Firooz, Aravind Mohan, Vedanuj Goswami, Amanpreet Singh, Pratik Ringshia, and Davide Testuggine. "The hateful memes challenge: Detecting hate speech in multimodal memes." Advances in neural information processing systems 33 (2020): 2611-2624.
Pramanick, Shraman, Dimitar Dimitrov, Rituparna Mukherjee, Shivam Sharma, Md Shad Akhtar, Preslav Nakov, and Tanmoy Chakraborty. "Detecting harmful memes and their targets." arXiv preprint arXiv:2110.00413 (2021).


Submission Format:

1. Table of Contents:
2. Introduction:
3. Dataset Prepossing:
4. Model Architecture and Training Methodology:
5. Performance Evaluation:
6. Results and Discussion:
7. Summary of model performance on the test set.
8. Optimization Strategies:
9. Conclusion:
10. References:

</h3> -->



