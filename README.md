# Suhail Chatbot Datasets  
# 🌍 Saudi Culture Datasets  

This repository contains two datasets designed to explore and interact with Saudi culture. These datasets are tailored for educational purposes, cultural studies, and AI-based projects like training SuhailChatbot.

---

## 📂 Dataset Overview  

### 1. General Dataset (`DataSet_general_u.csv`)  
This dataset provides a comprehensive overview of Saudi cultural topics by classifying information under broad categories and subcategories, with detailed descriptions and credible sources.  

#### 🗂 Feature Descriptions  

| **Feature Name** | **Data Type** | **Description** | **Example** |
|------------------|---------------|-----------------|-------------|
| **Main Category** | Object | Broad category under which each entry is classified, covering high-level Saudi cultural topics. | Architecture, Arts, Economy, Environment, Festivals, History, etc. |
| **Subcategory** | Object | More specific classification within each main category, providing detailed insight. | Religious Architecture, Heritage Villages, Eid al-Fitr, Unification of Saudi Arabia |
| **Description** | Object | Pre-processed text that describes each subcategory and can be turned into questions and follow-ups for SuhailChatbot. | "Kabsa is a popular Saudi dish made of rice…" |
| **Source** | Object | Origin of the information for credibility and traceability, with references to authoritative entities. | Ministry of Culture, Saudi Tourism, Saudi Historical Society |

#### 📊 Data Insights  

| **Main Category**       | **Number of Entries** | **Brief Description**                                                   |
|-------------------------|-----------------------|-------------------------------------------------------------------------|
| Architecture            | 5                     | Architectural styles such as religious and historical architecture.    |
| Arts                    | 1                     | Details aspects of the arts.                                           |
| Crafts and Handicraft   | 16                    | Traditional crafts and handicraft practices.                           |
| Cultural Etiquette      | 5                     | Traditional customs and etiquette.                                     |
| Economy                 | 8                     | Economic sectors, growth, and developments.                           |
| Education               | 16                    | Educational systems and institutions within Saudi Arabia.              |
| Environment             | 5                     | Natural resources and ecosystems of Saudi Arabia.                      |
| Festivals               | 8                     | Traditional celebrations that contribute to Saudi’s cultural history.  |
| Folklore                | 13                    | Traditional stories, myths, and folklore.                              |
| Food                    | 1                     | Popular dishes in Saudi Arabia.                                        |
| Geography               | 9                     | Geographical features and landscapes.                                  |
| History                 | 1                     | Cultural heritage and historical events.                               |
| Landmarks               | 1                     | Notable and iconic landmarks.                                          |
| Language                | 1                     | Information on the Arabic language.                                    |
| Literature              | 9                     | Traditional and modern Saudi literature, including notable authors.    |
| Modern Culture          | 21                    | Current cultural practices and modern lifestyle trends.                |
| Music                   | 1                     | Role of music in Saudi culture.                                        |
| Music and Dance         | 4                     | Information on music and dance forms.                                  |
| Religion                | 2                     | Religious practices, beliefs, and aspects of Islam.                    |
| Sports                  | 17                    | Popular sports in Saudi Arabia.                                        |

---

### 2. Question-Based Dataset (`DataSet_Sohail-Qestions.csv`)  
This dataset enhances the functionality of SuhailChatbot by using information collected from reliable sources about Saudi cultural topics. It contains multiple user queries, responses, and follow-up questions to facilitate deeper interactions.  

#### 🗂 Feature Descriptions  

| **Column Name**         | **Description**                                                                     | **Data Type** | **Example**                                 |
|-------------------------|-------------------------------------------------------------------------------------|---------------|---------------------------------------------|
| **Category**            | The main subject that defines the type of question.                                | Object        | Food                                        |
| **User Query**          | Possible user queries about Saudi culture.                                         | Object        | "What are the most popular traditional Saudi dishes?" |
| **Response**            | Initial response to the user's query.                                              | Object        | "Some of the most popular traditional Saudi dishes include Kabsa, Mandi, and Jareesh." |
| **Entities**            | Key terms extracted from the response to refine chatbot responses.                 | Object        | "Kabsa", "Mandi", "Jareesh"                |
| **First Follow-up Question** | The first possible follow-up question a user might ask after receiving the initial response. | Object | "What are the key ingredients in Kabsa?"    |
| **Response**            | The first response from SuhailChatbot to the First Follow-up Question.             | Object        | "Kabsa includes rice, meat, vegetables, and spices." |
| **Entities**            | Key entities mentioned in the first follow-up response.                            | Object        | "Rice", "Meat", "Spices"                   |
| **Second Follow-up Question** | The second follow-up question for deeper inquiry.                            | Object        | "How is Mandi different from Kabsa?"       |
| **Response**            | Response to the Second Follow-up Question.                                         | Object        | "Mandi is cooked in a tandoor-style oven, while Kabsa is not." |
| **Entities**            | Key entities mentioned in the second follow-up response.                           | Object        | "Mandi", "Tandoor"                         |
| **Third Follow-up Question** | The third follow-up question for further exploration.                         | Object        | "What is the significance of Jareesh in Saudi cuisine?" |
| **Response**            | Response to the Third Follow-up Question.                                          | Object        | "Jareesh is a staple dish made from crushed wheat." |
| **Entities**            | Key entities mentioned in the third follow-up response.                            | Object        | "Jareesh", "Wheat"                         |
| **Fourth Follow-up Question** | The fourth follow-up question for more details.                              | Object        | "Are there regional variations of these dishes?" |
| **Response**            | Response to the Fourth Follow-up Question.                                         | Object        | "Yes, dishes like Kabsa have variations across regions." |
| **Entities**            | Key entities mentioned in the fourth follow-up response.                           | Object        | "Regional Variations"                      |

#### 📊 Data Insights  

- **Rows:** 80  
- **Columns:** 16  
- **Purpose:** Develops direct questions and follow-ups to provide a deeper understanding of topics for SuhailChatbot users.  

---

## 💡 Applications  

1. **📚 Educational Tools:** Explore Saudi cultural topics for learning and analysis.  
2. **🤖 AI Development:** Train conversational AI models for interactive cultural learning.  
3. **📊 Data Analysis:** Perform exploratory data analysis (EDA) or visualization on cultural trends.  

---

## 🚀 Usage  

Load the datasets  

  
import pandas as pd

# Load General Dataset
general_data = pd.read_csv('DataSet_general_u.csv')

# Load Question-Based Dataset
question_data = pd.read_csv('DataSet_Sohail-Qestions.csv')
