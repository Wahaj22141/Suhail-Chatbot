# 🌟 Suhail Chatbot Datasets  
This repository contains two datasets designed to explore and interact with Saudi culture. These datasets are tailored for educational purposes, cultural studies, and AI-based projects like training SuhailChatbot.

---

## 📂 Dataset Overview  

Two datasets have been built for the Suhail chatbot. They were collected from **132 reliable sources**.  

### 1. General Dataset (`DataSet_general_u.csv`)  
This dataset is general and contains **166 rows and 4 columns** :  

- The **first column** represents the main categories, such as Architecture, Arts, Economy, and more.  
- The **second column** dives deeper to represent subcategories such as Religious Architecture, Heritage Villages, etc.  
- The **third column** provides pre-processed descriptions related to the different subcategories.  
- The **fourth column** contains the sources from where the data were collected, providing a reference if it is necessary to revisit the original information.  

The dataset is **text-based**, with **no missing values or null entries**. It is **well-structured**, meaning all fields are complete, ensuring a clean dataset for training purposes.  

### Dataset Characteristics:  

- **Total Samples:** 80 (equivalent to the number of rows).  
- **Memory Usage:** 18.5 KB (lightweight and easy to process).  
- **Structure:** Provides both general and specific information about Saudi culture.  

This dataset will be processed further in the form of questions with follow-up questions, which will be used to train the model of Suhail Chatbot.

---

### 2. Question-Based Dataset (`DataSet_Sohail-Qestions.csv`)  
This dataset enhances the functionality of SuhailChatbot by using information collected from reliable sources about Saudi cultural topics. It contains **16 columns** to facilitate detailed interactions, such as:  

- User queries about Saudi culture.  
- Initial responses, key entities, and follow-up questions to dive deeper into the topic.  
- Structured responses and additional insights to improve conversational quality.  

---

## 📊 Feature Descriptions  

### General Dataset  

| **Feature Name** | **Data Type** | **Description** | **Example** |
|------------------|---------------|-----------------|-------------|
| **Main Category** | Object | Broad category under which each entry is classified, covering high-level Saudi cultural topics. | Architecture, Arts, Economy, Environment, Festivals, History, etc. |
| **Subcategory** | Object | More specific classification within each main category, providing detailed insight. | Religious Architecture, Heritage Villages, Eid al-Fitr, Unification of Saudi Arabia |
| **Description** | Object | Pre-processed text that describes each subcategory and can be turned into questions and follow-ups for SuhailChatbot. | "Kabsa is a popular Saudi dish made of rice…" |
| **Source** | Object | Origin of the information for credibility and traceability, with references to authoritative entities. | Ministry of Culture, Saudi Tourism, Saudi Historical Society |

---

### Question-Based Dataset  

| **Column Name**         | **Description**                                                                     | **Example**                                 |
|-------------------------|-------------------------------------------------------------------------------------|---------------|---------------------------------------------|
| **Category**            | The main subject that defines the type of question.                                 | Food                                        |
| **User Query**          | Possible user queries about Saudi culture.                                          | "What are the most popular traditional Saudi dishes?" |
| **Response**            | Initial response to the user's query.                                               | "Some of the most popular traditional Saudi dishes include Kabsa, Mandi, and Jareesh." |
| **Entities**            | Key terms extracted from the response to refine chatbot responses.                  | "Kabsa", "Mandi", "Jareesh"                |
| **First Follow-up Question** | The first possible follow-up question a user might ask after receiving the initial response. | Object | "What are the key ingredients in Kabsa?"    |
| **Response**            | The first response from SuhailChatbot to the First Follow-up Question.              | "Kabsa includes rice, meat, vegetables, and spices." |
| **Entities**            | Key entities mentioned in the first follow-up response.                             | "Rice", "Meat", "Spices"                   |
| **Second Follow-up Question** | The second follow-up question for deeper inquiry.                             | "How is Mandi different from Kabsa?"       |
| **Response**            | Response to the Second Follow-up Question.                                         || "Mandi is cooked in a tandoor-style oven, while Kabsa is not." |
| **Entities**            | Key entities mentioned in the second follow-up response.                            | "Mandi", "Tandoor"                         |

---

## 💡 Applications  

1. **📚 Educational Tools:** Explore Saudi cultural topics for learning and analysis.  
2. **🤖 AI Development:** Train conversational AI models for interactive cultural learning.  
3. **📊 Data Analysis:** Perform exploratory data analysis (EDA) or visualization on cultural trends.  

---

## 🚀 Usage  

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-repo/saudi-culture-datasets.git
   cd saudi-culture-datasets
   ```
2. Load the datasets:  

   ```python
   import pandas as pd

   # Load General Dataset
   general_data = pd.read_csv('DataSet_general_u.csv')

   # Load Question-Based Dataset
   question_data = pd.read_csv('DataSet_Sohail-Qestions.csv')
   ```
3. Use the data for analysis, training, or applications.  

---

## 🤝 Contributions  

Contributions are welcome! Help us expand the dataset, improve the structure, or suggest innovative use cases.  

---

## 📜 License  

This project is licensed under the **MIT License**.  

---
