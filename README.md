# 🔐 SQL Injection Lab (DVWA)

## 🔍 Description
This project demonstrates SQL Injection attacks performed in a controlled lab environment using DVWA (Damn Vulnerable Web Application).

SQL Injection is a vulnerability where user input is directly included in SQL queries, allowing attackers to manipulate database behavior. :contentReference[oaicite:1]{index=1}

---

## ⚙️ Lab Setup
- Tool: DVWA (Damn Vulnerable Web Application)
- Environment: XAMPP (Apache + MySQL)
- Security Level: Low

---

## 💉 Attack Performed

### 🔹 Normal Query
Input:
1

### 🔹 SQL Injection Payload
' OR'a'='a

👉 This bypasses authentication and returns all database records.

---

## 📸 Screenshots

### Injection Input
![Injection](injection.png)

### Output Result
![Result](result.png)

---

## 🧠 Explanation
The payload `' OR'a'='a` always evaluates to TRUE, causing the database to return all records instead of a specific user.

---

## 🛡️ Prevention Techniques
- Use Prepared Statements  
- Input Validation  
- Parameterized Queries  

---

## 📚 Learning Outcome
- Understood SQL Injection vulnerability  
- Learned authentication bypass techniques  
- Explored secure coding practices  

---

## ⚠️ Disclaimer
This project was performed in a controlled lab environment for educational purposes only.
