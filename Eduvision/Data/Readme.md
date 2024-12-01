### **Dataset Description and Preprocessing Steps**

The dataset we utilized for this project is the **PISA 2022 Global Dataset**, which is publicly available on the official PISA website. This dataset, provided in SAV format, is approximately **2.6GB** in size and contains the data collected from the **PISA (Programme for International Student Assessment)**, the **largest educational survey in the world**. It evaluates the performance of **15-year-old students** in participating countries, assessing their skills in reading, mathematics, and science, along with other contextual variables.

### **Challenges and Approach**
Given the time constraints and the vast size of the dataset, processing the data posed significant challenges. The dataset originally contained **over 1120 variables**, which included information on student performance, school environment, demographic factors, and more.

To address these challenges:
1. **Filtering and Computing Performance Variables**:
   - We focused on variables directly related to **performance metrics** and other relevant social or contextual indicators.
   
2. **Variable Reduction**:
   - Initially, we reduced the number of variables to **25** based on relevance to our analysis objectives (and because most of them are the questions in the students questionnaire, so we kept the composite variables).
   - After team discussions and alignment on the project goals, a **final selection** of variables was made.
   - The final selection was based on **data quality** criteria, such as the presence of missing values and the overall consistency of the data.

3. **Preprocessing Workflow**:
   - Due to the dataset's complexity and size, we adopted a combined approach:
     - **IBM SPSS Statistics** was used for initial filtering and variable exploration.
     - **Python scripts** were employed for further preprocessing, cleaning, and transformation of the data.

### **Key Highlights**
- The PISA dataset provides an unparalleled resource for understanding educational performance across countries.
- Our focus on reducing the dataset to relevant variables ensured the analysis remained efficient and targeted, without compromising on the quality of insights.
- The combination of **SPSS** and **Python** allowed us to effectively handle and preprocess the dataset, ensuring accurate and actionable results despite its complexity.
