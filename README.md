# 🗣️ NLP to SQL Converter

> Convert natural language questions into SQL queries using Natural Language Processing and Machine Learning.

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![SQLite](https://img.shields.io/badge/Database-SQLite-green.svg)
![NLP](https://img.shields.io/badge/NLP-Natural%20Language-orange.svg)
![License](https://img.shields.io/badge/License-MIT-blue.svg)

---

## 📖 Overview

The **NLP to SQL Converter** enables users to interact with databases using plain English instead of writing SQL manually.

Users can simply ask questions like:

> "Show all employees earning more than 50000."

The system automatically generates the corresponding SQL query and executes it on the database.

This project demonstrates the integration of **Natural Language Processing**, **SQL**, and **Python** to build an intelligent database query assistant.

---

## ✨ Features

- 🔹 Convert English questions into SQL queries
- 🔹 Execute generated SQL queries automatically
- 🔹 Support for SELECT statements
- 🔹 WHERE clause generation
- 🔹 ORDER BY support
- 🔹 LIMIT clause support
- 🔹 Aggregate functions (COUNT, SUM, AVG, MAX, MIN)
- 🔹 Easy-to-use interface
- 🔹 SQLite database integration
- 🔹 Error handling for invalid inputs

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|----------|
| Python | Backend Development |
| SQLite | Database |
| SQL | Query Language |
| Pandas | Data Processing |
| NLTK / spaCy | Natural Language Processing |
| Regex | Text Parsing |
| Streamlit / Flask *(Optional)* | User Interface |

---

## 📂 Project Structure

```text
NLP-to-SQL/
│
├── data/
│   ├── database.db
│   └── sample_data.csv
│
├── models/
│
├── sql/
│
├── utils/
│   ├── parser.py
│   ├── sql_generator.py
│   └── database.py
│
├── app.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

## ⚙️ How It Works

```text
User Question
       │
       ▼
Natural Language Processing
       │
       ▼
Intent Detection
       │
       ▼
Entity Extraction
       │
       ▼
SQL Query Generation
       │
       ▼
Execute Query
       │
       ▼
Display Results
```

---

## 💡 Example

### User Input

```text
Show all employees whose salary is greater than 50000.
```

Generated SQL

```sql
SELECT *
FROM Employees
WHERE Salary > 50000;
```

---

### User Input

```text
How many employees work in HR?
```

Generated SQL

```sql
SELECT COUNT(*)
FROM Employees
WHERE Department='HR';
```

---

### User Input

```text
Show the top 5 highest-paid employees.
```

Generated SQL

```sql
SELECT *
FROM Employees
ORDER BY Salary DESC
LIMIT 5;
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/NLP-to-SQL.git
```

Navigate to the project

```bash
cd NLP-to-SQL
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
python app.py
```

---

## 📊 Supported SQL Operations

- SELECT
- WHERE
- ORDER BY
- LIMIT
- COUNT
- SUM
- AVG
- MAX
- MIN
- GROUP BY *(Optional)*
- HAVING *(Optional)*

---

## 📈 Future Improvements

- Support JOIN queries
- Nested SQL queries
- Multiple database support
- Transformer-based Text-to-SQL model
- Voice-to-SQL
- Query explanation
- Query optimization
- Interactive dashboard
- User authentication
- Query history

---

## 🎯 Applications

- Business Intelligence
- Data Analytics
- Database Management
- Educational SQL Learning
- Enterprise Reporting
- AI-powered Database Assistants

---

## 📷 Workflow

```text
Natural Language
        │
        ▼
Preprocessing
        │
        ▼
NLP Model
        │
        ▼
SQL Generator
        │
        ▼
SQLite Database
        │
        ▼
Results
```

---

## 📚 Learning Outcomes

This project demonstrates:

- Natural Language Processing
- SQL Query Generation
- Database Connectivity
- Python Programming
- Data Processing
- AI-assisted Database Interaction

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a new feature branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 📜 License

This project is licensed under the MIT License.

---

## 👩‍💻 Author

**Suhani Keni**

- GitHub: https://github.com/SuhaniKeni
- LinkedIn: https://www.linkedin.com/in/suhanikeni

⭐ If you found this project useful, consider giving it a star!
