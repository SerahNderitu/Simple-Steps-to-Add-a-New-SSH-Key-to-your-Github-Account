# Simple-Steps-to-Add-a-New-SSH-Key-to-your-GitHub-Account

SSH key is an access credential used to connect and authenticate to remote servers and services. It serves a similar purpose as user names and passwords, although system administrators and power users typically use the keys to automate procedures and achieve single sign-on.

## Basic Functions of an SSH Key

SSH key serves various purposes. These are some of the functions you can get from the SSH key.

* Used inside file transfer tools and configuration management tools for managing networks, operating systems, and configurations.   

* SSH keys enable the automation that makes modern cloud services and other computer-dependent services possible and cost-effective. They offer convenience and improved security when properly managed.

* They provide identity and access management by controlling who can access what. 


## Using SSH Key on Github
You can log in to GitHub using SSH keys without providing your username and unique access token each time. Commits can also be signed with an SSH key.

SSH can be used to read and write data in repositories on GitHub. A private key file on your local computer is used for authentication when connecting via SSH.

## Adding SSH Key to GitHub

Before continuing with this guide, make sure you have the SSH key already generated on your local machine. If you don’t have the SSH key yet, follow our guide on [how to generate a new SSH key](https://github.com/SerahNderitu/How-to-Generate-a-New-SSH-Key-on-Linux-and-Add-it-to-the-SSH-Agent).

You can check if you already have any SSH keys before you generate a new one. Just go to the terminal and enter ``ls -al ~/.ssh.`` If any key exists, they will be listed in your .ssh directory.

You can authenticate Git activities through the SSH key if you already have it. Alternatively,  generate a new SSH key if you don't have one or if you don't want to use the one that is already available.

To allow SSH access to your account after generating an SSH key pair, you must add the public key to GitHub.To add your SSH key to GitHub, follow the following steps;

### Step 1: Locate and Copy the SSH Key

Locate the **.ssh** folder, open the file in your preferred text editor, and copy the contents to your clipboard. 
Or you can copy your key on the terminal using ``$ cat ~/.ssh/id_rsa.pub``. Then select and copy the contents of the id_rsa.pub file as displayed on your terminal screen. If you don’t have the id_rsa key, it could be id_ed25519.pub or any other.

### Step 2: Open the GitHub Settings Page

Click your profile picture in the top-right corner of your GitHub page, then click **Settings**. 

### Step 3: Locate the Access Section

On the **Access** section located in the sidebar, click **SSH and GPG keys** 

### Step 4: Add SSH Key

Choose either Add SSH key or New SSH key. 

### Step 5: Give SSH Key a Title

Give the new key a descriptive name in the **Title** field. Choose a title that you want. 

### Step 6: Indicate the Key Type

Choose the key type, either signing or authentication.

### Step 7: Paste Key

Copy and paste your public key into the **Key** section. 

### Step 8: Click “Add SSH key”

When prompted, verify access to your GitHub account. 


That is it! You’ve successfully added a new SSH key to your GitHub account and now you use it to connect and authenticate to remote servers and services. 



 

