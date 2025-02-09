# 🤖 Chatbot Using Python  

## 📌 Overview  
This project implements a simple chatbot using **TensorFlow**, a machine learning framework developed by Google. The chatbot is trained to recognize user **intents** based on predefined patterns and provide appropriate responses.  

---

## 📚 Libraries Used  

- **numpy**: Handles arrays and performs mathematical operations efficiently.  
- **tensorflow**: Builds, trains, and deploys the chatbot's neural network model.  
- **nltk**: Performs natural language processing (NLP) tasks like tokenization, stemming, and lemmatization.  
- **nltk.download('wordnet')**: Downloads the **WordNet corpus**, essential for lemmatization (reducing words to their base form).  

---

## 📂 File Structure & Execution Order  

### 📄 **Files in the Project**  
1. `Readme1.txt`: General information about the project.  
2. `Readme2.txt`: Additional instructions or details.  
3. `new.py`:  
   - Preprocesses the data.  
   - Trains the chatbot model using TensorFlow.  
   - Saves the trained model for later use.  
4. `chatbot.py`:  
   - Loads the trained model.  
   - Accepts user input.  
   - Recognizes intents and generates responses.  

### ▶ **How to Run the Project**  
#### **Step 1: Install Dependencies**  
Ensure you have **Python 3.x** installed. Then, install the required libraries using:  
```bash
pip install numpy tensorflow nltk
```
#### **Step 2: Train the Chatbot Model**  
Run **new.py** to preprocess data and train the chatbot:
```bash
python new.py
```
### **Step 3: Run the Chatbot**
Once trained, execute **chatbot.py** to interact with the chatbot:
```bash
python chatbot.py
```

## 🔧 Adjusting File Paths  
The chatbot uses an **intents.json** file containing predefined patterns and responses for training.  
Ensure the correct file paths are set to prevent errors in locating required files.  

---

## ✨ Customization & Enhancements  
You can modify the chatbot to better fit your needs:  
✅ Update `intents.json` with new patterns and responses.  
✅ Tune training parameters for improved accuracy.  
✅ Implement advanced NLP techniques for better understanding.  
✅ Integrate with a **GUI** or a **web-based chatbot**.  

---

## 🚀 Future Improvements  
- Implement **speech-to-text** interaction.  
- Add **database connectivity** for dynamic responses.  
- Enhance the model with **transformers** for better accuracy.  

---

## 🤝 Contribute & Feedback  
Feel free to contribute, modify, and enhance the chatbot!  
Let us know your feedback to improve the project.  

💡 **Happy Coding!** 🚀  
