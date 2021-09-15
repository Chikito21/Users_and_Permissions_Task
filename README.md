## Users_and_Permissions_Task
SCA Cloud School Task


i.	Create 3 groups and 15 users

ii.	Assign the 15 users across the 3 groups



*From an Ubuntu server*

**Created Users**

Create a user with a home directory with the following command:

`sudo useradd -m <username>`

Repeat until 15 users are created.

**Created Groups**
  
Create a group with the command below:

`sudo groupadd <groupname>`

Repeat until 3 groups are created.

**Added Users to groups**
  
`sudo usermod -a -G <groupname> <username>`

15 users were added to 3 groups; 5 users to one group.


**To list members in a group:**

`members groupname`

**To list normal users in your server (Linux system), use the following command:**

`getent passwd {1000..60000}`
