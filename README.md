## Description
Certain network interfaces of the HP OfficeJet Pro series and LaserJet Pro series printers do not require authentication. Attackers can remotely tamper with printer configurations or directly manipulate the printer, such as:  
- Disabling or deleting the printer's web services.
- Closing the default port used for printing.
- Restarting the printer.
- Modifying firewall rules.
- Setting up network folders or email accounts to send scanned or copied documents from the printer to the attacker.

The affected printers do not have any authentication mechanisms enabled in their factory default configuration (such as an administrator account password not being set), resulting in their network management interface (including but not limited to the web console, SNMP services, FTP services, 9100 port printing services, etc.) being directly accessible by unauthorized users.

## Vulnerability Type
CWE-306: Missing Authentication for Critical Function

## The affected products and versions include, but are not limited to:

- HP LaserJet Pro MFP M428fdn  
Firmware version: TETONXXXXN002.2445A.00

- HP LaserJet Pro MFP 4101fdw  
Firmware version: LOCHSAXXXN002.2513A.00

- HP LaserJet Pro MFP M428fdw  
Firmware version: TETONXXXXN002.2512A.00

- HP Color LaserJet Pro MFP M479fdw  
Firmware version: CLRWTRXXXN002.2445A.00

- HP DeskJet 4100 All-in-One Printer series  
Firmware version: TOP1FN2424DR

- HP DeskJet Ink Advantage 3700 All-in-One Printer series  
Firmware version: LAP1FN2125BR

- HP OfficeJet 8020 series  
Firmware versions: MALBECPP1N001.1921A.00, MALBECPP1N004.2512C.00

- HP OfficeJet Pro 8210  
Firmware versions: NON-HP-NC.1803A11.00, NON-HP-NC.1803A31.00, TESPDLPP1N001.2514A.00

- HP OfficeJet Pro 9010 series  
Firmware versions: MANHTNPP1N005.2512A.00, MANHTNPP1N002.2042A.00

- HP OfficeJet Pro 9020 series  
Firmware versions: MANHHIPP1N005.2512A.00, MANHHIPP1N002.2042A.00

- HP OfficeJet Pro 8710  
Firmware versions: NON-HP NC 71631, NON-HP NC 71611, WBP2CN1716AR

- HP OfficeJet Pro 8720  
Firmware version: NON-HP NC 72010

- HP OfficeJet Pro 7740 Wide Format All-in-One  
Firmware versions: NON-HP-NC 1729E11.00, EDWINXPP1N002.1849A.00

- HP OfficeJet Pro 7720 Wide Format All-in-One  
Firmware version: ELLISXLP1N003.1928A.00


## POC:
![poc1.png](poc1.png)
![poc2.png](poc2.png)
![poc3.png](poc3.png)
![poc4.png](poc4.png)
![poc5.png](poc5.png)
![poc6.png](poc6.png)
