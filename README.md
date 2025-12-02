# NL-SQL-Agent

This project is a lightweight **NL-to-SQL automation agent** built in **n8n**.  
It allows users to ask questions in plain English and automatically converts them into SQL queries executed on a Postgres database.  
Results are returned instantly through the chat interface, creating a conversational analytics experience without requiring SQL knowledge.

---

## 🌟 What It Does

- Converts natural-language questions into valid SQL  
- Uses schema-aware memory to avoid hallucinations  
- Executes queries directly on Postgres  
- Returns structured, human-readable results  
- Handles missing data with intelligent fallback responses  

---

## 🔧 How It Works

1. Chat message triggers the workflow  
2. AI Agent interprets user intent  
3. Schema stored in memory guides SQL generation  
4. Postgres runs the generated query  
5. Results are formatted and sent back to the user  

---

## 🖼 Workflow Diagram

```md
![Workflow Diagram](natural language to sql query.png)

