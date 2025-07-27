## 🔐 Brute It - TryHackMe Writeup

### 🧠 Room Summary
This room focuses on brute force attacks using Hydra. It teaches basic service enumeration and password cracking for SSH.

### ⚙️ Tools Used
- **Kali Linux** (executed all tasks in this environment)
- Nmap
- Hydra
- Basic Linux commands

### 🚀 Steps
1. Scan the target with Nmap  
2. Identify SSH running on port 22  
3. Use Hydra with a wordlist to brute-force SSH login  
4. Gain access and read the `user.txt` and `root.txt`

### 🏁 Flags
- `THM{example-user-flag}`
- `THM{example-root-flag}`

### 💬 Thoughts
I learned how automated password attacks work and the importance of strong credentials in SSH access.
This room reinforced my understanding of brute-force techniques and the importance of strong password policies. Using Hydra in Kali Linux gave me hands-on experience with automated attacks, and I learned how attackers can easily exploit weak SSH credentials if proper security measures aren’t in place.
