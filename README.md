📊 AI Tools Dataset Visualization

This project explores and visualizes an open-source dataset of AI Tools. Using Seaborn and Matplotlib, we generate meaningful plots to understand the distribution, usage, and popularity of different AI tool types.

📂 Dataset

File: AI_Tools_List.csv

Key Columns:

Tool Name → Name of the AI tool.

AI Type → Category/type of AI tool (e.g., Chatbot, Vision, NLP, etc.).

Popularity Score (1-10) → Popularity rating.

Use Cases → Applications and domains where the tool is used.

⚙️ Tech Stack

Python 3

Libraries:

pandas → Data handling

matplotlib → Plotting

seaborn → Advanced visualization

📊 Visualizations

The following plots were created:

Count Plot

Shows how many tools exist in each AI type.

Bar Plot (Mean Popularity by AI Type)

Average popularity score across different AI categories.

Box Plot + Swarm Plot

Spread of popularity scores for each AI type with data distribution.

Violin Plot

Distribution density of popularity scores.

KDE / Histogram

Popularity score distribution with kernel density estimation.

🔍 Insights

Certain AI tool types dominate in number (e.g., Chatbots/NLP).

Average popularity varies significantly between categories.

Some AI types show higher variance in popularity (useful for trend analysis).

KDE plots highlight common score ranges (most tools cluster around mid-popularity).

▶️ How to Run

Clone this repo:

git clone https://github.com/your-username/ai-tools-visualization.git
cd ai-tools-visualization


Install dependencies:

pip install pandas seaborn matplotlib


Run the notebook or Python script:

jupyter notebook ai_tools_visualization.ipynb

📷 Example Plots

 <img width="955" height="440" alt="image" src="https://github.com/user-attachments/assets/04046ddd-e092-4fd8-99ec-f71af62b4010" />
 
 <img width="851" height="577" alt="download" src="https://github.com/user-attachments/assets/9f9870e4-8167-441c-b5c7-6b42b16eae54" />
 
<img width="954" height="444" alt="image" src="https://github.com/user-attachments/assets/314e5aad-2b71-4a09-a80f-a391c82682c3" />



📌 Conclusion

This project demonstrates how exploratory data analysis (EDA) with visualization helps us quickly interpret datasets and uncover patterns. The AI tools dataset reveals valuable trends in categories and popularity, useful for research and industry applications.
