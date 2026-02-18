# Creating a backdoor with SET
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

<img width="602" height="327" alt="image" src="https://github.com/user-attachments/assets/a6ccd1cf-e439-4769-8d40-ca716c2b9f3d" />


<img width="922" height="846" alt="image" src="https://github.com/user-attachments/assets/ec1d3215-4d43-4e84-9a8c-86409838840d" />


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT
<img width="606" height="230" alt="image" src="https://github.com/user-attachments/assets/1e65f8a0-04b3-43bf-80ce-9e5fc9a9ec14" />




It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="668" height="273" alt="image" src="https://github.com/user-attachments/assets/c2fc7cc7-7620-4909-87a3-eee82035a4fe" />



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="895" height="315" alt="Screenshot 2026-02-17 105921" src="https://github.com/user-attachments/assets/d8e4a91f-a79a-414c-af59-4cec3e84a89d" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="834" height="375" alt="image" src="https://github.com/user-attachments/assets/a8e89ebb-99e2-415c-b99d-eb52104d82a0" />



It shows the following screen in which the option Google can be selected:
## OUTPUT


<img width="752" height="409" alt="image" src="https://github.com/user-attachments/assets/619a1a2b-98b0-47e6-9e02-afdb9a038a33" />



SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="938" height="565" alt="image" src="https://github.com/user-attachments/assets/0416b31b-ebe9-46bc-949a-237cd87dd02c" />


In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

<img width="947" height="879" alt="image" src="https://github.com/user-attachments/assets/388c2449-e8ab-437d-a050-051412f1a7ad" />


SET logs the information regarding the Google credentials:
## OUTPUT

<img width="930" height="554" alt="image" src="https://github.com/user-attachments/assets/1348b75e-9eaa-479b-a212-20cf9d264a3c" />


SET logs the information in the xml file under /root/.set directory:






## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully.
