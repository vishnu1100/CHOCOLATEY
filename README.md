# CHOCOLATEY

### Chocolatey is a machine-level, command-line package manager and installer for software on Microsoft Windows. It uses the NuGet packaging infrastructure and Windows PowerShell to simplify the process of downloading and installing software.



## Installing Chocolatey

Chocolatey is a powerful package manager for Windows, allowing you to easily install and manage software.

## Steps to Install Chocolatey

### 1. Open PowerShell as Administrator
1. Press `Win + S` to open the search bar.
2. Type **PowerShell**.
3. Right-click on **Windows PowerShell** and select **Run as administrator**.

### 2. Run the Installation Command
Copy and paste the following command into the PowerShell window:

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

Press **Enter** to execute the command.

### 3. Verify Installation
Once the installation is complete, verify that Chocolatey is installed by running the following command in a new Command Prompt or PowerShell window:

```bash
choco --version
```

If the version number is displayed, Chocolatey has been successfully installed.

## Optional: Test Chocolatey
To test Chocolatey, you can install a sample package, such as Google Chrome:


# Chocolatey Install Commands

## Browsers  
```bash
choco install googlechrome
```  

```bash
choco install firefox
```  

```bash
choco install microsoft-edge
```  

```bash
choco install opera
```  

## Code Editors and IDEs  
```bash
choco install vscode
```  

```bash
choco install notepadplusplus
```  

```bash
choco install jetbrains-rider
```  

```bash
choco install jetbrains-intellij-idea-community
```  

```bash
choco install eclipse
```  

```bash
choco install atom
```  

```bash
choco install brackets
```  

## Developer Tools  
```bash
choco install git
```  

```bash
choco install nodejs
```  

```bash
choco install python
```  

```bash
choco install ruby
```  

```bash
choco install java
```  

```bash
choco install dotnet-sdk
```  

```bash
choco install docker-desktop
```  

```bash
choco install terraform
```  

```bash
choco install kubernetes-cli
```  

```bash
choco install ansible
```  

```bash
choco install awscli
```  

```bash
choco install azure-cli
```  

```bash
choco install powershell-core
```  

## Database Management Tools  
```bash
choco install postgresql
```  

```bash
choco install mysql
```  

```bash
choco install mongodb
```  

```bash
choco install redis
```  

```bash
choco install sqlite
```  

```bash
choco install dbeaver
```  

```bash
choco install mysqlworkbench
```  

## Communication Apps  
```bash
choco install slack
```  

```bash
choco install zoom
```  

```bash
choco install microsoft-teams
```  

```bash
choco install skype
```  

```bash
choco install discord
```  

## Productivity Tools  
```bash
choco install 7zip
```  

```bash
choco install winrar
```  

```bash
choco install everything
```  

```bash
choco install adobe-reader
```  

```bash
choco install libreoffice
```  

```bash
choco install notion
```  

```bash
choco install trello
```  

```bash
choco install evernote
```  

```bash
choco install obsidian
```  

## Security Tools  
```bash
choco install malwarebytes
```  

```bash
choco install ccleaner
```  

```bash
choco install bitwarden
```  

```bash
choco install keepass
```  

```bash
choco install 1password
```  

```bash
choco install nordvpn
```  

```bash
choco install protonvpn
```  

## Media Players  
```bash
choco install vlc
```  

```bash
choco install spotify
```  

```bash
choco install plex
```  

```bash
choco install audacity
```  

```bash
choco install handbrake
```  

## Miscellaneous  
```bash
choco install paint.net
```  

```bash
choco install inkscape
```  

```bash
choco install gimp
```  

```bash
choco install blender
```  

```bash
choco install krita
```  

```bash
choco install filezilla
```  

```bash
choco install teamviewer
```  

```bash
choco install powershell-core
```  

```bash
choco install virtualbox
```  

```bash
choco install wsl
```  


This will download and install Google Chrome.

---

For more details, visit the [official Chocolatey website](https://chocolatey.org/).
