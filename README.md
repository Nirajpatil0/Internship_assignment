# Contact Information Extraction and Summarization Project

## 📌 Project Overview
This project demonstrates **text summarization** and **information extraction** using OpenAI's GPT model with function calling.  
The assignment is divided into **two main tasks**:

- **Task 1**: Summarization & Extraction  
- **Task 2**: Periodic Summarization & Extraction with Schema

The goal is to:
1. Generate concise summaries from long text.
2. Truncate text intelligently.
3. Periodically summarize content.
4. Extract structured information (like name, email, phone, location, age) in JSON format.

---

## 🛠️ Technologies Used
- **Python 3.8+**
- **Jupyter Notebook**
- **OpenAI GPT Models** (for summarization & function calling)
- **JSON Schema** (for structured extraction)

---

## 🚀 How I Built It (Step by Step)

### 🔹 Step 1: Import Required Libraries
- Imported `json`, `openai`, and basic utilities.  
- Set up environment for running GPT models.

### 🔹 Step 2: Input Text
- Defined the input text (article/document) for summarization and extraction.  

### 🔹 Step 3: Summarization
- Implemented a function to generate a **short summary** of the input text using GPT.

### 🔹 Step 4: Truncation
- Implemented logic to truncate the text into smaller chunks without losing important meaning.

### 🔹 Step 5: Periodic Summarization
- Applied summarization **after every few sentences/paragraphs** to demonstrate continuous summarization.

### 🔹 Step 6: Define Schema for Extraction
- Defined a **function-calling schema** with fields:
  - `name`
  - `email`
  - `phone`
  - `location`
  - `age`

### 🔹 Step 7: Extraction Implementation
- Passed the schema to GPT model.  
- Model extracted **structured JSON output** for contact details.

### 🔹 Step 8: Testing
- Validated the pipeline on sample input text.  
- Verified summarization outputs and schema-based extraction.

---

## 📊 Sample Output

### ✅ Summarization Output

### ✅ Extraction Output
```json
{
  "name": "John Doe",
  "email": "johndoe@example.com",
  "phone": "+91-9876543210",
  "location": "Mumbai, India",
  "age": "29"
}
``` 
### **📌 Key Learnings**

- Using GPT for abstractive summarization.  
- Handling long text by truncation.  
- Implementing periodic summarization.  
- Extracting structured JSON data using GPT function calling.  
