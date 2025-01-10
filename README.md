Suhail Chatbot Datasets
This repository contains two datasets designed to explore Saudi culture. These datasets are suitable for educational purposes, data analysis, and AI-based projects such as chatbot training.

---

## 📂 Dataset Details  

### 1. General Dataset (`DataSet_general_u.csv`)  
- **📖 Description:**  
  This dataset provides an overview of Saudi culture, categorized into topics like Architecture, History, and Traditions. Each row includes a main category, subcategory, a detailed description, and the source of information.  
- **📊 Structure:**  
  - **Rows:** 165  
  - **Columns:** 4  
  - **Column Details:**  
    1. `Category`: Broad topic (e.g., Architecture, Arts).  
    2. `Subcategory`: Specific classification (e.g., Religious Architecture, Heritage Villages).  
    3. `Description`: Detailed explanation of the subcategory.  
    4. `Source`: Source of the information.  
- **📌 Usage:**  
  Ideal for cultural studies, data visualization, or creating informative applications about Saudi culture.

### 2. Question-Based Dataset (`DataSet_Sohail-Qestions.csv`)  
- **📖 Description:**  
  This dataset is designed for interactive learning and conversational AI applications. It contains primary user queries about Saudi culture, follow-up questions, responses, and extracted entities to support multi-turn conversations.  
- **📊 Structure:**  
  - **Rows:** 80  
  - **Columns:** 16  
  - **Column Details:**  
    1. `Category`: Main cultural topic (e.g., Food, Landmarks).  
    2. `User Query`: Primary question asked by the user.  
    3. `Response`: The response to the primary query.  
    4. `Entities`: Key terms extracted from the response.  
    5. Additional columns for follow-up questions, responses, and entities (up to 4 levels).  
- **📌 Usage:**  
  Suitable for training chatbots, conducting NLP tasks, or building interactive applications about Saudi culture.

---
**💡Applications:**

📚 Cultural Learning: Analyze and learn about Saudi culture.
🤖 Chatbot Training: Use the question-based dataset to train conversational AI models.
📊 EDA and Visualizations: Perform exploratory data analysis or create cultural insights.

## 🚀 Getting Started  

1. Clone the repository or download the dataset files.  
2. Use Python or any other tool to load and explore the data. Example code in Python:  

```python
import pandas as pd

# Load General Dataset
general_data = pd.read_csv('DataSet_general_u.csv')
print(general_data.head())

# Load Question-Based Dataset
question_data = pd.read_csv('DataSet_Sohail-Qestions.csv')
print(question_data.head())
