<img width="405" height="154" alt="image" src="https://github.com/user-attachments/assets/a51f99a9-6c6d-4d95-853b-cf63bff5b52a" /># Linux_Assignment

## 1. Configure smtp in localhost.
### Step 1: Install Postfix & Mail Utilities.
<img width="771" height="49" alt="image" src="https://github.com/user-attachments/assets/b1dc88c8-fb32-462c-8b64-90d563dc800a" />
<img width="805" height="239" alt="image" src="https://github.com/user-attachments/assets/3a7dd3af-3534-4997-b6d9-6a3b7580f486" />

### Step 2: Start the Postfix using Systemctl command and verify if it's running on port 25.
<img width="810" height="294" alt="image" src="https://github.com/user-attachments/assets/bc6f0784-54f7-4ef8-9f6f-117a347e0dbd" />
<img width="811" height="424" alt="image" src="https://github.com/user-attachments/assets/182fa55d-9c34-4a6a-9566-bfe443b33775" />

### Step 3: Add a testuser using Sudo command. By default the new user will not be a sudoer.
<img width="800" height="377" alt="image" src="https://github.com/user-attachments/assets/54f57278-436c-4fa2-bf6e-048a3208b602" />
<img width="567" height="90" alt="image" src="https://github.com/user-attachments/assets/5f4e6307-01c2-44c8-a867-1c6d4875ae0b" />

### Step 4: Check if you are in remote machine or on localhost. Empty output states we are in localhost
<img width="567" height="90" alt="image" src="https://github.com/user-attachments/assets/bc5f0b82-2899-4b3f-ab64-8b6dc2d12ab1" />

## Configure your system in such a way that when a user type and executes a describe command from anywhere of the system it must list all the files and folders of the user's current directory.

Ex:- $ describe
$  content1 content2
Content3 content 4

### Step 5: Create a command 'describe' in /usr/local/bin. After writing the shebang protocol put 'ls' command and make the command executable using chmod.
<img width="676" height="47" alt="image" src="https://github.com/user-attachments/assets/d0b0a985-eed9-4656-a114-c89e830b2187" />
<img width="807" height="537" alt="image" src="https://github.com/user-attachments/assets/9d119d21-8a69-49df-ae1e-75d15b03fff5" />
<img width="758" height="54" alt="image" src="https://github.com/user-attachments/assets/bb1d098c-d4d7-449f-9d28-580d654f6263" />

### Step 6: Verify the command if its accesible from any directory.
<img width="711" height="955" alt="image" src="https://github.com/user-attachments/assets/52ead0fc-ecb8-4a37-a576-7c2bc23b94ef" />

### Step 7: Create research.txt file. compress and move it to a dir.
<img width="781" height="232" alt="image" src="https://github.com/user-attachments/assets/a427d6f2-e690-4886-86b5-73e865559866" />

### Step 8: Use find command to search the file. Check the status of the file whether its compressed or not and then uncompress it.

<img width="1479" height="347" alt="image" src="https://github.com/user-attachments/assets/8f9bc72d-8bcc-4cd5-80a0-e8abd5e53797" />

### Step 9: Adding umask 777 in /etc/profile enforces a default no-permission policy for new files at user login; source /etc/profile is used to apply it without re-login.

## Create a service with the name showtime , after starting the service, every minute it should print the current time in a file in the user home directory.

Ex:-
sudo service showtime start   -> It should start writing in file.
sudo service showtime stop   -> It should stop writing in file.
sudo service showtime status -> It should show status.

### Step 10: A showtime systemd service was created to write the current time every minute into a file in the user’s home directory and is controlled using start, stop, and status commands.


<img width="405" height="154" alt="image" src="https://github.com/user-attachments/assets/8dd599a3-cbf0-4384-bd0f-67d499cb483d" />

<img width="813" height="467" alt="image" src="https://github.com/user-attachments/assets/08057dea-64a9-4d21-ab0f-6bd1962b42dd" />

<img width="418" height="255" alt="image" src="https://github.com/user-attachments/assets/b246a8a0-b1da-4a59-95cc-9bdf1f75f945" />

