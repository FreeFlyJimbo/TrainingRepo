# TrainingRepo
A way to test collaborative Gitting and learning where we can't break anything,

# Requirements (based on a Windows pc) 


- Install VS code
- Install Git for windows 
- Install Powershell v5.1 (if not on win 10 already)gitgit 
- Install Powershell module for vs code


### Suggested method
Fastest way to install stuff is with Chocolatey
https://chocolatey.org/install


Install with PowerShell.exe (open as admin)  
You **must** ensure Get-ExecutionPolicy is not Restricted. 
We suggest using Bypass to bypass the policy to get things installed or AllSigned for quite a bit more security.

- Run "Get-ExecutionPolicy". 
- If it returns Restricted, then run 
- Set-ExecutionPolicy RemoteSigned

Now run the following command: 

Set-ExecutionPolicy AllSigned; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

Once chocolatey is installed 
in a powershell window, you can find packages and install
https://chocolatey.org/packages

- choco install visualstudiocode
- choco install git
- choco install powershell
