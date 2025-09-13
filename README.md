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
```
---

## 📸 Screenshots

<table>
  <tr>
    <td><img width="1907" height="911" alt="image" src="https://github.com/user-attachments/assets/57dd1289-2997-4c0c-b5bb-186aeb7f5b0e"/></td>
    <td><img width="1901" height="912" alt="image" src="https://github.com/user-attachments/assets/59b9c66b-d85b-4a3c-b9f9-9abc6950ab9b" /></td>
    <td><img width="1905" height="915" alt="image" src="https://github.com/user-attachments/assets/7b42f634-81b0-459e-94a5-802dba181ed9" /></td>
   <td><img src="screenshots/summary.png" alt="Summary" width="300"/></td>
<img width="1907" height="911" alt="image" src="https://github.com/user-attachments/assets/16d1b2f5-5b50-4cb8-bef1-c5c824c28491" />

  </tr>
</table>

