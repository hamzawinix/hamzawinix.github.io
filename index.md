<b>[coming soon]</b>



<h1>
<a href="https://notes.hamzawinix.com/">My notes</a>
</h1>
<!--maybe like this website https://juliette1012.github.io/posts/THM-Burp-Suite/ -->



Welcome to my blog
About
Cyber Security Enthusiast
Bad Programmer
Interested in Malware and Reverse Engineering
Focused on Red Teaming and Penetration Testing

- HackTheBox APT walkthrough
Short summary
APT was one of the most controversial HTB boxes. Many people did not like it and it took 7 days to blood root. Today, we will go over one of the paths that can be taken to gain Administrator privilege level on the box. We start with an RPC endpoint enumeration, which eventually will give us an ipv6 IP. The ipv6 IP will allow anonymous login in its smb shares and we will get a backup file. We will crak the backup file to retrieve some ntds files. Then we will use kerbrute to bruteforce valid users, and we will have to use reg.py to retrieve the user password. After that we learn that NTLMv1 is enabled, so we will cause a hash leak and then perform a PTH attack to root. Note: This writeup might be boring for the reason that it has a lot of information in it, and that is because I wanted people to understand every single step, without hand waving at concepts they did not understand.

Contact me:
@xDragon#2009 - Discord
