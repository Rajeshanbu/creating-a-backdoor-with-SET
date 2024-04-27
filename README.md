# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:

![eth7 1](https://github.com/Rajeshanbu/creating-a-backdoor-with-SET/assets/118924713/d068e7c5-191c-4143-9c83-513c167fbd11)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
![eth7 2](https://github.com/Rajeshanbu/creating-a-backdoor-with-SET/assets/118924713/31fc4732-1cea-4fcd-8348-48813725a15c)


It displays the following menu and select 2 for Website Attack Vectors:
![eth7 3](https://github.com/Rajeshanbu/creating-a-backdoor-with-SET/assets/118924713/79f5b347-954d-482d-b751-6fdd27ce3a95)


The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![eth7 4](https://github.com/Rajeshanbu/creating-a-backdoor-with-SET/assets/118924713/706953ed-89ca-439b-8382-0d8ffb24053f)


The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![eth7 6](https://github.com/Rajeshanbu/creating-a-backdoor-with-SET/assets/118924713/6198f175-3d09-4f61-9607-9c83b04e5940)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![Uploading 324251581-9e47900b-3757-4fc2-b28e-e15a1f869e71.png…]()


It shows the following screen in which the option Google can be selected:
![eth7 9](https://github.com/Rajeshanbu/creating-a-backdoor-with-SET/assets/118924713/5ad1161a-2790-415f-985e-018d89310407)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
![eth7 10](https://github.com/Rajeshanbu/creating-a-backdoor-with-SET/assets/118924713/1f5305b5-9879-4af3-911c-d42d0992aeba)


In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

VirtualBox_Windows 7_16_04_2024_08_56_25

SET logs the information regarding the Google credentials:


![eth7 11](https://github.com/Rajeshanbu/creating-a-backdoor-with-SET/assets/118924713/816b9b56-d4a6-4fce-9c72-943596b91543)



## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
