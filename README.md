🛍️ Customer Segmentation with K-Means (Built from Scratch)

This is a beginner-friendly Data Science project where I try to group wholesale customers based on their spending habits.
The idea was to practice EDA, feature scaling, and unsupervised learning.

I originally planned to use scikit-learn, but I had environment issues, so I built a simple version of K-Means from scratch using NumPy.
It took me some time, but it helped me understand the algorithm much better.

🔧 What I learned

Loading and inspecting data with Pandas

Standardizing features manually

Implementing a basic K-Means algorithm using only NumPy

Plotting clusters with Matplotlib

Interpreting customer behavior from the results

It’s a small project, but it helped me practice the fundamentals of machine learning.

📊 Project Workflow

Load and explore the dataset

Select numerical features

Standardize all variables

Apply K-Means (custom implementation)

Assign customers to clusters

Visualize and interpret the results

🔍 Main Insights

One cluster focuses on groceries and cleaning supplies → likely supermarkets

Another cluster buys mostly fresh and frozen products → possibly restaurants or hotels

A smaller cluster has low overall spending → small shops or low-volume clients

These patterns are useful for understanding customer types and for segmentation strategies.

📁 Files

customer_segmentation.ipynb – full analysis

Wholesale customers data.csv – dataset

README.md – project documentation

🚀 Future Improvements

Try different values of k

Use PCA to reduce dimensions

Evaluate clusters with Silhouette Score

Re-run the project using scikit-learn when the environment issue is solved

Thanks for checking out the project!
Any feedback is welcome!
