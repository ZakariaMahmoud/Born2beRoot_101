# Born2beroot

---

## Mandatory part

1. Download Debian from [https://www.debian.org/CD](https://www.debian.org/CD/http-ftp/)
2. Install VirtualBox from [https://www.virtualbox.org/wiki/Downloads](https://www.virtualbox.org/wiki/Downloads)
3. Open VirtualBox
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled.png)
    
4. Click  in **New** button  
    
    → Change Machine Folder to goinfre folder and select version Debian (64-bit)
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%201.png)
    

1. Click Continue → Continue → Create (Select Create a Virtual hard disk now) → Continue ( Select VDI) → Continue (Select  Dynamically allocated) → Create.
2. Right click in your Virtual machine and select Setting
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%202.png)
    
3. Select network and change from **NAT** to **Bridged Adapter** and click **OK.**
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%203.png)
    
4. Start your machine and select your Debian image downloaded in **step 1** and click start 
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%204.png)
    
5. choice from bar menu View → Scaled Mode (Host + C)
6. Select Install 
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%205.png)
    
7. Select English → United States → American English.
8. The hostname of your virtual machine must be your login ending with 42 (e.g.,
wil42). You will have to modify this hostname during your evaluation.
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%206.png)
    
9. You can set empty Domain name
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%207.png)
    
10. You have to implement a strong password policy.
    - A strong password must be at least 8 characters long.
    - It should not contain any of your personal information — specifically, your real name, username or your company name.
    - It must be very unique from your previously used passwords.
    - It should not contain any word spelled completely.
    - A strong password should contain different types of characters, including uppercase letters, lowercase letters, numbers and characters.
    
    💡 You can use Secure Password Generator tool :  [https://passwordsgenerator.net/](https://passwordsgenerator.net/)
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%208.png)
    
11. Re-enter password to verify
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%209.png)
    
12. Full name for the new user
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2010.png)
    
13. username for your account
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2011.png)
    
14. Choose a password for the new user
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2012.png)
    
15. Re-enter password to verify
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2013.png)
    
16. Select your time zone
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2014.png)
    
17. Select Guided - use entire disk and set up encrypted LVM
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2015.png)
    
18. Select disk to partition 
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2016.png)
    
19. Select Separate /home partition 
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2017.png)
    
20. Write the changes to disks and configure LVM? Select <Yes>
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2018.png)
    
21. You need to choose a passphrese to encrypt SCSI.
    
    **What is Passphrase?**
    
    A *passphrase* is similar to a password. However, a password generally refers to something used to authenticate or log into a system. A password generally refers to a secret used to protect an encryption key. Commonly, an actual encryption key is derived from the passphrase and used to encrypt the protected resource.
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2019.png)
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2020.png)
    
22. Amount of Volume group to use for guided partitioning
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2021.png)
    
23. Select Finish partitioning and write changes to disk
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2022.png)
    
24. Select **→** **Yes ←** 
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2023.png)
    
25. Select  No
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2024.png)
    
26. Select Debian archive mirror countr
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2025.png)
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2026.png)
    
27. Select **Yes**
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2027.png)
    
28. Deselect **SSH server** and click Continue.
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2028.png)
    
29. Install the GRUB boot loader to your primary drive
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2029.png)
    
30. Select /dev/sda 
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2030.png)
    
31. Click in Continue
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2031.png)
    
32. Enter your **Passphrase (Step 23).**
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2032.png)
    
33. Enter Your login and your password
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2033.png)
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2034.png)
    
34. `lsblk` **** *lists information about all available or the specified block device*
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2035.png)
    

---

- **What is APT?**
    
    **A**dvanced **P**ackage **T**ool, **is a collection of tools used to install, update, remove, and otherwise manage software packages on Debian.** and its derivative operating systems, including Ubuntu and Linux Mint. APT works through the use of *repositories*, or special directories that hold collections of software packages.
    
    You can check this file 
    
    ```c
    cat /etc/apt/sources.list
    ```
    
- **What is Aptitude**
    
    Aptitude is front-end to advanced packaging tool which adds a user interface to the functionality, thus allowing a user to interactively search for a package and install or remove it. Initially created for Debian.
    
