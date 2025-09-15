# Social Engineering using SET

## Summary
Im presenting the process of a successful phishing attacking showing both sides the target and the attacker.
## Project Overview 
### Resources:
  I'll be using a VM to execute this project.


![Capturegg](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20112428.png)


# Attacker: Kali 2 Attack Machine

  I start in the command line.


![Capture44](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20112708.png)

I used the code setoolkit to create my phishing attack and proceed with the steps going to option 1: Social Engineering Attacks, option 2: Website Attack Vectors, option 2: Metasploit Browser Exploit Method, and then option 1: Web Templates. 

![Capture3](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20112953.png)
![Capture2](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20113009.png)
![Capture2](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20113033.png)
![Capture2](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20113059.png)




Now to make sure to enter no for NAT/Port Forwarding.



![Captureii](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20113134.png)



Now to enter the Host IP address

![Capture;;](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20113240.png)


Now proceeding with the steps selecting option 3: Facebook email template, option 46: Metasploit Browser Autopwn, option 2: Windows reverse TCP Meterpreter, enter port 443, and then wait for the system to finish processing.


![eee](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20113258.png)
![Capturedd](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20113317.png)
![Capturedd](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20113352.png)
![Capturedd](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20113410.png)
![Capturedd](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20113637.png)



# Target: Windows Server 
I start going through the opera mailing program and proceed to click on the facebook url.

![Capturekkk](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20113818.png)

As normal the target wouldn't notice anything and begin to enter their login credentials.

![Capturesdfsdf](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20113912.png)


# Back to the Attacker: Kali 2 Attack Machine
I check the command line and see the target successfully logged in giving me full control of their device.

![Capturesdfsdaf](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20115439.png)

I type in the code session -l to fully see what device was connected to the url.

![fffff](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20115511.png)

Now I type the code session -i 1 to connect to the specific device.

![fffff](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20115550.png)

Now I proceed with steps to download specific files typing the code pwd to present directory, then type cd \ to change directory, then type ls to see the list in the current directory, type cd share to see files in the share folder, then type cd DeathStar to direct to the specific folder, and then gain access to the blueprint jpgs.

![fffff](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20115615.png)

![fffff](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20115635.png)

![fffff](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20115704.png)

![fffff](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20115723.png)

![fffff](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20115757.png)

![fffff](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20115925.png)

Finally I type in the code download *.* /root downloading the jpgs to the attack machine where I can view them on the photos directory.

![fffff](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20120003.png)

![fffff](https://github.com/Silveshadow/Social-Engineering-using-SET/blob/main/Screenshot%202025-09-15%20120121.png)

