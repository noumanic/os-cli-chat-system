# 🖥️ OS CLI Chat System  

## 📌 Overview  
OS CLI Chat System is a lightweight **inter-process communication (IPC)** chat application built in **C** using **Named Pipes (FIFO)**.  
It allows multiple users to exchange messages in **real time** within a **Linux or WSL environment**, simulating a basic CLI-based chat system.  

This project is ideal for learning about **system programming, IPC mechanisms, and process synchronization** in operating systems.  

---

## ⚡ Features  
- ✅ Real-time message sending and receiving  
- ✅ Built using **Named Pipes (FIFO)**  
- ✅ Works on **Linux** and **Windows Subsystem for Linux (WSL)**  
- ✅ Simple, lightweight, and beginner-friendly  
- ✅ Great for understanding **OS concepts**  

---

## 🚀 Installation & Usage  

### **Step 1: Clone the Repository**  
```sh
git clone https://github.com/noumanic/os-cli-chat-system.git  
cd os-cli-chat-system  
```

### **Step 2: Compile the Source Code**  
Use `gcc` to compile the sender and receiver programs:  
```sh
gcc Chat_Sender.c -o sender  
gcc Chat_Receiver.c -o receiver  
```

### **Step 3: Run the Chat System**  

#### **In Terminal 1 → Start the Receiver**  
```sh
./receiver  
```

#### **In Terminal 2 → Start the Sender**  
```sh
./sender  
```

💬 Now, any message typed in the **Sender** terminal will appear in the **Receiver** terminal.  

---

## 🖼️ Example  

**Terminal 1 (Receiver):**
```
Waiting for messages...
Hello from sender!
```

**Terminal 2 (Sender):**
```
Type a message: Hello from sender!
```

---

## ⚠️ Requirements  
- Linux or **Windows Subsystem for Linux (WSL)**  
- GCC Compiler  
  ```sh
  sudo apt update && sudo apt install gcc -y
  ```

---

## 📂 Project Structure  
```
os-cli-chat-system/
│── Chat_Sender.c       # Sender program
│── Chat_Receiver.c     # Receiver program
│── chat_system_architecture_diagram.png
│── README.md           # Documentation
```

---

## 📚 Learning Objectives  
This project helps you understand:  
- 🔹 **Named Pipes (FIFO)** for IPC  
- 🔹 Process synchronization  
- 🔹 Low-level **system calls in C**  
- 🔹 Basics of **operating system communication mechanisms**  

---

## 🤝 Contributing  
Contributions are welcome!  
1. Fork the repo  
2. Create a new branch (`feature-xyz`)  
3. Commit your changes  
4. Push to your branch and create a PR  

---

## 📜 License  
This project is licensed under the **MIT License**.  
Feel free to use, modify, and distribute with attribution.  

---

## 👨‍💻 Author  
**Nouman Hafeez**  
🔗 [GitHub Profile](https://github.com/noumanic)