- **Apt and Aptitude**
    - Apt-get being a lower level package manager is restricted only to command line, while Aptitude being a higher-level tool has a default text-only interactive interface along with option of command-line operation by entering required commands.
    - While apt-get lacks UI, Aptitude has a text-only and interactive UI
    - **Aptitude has a better package management than apt-get**
- apt vs apt-get
- **AppArmor**
    
    [AppArmor](http://wiki.apparmor.net/) is a Mandatory Access Control framework. When enabled, AppArmor confines programs according to a set of rules that specify what files a given program can access. This proactive approach helps protect the system against both known and unknown vulnerabilities.
    
- **SSH**
    
    SSH or Secure Shell is a network communication protocol that enables two computers to communicate (c.f http or hypertext transfer protocol, which is the protocol used to transfer hypertext such as web pages) and share data. An inherent feature of ssh is that the communication between the two computers is encrypted meaning that it is suitable for use on insecure networks.
    
    SSH provides a layer of security for information transfer between machines. Some important use cases for SSH are:
    
    - Remote access – SSH ensures encrypted remote connections for users and processes.
    - File transfers – SFTP, a secure file transfer protocol managed by SSH, provides a safe way to manipulate files over a network.
    - Tunneling – This encapsulation technique provides secure data transfers. Tunneling is useful for accessing business-sensitive online materials from unsecured networks, as it can act as a handy VPN alternative.
    - Network management – The SSH protocol manages network infrastructure and other parts of the system.
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2036.png)
    
1. Install SSH
    
    ```bash
    su - # Connect  as root
    apt update
    apt install openssh-server -y
    ```
    
    Verify the installation by running the following command
    
    > The **systemctl** command is a utility which is **responsible for examining and controlling the systemd system and service manager**.
    > 
    
    ```bash
    systemctl status ssh
    ```
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2037.png)
    
    💡 The default port for SSH client connections is 22
    
2. Install Vim and Change port of SSH from 22 to 4242.
    
    ```bash
    apt install vim -y # Install Vim 
    find / -name "sshd_config"
    vi /etc/ssh/sshd_config # update again 
    ```
    
    - iLocate line that read as follows:
    
    ```bash
    #Port 22
    #PermitRootLogin prohibit-password
    ```
    
    - Change to :
    
    ```bash
    Port 4242 
    PermitRootLogin no
    ```
    
    Save and close the file.
    
3. Restart service SSH and copy ip address of Debian
    
    ```bash
    systemctl restart ssh
    ip address # my ip address = 10.12.178.178
    ```
    
4. Open the SSH terminal on your machine and run the following command:  ssh your_username@host_ip_address and enter your password.
    
    ```bash
    ssh zmahmoud@10.12.178.178 -p 4242 # -p = Port
    ```
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2038.png)
    
5. Configure your operating system with the UFW firewall and thus leave only port 4242 open.
    - **What is UFW ?**
        
        UFW, or Uncomplicated Firewall, is an interface to `iptables` that is geared towards simplifying the process of configuring a firewall. While `iptables` is a solid and flexible tool, it can be difficult for beginners to learn how to use it to properly configure a firewall. If you’re looking to get started securing your network, and you’re not sure which tool to use, UFW may be the right choice for you.
        
    - Install UFW
        
        ```bash
        su - 
        apt update
        apt install ufw
        ```
        
    - Enable/Start firewall on Debian
        
        ```bash
        ufw enable
        ```
        
    - Check Status of UFW
        
        ```bash
        ufw status
        ```
        
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2039.png)
    
    - Allow only port 4242 open
        
        ```bash
        ufw allow 4242
        ```
        
6. **IF You will** change your hostname follow these steps.
    - Connect as root in your SSH terminal
    
    ```bash
    su -
    ```
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2040.png)
    
    - Display the current hostname for Debian Linux
    
    ```bash
    hostnamectl
    ```
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2041.png)
    
    - For example, to change the system hostname to zmahmoud1337 (This command update file `/etc/hostname`)**.**
        
        The syntax is as follows: hostnamectl set-hostname {name-here}
        
        ```bash
        hostnamectl set-hostname zmahmoud1337
        ```
        
        ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2042.png)
        
    - Update file `/etc/hosts`
        - Before
        
        ```bash
        #Connect As root
        su -
        vi /etc/hosts
        ```
        
        ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2043.png)
        
        - After
        
        ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2044.png)
        
    - Reboot your machine
    
    ```bash
    reboot
    ```
    
    - I will change it again to **zmahmoud42**  😄
