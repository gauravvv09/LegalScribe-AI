
** **LegalScribeAI – AI-Powered Legal Document Assistant** ** 

 **Introduction**  
Legal documentation can be a daunting task for individuals and small businesses, often requiring professional expertise to ensure accuracy and compliance. The complex language used in legal documents makes it challenging for non-lawyers to understand, leading to potential errors and misinterpretations.  

 **Project Objective**  
LegalScribeAI is designed to streamline the legal documentation process by leveraging AI to generate legally sound documents in clear and simple language. The system ensures accessibility, customization, and accuracy by integrating AI-driven automation with legal databases.  

 **Core Features**  
🔹 **Intuitive User Interface** – A simple and interactive platform for users to input essential legal details.  
🔹 **Automated Document Generation** – AI recommends and drafts legal documents based on user input.  
🔹 **Customizable Templates** – Users can modify documents to suit their specific needs.  
🔹 **Integration with Legal Databases** – Ensures documents adhere to legal standards and remain up to date.  

 **Technology Stack**  
📌 **Frontend:** React, Tailwind CSS  
📌 **Backend:** Python, Flask, PostgreSQL  
📌 **AI & Machine Learning:** Natural Language Processing (NLP) for document analysis and generation  

 **Project Structure**  
📁 **Legal-Documentation-Assistant**  
┣ 📂 **assets** – Stores images, reference files, and media assets  
┣ 📂 **client** *(Frontend - React Application)*  
┃ ┣ 📂 src  
┃ ┃ ┣ 📂 components  
┃ ┃ ┃ ┣ 📄 Chat.jsx *(Chatbot Component)*  
┃ ┃ ┣ 📄 About.jsx *(Project Overview Page)*  
┃ ┃ ┣ 📄 Faq.jsx *(Frequently Asked Questions Section)*  
┃ ┃ ┣ 📄 Home.jsx *(Main Homepage)*  
┃ ┃ ┣ 📄 InputForm.jsx *(User Input Form for Legal Documents)*  
┃ ┃ ┣ 📄 LoginPage.jsx *(User Authentication Page)*  
┃ ┣ 📂 public *(Static Files - HTML, Icons, etc.)*  
┃ ┃ ┣ 📄 index.html  
┣ 📂 **model** *(AI-Powered Legal Processing Model)*  
┃ ┣ 📄 similarity.py *(Cosine Similarity Model for Query Matching)*  
┃ ┣ 📄 bot.py *(Main AI Bot Logic)*  
┃ ┣ 📄 chat.py *(Standalone AI Chat Module)*  
┃ ┣ 📄 model.py *(Bag of Words-based NLP Model)*  
┃ ┣ 📄 train.py *(Model Training Script)*  
┃ ┣ 📄 dataset.py *(Legal Data for AI Training)*  
┃ ┣ 📄 util.py *(Utility Functions)*  
┃ ┣ 📄 trained_model.pth *(Pre-trained AI Model)*  
┃ ┣ 📄 intents.json *(Dataset for Chatbot Training)*  
┣ 📂 **server** *(Backend API and Database Management - Flask & PostgreSQL)*  
┃ ┣ 📂 docs *(Folder for Generated Legal Documents)*  
┃ ┃ ┣ 📄 localfile.docx *(Sample Document)*  
┃ ┃ ┣ 📄 Output2.docx *(Generated Legal Document Example)*  
┃ ┣ 📄 app.py *(Flask Backend Application)*  
┃ ┣ 📄 createdatabase.py *(Database Initialization Script)*  
┃ ┣ 📄 requirements.txt *(List of Required Dependencies)*  
┣ 📄 **README.md** *(Project Documentation and Setup Guide)*  

 **Conclusion**  
LegalScribeAI simplifies the legal documentation process by making it more accessible, user-friendly, and efficient. By combining AI-powered automation with legal expertise, this platform empowers individuals and businesses to create accurate and customized legal documents with ease. 🚀  

