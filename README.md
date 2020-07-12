# Vegeta-Vulnhub
A new and easy machine for beginners..

Got the ip using netdiscover

Now i tried to enumerate using nmap and dirb on ip.
Port 22 and Port 80 both are open

By dirb scan i got some directories but couldn't find any juicy information

Tried robots.txt from there i found a password (Hint=/find_me)

Still didnt get any other information

#Vegeta is a character from Dragonballz show 

So i made a wordlist of few names of the characters of Dragonballz show..

With the new wordlist in my hand i again tried for dirb but this time i added my own wordlist of the names..

I got some directories which i checked one by one.
From one directory i found a wav file then i tried to listen to it but couldn't get it.

#One of my friend help me and told that its a morse code encoded audio.


Then from online morse code audio decoder i got the username and password..


Now i tried for ssh login with the credentials i founded..
Successfully logged in YEAHH!!!

Now for root we need to do privilege escalation..
Change user id to root id as user can read and write etc/passwd ..

Thank You.
