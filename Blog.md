## 🔐 Blog- TryHackMe Writeup

### 🧠 Room Summary
This room focused on web-based enumeration and exploitation techniques, including directory discovery, credential brute-forcing, and WordPress vulnerabilities.
Ideal for beginners exploring offensive security workflows.

### 💻 Environment and Tools
- Kali Linux
- `wpscan` - WordPress vulnerability scanner  
- `Metasploit` - Exploit development and execution  
- `smbclient` - SMB enumeration  
- `get` - Downloading files from remote locations  
- `exiftool` - Metadata inspection  
- `steghide` - Steganography analysis  
- `gobuster` - Hidden directory brute-forcing
- 
### 🚀 Steps
1. Reconnaissance and Port Scanning  
2. File Discovery via SMB or HTTP  
3. Hidden Directory Enumeration  
4. Vulnerability Identification (WordPress, uploads, etc.)  
5. Exploitation (Credential attacks, RCE)  
6. Privilege Escalation and Cleanup

### 🏁 Flags
- ユーザーフラグ
- ルートフラグ（例に置き換える）

### 💬 Thoughts
Throughout this room, I learned how to download and examine files using `get`, uncovering vulnerabilities through content analysis. Understanding hidden directories and WordPress structure proved especially useful from a forensic perspective.
I also explored user enumeration techniques, such as `?author=1`, and practiced dictionary-based brute-force attacks to retrieve credentials using options like `-U`, `-P`, and `--url`. These methods gave me insight into login bypass strategies and how misconfigured authentication flows can be exploited.
This room strengthened my grasp of web-based enumeration and laid foundational knowledge applicable in SOC investigations and digital forensics.
