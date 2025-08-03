# 📧 RAG-based Cold Mail Generator

This cold email generator is designed for service companies. It uses Groq, LangChain, and Streamlit to help users create personalized cold emails. Inspired from CodeBasics YouTube channel

Users input the URL of a company’s careers page, and the tool extracts job listings from that page. It then generates tailored cold emails that include relevant portfolio links retrieved from a vector database, matched specifically to the job descriptions.

**Imagine a scenario:**

- Nike needs a Principal Software Engineer and is spending time and resources in the hiring process, on boarding, training etc
- Atliq is Software Development company can provide a dedicated software development engineer to Nike. So, the business development executive (Mohan) from Atliq is going to reach out to Nike via a cold email.

![img.png](imgs/img.png)

## Architecture Diagram
![img.png](imgs/architecture.png)

## Set-up
1. To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside `app/.env` update the value of `GROQ_API_KEY` with the API_KEY you created. 


2. To get started, first install the dependencies using:
    ```commandline
     pip install -r requirements.txt
    ```
   
3. Run the streamlit app:
   ```commandline
   streamlit run app/main.py
   ```
   


