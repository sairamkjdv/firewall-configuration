# Task 4 – Firewall Configuration

## Objective
Configure and test basic firewall rules in Windows 11 to allow or block network traffic.

## Tools Used
- **OS**: Windows 11 Home
- **Tool**: Windows Defender Firewall with Advanced Security

## Steps Performed

1. **Opened Windows Defender Firewall with Advanced Security**  
   ![Firewall Home](./screenshots/1-firewall-home.png)

2. **Checked existing inbound rules (before any changes)**  
   ![Before Rules](./screenshots/2-before-rules.png)

3. **Created a New Inbound Rule – Selected Port type**  
   ![Select Port](./screenshots/3-select-port.png)

4. **Chose TCP and specified port 23**  
   ![TCP Port 23](./screenshots/4-tcp-port23.png)

5. **Selected "Block the connection" action**  
   ![Block Connection](./screenshots/5-block-connection.png)

6. **Applied the rule to Domain, Private, and Public profiles**  
   ![Apply Rule to Profiles](./screenshots/6-rule-application-to-profiles.png)

7. **Named the rule as Block Telnet Port 23**  
   ![Rule Name](./screenshots/8-rule-name.png)

8. **Verified the rule appeared in inbound rules**  
   ![Rule Added](./screenshots/7-rule-added.png)

9. **Tested blocking by attempting a Telnet connection to localhost on port 23 (failed to connect)**  
   ![Telnet Blocked](./screenshots/9-telnet-blocked.png)

10. **Removed the port 23 blocking rule to restore the original state**  
    ![Rule Deleted](./screenshots/10-rule-deleted.png)

## Learning Outcomes
- Learned how to block specific ports on Windows Firewall.
- Understood inbound rules, profiles, and traffic blocking.
- Verified rules with practical testing.

## Screenshots
All screenshots are located in the `/screenshots` folder and are mapped to each step above.

---

> Task successfully completed as part of the Elevate Labs Cyber Security Internship Program.
