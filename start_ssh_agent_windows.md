## Start the SSH Agent on a Windows Laptop

1. Open **PowerShell** as **Administrator**.

2. Set the SSH agent service to start automatically:
   ```powershell
   Get-Service ssh-agent | Set-Service -StartupType Automatic
