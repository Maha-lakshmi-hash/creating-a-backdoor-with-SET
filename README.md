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
## OUTPUT

<img width="697" height="420" alt="image" src="https://github.com/user-attachments/assets/4e2ec6be-e43a-4258-8ed0-171ea3bd896f" />
<img width="798" height="541" alt="image" src="https://github.com/user-attachments/assets/e53d3457-acaf-4921-840d-6167e0d4855a" />

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="450" height="268" alt="image" src="https://github.com/user-attachments/assets/b6778663-62ad-4bda-ad48-465a746b41bd" />
<img width="878" height="812" alt="image" src="https://github.com/user-attachments/assets/f447072d-a996-41c5-a4f5-69ae49cf5680" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="842" height="380" alt="image" src="https://github.com/user-attachments/assets/c542ce17-5286-4bc9-8c3c-064bdf27afe9" />

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="912" height="521" alt="image" src="https://github.com/user-attachments/assets/87843e26-194d-4d6c-9392-89d048d181ef" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="962" height="492" alt="image" src="https://github.com/user-attachments/assets/bc6ea6ce-afa7-4484-bb86-5ec151d1ea20" />

It shows the following screen in which the option Google can be selected:
## OUTPUT

<img width="1741" height="903" alt="image" src="https://github.com/user-attachments/assets/d80a90d9-0f5e-403f-b3a6-4d7cd5133e0f" />

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="1741" height="903" alt="image" src="https://github.com/user-attachments/assets/bb6fce34-8c71-4c28-adc3-61a3e8a0b5df" />



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

<img width="1825" height="862" alt="image" src="https://github.com/user-attachments/assets/a1aaa8a2-b6c7-4e51-a139-70399fc9c3d5" />

SET logs the information regarding the Google credentials:
## OUTPUT

<img width="1056" height="472" alt="image" src="https://github.com/user-attachments/assets/040f62e8-365b-4e4e-aed4-68c0f353e30e" />

SET logs the information in the xml file under /root/.set directory:
## OUTPUT

<img width="1043" height="746" alt="image" src="https://github.com/user-attachments/assets/ea54af88-9e86-4bee-bf2e-e26d0f879b9f" />

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
