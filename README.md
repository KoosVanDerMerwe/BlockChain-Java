# 🚀 Simple Java Blockchain

This is a simple blockchain implementation that I built in Java by following the two-part “Programmer’s Blockchain” tutorial series on Medium.
My goal with this project was to properly understand how a blockchain works under the hood — hashing, linking blocks, transactions, wallets, mining, and chain validation — all from scratch.

---

## 📈 Learning Journey

This project was my introduction to blockchain technology and cryptographic concepts. By building from scratch whilst following a tutorial, I gained deep understanding of:

- Cryptographic hashing and digital signatures
- Blockchain consensus mechanisms (proof-of-work)
- Public/private key cryptography
- Transaction validation and UTXO management
- Distributed ledger fundamentals

---

🧱 Features

✔️ Blocks

Each block contains:

* Timestamp
* Data (transactions)
* Hash
* Previous hash
* Nonce (for mining)

✔️ Blockchain

I implemented:

* A full chain stored in an ArrayList
* Mining with adjustable difficulty
* Automatic hash validation
* Chain integrity checking

✔️ Transactions

I added:

* ECDSA key generation
* Digital signatures
* Transaction inputs/outputs
* A UTXO list
* A simple coin-transfer simulation

✔️ Wallets

Each wallet can:

* Generate public/private keys
* Sign transactions
* Track its own balance using UTXOs

---

🗂️ Project Structure

My project looks like:

```
/src
  /main
    /java
      Block.java
      Blockchain.java
      StringUtil.java
      Transaction.java
      TransactionInput.java
      TransactionOutput.java
      Wallet.java
      NoobChain.java    // main demo class
```

---

▶️ How to Run It

**Prerequisites**

* Java 8+
* Any Java IDE (IntelliJ, VS Code, Eclipse, etc.)

**Steps**

1. Clone the repo:

   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
2. Open the project in your IDE.
3. Run the main class (`NoobChain` or your entry point).

The console will show:

* Wallet creation
* Mining activity
* Transaction signing
* Balances
* Chain validation

---

🧪 Example Output

You’ll see something like:

```
WalletA's balance: 100.0
WalletA is attempting to send funds (40) to WalletB...
Transaction Successfully Added to the Blockchain!
WalletA's balance: 60.0
WalletB's balance: 40.0
Blockchain is Valid
```

---

## 📚 Tutorial Credit

**Full credit to the original tutorial author** - this is my implementation of the "Programmer's Blockchain" tutorial series:

- Part 1 — [Creating the blockchain](https://medium.com/programmers-blockchain/create-simple-blockchain-java-tutorial-from-scratch-6eeed3cb03fa)
- Part 2 — [Adding transactions](https://medium.com/programmers-blockchain/creating-your-first-blockchain-with-java-part-2-transactions-2cdac335e0ce)

This is not my original concept - I built this to understand how blockchains work at a fundamental level.

---

📝 License

This project is for educational purposes only.
Feel free to use, modify, or experiment with it.

---

⭐ If You Like It

Give the repo a ⭐ — it helps others discover it!

