# Teddy
TEDDY low bandwidth ICMP attack that is capable of doing denial of service to well known firewalls. ... When an attack is ongoing, users from the LAN side will no longer be able to send/receive traffic to/from the Internet. All firewalls we have seen recover when the attack stops.

# Vulnerable System
Cisco ASA 5505, 5506, 5515, 5525 , 5540 (default settings)
Cisco 6500 routers with SUP2T and Netflow v9 on the inbound interface - 100% CPU load
Cisco ASA 5550 (Legacy) and 5515-X (latest generation)
Cisco Router 897 - Can be mitigated - The current code from https://www.cymru.com/Documents/secure-ios-template.html will make evil worse.

# Disclaimer
This or previous program is for Educational purpose ONLY. Do not use it without permission. The usual disclaimer applies, especially the fact that me (opsxcq) is not liable for any damages caused by direct or indirect use of the information or functionality provided by these programs. The author or any Internet provider bears NO responsibility for content or misuse of these programs or any derivatives thereof. By using these programs you accept the fact that any damage (dataloss, system crash, system compromise, etc.) caused by the use of these programs is not opsxcq's responsibility.

