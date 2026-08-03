# ConnectaTel Analysis - Sprint 7

This project looks at how ConnectaTel customers in Mexico and Colombia use their phone services.

By looking at data from plans, users, and service usage, we can see how people use their phones, find unusual patterns, and understand different groups of customers.
This helps the company improve its offers, make customers happier, and keep them using the service.

📂 What’s in this folder?

- S7-Project-ConnectaTel.ipynb
  The main file containing the data cleaning, charts, analysis, and final results.

- data/plans.csv  
  Information about plan prices, included minutes, data (GB), and extra costs.

- data/users_latam.csv  
  Customer details like age, city, sign-up date, and their current plan.

- data/usage.csv  
  A record of activity, such as how long calls lasted and how many texts were sent.

▶ How to open the analysis in Google Colab

Click the button below:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]([S7-Project-ConnectaTel.ipynb](https://colab.research.google.com/github/LeidyNathaly/telecom-analysis/blob/99bef5c6885d48cad697a3444b207e8143273e67/notebooks/proyecto7_connectatel.ipynb
))

Or:

1. Open the .ipynb file on GitHub.  
2. Click the Open in Colab button.


📘 How to run the analysis yourself

1. Download these files to your computer.  
2. Make sure the three .csv data files are in the correct folder.  
3. Open the file notebooks/proyecto7_connectatel.ipynb.  
4. Run the code boxes one by one in order.  
5. If using Google Colab, make sure the file paths in the code match where you saved your data.

🧠 Goals of this study

- Understand how customers in Mexico and Colombia use their plans.  
- Find and fix missing or incorrect information in the data.  
- Organize the data so it is easy to read and use.  
- Look for patterns and see if some customers use the service much more or less than average.  
- Group users by age, country, and how much they use their phones.  
- Provide clear tips and advice for the company's business strategy.

🔎 Steps taken

1. Data Loading: Opening the files.  
2. Quality Check: Looking for errors or missing info.  
3. Cleaning: Fixing those errors.  
4. Summary: Calculating basic numbers (averages, totals).  
5. Charts: Creating visual graphs to see patterns.  
6. Grouping: Sorting users into different categories.  
7. Final Results: Summarizing what we learned.

⚙️ Tools needed

To run this analysis, you will need these Python libraries:

- pandas  
- numpy  
- matplotlib  
- seaborn
