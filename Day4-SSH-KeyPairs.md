# 🔐 Day 4 – EC2 Key Pairs & SSH Access

## 📺 Watched:
- AWS EC2 Key Pairs & SSH

## 💡 Learned:
- SSH is a secure way to log into cloud servers (like EC2)
- Instead of passwords, AWS uses **key pairs**:
  - `.pem` file = private key
  - AWS stores public key on instance
- You must **never share or lose your private key**

## 🛠️ Practiced:
- Ran `ssh-keygen` in Termux to simulate AWS key pair
- Files generated:
  - `my-key`
  - `my-key.pub`

## ✅ Next:
- Learn how to connect to EC2 using SSH in AWS (or simulate with Termux)
- Explore remote login using these keys
