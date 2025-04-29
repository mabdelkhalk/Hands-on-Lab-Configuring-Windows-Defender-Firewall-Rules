# Hands-on-Lab-Configuring-Windows-Defender-Firewall-Rules
This lab walks through creating and modifying firewall rules in Windows Defender Firewall with Advanced Security. Here are the key exercises covered:


Exercise 1: Allowing an App Through Firewall
Accessed Windows Security > Firewall & network protection
Modified Firefox permissions to allow public network communication
Demonstrated basic app permission management

Exercise 2: Enabling Inbound Rules for Remote Service Management
Created new inbound rules for remote administration
Selected predefined "Remote Service Management" rules
Configured to allow only secure connections
Added Administrator as authorized user

Exercise 3: Configuring Key Management Service Rules
Modified existing KMS rule to:
Allow connections on Domain/Private networks
Block connections on Public networks
Created duplicate rule specifically blocking Public network
Enabled both rules to enforce the policy

Key Takeaways:
Windows Defender Firewall provides granular control over network traffic
Rules can be configured per network profile (Domain/Private/Public)
Both allow and block rules can coexist for different networks
Predefined rules simplify configuration for common services
