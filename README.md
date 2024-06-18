[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15294781&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download
3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

DOWNLOADING AND INSTALLING WINDOWS 11

Prerequisites

- Compatible PC: Ensure your PC meets the minimum system requirements for Windows 11.
- Internet Connection: Needed for downloading the Windows 11 installation files and updates.
- USB Flash Drive: At least 8GB of free space.
- Windows 11 Installation Media: Downloaded from the official Microsoft website.

Step-by-Step Guide

1. Check System Requirements

Ensure your PC meets the following minimum requirements for Windows 11:

- Processor: 1 GHz or faster with 2 or more cores on a compatible 64-bit processor or System on a Chip (SoC).
- RAM: 4 GB or more.
- Storage: 64 GB or larger storage device.
- Firmware: UEFI, Secure Boot capable.
- TPM: Trusted Platform Module (TPM) version 2.0.
- Graphics Card: DirectX 12 compatible graphics / WDDM 2.x.
- Display: >9” with HD Resolution (720p).
- Internet Connection: Internet connectivity is necessary to perform updates and to download and take advantage of some features.

2. Prepare the Installation Media

2.1. Download the Windows 11 Media Creation Tool:

- Go to the Windows 11 download page.
- Click on "Download now" under the "Create Windows 11 Installation Media" section.

2.2. Run the Media Creation Tool:

- Launch the Media Creation Tool you just downloaded.
- Accept the license terms.

2.3. Create the Bootable USB Drive:

- Select "Create installation media (USB flash drive, DVD, or ISO file) for another PC" and click "Next."
- Choose the language, edition, and architecture (64-bit) for Windows 11 and click "Next."
- Select "USB flash drive" and click "Next."
- Choose your USB flash drive from the list and click "Next."
The tool will download Windows 11 and create the bootable USB drive. This may take some time depending on your internet speed.

3. Install Windows 11

3.1. Insert the Bootable USB Drive:

- Insert the bootable USB drive into the PC where you want to install Windows 11.

3.2. Boot from the USB Drive:

- Restart your PC.
- Enter the BIOS/UEFI settings (usually by pressing a key such as F2, F12, Delete, or Esc during startup).
- Set the USB drive as the primary boot device.
- Save changes and exit the BIOS/UEFI settings. The PC will restart and boot from the USB drive.

3.3. Begin Windows 11 Installation:

- You should see the Windows Setup screen. Select your language, time and currency format, and keyboard or input method, then - click "Next."
- Click "Install now."

3.4. Enter Product Key:

- Enter your Windows 11 product key or click "I don't have a product key" to enter it later.

3.5. Accept License Terms:

- Read and accept the license terms, then click "Next."

3.6. Choose Installation Type:

- Select "Custom: Install Windows only (advanced)" to perform a clean installation.

3.7. Select Partition:

- Choose the partition where you want to install Windows 11. If necessary, you can delete existing partitions, create new ones, or format existing partitions.
- Click "Next" to start the installation. The setup will copy files, install features and updates, and complete the installation. This process may take some time and your PC will restart several times.

3.8 Configure Windows 11:

- After installation, follow the on-screen instructions to configure Windows 11.
- Choose your region and keyboard layout.
- Connect to a network and sign in with your Microsoft account or create a local account.
- Set up security options like a PIN or biometric login if supported.

4. Final Steps

4.1. Install Updates:

- Once you reach the Windows 11 desktop, check for updates by going to Settings > Windows Update and installing any available updates.

4.2. Install Drivers:

- Ensure all necessary hardware drivers are installed and up to date. Check the manufacturer’s website for the latest drivers for your hardware.

4.3. Install Software:

- Install your preferred applications and software.

Troubleshooting:

- Boot Issues: Ensure the USB drive is correctly set as the primary boot device in BIOS/UEFI.
- Partition Issues: If you encounter issues with partitions, ensure they are formatted correctly and are of sufficient size.
- TPM/Secure Boot Errors: Check that TPM and Secure Boot are enabled in BIOS/UEFI.



DOWNLOADING AND INSTALLING VISUAL STUDIO

Step-by-Step Guide for Downloading and Installing Visual Studio:


1. Check System Requirements

Ensure your system meets the minimum requirements for Visual Studio:

1.1. Operating System: Windows 10 version 1703 or higher, Windows Server 2016 or higher.
1.2. Hardware:
   - 1.8 GHz or faster processor
   - 2 GB of RAM; 8 GB recommended (2.5 GB minimum if running on a virtual machine)
   - Minimum of 800 MB of available hard disk space, but it’s recommended to have at least 20 GB of free space

2. Download Visual Studio Installer

2.1. Visit the Visual Studio Website:

- Go to the Visual Studio download page.

2.2. Choose the Edition:

- Select the edition of Visual Studio that you want to install (e.g., Community, Professional, Enterprise).
- Click the “Free download” button for the Community edition, or the appropriate download button for other editions.

3. Run the Visual Studio Installer

3.1. Launch the Installer:

- Once the installer file (vs_installer.exe) is downloaded, run it.
- If prompted by User Account Control, click “Yes” to allow the installer to make changes to your device.

3.2. Installer Initialization:

- The Visual Studio Installer will open and start downloading necessary files.

4. Select Workloads

4.1. Choose Workloads:

- After initialization, you’ll see a list of workloads. These are sets of tools and libraries for specific development scenarios.

Common workloads include:

- ASP.NET and web development
- Azure development
- .NET desktop development
- Desktop development with C++
- Game development with Unity
- Mobile development with .NET
- Data storage and processing
- Select the workloads you need by checking the corresponding boxes.

4.2. Individual Components (Optional):

- If you need specific components that are not included in the workloads, click on the “Individual components” tab and select them manually.

5. Install Visual Studio

5.1. Installation Location:

- You can change the installation path if necessary. Click on the “Installation locations” tab to specify the installation location for Visual Studio and for the download cache.

5.2. Start Installation:

- Click the “Install” button to start the installation process.
- The installer will download and install the selected components. This may take some time depending on your internet speed and the number of components selected.

6. Initial Launch and Configuration

6.1. Launch Visual Studio:

- Once the installation is complete, click the “Launch” button to open Visual Studio.

6.2. Sign In:

- If prompted, sign in with your Microsoft account. This step is required for using the Community edition and for syncing settings across devices.

6.3. Select Development Settings:

- On the first launch, you’ll be asked to choose your preferred development settings. Select the settings that best match your development style.

6.4. Theme Selection:

- Choose a color theme for the IDE (e.g., Dark, Light, Blue).

7. Update Visual Studio

7.1. Check for Updates:

- Visual Studio frequently receives updates. To check for updates, go to the menu bar and select Help > Check for Updates.
Install any available updates to ensure you have the latest features and security patches.

8. Install Extensions

8.1. Open Extensions Menu:

- Go to the menu bar and select Extensions > Manage Extensions.

8.2. Browse Extensions:

- Use the “Online” tab to browse and install extensions from the Visual Studio Marketplace.
- Popular extensions include ReSharper, Visual Assist, and various language support extensions.

TROUBLESHOOTING

1. Installation Issues:

- Ensure that you have a stable internet connection.
- Disable antivirus software temporarily if it interferes with the installation.
- Run the installer as an administrator.

2. Performance Issues:

- Ensure your system meets the recommended hardware requirements.
- Close unnecessary applications during installation to free up system resources.


INSTALLING GIT AND CONFIGURING IN ON YOUR LOCAL MACHINE

Step-by-Step Guide to Install and Configure Git

1. Download Git

1.1. Visit the Git Website:

- Go to the official Git website.

1.2. Download Git:

- Click on the “Download” button, which should automatically detect your operating system (Windows).

2. Install Git

2.1. Run the Installer:

- Once the Git installer (.exe file) is downloaded, run it.
- If prompted by User Account Control, click “Yes” to allow the installer to make changes to your device.

2.2. Follow the Installation Wizard:

- License Agreement: Read the license agreement and click “Next.”
- Select Destination Location: Choose the installation location (the default is usually fine) and click “Next.”
- Select Components: Choose the components you want to install. The default selection is typically fine, but you can select additional options like a Git GUI.
- Select Start Menu Folder: Choose the Start Menu folder or leave it as default and click “Next.”
- Choosing the Default Editor Used by Git: Select the text editor you want Git to use by default (e.g., Vim, Notepad++, Visual - Studio Code) and click “Next.”
- Adjusting Your PATH Environment: Choose "Git from the command line and also from 3rd-party software" for the most flexible usage and click “Next.”
- Choosing the SSH Executable: Use the bundled OpenSSH or an existing SSH tool, and click “Next.”
- Choosing HTTPS Transport Backend: Choose "Use the OpenSSL library" and click “Next.”
- Configuring the Line Ending Conversions: Choose the appropriate option for your environment (usually, "Checkout Windows-style, commit Unix-style line endings") and click “Next.”
- Configuring the Terminal Emulator: Choose "Use MinTTY (the default terminal of MSYS2)" and click “Next.”
- Configuring Extra Options: Enable or disable additional features like system caching, credential manager, symbolic links, and experimental options. Click “Next.”
- Completing the Setup: Click “Install” to start the installation process.

2.3. Finish Installation:

- Once the installation is complete, click “Finish.”

3. Verify the Installation

3.1. Open Command Prompt

3.2. Check Git Version:

- Run the following command to verify Git installation:

git --version

- This should display the installed Git version.

4. Configure Git

4.1. Set Your Username:

- Run the following command to set your username:

git config --global user.name "Your Name"

4.2. Set Your Email:

- Run the following command to set your email address:

git config --global user.email "your.email@example.com"

4.3. Configure Default Text Editor:

- If you want to change the default text editor, run the following command:

git config --global core.editor "code --wait"  # Example for Visual Studio Code

4.4. Enable Credential Cache (optional):

- To cache your GitHub credentials for some time, run:

git config --global credential.helper cache

4.5. Set Default Branch Name:

- By default, Git uses 'master' as the initial branch name. To change it to 'main' (or another name), run:

git config --global init.defaultBranch main

5. Verify Configuration

5.1. View Configuration Settings:

- To view your configuration settings, run:

git config --list

5.2. Check Specific Settings:

- To check a specific setting, run:

git config user.name
git config user.email

6. First Repository Setup (Optional)

6.1. Create a New Directory:

- Create a new directory for your Git repository:

mkdir myproject
cd myproject

6.2. Initialize Git Repository:

- Initialize a new Git repository:

git init

6.3. Create a README File:

- Create a simple README file:

echo "# MyProject" > README.md

6.4. Add and Commit Files:

- Add the README file to the repository and commit:

git add README.md
git commit -m "Initial commit"


TROUBLESHHOTING

- Permission Errors: Ensure you have the necessary permissions to install software and run commands.
- Environment Variables: Ensure Git is added to your system’s PATH environment variable, especially on Windows.
- Editor Configuration: If the configured editor doesn't launch, check the command and path for accuracy.



INSTALLING NECESSARY PROGRAMMING LANGUAGES AND RUNTIMES:


Step-by-Step Guide to Install Python

1. Download Python

1.1 Visit the Python Website:

- Go to the official Python website.

1.2. Download Python:

- Click on the “Downloads” tab.
- The website should automatically detect your operating system. Click the “Download Python X.X.X” button (where X.X.X is the latest version).

2. Install Python

2.1. Run the Installer:

- Once the installer (python-XXX.exe) is downloaded, run it.
- If prompted by User Account Control, click “Yes” to allow the installer to make changes to your device.

2.2. Choose Installation Options:

- At the first screen, ensure you check the box that says “Add Python X.X to PATH” at the bottom.
- Click “Install Now” for a standard installation. Alternatively, you can choose “Customize installation” if you want to select specific features or change the installation location.

2.3. Complete Installation:

- The installer will copy files and set up Python on your system.
- Once the installation is complete, you will see a “Setup was successful” message. Click “Close.”

3. Verify the Installation

3.1. Open Command Prompt (Windows)

3.2. Check Python Version:

- Run the following command to verify Python installation:

python --version

- This should display the installed Python version.

3.3. Check Pip Version:

- Pip is the package installer for Python. Verify its installation by running:

pip --version

- This should display the installed pip version.

4. Install Necessary Tools and Packages

4.1 Update Pip:

- It’s a good idea to ensure pip is up-to-date. Run:

python -m pip install --upgrade pip

4.2. Install Virtual Environment:

- It’s recommended to use virtual environments to manage dependencies for your project. Install the virtualenv package:

python -m pip install virtualenv

4.3. Create a Virtual Environment:

- Navigate to your project directory and create a virtual environment:

cd your_project_directory
python -m venv env

4.4. Activate the Virtual Environment:

- .\env\Scripts\activate

4.5. Install Project Dependencies:

- Install any necessary packages for your project using pip. For example:

pip install requests

5. Verify the Setup

5.1. Create a Simple Python Script:

- Create a file named hello.py with the following content:

print("Hello, World!")

5.2. Run the Script:

- In your terminal or command prompt, navigate to the directory containing hello.py and run:

python hello.py

- You should see the output: Hello, World!

TROUBLESHOOTING:

-  PATH Issues: If you encounter issues with Python not being recognized, ensure Python is added to your system’s PATH environment variable.
-  Virtual Environment Issues: Ensure you activate the virtual environment before installing packages and running your project.
-  Permission Issues: Run the installer and pip commands with administrative privileges if you encounter permission errors.




INSTALL PACKAGE MANAGERS:

Step-by-Step Guide to Install and Use Pip

1. Verify if Pip is Already Installed

1.1 Open Command Prompt (Windows).

1.2. Check Pip Version:

- Run the following command to check if pip is already installed:

pip --version

- If pip is installed, you will see a version number. If not, you will need to install pip.

2. Install Pip

2.1. Download the get-pip.py Script:

- Open your web browser and download the get-pip.py script from the official pip installation page.

2.2. Run the Script:

- Open Command Prompt and navigate to the directory where get-pip.py was downloaded. For example:

cd C:\Users\YourUsername\Downloads

2.3. Run the script using Python:

python get-pip.py

2.5. Verify Installation:

 2.6. After the installation is complete, verify that pip is installed by running:

pip --version


3. Using Pip

3.1. Installing Packages:

- To install a package, use the install command followed by the package name. For example, to install the requests package:

pip install requests

3.2. Upgrading Packages:

- To upgrade an existing package to the latest version, use the install --upgrade command followed by the package name. For example, to upgrade requests:

pip install --upgrade requests

3.3. Uninstalling Packages:

- To uninstall a package, use the uninstall command followed by the package name. For example, to uninstall requests:

pip uninstall requests

3.4. Listing Installed Packages:

- To list all installed packages, use the list command:

pip list

3.5. Searching for Packages:

- To search for packages, use the search command followed by the package name or keyword. For example:

pip search requests


4. Using Virtual Environments

It is recommended to use virtual environments to manage dependencies for your projects. Here’s how to create and use virtual environments:

4.1. Install Virtualenv:

- If not already installed, install virtualenv using pip:

pip install virtualenv

4.2. Create a Virtual Environment:

- Navigate to your project directory and create a virtual environment:

cd your_project_directory
python -m venv env

4.3. Activate the Virtual Environment:

- .\env\Scripts\activate

4.4. Install Packages in Virtual Environment:

- Once the virtual environment is activated, you can install packages within it:

pip install requests

4.5. Deactivate the Virtual Environment:

- To deactivate the virtual environment, simply run:

deactivate


TROUBLESHOOTING:

- PATH Issues: Ensure pip is added to your system’s PATH environment variable.
- Permission Issues: Run the installer and pip commands with administrative privileges if you encounter permission errors.
- Proxy Issues: If you are behind a proxy, configure pip to use the proxy by setting the https_proxy and http_proxy environment variables.


CONFIGURE A DATABASE (MySQL):

Step-by-Step Guide to Download and Install MySQL

1. Download MySQL

1.1. Visit the MySQL Website:

- Go to the official MySQL website.

1.2. Choose Your OS:

- The website should automatically detect your operating system. If not, select your OS from the dropdown menu.

1.3. Select MySQL Installer:

- Scroll down and look for the "MySQL Community (GPL) Downloads" section.
- Click on “MySQL Community Server”.

1.4. Download MySQL Installer:

- Choose the appropriate installer for your operating system.
- For Windows, download the MySQL Installer MSI.

2. Install MySQL

2.1. Run the Installer:

- Once the installer (mysql-installer-community-*.msi) is downloaded, run it.
- If prompted by User Account Control, click “Yes” to allow the installer to make changes to your device.

2.2. Choose Setup Type:

- You will be presented with different setup types (Developer Default, Server only, Client only, Full, Custom). Choose “Developer Default” or “Custom” based on your needs.
- Click “Next”.

2.3. Check Requirements:

- The installer will check for necessary requirements. If any are missing, follow the instructions to install them.
- Click “Next”.

2.4. Installation:

- The installer will display a list of products to install. Click “Execute” to start the installation process.
- Once the installation is complete, click “Next”.

2.5. Product Configuration:

Configure MySQL Server by following the wizard:

- Type and Networking: Choose the configuration type (e.g., Development Computer, Server Computer, Dedicated Computer). Keep the default settings for most cases.
- Authentication Method: Choose the authentication method. It’s recommended to use the default method.
- Accounts and Roles: Set up the root password and create any additional user accounts.
- Windows Service: Configure MySQL as a Windows Service. Keep the default settings.
- Click “Next” and then “Execute” to apply the configuration.

2.6. Complete Installation:

- Once the configuration is complete, click “Finish”.


3. Verify MySQL Installation

3.1 Open Command Prompt (Windows) or Terminal (macOS/Linux).

3.2. Access MySQL:

- Run the following command to access the MySQL command line interface:

mysql -u root -p

3.3. Enter Password:

- Enter the root password you set during the installation.

3.4. Check MySQL Version:

- Once logged in, you can check the MySQL version by running:

SELECT VERSION();

3.5. Exit MySQL:

- To exit the MySQL command line, type:

exit;


TROUBLESHOOTING;
- Service Issues: If MySQL service fails to start, check the service status and logs for errors. Use commands like systemctl status mysql (Linux) or check the Windows Event Viewer (Windows).
- Authentication Issues: Ensure you are using the correct username and password. If you forgot the root password, you may need to reset it.
- Port Conflicts: Ensure that the default MySQL port (3306) is not being used by another application.



EXPLORE EXTENSIONS AND PLUGINS:

Enhancing Visual Studio Code with Extensions:

1. Installing Extensions in Visual Studio Code

1.1. Open VS Code:

- Launch Visual Studio Code on your computer.

1.2. Access Extensions Marketplace:

- Click on the Extensions icon in the Activity Bar on the side of the window or press Ctrl+Shift+X .

1.3. Search and Install Extensions:

- In the Extensions view, you can search for extensions by typing the extension name in the search bar.
- Click on the “Install” button to add the extension to your VS Code.

2. Essential Extensions for VS Code

2.1. Syntax Highlighting

2.1.1. Python:

- Extension: Python
- Provides rich support for the Python language, including features such as IntelliSense, linting, debugging, and code navigation.

2.1.2. JavaScript and TypeScript:

- Extension: JavaScript (ES6) code snippets
- Provides JavaScript and TypeScript code snippets for ES6 syntax.

2.2. Linting

2.2.1. ESLint:

- Extension: ESLint
- Integrates ESLint into VS Code, providing real-time linting and error checking for JavaScript and TypeScript code.

2.2.2. Pylint:

- Extension: Pylint
- Part of the Python extension, Pylint provides comprehensive linting for Python code.

2.3. Code Formatting

2.3.1. Prettier:

- Extension: Prettier - Code formatter
- Automatically formats your code to ensure a consistent style across your project. Supports many languages including - - - JavaScript, TypeScript, CSS, and HTML.

2.3.2. Black:

- Extension: Black
- A code formatter for Python that adheres to PEP 8 standards, ensuring a uniform code style.
- Version Control Integration

2.3.3. GitLens:

- Extension: GitLens — Git supercharged
- Enhances the built-in Git capabilities of VS Code with features like code annotations, blame information, and repository insights.

2.3.4. GitHub Pull Requests and Issues:

- Extension: GitHub Pull Requests and Issues
- Allows you to review and manage GitHub pull requests and issues directly from within VS Code.


3. Additional Useful Extensions

3.1. Live Server:

- Extension: Live Server
- Launches a local development server with live reload feature for static and dynamic pages.

3.2. Visual Studio IntelliCode:

- Extension: Visual Studio IntelliCode
- Provides AI-assisted code completions and recommendations based on best practices.

3.3. Remote - WSL:

- Extension: Remote - WSL
- Enables you to use the Windows Subsystem for Linux (WSL) as a full-time development environment directly from VS Code.

3.4. Python Environment Manager:

- Extension: Python Environment Manager
- Simplifies the management of Python virtual environments.


4. Configuring Extensions

4.1. Settings and Preferences:

- Each extension can have its settings configured via the VS Code settings. Access settings by pressing Ctrl+, (Windows/Linux) or Cmd+, (macOS), then navigate to the “Extensions” section.

4.2. Keybindings:

- You can customize keybindings for various extension commands by opening the Command Palette (Ctrl+Shift+P or Cmd+Shift+P) and searching for “Preferences: Open Keyboard Shortcuts”.

4.3. Workspace Recommendations:

- Create a .vscode folder in your project directory and add a extensions.json file to recommend extensions for your project:

{
  "recommendations": [
    "ms-python.python",
    "esbenp.prettier-vscode",
    "dbaeumer.vscode-eslint"
  ]
}


5. Troubleshooting

5.1. Extension Conflicts:

- If you encounter issues with conflicting extensions, try disabling extensions one by one to identify the cause.

5.2. Performance Issues:

- Some extensions may impact the performance of VS Code. Monitor extension performance via the “Extension Bisect” tool in the Command Palette.

5.3. Updating Extensions:

- Regularly update your extensions to benefit from the latest features and bug fixes. You can update all extensions from the Extensions view.
