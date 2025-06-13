# Openfi-Bot

| Feature                |
|------------------------|
| Auto Get Account Info  |
| Auto Mint Faucet       |
| Auto Deposit           |
| Auto Supply            |
| Auto Borrow            |
| Auto Withdraw          |
| Proxy Modes            |

Tentu! Berikut adalah versi **bahasa Inggris** dari instruksi menjalankan **Openfi-Bot**, sudah dirapikan dan cocok untuk README.md:

---

### 🚀 **Steps to Run Openfi-Bot**

---

#### 1. **Clone the Repository**

```bash
git clone https://github.com/ZonaAirdrop/Openfi-Bot.git
```

> This command clones the project from GitHub to your local machine.

---

#### 2. **Navigate to the Project Directory**

```bash
cd Openfi-Bot
```

---

#### 3. **Install Python Dependencies**

```bash
pip install -r requirements.txt
```

> Installs all required Python packages listed in `requirements.txt`.

---

#### 4. **Create `accounts.txt` File**

In the project folder, create a file named `accounts.txt` and add your private keys, one per line:

```
your_private_key_1
your_private_key_2
```

---

#### 5. **Create `proxy.txt` File (Optional)**

Create a `proxy.txt` file if you want to use proxies. Supported formats:

```
ip:port
http://ip:port
http://user:pass@ip:port
```
---
#### 6. **Run the Bot**
```bash
python3 bot.py
```
> This will execute the bot script using your accounts and proxies (if provided).

