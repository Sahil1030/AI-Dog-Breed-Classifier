# 🐶 AI-Dog-Breed-Classifier

## 📌 Description
**AI-Dog-Breed-Classifier** is a Python-based AI application that identifies the **breed of a dog** from an image and provides detailed breed-specific facts. It leverages **Groq's AI**, **image processing**, and **API integrations** to recognize dog breeds and offer insights on their characteristics.

## ✨ Features
✅ **Dog Breed Recognition:** Identifies the breed of a dog from an uploaded image.
✅ **AI-Powered Analysis:** Uses **Groq's Vision AI** to analyze images.
✅ **Dog Facts API:** Fetches breed-specific information (e.g., shedding, barking, energy level).
✅ **Interactive Assessments:** Generates structured assessments based on breed characteristics.

## 🛠️ Technologies Used
- 🐍 **Python 3.12.4**
- 🤖 **Groq API** (for image recognition and breed classification)
- 🐕 **API Ninjas** (for fetching dog breed details)
- 🔑 **dotenv** (for managing API keys)
- 🖼️ **base64** (for image encoding)
- 🌐 **requests** (for API calls)
- 📜 **JSON** (for data processing)

## 🚀 Installation
### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/Sahil1030/AI-Dog-Breed-Classifier.git
cd AI-Dog-Breed-Classifier
```

### **2️⃣ Install Dependencies**
Ensure you have Python 3.12.4 installed, then run:
```bash
pip install -r requirements.txt
```

### **3️⃣ Set Up API Keys**
Create a `.env` file in the project directory and add:
```ini
GROQ_API_KEY=your_api_key_here
NINJA_API_KEY=your_api_key_here
```

### **4️⃣ Prepare Image for Analysis**
📷 Ensure you have an image file (e.g., `dog_image.jpeg`) in the correct directory.
✏️ Update the `image_path` variable in `only_doggy_base.py` to match the image file location.

### **5️⃣ Run the Application**
```bash
python only_doggy_base.py
```
This will analyze the image and display the identified breed along with additional information.

## 🎯 Usage
1️⃣ Place an image of a dog in the directory.
2️⃣ Run the Python script to analyze the image.
3️⃣ View the breed name and its characteristics.

## 📋 Requirements
The application requires the following dependencies, which are listed in the `requirements.txt` file:
```bash
groq
dotenv
requests
base64
json
ipython
```

## 🤝 Contributing
Feel free to submit **pull requests** or report issues in the GitHub repository.

## 📜 License
This project is licensed under the **MIT License**.

---
🌟 If you like this project, don't forget to give it a star on GitHub! ⭐

