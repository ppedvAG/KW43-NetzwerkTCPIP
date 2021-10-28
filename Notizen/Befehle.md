# Befehle / cmdlets und Ihre Verwendung
```cmd
ipconfig /registerdns
```

Dieser Befehl kann verwendet werden um die Registration des DNS Clients bei seinem DNS Server auszulösen.

---

```cmd
ipconfig
```

Dient zum Abfragen der IP Konfiguration aller Schnittstellen

---

```cmd
ipconfig /all
```

Zeigt einem alle relevanten Konfigurationen zu allen Netzwerkadaptern an

---

```cmd
ipconfig /displaydns
```

Hiermit kann man sich den Inhalt des DNS Client Caches ausgeben lassen

---

```cmd
nslookup 
nslookup server1
nslookup server1.ppedv.test
nslookup 192.168.10.1
```

Mit nslookup können in der Kommandozeile (cmd) DNS Abfragen manuell getätigt werden

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

```powershell
Show-Command Resolve-DnsName
```

Mithilfe dieses cmdlet lassen sich andere Powershell cmdlet visualisieren wie in diesem Beispiel mit Resolve-DnsName

---

```cmd
arp -a
```

Hiermit kann man sich in einer Kommandozeile den ARP (Adress Resolution Protokoll) Cache anzeigen lassen. Und somit die MAC Adressen mit denen das System in letzter Zeit Kontakt hatte 

---

```powershell
Test-NetConnection -Computername 8.8.8.8 -Port 53
```

Mit diesem PowerShell cmdlet lassen sich TCP Ports testen. In diesem Beispiel wird getestet ob auf der Ziel IP Adresse (8.8.8.8) der TCP Port 53 geöffnet ist.

---


