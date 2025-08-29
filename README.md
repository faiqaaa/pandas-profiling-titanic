# 🚢 Titanic EDA with ydata_profiling  

This project shows how to perform **Exploratory Data Analysis (EDA)** on the Titanic dataset using  
👉 `ydata_profiling` (formerly Pandas Profiling).  

With just a few lines of code, you can generate a **complete HTML report** containing:  
- 📊 Dataset overview  
- 🔎 Missing values detection  
- 🔗 Correlations & interactions  
- 📈 Automatic visualizations  

---

## 📂 Files in this Repository
- `Titanic_EDA.ipynb` → Jupyter/Colab notebook with the code  
- `output.html` → Generated profiling report
- ▶️ Usage Example
from ydata_profiling import ProfileReport
import pandas as pd

# Load dataset
df = pd.read_csv("titanic.csv")

# Create report
profile = ProfileReport(df)
profile.to_file("output.html")

---

## ⚙️ Installation
To install `ydata_profiling`, run:
```bash
pip install ydata_profiling
## 📸 Example Report
<img width="1802" height="807" alt="ml" src="https://github.com/user-attachments/assets/37fe42d4-2012-4ff9-aa9b-2d3dee65b914" />
<img width="1867" height="950" alt="ML 2" src="https://github.com/user-attachments/assets/ec9db87c-6b91-4680-9223-7f94dc3f3238" />
<img width="1902" height="1016" alt="ML 3" src="https://github.com/user-attachments/assets/2082d5a4-761a-4340-b821-e3644e5576bf" />
## 🌟 Key Learning

Today I learned how to use pandas profiling (ydata_profiling) to quickly analyze datasets.
It makes EDA super easy and saves a lot of time 🚀