7. Implement a strong password policy.
    - To set up a strong password policy, you have to comply with the following requirements.
        - Your password has to expire every 30 days.
        - The minimum number of days allowed before the modification of a password will
        be set to 2.
        - The user has to receive a warning message 7 days before their password expires.
        - Your password must be at least 10 characters long. It must contain an uppercase
        letter and a number. Also, it must not contain more than 3 consecutive identical
        characters.
        - The password must not include the name of the user.
        - The following rule does not apply to the root password: The password must have
        at least 7 characters that are not part of the former password.
        - Of course, your root password has to comply with this policy.
    
    ```bash
    vi /etc/login.defs
    ```
    
    - Update **PASS_MAX_DAYS** and **PASS_MIN_DAYS** and **PASS_WARN_AGE** and save file.
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2045.png)
    
    - Update old users password policy
        - user root
        
        ```bash
        chage root -M 30 -m 2 -W 7
        chage root -l
        ```
        
        ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2046.png)
        
        - user zmahmoud `(your_username)`
        
        ```bash
        chage zmahmoud -M 30 -m 2 -W 7
        chage zmahmoud -l
        ```
        
        ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2047.png)
        
    - Force Users To Use Strong Passwords
    
    → We will use the PAM (Pluggable Authentication Modules) module to set the default password quality requirements for the system passwords, you need to install an additional module called [libpam-pwquality](https://linux.die.net/man/5/pwquality.conf). To do so, run the following command from Terminal:
    
    ```bash
    apt update -y
    apt install libpam-pwquality -y
    ```
    
    → After the package installation, the password policies are defined in **/etc/security/pwquality.conf** file. Before making any changes, backup this file.
    
    ```bash
    cp /etc/security/pwquality.conf /etc/security/pwquality.conf.bak
    ```
    
    → You’ll need to edit the /etc/security/pwquality.conf file to set password requirements.
    
    ```bash
    vi /etc/security/pwquality.conf
    ```
    
    - The possible options in the file are:
        
        **difok**
        
        Number of characters in the new password that must not be present in the old password. (default 5)
        
        **minlen**
        
        Minimum acceptable size for the new password (plus one if credits are not disabled which is the default). (See ***[pam_pwquality](https://linux.die.net/man/8/pam_pwquality)**(8)*.) Cannot be set to lower value than 6. (default 9)
        
        **dcredit**
        
        The maximum credit for having digits in the new password. If less than 0 it is the minimum number of digits in the new password. (default 1)
        
        **ucredit**
        
        The maximum credit for having uppercase characters in the new password. If less than 0 it is the minimum number of uppercase characters in the new password. (default 1)
        
        **lcredit**
        
        The maximum credit for having lowercase characters in the new password. If less than 0 it is the minimum number of lowercase characters in the new password. (default 1)
        
        **ocredit**
        
        The maximum credit for having other characters in the new password. If less than 0 it is the minimum number of other characters in the new password. (default 1)
        
        **minclass**
        
        The minimum number of required classes of characters for the new password (digits, uppercase, lowercase, others). (default 0)
        
        **maxrepeat**
        
        The maximum number of allowed same consecutive characters in the new password. The check is disabled if the value is 0. (default 0)
        
        **maxclassrepeat**
        
        The maximum number of allowed consecutive characters of the same class in the new password. The check is disabled if the value is 0. (default 0)
        
        **gecoscheck**
        
        If nonzero, check whether the words longer than 3 characters from the GECOS field of the user's passwd entry are contained in the new password. The check is disabled if the value is 0. (default 0)
        
        **badwords**
        
        Space separated list of words that must not be contained in the password. These are additional words to the cracklib dictionary check. This setting can be also used by applications to emulate the gecos check for user accounts that are not created yet.
        
        **dictpath**
        
        Path to the cracklib dictionaries. Default is to use the cracklib default.
        
        **usercheck=N**
        
        If nonzero, check whether the password (with possible modifications) contains the user name in some form. It is not performed for user names shorter than 3 characters. (default 1)
        
        **usersubstr=N**
        
        If greater than 3 (due to the minimum length in usercheck), check whether the password contains a substring of at least *N* length in some form. (default 0)
        
        **enforcing=N**
        
        If nonzero, reject the password if it fails the checks, otherwise only print the warning. This setting applies only to the pam_pwquality module and possibly other applications that explicitly change their behavior based on it. It does not affect [pwmake(1)](https://www.mankier.com/1/pwmake) and [pwscore(1)](https://www.mankier.com/1/pwscore). (default 1)
        
    
    → Change.
    
    - From
    
    ```bash
    #difok = 7
    #minlen = 8
    #dcredit = 1
    #ucredit = 1
    #maxrepeat = 3
    #usercheck = 1
    #enforce_for_root
    ```
    
    - To
    
    ```bash
    difok = 7
    minlen = 10
    dcredit = -1
    ucredit = -1
    maxrepeat = 3
    usercheck = 1
    enforce_for_root
    ```
    
    → Change the settings to fit your desired password policy, then reboot your system.
    
    ```bash
    reboot
    # Go to VM and unlock disk sda5_crypt (Enter password)
    ```
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2048.png)
    
8. **Repeat step 42.**
    
    Open the SSH terminal on your machine and run the following command:  ssh your_username@host_ip_address and enter your password.
    
    ```bash
    ssh zmahmoud@10.12.178.178 -p 4242 # -p = Port
    ```
    
9. Change password of account ( your_username).
    
    the command **passwd username** (where **username** is the name of the user whose password you want to change).
    
    ```bash
    passwd zmahmoud
    ```
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2049.png)
    
    <aside>
    ⚠️ After setting up your configuration files, you will have to change all the passwords of the accounts present on the virtual machine, including the root account.
    
    </aside>
    
10. Install and configure sudo following strict rules.
    
    ```bash
    apt update
    apt upgrade
    apt install sudo
    ```
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2050.png)
    
    - Create group **user42**
    
    ```bash
    groupadd user42
    ```
    
    If you will execute command sudo it necessary add user (zmahmoud) to sudo group.
    
    - For add `your_user` to sudo and user4 groups.
    
    ```bash
    su -
    usermod -aG sudo zmahmoud
    usermod -aG user42 zmahmoud
    ```
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2051.png)
    
    - logout user **zmahmoud** and login again using SSH (**Step 42)**
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2052.png)
    
    - Create new user and add it to sudo group
    
    ```bash
    su -
    adduser newuser
    usermod -aG sudo newuser
    groups newuser
    ```
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2053.png)
    
    - For list all users in your machine you can use :
    
    ```bash
    sudo cat /etc/passwd
    ```
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2054.png)
    

