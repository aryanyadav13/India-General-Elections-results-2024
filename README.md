# India-General-Elections-results-2024
# 🗳️ India General Election Result Analysis 2024 (SQL Project)

## 📌 Project Overview  
This project analyzes the **India General Election Results 2024** using SQL.  
The database contains information about candidates, constituencies, states, parties, and alliances.  

The goal is to answer key analytical questions such as:  
- Who won in each constituency and with what margin?  
- How do EVM vs Postal votes differ for candidates?  
- Which parties and alliances performed the best?  
- State-wise and national-level election summaries.  

---

## 🏗️ Database Schema (ERD)  

### **Tables**  
1. **partywise_results**  
   - Party  
   - Won  
   - Party ID  

2. **constituencywise_details**  
   - Candidate  
   - Party  
   - EVM Votes  
   - Postal Votes  
   - Total Votes  
   - % of Votes  
   - Constituency ID  

3. **constituencywise_results**  
   - Parliament Constituency  
   - Constituency Name  
   - Winning Candidate  
   - Total Votes  
   - Margin  
   - Constituency ID  
   - Party ID  

4. **statewise_results**  
   - Constituency  
   - Const. No.  
   - Parliament Constituency  
   - Leading Candidate  
   - Trailing Candidate  
   - Margin  
   - Status  
   - State ID  
   - State  

5. **states**  
   - State ID  
   - State  

---

## ❓ Problem Statements Solved  

### Candidate & Constituency Level  
- Winning candidate’s name, party name, total votes, and margin for a specific state and constituency  
- Distribution of **EVM vs Postal votes** for candidates in a constituency  
- Candidate with the **highest EVM votes (Top 10)**  
- Winner and runner-up for each constituency  

### Party & State Level  
- Which party won the most seats in a state  
- Total seats won by each **party alliance (NDA, I.N.D.I.A, OTHER)**  
- Breakdown of seats won by alliance parties in each state  

### National Level  
- Total seats available for elections  
- Seats won by NDA, I.N.D.I.A, and OTHER alliances across India  
- Which alliance won the most seats nationwide  

### Maharashtra Special Analysis  
- Total seats, candidates, and parties in Maharashtra  
- Total votes (EVM + Postal)  
- Breakdown of EVM vs Postal votes  

---

## ⚙️ Tech Stack  
- **SQL**: Querying and analysis  
- **Database**: MySQL / PostgreSQL  
- **Visualization (Optional)**: Power BI / Tableau  

---

