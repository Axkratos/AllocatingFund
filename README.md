# Clustering Countries for Aid Allocation

 **About Dataset**  
Clustering the Countries by Using Unsupervised Learning for HELP International

 **This notebook includes the following:**  
- Preprocessing  
- Data cleaning  
- Exploratory data analysis (EDA)  
- Principal component analysis (PCA)  
- Clustering analysis  

 **Objective**  
The goal of this project is to cluster countries based on various numerical features such as economic indicators, health factors, and social parameters. This is an unsupervised learning problem because we do not have any predefined categories or labels for the countries. We use machine learning techniques to create clusters of similar countries based on their features. The resulting clusters will help in the allocation of funds for assistance during natural disasters and calamities, as countries with similar characteristics are likely to face similar challenges during such events.

---

## Result of Clustering  
After fitting the K‑Means model, each country was assigned to one of three clusters. We then mapped these labels to world map:

```python
fund_cat = {
    2: "Funding Needed",
    0: "May or May Not need Funds",
    1: "Funding Not Needed"
}

