# Help-Desk-Knowledge-Base

## Categories

- [Account and Access Issues](#account-and-access-issues)
- [Printing Issues](#printing-issues)
- [Network and Connectivity](#network-and-connectivity)
- [Email and Communication](#email-and-communication)
- [Hardware Support](#hardware-support)
- [Software Troubleshooting](#software-troubleshooting)
- [Remote Support](#remote-support)

## Account and Access Issues

1. **How to reset a forgotten Windows password**
    - Open the user account management tool (Active Directory Users and Computers).
    - Locate the user account via search.
    - Right-click the account ---> Select Reset Password.
    - Enter and confirm the new password.
    - Check the box for "User must change password at next logon" (optional).
    - Click OK and notify the user.

2. **Unlock a locked-out account**
   - Open Active Directory Users and Computers.
   - Search for the locked-out user account.
   - Right-click and select Properties
   - Go to the Account tab.
   - Uncheck Account is locked out, then click OK.
   - Inform the user that the account is now accessible.

## Printing Issues

3. **Printer Not Responding**
   
   - Check if the printer is powered on and connected to the network.
   - Verify cables and Wi-Fi connection.
   - Restart the printer and the user's computer.
   - On the user's device, go to Device and Printers ---> Right-click the printer ---> Troubleshoot.
   - Clear print queue: Open Services ---> Restart the Print Spooler.
   - Try a test print.
  
## Network and Connectivity

4. **No Internet Access**
   
   - Ask the user to check the physical connection or Wi-Fi icon.
   - Run ipconfig /release and ipconfig /renew in Command Prompt.
   - Check network adapter settings ---> Ensure DHCP is enabled.
   - Restart router (if home user) or verify switch/router (if in-office)
   - Ping 8.8.8.8 to verify connectivity
  
## Email and Communication

5. **Outlook Won't Open/Crashes**
   
   - Close Outlook
   - Open Run box ---> type: outlook.exe /safe
   - If it opens in Safe Mode, disable add-ins:
       - File ---> Options ---> Add-ins ---> Manage COM Add-ins ---> Disable all.
   - Restart Outlook normally.
   - If the issue persists, repair Outlook via Control Panel ---> Programs ---> Office ---> Change ---> Repair.
  
## Hardware Support

6. **External Monitor Not Working**
   
   - Check cable connections (HDMI, VGA, DisplayPort).
   - Press Windows + P and choose the correct display mode (Duplicate/Extend).
   - Update or reinstall display drivers via Device Manager.
   - Test with another monitor or cable to rule out hardware failure.
  
## Software Troubleshooting

7. **Application Not Responding or Crashing**
   
   - Ask the user to close the application completely using the task manager.
   - Reopen the application and check for behavior.
   - If it crashes again, check for updates via the app's Help or Settings menu.
   - If updates fail, uninstall and reinstall the application.
   - Check system logs (Event Viewer) for recurring errors related to the app.
  
## Remote Support

8. **Connecting to a Remote User with TeamViewer**
   
   - Ask the user to open TeamViewer and read their ID and Password.
   - On your device, open TeamViewer and enter the remote ID.
   - Click Connect, then enter the provided password.
   - Once connected, take control and begin troubleshooting
   - Log actions taken in the support ticket system.
