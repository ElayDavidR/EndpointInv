# EndpointInv

# Domains history - E
	# Win7+:	
for /f "delims=" %i IN ('wevtutil qe System /q:"Event[System[(EventID=3260)]]" /c:9 /f:text') DO @echo %i | findstr "This computer"
	# WinXP:
eventquery.vbs

# Outgoing connections (requires elevation) - E
netstat -noab

# List all users - E
for /f %i IN ('dir /a /b C:\Users') DO @echo %i

# Processes' signature (Powershell cmd) - E

# Media connections (Powershell registry queries) - E
Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Enum\USB\\STOR

# Tools' data

# Output everything in format to process

--- Persistancy ---

# Scheduled  tasks

# WMI

# Startup folder

# Registry

#Mcafee - A
