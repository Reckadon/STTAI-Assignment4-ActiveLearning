# Assignment 4 - Active Learning and Cost Effective-Labelling  

## Introduction
Active learning is a machine learning approach that aims to improve model performance by iteratively selecting the most informative data points for labeling. In this assignment, we compare three active learning methods—**Random Sampling**, **Uncertainty Sampling**, and **Query-by-Committee**—based on their **final accuracy** and **delta** values. The goal is to determine which method is the most cost-effective for achieving high accuracy.

> ## Open the jupyter notebook `STTAI_Assignment_4.ipynb` for the code and analysis.

### **Conclusion**
- **Query-by-Committee** is the best choice when **maximizing accuracy and improvement** is the primary goal, even if it requires more resources.
- **Random Sampling** is the most **cost-effective** method overall, offering a good balance between **final accuracy** and **improvement**, making it suitable for a wide range of applications.
- **Uncertainty Sampling** is the least effective method in this comparison, as it provides the smallest improvement and lowest final accuracy in return of additional complexity.