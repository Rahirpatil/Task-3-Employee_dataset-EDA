# 📦 Task 3: Internship Product Sales Data Cleaning

This notebook is part of my Artificial Intelligence internship at iGAP Technologies. Task 3 focuses on cleaning and preparing a product sales dataset using Python libraries in Jupyter Notebook. The objective was to handle missing values, standardize formats, and prepare the data for analysis or modeling.

---

## 📚 Libraries Used

- **pandas** – for data manipulation  
- **numpy** – for numerical handling  
- **matplotlib** – for basic visualizations  
- **seaborn** – for data exploration

---

## 🧼 Cleaning Steps Performed

### 📥 Data Loading

- Imported essential libraries  
- Loaded the dataset using `read_csv()`  
- Inspected the dataset for nulls and structure  

### 💰 `Price` Column

- Converted `Price` to numeric values  
- Calculated the mean  
- Replaced missing price values with the mean  

### 📦 `Quantity` Column

- Filled missing values using the most frequent value (`mode()[0]`)  
- Printed the column to confirm the changes  

### 🏙️ `City` Column

- Analyzed the column with `describe()`  
- Checked for inconsistencies or missing entries  

### 🗓️ `Purchase Date` Column

- Reviewed the format  
- No cleaning required for this column  

---

## ✅ Final Output

- Cleaned and consistent dataset  
- All missing data filled appropriately  
- Ready for visualization, dashboarding, or machine learning models

---

## 📂 Files

├── Task-3/
│ ├── task-3.ipynb # Jupyter Notebook with all cleaning steps
│ └── README.md # This documentation file

---

## 🏁 Status

✔️ Task 3 completed successfully  
⚙️ Dataset cleaned and structured for analysis
