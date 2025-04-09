# ✨ MailGuard AI: Email Spam Filter Demonstration

💌 Welcome to **MailGuard AI**, an interactive and educational demonstration of email spam filtering powered by Machine Learning. This project showcases how a **Naive Bayes** classifier can be used to detect spam emails in real time using a user-friendly **Streamlit interface**.

---

## 🎯 Objective

The aim of this project is to demonstrate the power of **Machine Learning in action** — specifically how a trained algorithm can be used to **classify emails as spam or ham** (legitimate). With an easy-to-use web interface, users can input email messages and get immediate, intelligent results.

---

## 🚀 Features

- 🔤 **Interactive UI**: Powered by Streamlit — type or paste an email to get instant feedback.
- 🧠 **Naive Bayes Algorithm**: Trained on real-world spam data and labeled ham messages.
- 📊 **Confidence Score**: See how sure the model is in its classification.
- 🔄 **Feedback Loop**: Provide feedback on classification accuracy to help refine the system.
- 🛠️ **Error Handling**: Built-in exception handling for a smooth user experience.
- 📚 **Educational Focus**: Designed to teach how ML models work behind the scenes.

---

## 🧪 How It Works

I trained this model using:
- A dataset composed of my own collected spam emails
- An online dataset of ham (non-spam) emails
- Manual labeling to ensure accuracy

Using the **Naive Bayes algorithm**, a classic and efficient classification model, I built a lightweight yet effective spam detector. Then, I integrated it into a **Streamlit** web application to make it interactive and intuitive.

This project is not just about filtering spam — it’s about **demonstrating machine learning concepts** in a hands-on, beginner-friendly way.

---

## 🧰 Requirements

### 🖥️ Hardware
- A laptop or desktop

### 💾 Software
- Python 3.x
- Jupyter Notebook
- PyCharm (Community Edition recommended)
- Streamlit
- Pandas
- Numpy

---

## 📦 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/mailguard-ai.git
   cd mailguard-ai
   ```
   
2. **Install the dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the app**
   ```bash
   streamlit run app.py
   ```

4. **Use the interface**
   
- Type or paste an email message
- Click to classify it
- View the spam/ham result with confidence score
- Submit feedback if desired

---

## 📉 Limitations

- This is a simplified demo and not a production-level spam filter
- Naive Bayes, while fast and effective, is not state-of-the-art for complex spam patterns
- No support for advanced spam defenses like blacklists or dynamic keyword detection

---



