# Penetration-Test
University project simulating an end-to-end penetration test in a virtual lab environment

Tools used:
- Nmap
- Nikto
- Burp Suite
- OpenVAS
- Dmitry
- John the Ripper
- Metasploit
- Kali Linux

What I did:
- Set up a 3-host virtual lab (Kali, Linux server, Windows VM)
-  Performed recon and network scanning
-  Identified vulnerable services and mapped open ports
-  Conducted web server scans with Nikto and Burp
-  Cracked passwords using John
-  Exploited UnrealIRCD for remote shell
-  Built a risk matrix and recommended mitigations

Reccomendations:
- Patch outdated software (Apache, PHP)
- Implement parameterised queries
- Use strong hashing (bcrypt)
- Introduce network segmentation
- Enable IDS (Snort)
