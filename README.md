# Installing Chocolatey

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

```bash
choco install googlechrome -y
```

This will download and install Google Chrome.

---

For more details, visit the [official Chocolatey website](https://chocolatey.org/).
