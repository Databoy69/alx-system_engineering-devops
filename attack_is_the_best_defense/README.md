Attack is the best defense
DevOps
Scripting
Hacking


Concepts
For this project, we expect you to look at these concepts:

Network basics
Docker

Resources
Read or watch:

Network sniffing
ARP spoofing
Connect to SendGrid’s SMTP relay using telnet
What is Docker and why is it popular?
Dictionary attack
man or help:

tcpdump
hydra
telnet
docker


0. ARP spoofing and sniffing unencrypted traffic

. Dictionary attack
#advanced
Password-based authentication systems can be easily broken by using a dictionary attack (you’ll have to find your own password dictionary). Let’s try it on an SSH account.

Install Docker on your machine Ubuntu
Pull and run the Docker image sylvainkalache/264-1 with the command docker run -p 2222:22 -d -ti sylvainkalache/264-1
Find a password dictionary (you might need multiple of them)
Install and use hydra to try to brute force the account sylvain via SSH on the Docker container
Because the Docker container is running locally, hydra should access the SSH account via IP 127.0.0.1 and port 2222
Hint: the password is 11 characters long
Once you found the password, share it in your answer file.
