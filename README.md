
## 📌 About the Project  

This project demonstrates how to perform **Exploratory Data Analysis (EDA)** on a **Weather Dataset** using **Pandas** in Python.  
It covers **data exploration, cleaning, statistics, and conditional queries** to better understand the dataset.  

---

## 🔧 Pandas Functions Used  

- `head()` → Shows the first N rows (default = 5)  
- `shape` → Returns total number of rows & columns  
- `index` → Provides the index range of the DataFrame  
- `columns` → Displays all column names  
- `dtypes` → Shows the data type of each column  
- `unique()` → Lists unique values of a column  
- `nunique()` → Counts unique values in a column/DataFrame  
- `count()` → Returns count of non-null values  
- `value_counts()` → Shows unique values with their frequency (column only)  
- `info()` → Summary of DataFrame (columns, dtypes, nulls, memory)  

---

## 📝 Analysis Questions  

Below are the analysis queries performed on the dataset:  

1️⃣ Find all the unique **Wind Speed** values.  
2️⃣ Find the number of times when the **Weather is exactly Clear**.  
3️⃣ Find the number of times when the **Wind Speed was exactly 4 km/h**.  
4️⃣ Find out all the **Null Values** in the data.  
5️⃣ Rename the column **Weather → Weather Condition**.  
6️⃣ What is the **Mean Visibility**?  
7️⃣ What is the **Standard Deviation of Pressure**?  
8️⃣ What is the **Variance of Relative Humidity**?  
9️⃣ Find all instances when **Snow** was recorded.  
🔟 Find all instances when **Wind Speed > 24** and **Visibility = 25**.  
1️⃣1️⃣ Find the **Mean value of each column** against each *Weather Condition*.  
1️⃣2️⃣ Find the **Minimum & Maximum value** of each column against each *Weather Condition*.  
1️⃣3️⃣ Show all records where **Weather Condition = Fog**.  
1️⃣4️⃣ Find all instances when **Weather is Clear** OR **Visibility > 40**.  
1️⃣5️⃣ Find all instances when:  
   - A. **Weather is Clear** AND **Relative Humidity > 50**  
   - B. **Visibility > 40**  

---

## ⚙️ How to Run  

1️⃣ Install dependencies:  
```bash
pip install pandas jupyter
