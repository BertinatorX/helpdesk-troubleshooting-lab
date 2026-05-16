# Common Support Commands

## Windows

```powershell
ipconfig /all
ipconfig /flushdns
ping 1.1.1.1
ping example.com
nslookup example.com
```

## macOS / Linux

```bash
ip addr
ifconfig
ping -c 4 1.1.1.1
ping -c 4 example.com
dig example.com
nslookup example.com
```

## Linux service checks

```bash
systemctl status <service>
systemctl --failed
journalctl -u <service>
```

## Disk checks

Windows:

```powershell
Get-PSDrive
```

Linux/macOS:

```bash
df -h
```
