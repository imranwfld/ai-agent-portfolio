# 🤖 AI Agent Portfolio

This repository showcases a collection of AI agents built by me. Each agent solves a specific task using intelligent automation and natural language understanding.

---

## 👤 About Me

With over **15 years of experience** in RAN virtualization engineering, I am a leading expert in delivering cutting-edge **vRAN** and **O-RAN** solutions for telecom operators. I have contributed to several major vRAN and O-RAN deployments for Tier-1 operators.

### 🔍 Current Focus Areas
- Building the world's first commercial **5G O-RAN Network**
- **O-RAN**, **vRAN** design and deployment
- Radio Access Network (RAN) engineering
- Using **RANGPT** for setup, configuration, and advanced troubleshooting to optimize RAN performance
- 5G validation and performance improvement
- Network performance and automation

### 🌐 Interests
Connectivity everywhere and anytime, 5G to 6G evolution, O-RAN/RIC, IoT, and AI/ML

---

## 📨 Agent 1: Youtube Summarizer Agent

### 🧠 Description  

- Summarize the content from a YouTube video
- Summarize the comments from the same video
- Display both summaries at the same time


🔗 **Access it here:** [[Youtube Summarizer Agent](https://app.mindstudio.ai/agents/youtube-summary-and-comment-analysis-4911930a/)]]

## Agent 2 : Ask the Chat bot

### Functionality

- Agent has access to a **Data Source** containing the written documentation for a product.
- I have used Mindstudio documentation as a Datasource for this chatbot.
- - User types in their question related to the docs.
- Check to see if the question is relevant to the product. If not, display a message prompting the user to ask a question about the product.

**Use RAG to answer the users question:**

- Enhance the user query for use in querying a vector database.
- Query the data source using the enhanced query.
- Using the Original Question, the Enhanced Query, and the Query Result, Generate a response to the user’s original question.
- Once answered, let the user continue chatting with the agent to ask more questions and continue using RAG in chat to answer those questions.

- 🔗 **Access it here:** : [[ask the chatbot]](https://app.mindstudio.ai/agents/ask-the-docs--chat-bot-c3b30c81/)

  
## Agent 3: Website Changes - Agent

### Functionality
- Scrape a specified website
- If first scrape:
    - Save the scraped content for use on the next run.
    - End the Workflow quietly without any notifications.
- If NOT first scrape:
    - Compare the current scrape to the previous scrape
    - Analyze for changes based on specified criteria
    - If there are changes:
        - Generate a report of the specific changes.
        - Send the report to Email or Slack
    - If NO changes:
        - End the workflow quietly without any notifications.

-  🔗 **Access it here:** : [[ Website Changes - Agent ]] (https://app.mindstudio.ai/agents/website-changes--agent-3f9c0e1e/)
---





---

## 👤 Author

**Imran Khan**  
GitHub: [@imranwfld](https://github.com/imranwfld)

---

## 📌 Notes

- All agents are public and accessible without login.  
- For issues or suggestions, feel free to open an issue or submit a pull request.

