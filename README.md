# 💸 Expense Tracker with LLM + Custom ML Model

This project combines the power of **Large Language Models (LLMs)** and a **custom Machine Learning text classifier** to automatically categorize expenses from plain text sentences.  

---

## 🚀 What it Involves
1. **Collecting a dataset** of expense-related sentences.  
   - Example: *"Paid ₹500 for Netflix"* → `Subscriptions`  
   - *"₹2000 rent transfer"* → `Rent`  
2. **Labeling the dataset** with predefined categories (e.g., `Subscriptions`, `Rent`, `Groceries`, `EMI`, etc.).  
3. **Training a text classification model**  
   - Options: 
     - Use a **lightweight LLM** for local inference  
     - Train a **custom ML pipeline** with Scikit-learn / spaCy 
4. **Deploying the model** for fast and cheap categorization of new expenses.

---

## ✅ Pros
- 🔹 **Fully Customizable** → Works with your own categories  
- 🔹 **Adaptable** → Learns your unique spending patterns  
- 🔹 **Local & Cheap** → Once trained, it runs offline without extra costs  
- 🔹 **Hybrid Approach** → ML model + LLM fallback  

---

## 🛠️ Tech Stack
- **Python** 🐍  
- **Scikit-learn** (ML text classification)  
- **Pandas & NumPy** (data handling)  
- **Joblib** (model saving/loading)  
- **Optional LLM API** for fallback classification
- **LLM Integration** (optional for edge cases)
- **Dataset labeling tools** (Prodi.gy / Label Studio / custom script)

---

## 📊 Example Flow
```text
Input  : "Paid ₹1200 for groceries at Big Bazaar"
Process: → Text Preprocessing → Model Inference  
Output : Category = "Groceries"
