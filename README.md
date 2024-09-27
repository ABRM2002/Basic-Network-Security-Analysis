# Basic Network Security Analysis

## Objective

The Basic Network Security Analysis is a guided project offered by coursera which guided me effectively to use Wireshark-a useful tool for capturing and analyzing network traffic. The course covers both encrypted and unencrypted protocols, including RADIUS, HTTP, DNS, Telnet, HTTPS, and SSH. Generating traffic for these protocols and gaining hands-on experience capturing and decrypting HTTPS traffic using a pre-master secret key. This project aims to enhance my understanding of network traffic analysis and secure communications.

### Skills Learned

- Learnt how to troubleshoot with Wireshark, capture Traffic and analyze already captured Traffic.
- Understood how to use Display and Capture Filters.
- Generated, Captured and analyzed both Unencrypted traffic- RADIUS, DNS, HTTP and Telnet as well as Encrypted Traffic- SSH and HTTPS.  
- Enhanced my knowledge of Encrypted and Unencrypted Traffic by decrypting the HTTPS Traffic and also the RADIUS encypted password.
- Development of network security skills in cybersecurity.

### Tools Used

- Network analysis tool called Wireshark for capturing and examining network traffic.

## Steps

-Task 1: Get to know Wireshark and its basic functionalities

![Screenshot 2024-09-27 181700](https://github.com/user-attachments/assets/77fc86b3-05c5-464c-8810-849aa710f80a)


Capturing some network traffic that is flowing through the machine presently at the time and analyzing already captured network traffic by opening a stored capture file.

-Task 2: Generate and Capture RADIUS Traffic

![image](https://github.com/user-attachments/assets/a6b078ab-8947-41e9-9636-81f28e47878b)


Knowing what the RADIUS Architecture consists of and decrypting the encrypted password with the shared-secret using Wireshark.

-Task 3: Analyze a HTTP Basic Authentication

![Screenshot 2024-09-27 173539](https://github.com/user-attachments/assets/7bef794f-51e0-417d-9e74-61a578eb7422)


Knowing the basics about HTTP, and knowing the difference between Wireshark’s Capture and Display Filters. Connecting to an HTTP Server and initiating a Basic HTTP Authentication and capturing its Traffic on Wireshark, analyzing the captured packets and seeing the username and password being sent.

-Task 4: HTTP Form-Based Authentication and DNS

![Screenshot 2024-09-27 184442](https://github.com/user-attachments/assets/5b538f5d-12e2-4cf4-9832-a6f832921a48)


Initiating an HTTP Form-based authentication, capturing it in Wireshark and analyzing it so you can see the username and password clearly. Also Capturing DNS Traffic.

-Task 5: Initiate, Capture and Analyze Telnet Sessions

![WhatsApp Image 2024-09-27 at 17 20 41_b39b6284](https://github.com/user-attachments/assets/bca6406a-dffb-4a92-865c-5dd4e4552d49)


 Knowing how Telnet works, starting a Telnet Session with a remote Device using PowerShell, capturing its traffic in Wireshark and analyzing it from the Security perspective.

-Task 6: Capturing and Analyzing SSH Sessions

![WhatsApp Image 2024-09-27 at 17 09 59_913bcebf](https://github.com/user-attachments/assets/78db46cb-bab7-4321-a1c5-d0f98008c5ac)


![image](https://github.com/user-attachments/assets/7e81a0a4-1fa2-4958-9a10-49a6d3341857)



Opening a SSH Session with the same Device as in Task 5, capturing the traffic and comparing it with the Telnet Packet Capture. Capturing traffic based on the host involved and how to see all the host, packet and protocol statistics as well as conversations that have happened in a certain Capture

-Task 7: Generate, Capture, Analyze then Decrypt HTTPS Traffic

![image](https://github.com/user-attachments/assets/fa1f53e1-00f7-405b-a816-8b837b04dc89)

![Screenshot 2024-09-27 194118](https://github.com/user-attachments/assets/d1197104-e248-4883-95b6-2b0f40d6c8ac)

![Screenshot 2024-09-27 200422](https://github.com/user-attachments/assets/09abe775-e46c-4b29-8662-018b3b3c28de)


Decrypt the SSL traffic with the help of Pre Master Secret Key method.
