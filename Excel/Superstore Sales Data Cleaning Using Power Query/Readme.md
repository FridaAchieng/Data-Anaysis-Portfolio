## Superstore Sales Data Cleaning Using Power Query


---

## 🔄 Transformations Applied

### 1. 📌 Append Queries  
Combine multiple data tables (e.g., Part 1 + Part 2) into a single dataset.  
![Append Queries](screenshots/append_queries.png)

---

### 2. 🔤 Capitalize Text  
Format names properly (e.g., convert `"john smith"` to `"John Smith"`).  
![Capitalize Text](screenshots/capitalize_text.png)

---

### 3. ✂️ Split Columns  
Split full name into `First Name` and `Last Name` using a space delimiter.  
![Split Columns](screenshots/split_columns.png)

---

### 4. 🔁 Replace Values  
Replace specific values (e.g., change `"None"` to `"Not Provided"`).  
![Replace Values](screenshots/replace_values.png)

---

### 5. 🧠 Conditional Column  
Create a column with logic (e.g., label customers with no email as "Incomplete").  
![Conditional Column](screenshots/conditional_column.png)


5. **Export to Cleaned Dataset**

---

## 🛠️ Tools Used

- Microsoft Excel (Power Query Editor)
- Power Query M Language
- Excel formulas and data model

---

## 📦 How to Use

1. Open the file `data/raw_customer_data.xlsx` in Excel.
2. Launch Power Query Editor.
3. Follow the steps outlined in `Customer_Data_Cleaning.pq.txt`.
4. Save the output to `data/cleaned_customer_data.xlsx`.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

Thanks for visiting this project! Feel free to fork, clone, or adapt it to your own workflows.

