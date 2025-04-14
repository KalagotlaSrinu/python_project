📊 Indian Census Data Analysis & Visualization (Python)
This project analyzes and visualizes Indian Census data using Python. It demonstrates data cleaning, transformation, exploratory data analysis (EDA), visualizations, and predictive modeling using linear regression. The dataset used in this project is sourced from the Census India Website.

🗂 Dataset
File Used: PYTHONDATASET.csv

Source: Census India

The dataset contains information on:

State/District/Sub-District level population

Area

Number of households

Rural vs Urban distribution

Population density

Gender breakdown

✅ Key Features
🧹 Data Cleaning
Renames and sanitizes column headers

Handles missing and non-numeric values

Converts columns with commas into integers

Ensures consistency in population totals (e.g., Total = Urban + Rural)

📊 Visualizations
Population Distribution Across States (Horizontal Bar Chart)

Urban vs Rural Population by State (Stacked Bar Chart)

Top 10 Districts by Population Density (Bar Chart)

Gender Ratio by State (Bar Chart with threshold line at 1000)

Households vs Population (Sub-Districts) (Scatter Plot with Hue by Area Type)

Pair Plot of Population, Households, Area, and Density (Sub-Districts)

Urban vs Rural Population Share in India (Pie Chart)

📈 Linear Regression
Builds a model to predict population at the sub-district level using:

Number of households

Area

Population density

Evaluates model using R² score and visualizes predictions

🔧 Technologies Used
Python 3.x

pandas

matplotlib

seaborn

scikit-learn

📁 How to Run
Clone the repository

Place the PYTHONDATASET.csv file in the project folder

Run the script using any Python IDE or Jupyter Notebook

bash
Copy
Edit
pip install pandas matplotlib seaborn scikit-learn
python census_analysis.py
📌 Future Work
Add more machine learning models (Random Forest, Decision Tree)

Create a dashboard using Plotly or Streamlit

Integrate interactive maps using Folium or GeoPandas

📝 License
This project is for educational and non-commercial use. Please cite the source of the dataset if used in publications or other work.


