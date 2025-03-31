## Description
Certain network interfaces of the HP OfficeJet Pro series and LaserJet Pro series printers do not require authentication. Attackers can remotely tamper with printer configurations or directly manipulate the printer, such as:  
- disabling or deleting the printer's web services.
- closing the default port used for printing.
- restarting the printer.
- modifying firewall rules.
- setting up network folders or email accounts to send scanned or copied documents from the printer to the attacker.

The affected printers do not have any authentication mechanisms enabled in their factory default configuration (such as an administrator account password not being set), resulting in their network management interface (including but not limited to the web console, SNMP services, FTP services, 9100 port printing services, etc.) being directly accessible by unauthorized users.

## Vulnerability Type
CWE-284: Improper Access Control

## POC:
![poc1.png](poc1.png)
![poc2.png](poc2.png)
![poc3.png](poc3.png)
![poc4.png](poc4.png)
![poc5.png](poc5.png)
![poc6.png](poc6.png)
