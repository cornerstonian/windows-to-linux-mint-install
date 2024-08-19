## Installing Linux Mint on a Dedicated Windows 10 HP Laptop

This guide provides step-by-step instructions for installing Linux Mint on a dedicated HP laptop currently running Windows 10. Follow these steps to ensure a successful installation.

### Prerequisites
- A backup of all important data from the Windows 10 system.
- A USB drive with at least 4GB of storage.
- A tool to create a bootable USB drive, such as [Rufus](https://rufus.ie/en/) or [Etcher](https://etcher.balena.io/). (I used Rufus).

### Step 1: Backup Data
Before starting the installation, back up all important data from the existing Windows 10 system. The installation process will erase all existing data on the laptop.

### Step 2: Create a Bootable Linux Mint USB Drive
1. **Download Linux Mint:**
   - Visit the [Linux Mint website](https://linuxmint.com/download.php) and download the ISO file for the desired Linux Mint edition.

2. **Download a USB Creation Tool:**
   - Obtain a tool such as [Rufus](https://rufus.ie/) or [Etcher](https://www.balena.io/etcher/) to create a bootable USB drive.

3. **Create the Bootable USB:**
   - Insert the USB drive into the computer.
   - Open the chosen USB creation tool (Rufus or Etcher).
   - Select the downloaded Linux Mint ISO file.
   - Choose the USB drive as the destination.
   - Initiate the process and wait for it to complete.

### Step 3: Prepare the HP Laptop for Installation
1. **Enter BIOS/UEFI Settings:**
   - Restart the laptop and press the appropriate key to access BIOS/UEFI settings (commonly F2, F10, F12, or Esc; refer to the startup screen for the exact key).

2. **Change Boot Order:**
   - Within the BIOS/UEFI settings, locate the boot order menu and set the USB drive as the primary boot device.

3. **Disable Secure Boot (if necessary):**
   - Some HP laptops require Secure Boot to be disabled to install Linux. This option is typically found under the "Security" or "Boot" tab in BIOS/UEFI settings.

4. **Save and Exit:**
   - Save changes and exit BIOS/UEFI settings.

### Step 4: Boot from the USB Drive and Install Linux Mint
1. **Boot from USB:**
   - Insert the bootable USB drive into the laptop and restart. The laptop should boot from the USB drive, displaying the Linux Mint live environment.

2. **Try Linux Mint (Optional):**
   - Select the "Try Linux Mint" option to test hardware compatibility before installation.

3. **Start the Installation:**
   - Double-click the “Install Linux Mint” icon on the desktop.

4. **Follow the Installation Wizard:**
   - **Choose Language:** Select the preferred language and click “Continue.”
   - **Prepare to Install Linux Mint:** Confirm that the system meets the requirements (internet connection, disk space, etc.) and click “Continue.”
   - **Installation Type:** Choose “Erase disk and install Linux Mint” to remove Windows and install Linux Mint. Note that this action will delete all existing data on the disk.
   - **Set Timezone:** Select the appropriate timezone and click “Continue.”
   - **Keyboard Layout:** Choose the keyboard layout and click “Continue.”
   - **User Information:** Enter the name, computer name, username, and password. Click “Continue” to begin the installation.

5. **Complete the Installation:**
   - Wait for the installation process to finish. This may take some time.

6. **Restart the Computer:**
   - Once the installation is complete, the user will be prompted to remove the USB drive and reboot the system.

### Step 5: Post-Installation Setup
1. **Initial Setup:**
   - After rebooting, the user will be greeted with the Linux Mint login screen. Log in using the credentials created during installation.

2. **Update System:**
   - After logging into Linux Mint, open the terminal and run: run `sudo apt update && sudo apt upgrade` in the terminal to ensure the system is up-to-date.

3. **Install Additional Drivers (if needed):**
   - Open “Driver Manager” to install any necessary drivers for hardware components.
4. **Install Additional Software:**
   - Use the Software Manager to install any additional applications you need.

6. **Restore Data:**
   - If data was backed up prior to installation, it can now be restored to the new Linux Mint installation.

![image](https://github.com/user-attachments/assets/671e9f42-fde0-4491-aadc-d5c54450bfb1)
###
![image](https://github.com/user-attachments/assets/acef2322-4db7-44e0-9a8a-bc67dff813e3)

### Resources

- **Linux Mint Installation Guide**: [Linux Mint Installation Guide](https://linuxmint-installation-guide.readthedocs.io/en/latest/)
- **Rufus Bootable USB Guide**: [Rufus Guide](https://rufus.ie/en/)
