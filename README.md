# Firewall Rule Configuration Task

## Objective
Block Telnet traffic (port 23) using Windows Firewall and test the rule.

## Steps Followed
1. Opened Windows Defender Firewall.
2. Created an inbound rule to block port 23.
3. Verified block using Nmap.
4. Removed the rule to restore original state.

## Summary
Firewalls work by filtering incoming/outgoing traffic using rules. In this task, I blocked port 23 (Telnet) and confirmed it using a port scan.

## Files Included
- `firewall_config.txt`: Step-by-step rule setup and test.

## Tools Used
- Windows Firewall
- Nmap (for testing)

## Screenshots
1. While setting up the firewall rule blocking port 23:
![Screenshot 2025-05-30 103635](https://github.com/user-attachments/assets/3eed6b93-483e-4e64-b2f9-6b456ba6fef0)

2. Testing the Rule
![Screenshot 2025-05-30 104303](https://github.com/user-attachments/assets/7acf997e-f486-4017-b279-9ee71f31da95)


