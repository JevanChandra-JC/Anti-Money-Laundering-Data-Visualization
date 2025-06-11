# 🕵️‍♂️ Anti-Money Laundering (AML) Analysis with Tableau

This project explores suspicious financial transactions using Tableau to visualize and analyze a synthetic dataset. The primary goal is to identify patterns of potential money laundering — including “round-tripping” behaviors and intermediary (mule) accounts — through visual storytelling.

## 📊 Project Overview

- **Tool used**: Tableau
- **Dataset**: Transaction records from January and February 2020
- **Focus**: Detect unusual patterns in fund transfers involving selected accounts (Kim & Lee)
- **Techniques**: Visual grouping, transaction flow mapping, and behavioral pattern analysis

---

## 🔍 Key Insights

1. **Account Segregation**  
   - Kim & Lee use separate accounts for sending and receiving funds.
   - Sender accounts have no inbound transactions; receiver accounts have no outbound ones.

2. **Suspicious Transaction Patterns**  
   - Funds are sent to intermediary accounts (Sherren, Jane, Tony, Jerry) and routed back to Kim & Lee accounts.
   - This tactic, known as **round-tripping**, is often used to launder money by mimicking legitimate transfers.

3. **Middlemen Identified**  
   - Among the intermediaries, **Jerry** is the most active, handling the highest number of transactions with Kim & Lee accounts.

---