48. To set up a strong configuration for your sudo group, you have to comply with the
following requirements:

```bash
sudo mkdir /var/log/sudo # The log file has to be saved in the /var/log/sudo/
sudo visudo # (/etc/sudoers)
```

→ Add next lines to sudoers file

- Add your username to User privilege specification
    
    ```bash
    zmahmoud42	ALL=(ALL:ALL) ALL
    ```
    
    ![Frame 1 (1).png](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Frame_1_(1).png)
    
- Authentication using sudo has to be limited to 3 attempts in the event of an incorrect password.
    
    ```bash
    Defaults	passwd_tries=3
    ```
    
- A custom message of your choice has to be displayed if an error due to a wrong
password occurs when using sudo.
    
    ```bash
    Defaults	badpass_message="Password is wrong, please try again"
    ```
    
- Each action using sudo has to be archived, both inputs and outputs. The log file
has to be saved in the /var/log/sudo/ folder.
    
    ```bash
    Defaults	logfile="/var/log/sudo/sudo.log"
    Defaults	iolog_dir="/var/log/sudo"
    Defaults	log_input
    Defaults	log_output
    ```
    
- The TTY mode has to be enabled for security reasons.
    
    ```bash
    Defaults  requiretty
    ```
    
- For security reasons too, the paths that can be used by sudo must be restricted.
    
    Example:
    /usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/snap/bin
    
    ```bash
    Defaults secure_path="/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin:/snap/bin"
    ```
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2055.png)
    
