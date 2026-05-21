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
<img width="815" height="590" alt="image" src="https://github.com/user-attachments/assets/dabf2ca6-a4c4-4e2e-8aa3-8214dc237557" />



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="810" height="694" alt="image" src="https://github.com/user-attachments/assets/138185d0-d21a-4817-ae08-0302e39b8f91" />


It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="693" height="284" alt="image" src="https://github.com/user-attachments/assets/1dc80ea8-5c1e-40c0-8458-a886a9292fe2" />



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT
<img width="817" height="513" alt="image" src="https://github.com/user-attachments/assets/219981df-53c2-4d29-a463-a398b2337733" />




It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT
<img width="721" height="53" alt="image" src="https://github.com/user-attachments/assets/51e9d972-1a61-4d3b-b59f-7faa2663c61c" />




It shows the following screen in which the option Google can be selected:
## OUTPUT
<img width="685" height="234" alt="image" src="https://github.com/user-attachments/assets/a09a71ab-5233-499e-9685-977b56dfd666" />






SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT
<img width="954" height="883" alt="image" src="https://github.com/user-attachments/assets/d6e1b4f4-f45d-4873-872d-18cfb4ce382e" />





In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT
<img width="903" height="280" alt="image" src="https://github.com/user-attachments/assets/b43bbac9-a70d-4dfc-b4cb-f48e8c993ac8" />


SET logs the information regarding the Google credentials:
## OUTPUT
<img width="454" height="80" alt="image" src="https://github.com/user-attachments/assets/dc21054c-77f4-4a49-af06-b1ab717ef251" />



SET logs the information in the xml file under /root/.set directory:
## OUTPUT












## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
