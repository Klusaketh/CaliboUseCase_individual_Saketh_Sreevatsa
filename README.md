# Calibo Use Case - Retail Category Intelligence EDA

This project analyses six months of retail transaction data to understand category performance, product contribution, discount effectiveness, and sales patterns.

The analysis was prepared to help a Category Manager make data-based decisions before a supplier review meeting.

## Project Objectives

* Inspect and validate the retail dataset
* Analyse monthly revenue for each product category
* Identify growing, declining, and consistent categories
* Find the top two and bottom two products in each category
* Evaluate whether higher discounts improve sales
* Identify the best and worst sales days and months
* Provide a final recommendation to the Category Manager

## Dataset

The dataset contains:

* 107,836 retail transactions
* 12 stores across Andhra Pradesh
* 5 product categories
* 25 products
* Sales data from January to June 2026

## Key Findings

* Electronics recorded the largest revenue decline of approximately 35%.
* Apparel showed the strongest growth of approximately 34.1%.
* Grocery was the most consistent category.
* Smart TV and Tablet were the bottom-performing products within Electronics.
* Average revenue per transaction fell from approximately ₹4,686 at 0% discount to ₹3,632 at 20% discount.
* Average units sold remained close to 2.6 across discount levels.
* Saturday had the highest average daily revenue, while Monday had the lowest.
* January was the strongest month, and June was the weakest.

## Recommendation

Apparel has the strongest case for additional investment because of its positive revenue growth.

Electronics requires closer review because of its declining revenue. The performance of Smart TV and Tablet should be discussed with the supplier before approving additional shelf space or promotional support.

Higher discounts should also be used carefully because they did not produce a meaningful increase in the number of units sold.

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

## Project Files

* `Saketh_MUC01_KLU_Notebook.ipynb` — complete analysis, charts, findings, and Category Manager briefing
* `Saketh_MUC01_KLU_Summary.docx` — one-page insight summary
* `MUC01_Retail_Sales_Dataset.csv` — retail transaction dataset

## How to Run

1. Download or clone this repository.
2. Keep the dataset and notebook in the same folder.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Start Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `Saketh_MUC01_KLU_Notebook.ipynb`.
6. Select **Kernel → Restart & Run All**.

## Author

**Saketh**
B.Tech Computer Science and Engineering
KL University
