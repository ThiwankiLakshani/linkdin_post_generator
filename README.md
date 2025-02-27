# LinkedIn Post Generator

## 🚀 Overview
The **LinkedIn Post Generator** is a Streamlit-based web application that helps users generate engaging LinkedIn posts with ease. It leverages AI-powered text generation to create customized posts based on selected topics, length, and language preferences.

## 🔥 Features
- **Easy-to-use UI** – Simple dropdowns for selecting post attributes.
- **AI-Generated Posts** – Uses NLP to generate high-quality LinkedIn content.
- **Customizable Options**:
  - Choose from different **topics**.
  - Select post **length** (Short, Medium, Long).
  - Pick a **language** (English, Hinglish).
- **One-Click Post Generation** – Get your LinkedIn post instantly with a button click.

## 🛠️ Installation & Setup
### **Prerequisites**
Ensure you have **Python 3.8+** installed. Then, install the required dependencies:

```sh
pip install -r requirements.txt
```

### **Clone the Repository**
To get a local copy of the project, run:

```sh
git clone https://github.com/yourusername/linkedin-post-generator.git
cd linkedin-post-generator
```

### **Run the App**
Once dependencies are installed, launch the app using:

```sh
streamlit run main.py
```

## 📌 Usage
1. Open the app in your browser (usually runs at `http://localhost:8503/`).
2. Select the **Topic**, **Length**, and **Language** for your post.
3. Click the **Generate** button to create a LinkedIn post.
4. Copy and use the generated post for your LinkedIn content.

## 🔧 Tech Stack
- **Python** – Backend logic
- **Streamlit** – Web UI framework
- **LangChain** – AI-based post generation
- **OpenAI/Groq API** – AI-powered content generation

## 📂 Project Structure
```
linkedin-post-generator/
│-- main.py          # Main application file
│-- post_generator.py # Handles AI-based post generation
│-- few_shot.py       # Few-shot learning implementation
│-- llm_helper.py     # Helper functions for AI model interaction
│-- requirements.txt  # Dependencies
│-- README.md         # Project documentation
```

## 🎯 Future Enhancements
- Add more **language options**.
- Improve **post personalization**.
- Integrate **direct LinkedIn posting**.
- Enhance UI/UX for better usability.
- Implement **user authentication**.
- Add **post editing features** before publishing.

## 🛡️ License
This project is open-source and available under the **MIT License**.

## 📬 Contact
For any queries or suggestions, feel free to reach out:
- **Email**: your-email@example.com
- **GitHub Issues**: [Open an issue](https://github.com/yourusername/linkedin-post-generator/issues)

---
🚀 **Happy Posting!**

