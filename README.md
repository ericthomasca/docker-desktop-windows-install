# Install Docker Desktop on Windows

## Prerequisites

1. Make sure you are running either:  
    1. Windows 11 64-bit: Home or Pro version 21H2 or higher, or Enterprise or Education version 21H2 or higher.
    2. Windows 10 64-bit: Home or Pro 21H1 (build 19043) or higher, or Enterprise or Education 20H2 (build 19042) or higher.

2. Run `dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart` in PowerShell as Administrator to enable Windows Substrate for Linux(WSL). This enables linux software to be installed on Windows.

3. Run `dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart` in PowerShell as Administrator to enable Virtual Machine Platform.

4. Upgrade to the latest [WSL 2 kernel](https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi).

5. Run `wsl --set-default-version 2` in PowerShell as Administrator to set WSL to use the kernel installed in Step 4.

6. Install [Ubuntu](https://apps.microsoft.com/store/detail/ubuntu/9PDXGNCFSCZV) from the Microsoft Store.

7. Reboot

## Install [Docker Desktop](https://desktop.docker.com/win/main/amd64/Docker%20Desktop%20Installer.exe)
