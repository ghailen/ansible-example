# ansible-example
In cas without Ansible:
![image](https://github.com/user-attachments/assets/b9370fe3-331e-4673-ba4f-ac8f97806944)
we need to connect each time to the machine via SSH and exectue this command and install apache , create directory...

Using Asnsible we can automate those tasks into a single Playbook which is we it as an ansible Playbook

This is a sample example of playbook:
![image](https://github.com/user-attachments/assets/4d4205f4-711e-4a2c-8c0e-a1a2c1b82ba6)

![image](https://github.com/user-attachments/assets/ca6b9144-26bb-4c4c-abba-a341cb49375b)

lets try first to get access to a shell linux command using this site: https://sdf.org/mkacct.cgi
New SDF Shell Account Information
CONTACT E-MAIL:
LOGIN:
PERSONAL URL: 	ghylenovic13@gmail.com
ghailene
http://sdf.org/~ghailene
and connect to your server using putty

now i connected using putty:
![image](https://github.com/user-attachments/assets/d17049c7-d0b5-42b2-a929-0b77d234bf9c)
putty is more helpful with interface.

but you can use directly bash ui : like this 
![image](https://github.com/user-attachments/assets/d3f7343e-9e14-43b8-9196-c8c1c7b30c4b)
and then you are connected

===============================================================================
WHY Ansible is Agentless ?
===============================================================================
![image](https://github.com/user-attachments/assets/59681d63-b595-4c25-b7c3-b1c14353de3e)

The ansible is installed in developer machine. prepare playbook , add instrcution playbook and run it.
for example connecting to the servers using ssh machine and executing the required command. thats why is agentless
![image](https://github.com/user-attachments/assets/e0da1064-f07d-4047-b856-7e3045b20034)

The extension of the playbook is YML.

============================================================
INSTALLING ANSIBLE
============================================================
https://discourse.ubuntu.com/t/install-ubuntu-on-wsl2-and-get-started-with-graphical-applications/26296
![image](https://github.com/user-attachments/assets/b828e8d6-f9e2-43a0-bb49-f252f98dbc49)

![image](https://github.com/user-attachments/assets/8f86ece6-204a-4526-9a14-b007a8c73515)

i created a machine : with user : hailene and password : 1994

for update security : sudo apt update
for adding gui : sudo apt install x11-apps (not necessary)

now lets install ansible with : sudo apt-get install ansible

![image](https://github.com/user-attachments/assets/b0a1102c-1202-4911-b346-e1c442fabe9b)

after installing the ansible rerun the command : sudo apt update
lets check the version of ansible : 
![image](https://github.com/user-attachments/assets/5703877f-00e5-4ddb-9d7e-e4bb1bd67869)

====================================================================
Ansible project setup
==============================================================
![image](https://github.com/user-attachments/assets/ecc12b0b-a231-4b73-9bbf-d42a1be6a28a)



