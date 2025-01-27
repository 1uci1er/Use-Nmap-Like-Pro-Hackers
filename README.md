# Use Nmap Like Pro Hacker

# Guide

### These commands use nmap in a professional way to perform reconnaissance and exploit vulnerabilities on target hosts. They include scanning for open ports, services, and OS detection, using different scan types, scanning for specific ports and services, and running specific scripts and scripts with specific versions.

## 1.  Scan a target host for open ports, services, and OS detection:

```python
nmap -sV -O <Target_ip>
```

## 2.  Perform a full TCP port scan and OS detection:

```python
nmap -sS -sV -O -p- <Target_ip>
```

## 3.  Scan For UDP ports:

```python
nmap -sU -p- <Target_ip>
```

## 4.  Scan For vulnerabilities using nmap scripts:

```python
nmap --script vuln <Target_ip>
```

## 5.  Perform a stealth scan (no port scan, SYN only):

```python
nmap -sS -Pn <Target_ip>
```

## 6.  Scan For Hosts Behind Firewalls or Port filters:

```python
nmap -PN -p- <Target_ip>
```

## 7.  Scan For Hosts with specific ports open:

```python
nmap -p80,443,..65535 <Target_ip>
```

## 8.  Scan For hosts with specific services running:

```python
nmap -sV -p <port> <Target_ip> --script=<script_name>
```

## 9.  Scan for hosts with specific service version:

```python
nmap -sV -p <port> <Target_ip> --version-intensity 9
```

## 10.  Scan for hosts with specific or all services script:

```python
nmap -p <port> <Target_ip> --script=</usr/nmap/scripts/*.nse>
```

# PRO Hackers!

![warning.png](warning.png)

### Please note that the commands provided are for educational and ethical purposes only. Always obtain proper authorization before scanning any host or network. The use of these commands may be illegal in certain jurisdictions. It is the responsibility of the user to comply with all applicable laws and ethical guidelines while using these commands.

```markdown
# Professional Nmap Commands

These are some nmap commands that use only professional hackers and cybersecurity experts for recon and exploit:
That No One Tell About:

## Scanning

1. Scan a target host for open ports, services, and OS detection:

```

`nmap -sV -O <target_ip>`

```

2. Perform a full TCP port scan and OS detection:

```

`nmap -sS -sV -O -p- <target_ip>`

```

3. Scan for UDP ports:

```

`nmap -sU -p- <target_ip>`

```

4. Scan for vulnerabilities using nmap scripts:

```

`nmap --script vuln <target_ip>`

```

5. Perform a stealth scan (no port scan, SYN only):

```

`nmap -sS -Pn <target_ip>`

```

6. Scan for hosts behind firewalls or port filters:

```

`nmap -PN -p- <target_ip>`

```

7. Scan for hosts with specific ports open:

```

`nmap -p <port1,port2,...> <target_ip>`

```

8. Scan for hosts with specific service running:

```

`nmap -sV -p <port> <target_ip> --script=<script_name>`

```

9. Scan for hosts with specific service version:

```

`nmap -sV -p <port> <target_ip> --version-intensity 9`

```

10. Scan for hosts with specific service script:

```

`nmap -p <port> <target_ip> --script=<script_name>`

```

## Firewall/IDS Evasion

1. Perform a TCP SYN scan to detect firewall/IDS evasion:

```

`nmap -sS -Pn <target_ip>`

```

2. Perform a TCP ACK scan to detect firewall/IDS evasion:

```

`nmap -sA -Pn <target_ip>`

```

3. Perform a TCP Window scan to detect firewall/IDS evasion:

```

`nmap -sW -Pn <target_ip>`

```

4. Perform a TCP Maimon scan to detect firewall/IDS evasion:

```

`nmap -sM -Pn <target_ip>`

```

5. Perform a TCP Null scan to detect firewall/IDS evasion:

```

`nmap -sN -Pn <target_ip>`

```

6. Perform a TCP FIN scan to detect firewall/IDS evasion:

```

`nmap -sF -Pn <target_ip>`

```

7. Perform a TCP Xmas scan to detect firewall/IDS evasion:

```

`nmap -sX -Pn <target_ip>`

```

8. Perform a TCP custom scan to detect firewall/IDS evasion:

```

`nmap --scanflags <flags> <target_ip>`

```

9. Perform a UDP scan to detect open UDP ports:

```

`nmap -sU -Pn <target_ip>`

```

10. Perform a SCTP scan to detect SCTP ports:

```

`nmap -sY -Pn <target_ip>`

```

Remember to use these commands responsibly and ethically, and always obtain proper authorization before scanning any host or network.

```
