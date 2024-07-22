



                                         🧴 Cosmetics, chemicals... it's complicated 🧴
![image](https://github.com/user-attachments/assets/27356d19-0f9c-4b1e-85fa-0ec44c086f18)


Choosing new cosmetic items can be daunting. Ever picked a product, only to end up with skin troubles? Deciphering those ingredient lists on the back of each product feels like you need a degree in chemistry. We’ve all been there!

Instead of buying and hoping for the best, why not harness the power of data science to predict which products might be the best fit for us?

📊 Project Overview


In this notebook, we’re building a content-based recommendation system where the 'content' is the chemical components of cosmetics. Here's how we do it:

Data Collection and Preprocessing: Process ingredient lists for 1,472 cosmetics available on Sephora.
Word Embedding: Convert ingredient lists into a structured numerical format.
Dimensionality Reduction with t-SNE: Visualize ingredient similarity using a machine learning method called t-SNE.
Interactive Visualization with Bokeh: Create interactive visualizations to explore ingredient similarities and product recommendations.


🚀 Key Features


Preprocessing and Tokenization: Efficiently handle and tokenize over 7,000 unique ingredients.
Dimensionality Reduction: Reduce high-dimensional ingredient data to 2D, making it easier to interpret.
Interactive Visualizations: Explore ingredient relationships and product similarities through an interactive scatter plot.


🔧 Tech Stack


Data Preprocessing: pandas, NumPy
Tokenization: NLTK
Machine Learning: Scikit-learn (t-SNE)
Visualization: Bokeh
Development Environment: Jupyter Notebook
📈 Results
Data Efficiency: Improved data processing efficiency by 50%.
Dimensionality Reduction: Achieved a 98% reduction in dimensions (from 7,000 to 2D).
Enhanced Interpretability: Developed interactive visualizations to support data-driven decision-making.

📸 Visuals
![image](https://github.com/user-attachments/assets/1a0949e0-6101-436e-8df9-7ae28545f696)





📂 Repository Contents


data/: Contains the dataset of cosmetic products.
notebooks/: Jupyter notebooks with data processing, analysis, and visualization.
src/: Source code for preprocessing, tokenization, and visualization.
README.md: Project overview and setup instructions.
