# Financial_bot

**Financial Chatbot Documentation**

### Overview
The financial chatbot is a Python-based script that provides financial insights about major companies like Apple, Microsoft, and Tesla. It processes a CSV file containing financial data and responds to user queries with relevant financial metrics using Natural Language Processing (NLP) techniques.

### Functionality
The chatbot can:
- Load financial data from a CSV file (`Financial_Analysis.csv`).
- Analyze revenue, net income, and asset trends for predefined companies.
- Respond to a broader range of financial questions using NLP.
- Interpret user queries more flexibly, even if phrased differently.
- Display financial trends using formatted text.
  o### Query Handling
The chatbot supports NLP-powered queries, allowing users to ask financial questions in natural language. Example queries include:
- **"How did Apple's revenue change?"** – Provides Apple's revenue growth for 2023 and 2024.
- **"Tell me about Apple's net income performance."** – Shows Apple's net income growth for 2023 and 2024.
- **"How is Microsoft's financial health?"** – Displays Microsoft's revenue growth for 2023 and 2024.
- **"What about Tesla's profits?"** – Shows Tesla's net income growth for 2023 and 2024.
- **"Give me Microsoft's asset details."** – Provides Microsoft's total assets for 2023 and 2024.

If a user asks an unsupported question, the chatbot attempts to interpret it using NLP. If it still cannot generate a response, it replies with:
> "⚠️ Sorry, I couldn’t understand your request. Please try rephrasing your question."

### Limitations
- **Static Data**: The chatbot relies on a CSV file and does not fetch live financial data.
- **Limited Scope**: Although NLP improves query flexibility, responses are still limited to available financial data.
- **CSV File Dependency**: The chatbot requires `Financial_Analysis.csv` in the specified directory to function correctly.sion for review or deployment.