1. Finally, you have to create a simple script called [monitoring.sh](http://monitoring.sh/). It must be developed in bash.
    
    ```bash
    su - # Connect  as root
    apt install net-tools
    ```
    
- Create `*monitoring.sh`*  in /sbin directory
    
    ```bash
    # Connect  as root 
    cd /sbin
    vi monitoring.sh
    ```
    
- Copy code and past in `*monitoring.sh` file*
    
    ```bash
    #!/bin/sh
    # https://github.com/ZakariaMahmoud
    total_mem_kilo=$(free --kilo | grep "Mem:" | awk '{print $2}')
    total_mem_mega=$(free --mega | grep "Mem:" | awk '{print $2}')
    used_mem_kilo=$(free --kilo | grep "Mem:" | awk '{print $3}')
    used_mem_mega=$(free --mega | grep "Mem:" | awk '{print $3}')
    memory_per=`free --kilo | grep "Mem:" | awk '{printf("%.2f", $3*100/$2)}'`
    disk_usage_gb=$(df  --total -h | grep "total" | awk '{print $2 "b"}')
    disk_usage_m=$(df  --total -m| grep "total" | awk '{print $3}')
    cpu_physical=`cat /proc/cpuinfo | grep physical\ id | sort | uniq | wc -l`
    cpu_load=`top -n1 -b | grep "%Cpu(s):" | awk '{print $2}'`
    
    if [ `lsblk | grep lvm | wc -l` -gt 0 ]
    then
    	lvm="yes"
    else
    	lvm= "no"
    fi
    
    wall "	#Architecture: `uname -a`
    	#CPU physical : `cat /proc/cpuinfo | grep physical\ id | sort | uniq | wc -l`
    	#vCPU : `cat /proc/cpuinfo | grep processor | wc -l`
    	#Memory Usage: $used_mem_mega/$total_mem_mega"MB "($memory_per%)
    	#Disk Usage: $disk_usage_m/$disk_usage_gb
    	#CPU load: $cpu_load%
    	#Last boot: `who -b | awk '{print $3 " " $4}'`
    	#LVM use: $lvm
    	#Connexions TCP : ` netstat | grep "ESTABLISHED" | wc -l` ESTABLISHED
    	#User log: `who | wc -l`
    	#Network: IP `hostname -I`(`ip a | grep link/ether | awk '{print $2}'`)
    	#Sudo : `journalctl -q | grep sudo | grep TTY | wc -l` cmd"
    ```
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2056.png)
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2057.png)
    
- Add execute permission to `monitoring.sh`.
    
    ```bash
    chmod +x monitoring.sh
    ./monitoring.sh # Test script
    ```
    
- Use Crontab
    
    The cron command-line utility, also known as cron job is a job scheduler on Unix-like operating systems. Users who set up and maintain software environments use cron to schedule jobs to run periodically at fixed times, dates, or intervals. 
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2058.png)
    
- Type the following command to enter crontab
    
    ```bash
    # Connect  as root 
    crontab -e -u sbin
    ```
    
- To get crontab to run a `monitoring.sh` every 10 minutes you could type as follow
    
    ```bash
    */10 * * * * /sbin/monitoring.sh
    ```
    
    **Save and close the file**
    
    - Where
        1. The asterisk (*) operator specifies all possible values for a field. For example, an asterisk in the hour time field would be equivalent to every hour or an asterisk in the month field would be equivalent to every month.
        2. The */10 is used in conjunction with ranges. For example, 0-23/2 can be used in the hours field to specify command execution every other hour. Steps are also permitted after an asterisk, so if you want to say every two hours just use */2. In this example, */10 in the minutes field to specify command execution every 10 minute.
        
    
    ![Untitled](Born2beroot%2054151631cd3f41fd860740a58b9eee40/Untitled%2059.png)
    

---