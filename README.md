# 📰 Fake News Detection  

This project compares a **fine-tuned transformer model (DistilBERT)** against a **traditional TF–IDF + Naïve Bayes baseline** for detecting fake news. It demonstrates how contextual embeddings from transformers outperform classical feature-based methods in text classification.  

---

## 📂 Project Structure
- **fake_news_detection.ipynb** → Jupyter Notebook with experiments, preprocessing, and training.  
- **README.md** → Documentation for the project.  
- **.gitignore** → Ignores unnecessary files (cache, virtual environments, etc.).  
- **LICENSE** → MIT license.  

*(You can also add your PDF report later inside a `reports/` folder for completeness.)*  

---

## 🚀 Models
- **DistilBERT (fine-tuned)** → lightweight transformer, achieves ~100% accuracy on the test set.  
- **TF–IDF + Naïve Bayes** → strong classical baseline, ~93% accuracy.  

---

## 📊 Results
| Model                  | Accuracy | Precision | Recall | F1-score | MCC  |
|-------------------------|----------|-----------|--------|----------|------|
| DistilBERT (Fine-tuned) | 100%     | 0.92      | 0.94   | 0.93     | 0.86 |
| TF–IDF + Naïve Bayes    | 93%      | 0.85      | 0.75   | 0.80     | 0.60 |

---

## ⚙️ Technologies
- Python 3.9+  
- HuggingFace Transformers  
- PyTorch  
- Scikit-learn  
- Pandas, NumPy, Matplotlib  

---

## 🔮 Future Work
- Zero-shot and few-shot fake news detection with large language models (LLMs).  
- Multilingual detection (e.g., mBERT, XLM-R).  
- Handling satire/irony detection.  
- Hybrid systems with human-in-the-loop fact-checking.  

---

## 👥 Team
- Roaa Al-Mdani  
- Lama Al-Alawfi  
- Shatha Mahrous  


---

## 📄 License
This project is licensed under the MIT License.

