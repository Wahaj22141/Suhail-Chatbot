# 🌍 Saudi Culture Datasets  

This repository contains two datasets designed to explore and interact with Saudi culture. These datasets can be utilized for educational purposes, cultural studies, and AI-based projects such as chatbot training.

---

## 📂 Dataset Overview  

### 1. General Dataset (`DataSet_general_u.csv`)  
This dataset provides a comprehensive overview of Saudi cultural topics. It categorizes information under broad topics and subcategories, with detailed descriptions and credible sources.

#### 🗂 Feature Descriptions  

| **Feature Name**       | **Data Type** | **Description**                                                                                 | **Example**                              |
|-------------------------|---------------|-------------------------------------------------------------------------------------------------|------------------------------------------|
| **Main Category**       | Object        | Broad category under which each entry is classified, covering high-level Saudi cultural topics. | Architecture, Arts, Economy, etc.        |
| **Subcategory**         | Object        | Specific classification within each main category.                                             | Religious Architecture, Heritage Villages |
| **Description**         | Object        | Pre-processed text describing each subcategory.                                                | "Kabsa is a popular Saudi dish..."       |
| **Source**              | Object        | Origin of the information for credibility and traceability.                                     | Ministry of Culture, Saudi Tourism       |

#### 📊 Data Insights  

| **Main Category**       | **Number of Entries** | **Brief Description**                                                   |
|-------------------------|-----------------------|-------------------------------------------------------------------------|
| Architecture            | 5                     | Covers architectural styles, including religious and historical sites. |
| Arts                    | 1                     | Details aspects of the arts.                                           |
| Crafts and Handicraft   | 16                    | Highlights traditional crafts and practices.                           |
| Cultural Etiquette      | 5                     | Focuses on customs and traditions.                                     |
| Economy                 | 8                     | Discusses economic sectors and developments.                           |
| Education               | 16                    | Covers the educational system and institutions.                        |
| Environment             | 5                     | Describes natural resources and ecosystems.                            |
| Festivals               | 8                     | Showcases traditional celebrations.                                    |
| Folklore                | 13                    | Features stories, myths, and folklore.                                 |
| Food                    | 1                     | Discusses popular Saudi dishes.                                        |
| Geography               | 9                     | Describes geographical features and landscapes.                        |
| History                 | 1                     | Covers cultural heritage and historical events.                        |
| Landmarks               | 1                     | Highlights notable landmarks.                                          |
| Language                | 1                     | Explores the Arabic language.                                          |
| Literature              | 9                     | Details traditional and modern Saudi literature.                       |
| Modern Culture          | 21                    | Discusses current cultural practices and lifestyles.                   |
| Music                   | 1                     | Explains the role of music in Saudi culture.                           |
| Music and Dance         | 4                     | Focuses on music and dance forms.                                      |
| Religion                | 2                     | Describes religious practices and beliefs.                             |
| Sports                  | 17                    | Highlights popular sports in Saudi Arabia.                             |

---

### 2. Question-Based Dataset (`DataSet_Sohail-Qestions.csv`)  
This dataset is designed for interactive learning and AI applications. It contains primary user queries, follow-up questions, responses, and extracted entities to support multi-turn conversations.

#### 🗂 Feature Descriptions  

| **Column Name**         | **Description**                                                                     | **Data Type** | **Example**                                 |
|-------------------------|-------------------------------------------------------------------------------------|---------------|---------------------------------------------|
| **Category**            | Main subject defining the type of question.                                        | Object        | Food                                        |
| **User Query**          | Primary user query about Saudi culture.                                            | Object        | "What are the most popular Saudi dishes?"   |
| **Response**            | Initial response to the user's query.                                              | Object        | "Popular dishes include Kabsa, Mandi, etc." |
| **Entities**            | Key terms extracted from the response.                                             | Object        | "Kabsa", "Mandi"                           |
| **Follow-up Questions** | Multiple levels of follow-up questions and responses for deeper exploration.        | Object        | "What are the key ingredients in Kabsa?"    |

#### 📊 Data Insights  

- **Rows:** 80  
- **Columns:** 16  
- **Memory Usage:** 27.2 KB  
- **No Missing Values:** Clean and ready for use.  
- **Purpose:** Enhances SuhailChatbot by supporting multi-turn conversations for in-depth learning.  

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
