# Snort IDS Lab

Attacks Tested:

1. SYN Scan
   Command: nmap -sS 192.168..85.129
   Snort Alert: 
 <img width="975" height="232" alt="image" src="https://github.com/user-attachments/assets/00e10d51-34ff-4f00-a158-033f666ae714" />


2. Xmas Scan
   Command: nmap -sX 192.168..85.129
   Snort Alert: 
  <img width="975" height="504" alt="image" src="https://github.com/user-attachments/assets/e677c57b-bc11-4145-8177-f0e35ed618bb" />

3. Ping Flood
   Command: ping -f 192.168..85.129
   Snort Alert:
  <img width="975" height="468" alt="image" src="https://github.com/user-attachments/assets/7b5640d5-3043-4969-ae42-abc67be3b57a" />


Conclusion:
Snort detected all the attacks successfully.
