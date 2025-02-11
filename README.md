Simple Bank - Motoko 💰🚀
A basic on-chain banking smart contract built with Motoko for the Internet Computer (ICP). This smart contract allows users to:

✅ Deposit funds 💰
✅ Withdraw funds 💸
✅ Check account balance 📊
✅ Reset account ♻️

All transactions are fully on-chain, leveraging ICP's actor-based model for decentralized finance (DeFi) applications.

📌 Features
Uses Motoko’s type system to handle Nat values securely.
Implements query & update functions (checkBalance(), deposit(), withdraw(), resetAccount()).
Ensures safe withdrawals using an if condition to prevent overdrafts.

🛠️ Setup & Deployment
1️⃣ Clone the Repository
sh
Copy
Edit
git clone https://github.com/JohnBenJB/simple-bank-motoko.git  
cd simple-bank-motoko  

2️⃣ Open in Motoko Playground
Go to Motoko Playground
Copy & paste the main.mo file into the editor.
Click Deploy and interact with the contract.

3️⃣ Run Functions
deposit(100) → Adds 100 tokens to balance.
withdraw(50) → Deducts 50 tokens (if sufficient balance).
checkBalance() → Returns current balance.
resetAccount() → Resets balance to 0.

🔗 Contributing & Feedback
Feel free to fork, modify, and improve this contract. If you encounter issues or have suggestions, open an issue or submit a pull request! 🚀

📜 License
This project is open-source under the MIT License.
