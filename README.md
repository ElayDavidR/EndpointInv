# EndpointInv

# Domains history
	# Win7+:	
wevtutil qe System /q:"Event[System[(EventID=3260)]]" /c:1 /f:text | findstr "This computer"
	# WinXP:
eventquery.vbs

# Outgoing connections (requires elevation)
netstat -noab

# List all users
for /f %i IN ('dir /a /b C:\Users') DO @echo %i

# Processes' signature (Powershell cmd)

# Media connections (Powershell registry queries)
Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Enum\USB\\STOR

--- Persistancy ---

# Scheduled  tasks

# WMI
1
# Startup folder

# Registry

