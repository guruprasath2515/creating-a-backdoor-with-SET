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

![Screenshot 2024-04-28 140445](https://github.com/22008496/creating-a-backdoor-with-SET/assets/119476113/4ce5dbbc-ccd8-4514-9853-4708c79368a4)

The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:

![Screenshot 2024-04-27 131757](https://github.com/22008496/creating-a-backdoor-with-SET/assets/119476113/00dc22f9-fb0d-40b3-abcc-28d8952a7bf5)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![Screenshot 2024-04-27 131819](https://github.com/22008496/creating-a-backdoor-with-SET/assets/119476113/e6c23412-0b67-41d0-8fd6-7f9418fbda08)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![Screenshot 2024-04-27 131902](https://github.com/22008496/creating-a-backdoor-with-SET/assets/119476113/869ccff2-1e17-4514-a1a3-8eb015135d84)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![Screenshot 2024-04-27 131913](https://github.com/22008496/creating-a-backdoor-with-SET/assets/119476113/57a32aea-2363-4c48-a896-521d6190cc2b)

It shows the following screen in which the option Google can be selected:

![Screenshot 2024-04-27 131927](https://github.com/22008496/creating-a-backdoor-with-SET/assets/119476113/81389f0b-7587-4a70-b70c-4540386d48a3)

SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![Screenshot 2024-04-27 131947](https://github.com/22008496/creating-a-backdoor-with-SET/assets/119476113/a30fbe64-3707-4e3d-bb03-db400af1fa44)

In windows IE, on giving the url http://192.168.1.2, the fake Google page is displayed. The victim can enter the username and password

![Screenshot 2024-04-28 142200](https://github.com/22008496/creating-a-backdoor-with-SET/assets/119476113/b9a750d0-8a98-4454-a407-01cf2433d942)

SET logs the information regarding the Google credentials:

![Screenshot 2024-04-27 132009](https://github.com/22008496/creating-a-backdoor-with-SET/assets/119476113/33de902c-425d-441b-ace7-c834db2b6c7b)

SET logs the information in the xml file under /root/.set directory:

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
