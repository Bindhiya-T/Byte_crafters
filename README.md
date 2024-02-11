
# Customer Churn Prediction Using SMOTE with oneAPI
Team Byte Crafters

# Introduction 👋

•	Project objective: The objective of our project is to investigate machine learning techniques, propose a model for anticipating customer churn, identify churning factors, and provide retention strategies.

•	Factors considered: Using diverse Machine learning techniques, Libraries like Scikit-learn & Streamlit, Python, LLM, Intel oneAPI Toolkit, oneDAL library and IDC(Intel Developer Cloud).

•	Expected outcomes: The Customer Churn Prediction model which gives accurate predictions. The Llama 2 Chatbot developed provides real-time assistance and valuable insights into Customer churn.

## 🛠 Built With
Intel oneAPI    
IDC(Intel Developer Cloud)  
Machine Learning Using oneAPI Toolkit   
Scikit-learn    
Streamlit   
LLM   
oneDAL      
Python  
Jupyter
 


## Tech Stack

**Intel oneAPI:**
Intel oneAPI is a comprehensive suite of software development tools designed to simplify the development of high-performance applications across a variety of architectures, including CPUs, GPUs, FPGAs, and other accelerators. One of the main benefits of oneAPI is that it enables developers to take advantage of the full power of modern hardware, including the latest CPUs and GPUs, without having to write separate code for each platform. This can help save time and reduce development costs, as well as improve the overall performance of the application. Some common uses of oneAPI include developing machine learning models, accelerating data analytics workloads, and optimizing scientific simulations.

**Use of Intel® AI Analytics Toolkit:** In our Customer Churn Prediction project, we used the Machine Learning Using oneAPI Toolkit of Intel oneAPI. The AI Kit maximizes performance from preprocessing through machine learning and provides interoperability for efficient model development. By using the AI Analytics Toolkit, we were able to gain direct access to analytics and AI optimizations from Intel which ensured that our software works together seamlessly.

**Use of oneDAL:**
We have used the oneDAL library of Intel oneAPI to optimize and accelerate our machine learning models. By using the oneDAL library, we were able to take advantage of Intel's industry-leading optimization and parallelization capabilities to improve the efficiency, accuracy, and performance of our models.
To use oneDAL in our project, we applied the sklearnex patch to our machine learning models. This was done using the code:


```bash
from sklearnex import patch_sklearn
patch_sklearn()
```


**Use of Streamlit and LLM:**
 The synergy of Streamlit and LLM allows seamless integration, providing an intuitive and efficient platform to build, deploy, and engage with the chatbot, bringing a personalized and responsive conversational experience to the users.


## How We built it
✅Installation and Importing of libraries  
✅Understanding the Data   
✅Test Different Models and find the best model out of it   
✅Train the model using Intel oneDAL to get better results and faster computation(Intel oneAPI Data Analytics Library (oneDAL))  
✅Save the model    
✅User Interface with Llama 2 Chatbot


## Demo
chatbot.png
https://github.com/Bindhiya-T/Byte_crafters/blob/caebc020122710f10e5793ef30c12d9c4023d66e/chatbot.png
