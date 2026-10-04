# Excel_Assignment_2
Data cleaning and transformation
## Data Loading
# 💻💻  Excel ➡️ Power Query 
## 📝 Solution
### 1) Handling Missing Values
-  **Price column:** Identified missing values and replacing missing values with a logical substitute ( median -130).
-  **Category column:** Filled missing categories using a placeholder label (Unknown).
  ### 2) Correcting inconsistent data:
 - **standardize text format (Product Name ):** Click  ' Product Name 'column header➡️Transform ➡️Format➡️ **Capitalize Each
        Each Word**.
   
   - **Fix Typos (Category) (Product Name ):** Click 'Category) column header ➡️Replace Values ("Electroni" or "Electronics",
       "Electronicscs" or Electronics" ➡️ OK.
### 3)Remove Duplicates
 - **Remove duplicates**  Click **Table icon** ➡️ Remove Dublicates.
### 4) Splitting & Merging Data
 - **Splitting:** click  Product Id ➡️ Transform➡️ Split Column ➡️ By Delimiter ➡️ ( - ) ➡️ Right - Most
           delimiter ➡️ OK
   - **Marge:**  click Ctrl + Brand  Name & Product Name ➡️ Right click ➡️ Merge Column ➡️Separator (   )➡️ 
                   New Column Name : Product Brand ➡️OK
### 5) Number Formatting 
  - **Formatting Price:**  Price Column ➡️ Left icon click ➡️currency
    - **Manufacturing  Date :**  Date column ➡️ Left icon ➡️ Date
   
        ###  HOME TAB  ➡️  CLOSE &  LOAD  

### 6) Conditional Formatting  
        - **Price column:**   Select Price Column full ➡️Home tab  ➡️ Styles Group  Conditional Formatting                                      ➡️Data bars ➡️ select 
        - **Category column:**    Select category column full ➡️ Conditional Formatting ➡️Highlight Cell Rules 
                                    ➡️Text that Contains ➡️ Electronics ➡️ select color ➡️ OK
                                    
        


