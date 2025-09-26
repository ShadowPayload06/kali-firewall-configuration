Kali Firewall Configuration — Internship

This repository documents a complete firewall configuration workflow using UFW (Uncomplicated Firewall) on Kali Linux Purple

“UFW (Uncomplicated Firewall) was used to configure and test firewall rules in a controlled Kali Linux Purple environment. Its simplicity and audit-friendly syntax make it ideal for internship-level security tasks.”

🔐 Objectives

- Configure and validate firewall rules using UFW.
- Block insecure services (Telnet) and allow secure access (SSH).
- Simulate rollback by removing rules and resetting the firewall.
- Document each step with terminal commands and screenshots.
- Maintain auditability and privacy compliance throughout.

📋 Steps Covered

| Step | Description |
|------|-------------|
| 1    | Install UFW |
| 2    | Enable UFW |
| 3    | Block Telnet (Port 23) |
| 4    | Verify Telnet Block |
| 5    | Allow SSH (Port 22) |
| 6    | Remove SSH Rule (Rollback) |
| 7    | Document Commands Used |
| 8    | Validate Firewall Rules (Telnet & SSH Tests) |


📁 Folder Structure

kali-firewall-configuration/ ├── step1_install_ufw.txt ├── step2_enable_ufw.txt ├── step3_block_telnet.txt ├── step4_verify_telnet_block.txt ├── step5_allow_ssh.txt ├── step6_remove_ssh.txt ├── step7_document_commands.txt ├── step8_validate_rules.txt ├── README.md └── screenshots/

🧠 Notes

- All steps executed via terminal — no GUI used.
- Each rule verified using `sudo ufw status numbered`.
- SSH tested using `ssh sukuna@xx.x.x.xx` and `ssh -X user@xxx.xxx.x.x`.
- Screenshots captured for each step and stored in `screenshots/`.
- Host IPs redacted in public documentation for privacy compliance.
