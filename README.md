# 🧠🪟 Pepe3 Daemon for Windows – v1.0.0

This repository provides the official **Pepe3 Daemon for Windows** – a full node solution that lets you run, mine, and interact with the Pepe3 blockchain through terminal commands, without a graphical interface.

---

📦 **Included in `pepe3-daemon-windows.zip`**

- ⚙️ `pepe3d.exe` – Full node daemon  
- 💻 `pepe3-cli.exe` – Command line RPC interface  
- 🧪 `pepe3-tx.exe` – Raw transaction tool

---

🛠️ **System Requirements**

- OS: Windows 7 / 10 / 11 (64-bit)  
- RAM: 2 GB minimum  
- Disk: 1 GB free  
- Internet connection for network sync

---

🚀 **Setup Instructions**

1. 📥 Extract the ZIP archive to a folder like `C:\Pepe3Daemon`
2. 📁 Open Notepad and paste the configuration below:

```
rpcuser=rpc_pepe3
rpcpassword=dR2oBQ3K1zYMZQtJFZeAerhWxaJ5Lqeq9J2
rpcbind=127.0.0.1
rpcallowip=127.0.0.1
listen=1
server=1
daemon=1
txindex=1
addnode=node3.walletbuilders.com
```

3. 💾 Save the file as `pepe3.conf` in:  
   `%APPDATA%\Pepe3\` (create the folder if it doesn’t exist)

4. ▶️ Open Command Prompt (`cmd.exe`), navigate to your extracted folder:

```cmd
cd C:\Pepe3Daemon
pepe3d.exe
```

5. 📡 Interact with your node using:

```cmd
pepe3-cli.exe getblockcount
```

To stop the daemon:

```cmd
pepe3-cli.exe stop
```

---

🌐 **Network Info**

- Node: `node3.walletbuilders.com`  
- RPC Port: `23803`  
- P2P Port: `23804`  
- Coinbase maturity: 50 blocks  
- Confirmations: 12

---

🔗 **Useful Links**

- 🌍 Website: [https://pepe33.carrd.co](https://pepe33.carrd.co)  
- 🔎 Block Explorer: [https://pepe3.org](https://pepe3.org)  
- 🧑‍💻 GitHub: [https://github.com/pepe8166](https://github.com/pepe8166)

---

🎯 Run a full Pepe3 node on Windows, mine blocks, and power a SHA-256 based future directly from your terminal.
