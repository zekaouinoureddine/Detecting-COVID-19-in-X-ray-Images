# Detecting COVID-19 in X-ray Images
Detecting COVID-19 in X-ray images with Keras, TensorFlow, and Deep Learning. To understand how we did it, do not hesitate to consult the [Jupyter Notebook file](https://github.com/zekaouinoureddine/Detecting-COVID-19-in-X-ray-Images/blob/main/Detecting%20COVID-19%20in%20X-ray%20images.ipynb)
## Table of contents
- [Business Problem](#business-problem)
- [Data Section](#data-section)
- [Technologies](#technologies)
- [Results Section](#results-section)
- [Discussion Section](#discussion-section)
- [Conclusion](#conclusion)
- [References](#References)
- [Author infos](#author-infos)

---
### Business Problem
**About COVID-19**

The novel coronavirus 2019 (COVID-2019), which first appeared in Wuhan city of China in December 2019, spread rapidly around the world and became a pandemic. It has caused a devastating effect on both daily lives, public health, and the global economy. It is critical to detect the positive cases as early as possible so as to prevent the further spread of this epidemic and to quickly treat affected patients. The need for auxiliary diagnostic tools has increased as there are no accurate automated toolkits available.

**Detecting COVID-19 in X-ray**

Coming down to business problem, our project aims to create a solution that can prevent COVID-19 in an automated way. This operation will be based on X-ray DataSet. However, the challenge is to find an efficient solution for detecting COVID-19 with a high sort of certainty using deep learning which is the start-of-art of recent technologies, especially in AI.

**Interested Audience**

I have only one tip before we get dive into our amazing project, please do not use this model to detect the novel coronavirus 2019, because the efficient ways are already fixed by the [WHO](https://www.who.int/). But students and working professionals in data science are common audience here. So, we may need to fascinate and inspire them all.

---
### Data Section
**What data is used?**

Recent findings obtained using radiology imaging techniques suggest that such images contain salient information about the COVID-19 virus. Application of advanced artificial intelligence (AI) techniques coupled with radiological imaging can be helpful for the accurate detection of this disease and can also be assistive to overcome the problem of a lack of specialized physicians in remote villages.

**How will we be solving using this data?**

As you may know, before creating a DL model that can do a specific task, we need to train it first using some similar data. Therefore, our model will be exposed to new data that have never seen before, then it will be able to do its job more efficiently than humans, if it've trained well.

---
### Technologies
- Python (TensorFlow, Keras, Skit-Learn, Pandas, Numpy…etc)
- Jupyter NoteBook in Colab
---
### Results Section
- **Summary of Accuracies and Losses :**

<table>
  <thead>
    <tr><th></th><th> Training </th><th> Validation </th> <th> Test </th></tr></thead>
  <tr>
    <td>Accuracy</td>
    <td>98.37%</td>
    <td>98.41%</td>
    <td>98.39%</td>
  </tr>
  <tr>
    <td>Loss</td>
    <td>5.09%</td>
    <td>2.97%</td>
    <td>10.68</td>
  </tr>
</table>

- **Training Vs. Validation Accuracy/Loss :**

 ![](acc.png)

- **Confusion Matrix :**
Note that :
    - **0** represents **Covid-19**: Person contaminated by the virus
    - **1** represents **No-findings**: Person not contaminated by the virus

 ![](mat.png)

- **Prediction :**

 ![](pred.png)

---

### Discussion Section
As a data scientist, the results obtained are impressive, and our model is ready to be deployed and go into production. Just one thing, concerning the errors which occurred (see the confusion matrix), of which a little expertise in medicine is required to be able to understand the provenance of these errors and to extirpate them to make our model perfect as much as we can at the level of its predictions

Despite the findings, there was some lack in data. However, we do not have enough data to train our model, especially in the COVID-19 folder.

---
### Conclusion
This project can be considered quite successful. Please if you are stuck or have any questions, suggestions or room for improvement, do not hesitate to [contact me](https://www.linkedin.com/in/nour-eddine-zekaoui-ba43b1177/) I will be available.

---
### References
- [Automated detection of COVID-19 cases using deep neural networks with X-ray images](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7187882/)
- [Detecting COVID-19 in X-ray images with Keras, TensorFlow, and Deep Learning](https://www.pyimagesearch.com/2020/03/16/detecting-covid-19-in-x-ray-images-with-keras-tensorflow-and-deep-learning/)
- [Plants Identification](https://github.com/zekaouinoureddine/Plants_Identification_DL_SI)

---
### Author infos
- LinkedIn: [Nour Eddine ZEKAOUI](https://www.linkedin.com/in/nour-eddine-zekaoui-ba43b1177/)
---
 Go to [Jupyter Notebook file](https://github.com/zekaouinoureddine/Detecting-COVID-19-in-X-ray-Images/blob/main/Detecting%20COVID-19%20in%20X-ray%20images.ipynb)
 
[Back To The Top](#detecting-covid-19-in-x-ray-images)
