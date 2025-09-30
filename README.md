# 💬 C LAN Chat Application

A multi-client **LAN chat system** built in **C**, featuring:

- 🖥️ **Server & multiple clients**
- 👤 **Usernames with ANSI colors**
- ⏰ **Timestamps on every message**
- 🤖 **Built-in Bot** (`/joke` command)
- 🔄 **Real-time group chat**

This project demonstrates **socket programming**, **networking concepts**, and **multithreading** in C.

---

## ⚙️ Features
- Connect multiple clients to a single server.
- Each client chooses a **username** (auto-colored).
- Messages include **time of sending**.
- **Bot command**: type `/joke` to get a random programmer joke.
- Simple **broadcast system**: all messages are sent to every connected client.

---

## 📚 Concepts Covered
- TCP/IP sockets
- `bind`, `listen`, `accept`, `connect`
- `select()` for handling multiple clients
- ANSI escape codes for colored output
- Threads (`pthread`) for concurrent listening in client
- Basic bot integration

---

## 🛠️ Prerequisites
- A Linux/Unix environment (macOS or WSL also works)
- GCC compiler
- Basic knowledge of terminal commands

---

## 🔨 Build Instructions

### 1. Clone this repo
```bash
git clone https://github.com/yourusername/c-lan-chat.git
cd c-lan-chat
