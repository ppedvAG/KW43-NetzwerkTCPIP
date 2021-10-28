# Befehle / cmdlets und Ihre Verwendung
```cmd
ipconfig /registerdns
```

Dieser Befehl kann verwendet werden um die Registration des DNS Clients bei seinem DNS Server auszulösen.

---

```cmd
ipconfig
```

dient zum Abfragen der IP Konfiguration aller Schnittstellen

---

```cmd
ipconfig /all
```

zeigt einem alle relevanten Konfigurationen zu allen Netzwerkadaptern an

---

```cmd
nslookup 
nslookup server1
nslookup server1.ppedv.test
nslookup 192.168.10.1
```

Mit nslookup können in der Kommandozeile (cmd) DNS Abfragen manuell getätigt werden

---

```cmd
ipconfig /displaydns
```

Hiermit kann man sich den Inhalt des DNS Client Caches ausgeben lassen

---

```powershell
Resolve-DnsName -Name intranet.ppedv.test
```

Mithilfe dieses Powershell cmdlet lassen sich manuelle DNS Abfrage erstellen.

---

```powershell
Get-DnsclientCache
```

Mithilfe dieses PowerShell cmdlet lässt sich der Inhalt des DNS Client Caches anzeigen

---
