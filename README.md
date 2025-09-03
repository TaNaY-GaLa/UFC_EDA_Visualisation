UFC Fighters Statistics – Data Cleaning & Visualization
Project Overview

This project explores UFC fighters' statistics to understand how physical attributes such as height, weight, and reach influence fight outcomes (wins, losses, and draws).

The process includes data cleaning, preprocessing, handling outliers, and creating visualizations to uncover meaningful patterns using Python libraries like pandas, matplotlib, and seaborn.

Steps Performed
1. Data Loading

Imported the dataset ufc-fighters-statistics.csv.

Checked the dataset shape, identified missing values, and detected duplicates.

2. Data Cleaning

Removed duplicate rows for accuracy.

Handled missing values systematically:

Numeric columns filled with median values.

Categorical columns filled with the most frequent category.

Converted data types into numeric and categorical formats where appropriate.

3. Outlier Handling

Applied IQR-based clipping to limit extreme values.

Ensured the dataset remained consistent while preserving key patterns.

4. Exploratory Data Analysis (EDA)

Generated histograms with Seaborn to explore how fight outcomes vary with physical traits.

Examined relationships between height, weight, reach and outcomes (wins, losses, draws).

Visualizations

Height Distributions
Fighters with certain height ranges showed higher frequencies of wins. Losses and draws followed slightly different patterns, indicating height may give some advantage but is not the sole factor.

Weight Distributions
Wins, losses, and draws were not evenly spread across weight categories. Certain weight classes displayed clusters of victories, hinting at possible dominance in specific ranges.

Reach Distributions
Fighters with greater reach showed a higher tendency for wins, but the overlap with losses and draws highlighted that skill and strategy play a role beyond just physical advantage.

✨ Together, these visualizations tell the story of how physical attributes matter in the UFC, while also reminding us that fighting outcomes depend on multiple factors beyond size alone.

Tech Stack

Python 3.x

pandas – Data handling

numpy – Numerical operations

matplotlib – Visualization

seaborn – Statistical plots

Results & Insights

Physical traits such as height, weight, and reach show visible correlations with fight outcomes.

Wins tend to cluster in specific ranges of these attributes, especially with reach.

Careful data cleaning ensured reliable analysis by removing duplicates, handling missing data, and controlling outliers.

Feel free to reach out with any questions or for collaborations!

📧 Email: tanaygala23oct@gmail.com

🔗 LinkedIn: www.linkedin.com/in/tanay-ketan-gala-23oct06/
