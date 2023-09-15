There may be other methods of opening ports, but I only figured out the two listed below. One is manual, the other uses the [wire-pod installation](https://github.com/kercre123/wire-pod/wiki/Installation) page to run a script that opens the ports

## Running a script to open the ports
The instruction in this section assume you're using the T95. When using the T95, some steps in the wire-pod instructions can be skipped

Before you begin

* Your PC needs to run either Windows 10 or 11. 
* You will need to install Linux on Windows
* You will type or copy and paste commands to setup and run the script

PCs purchased after 2015 would have come with Windows 10 or 11 installed. If you want to confirm the version of Windows on your PC you can do the following:

* Press the windows key
* Type system and click on System Information

You will see something like this

![Windows version and build display](/img/WindowsVersion.jpg)

### Command line tools

The instructions will utilize two command line tools; PowerShell and WSL. PowerShell comes already installed with Windows. WSL will need to be installed

When opened, PowerShell looks like this
![Windows Powershell window](/img/PowerShell.jpg)

A WSL window. You can determine which tool you're using by the tab at the top of each tool 
![WSL command line](/img/WSL.jpg)

### Installing WSL

I followed [Microsoft's instructions](https://learn.microsoft.com/en-us/windows/wsl/install) for installing Linux on Windows. The acronym WSL stands for Windows Subsystem for Linux. WSL is what you will see used in the wire-pod instructions and widely on the internet

To install WSL, open PowerShell by

1. Press the windows key
2. Begin typing PowerShell
3. Click on Run as Administrator

In the PowerShell window type
``` ps1
wsl --install
```

You can confirm WSL installed correctly by

* Press the windows key
* Type WSL

You'll see this

![WSL in the start menu](/img/OpenWSL.jpg)

!!! tip   

    Each time you open PowerShell and WSL, you need to click Run as administrator

You are now ready to run the script to open the ports. Go to the [wire-pod installation page](https://github.com/kercre123/wire-pod/wiki/Installation) and do the following:

!!! note

    The commands in the installation guide can be copied and pasted into your PowerShell or WSL window. Of course, you can type the commands

1. Scroll down to Guide 2: Windows 10/11
2. Go to step 7 
3. In a WSL window, type the command and hit the enter key to run the command

I was not asked for a password. I think this is because the T95 comes with wire-pod installed and ready to communicate with Vector

There are two more steps and these are done in PowerShell

4. Type the command in step 9 and hit the enter key to run the command

Your PC is now ready to run the PowerShell script in step 10. The script will open the ports

5. Copy the code listed in step 10. This can easily be done by clicking the icon in the top right of the code window in step 10
6. Paste the code into PowerShell and hit enter

You do not need to reboot after performing the steps to open the ports

## Manually opening the ports

The below instructions assume your PC is using the default firewall software named Windows Defender Firewall. If you are using different firewall software, the steps should be similar but won't match the screen captures below