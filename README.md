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


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

## OUTPUT

<img width="414" height="235" alt="Screenshot From 2026-02-13 08-47-43" src="https://github.com/user-attachments/assets/b8a2a9d8-ffa1-41b1-b9d9-a711d1fb4a2b" />

It displays the following menu and select 2 for Website Attack Vectors:

## OUTPUT

<img width="398" height="314" alt="Screenshot From 2026-02-13 08-47-56" src="https://github.com/user-attachments/assets/6b010e56-7cbd-4100-b35c-38ca8540161a" />

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

## OUTPUT

<img width="350" height="216" alt="Screenshot From 2026-02-13 08-48-09" src="https://github.com/user-attachments/assets/e21e3d8d-a60e-434b-ae01-c7bb243a8ad7" />

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

## OUTPUT

<img width="285" height="141" alt="Screenshot From 2026-02-13 08-48-23" src="https://github.com/user-attachments/assets/f497ed3f-ded9-42e3-90e9-c35fed0d802d" />

It shows the following screen in which the option Google can be selected:

## OUTPUT
<img width="638" height="470" alt="Screenshot From 2026-02-13 08-48-48" src="https://github.com/user-attachments/assets/8fa4f450-1ca6-456c-a32c-1d79a1e079f3" />

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

## OUTPUT
<img width="1443" height="157" alt="Screenshot 2026-02-14 140126" src="https://github.com/user-attachments/assets/df01c661-35f6-458e-8289-b88823e046ba" />


In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password

## OUTPUT
<img width="1571" height="755" alt="Screenshot 2026-02-14 134947" src="https://github.com/user-attachments/assets/1852e772-7b13-41cf-8423-bac8991e96e3" />


SET logs the information regarding the Google credentials:

## OUTPUT

<img width="1489" height="421" alt="Screenshot 2026-02-14 140110" src="https://github.com/user-attachments/assets/38ddf934-5091-42d3-9f49-021905f7e2d4" />

SET logs the information in the xml file under /root/.set directory:

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
