# Linux-Credly-Badges
Explanations of each badge earned through real world lab environments to test understanding of the Linux+ skills outlined by Comptia.

#

    Table Of Contents :
      1) Architecture
      2) Troubleshooting
      3) Networking
      4) Security
      5) Automation

      Note : Each badge hyper link is to Credly to verify the earning of the badge, and some additional 
              information.
#

##

<img width="268" alt="image" src="https://github.com/Austin44B/Linux-Credly-Badges/assets/134319619/861979c7-a22c-4d97-a579-745def653d5d">

In earning the [Linux+ Architecture](https://www.credly.com/badges/4910a7b1-647b-445f-8be6-9a7b1fa4e67c/public_urlv
) badge : 

There are many topics that were learned in achieving the architecture badge, And I will be going through them in more of a list style, with brief descriptions, I appreciate you taking the time to read my plethora of knowledge built through DA, If you have been reading other posts as well, I also appreciate you coming along with me through this journey, Stay Blessed :)

The first was learning basic Linux interactions, by logging into a command-line interface (CLI) Linux system and running some interactive commands such as elevating privileges, file management, tab completion and accessing the (man) manual pages for more help in regards to commands. 

Next up, we have a introduction to managing user accounts. I started with creating user accounts, within Linux, CentOS and Ubunto to perform basic tasks such as modifying comment fields to include user names and changing user default shells. I then explored how to remove user accounts, in which the home directory of one was preserved and the home directory of the other was not. 

I then continued on to managing group accounts, by doing nearly the same as managing user accounts, by creating some group accounts, then creating and adding users to the groups, displaying the group membership information, renaming groups and finally removing a group and checking the effect on members of that group. 

Moving on I then explored why it is important for Linux administrators to know how to configure and troubleshoot privilege escalation. For starters it is best practice for admins to avoid logging into root, to as not lead to accidental file deletion, misconfiguration or termination of services and many other irreversible actions. There are other ways to use root in more limited ways by first logging into a regular account and then elevating privileges, as required by using the su or the sudo command. By exploring and becoming familiar with the /etc/sudoers file, I was able to learn what control access the sudo command has.

Next let's take a peek at why Linux Admins should be proficient in understanding how to protect files and directories on a linux server by displaying and modifying linux permission using absolute or symbolic mode. First taking a look at existing permissions of a few files I then configured permissions for the file owner, the group, and all others for files and directories. 

It is also important to know how to configure special Linux permissions as a Linux admin, which also include SGID, the sticky bit and immutable flag. Especially in a scenario of employees of an organization being able to accidently delete or modify files pertaining to other groups or employees within an organization. By knowing special linux permissions the linux admin can adjust directories and files accordingly so situations like this don't happen.

Another feature of understanding permissions, is being able to configure access control lists, by doing so an admin can distribute specified permissions as needed for a single user in regards to directories or specific files, that are used by other departments within an organization.

We will wrap up the Architecture badge for Linux+ by acknowledging that one of the most useful skills as a admin, is having a foundational understanding to troubleshooting Linux permissions. The best way to become proficient with troubleshooting is having a general understanding of all the different permissions available and how to navigate them. From there, the more difficult scenarios one encounters and solves, will continue to grow and expand ones proficiency. Take each one, one breath at a time :) 

Thank you for making it this far, I hope that you may have pulled a few helpful ideas for you and your learning journey !

Best Wishes and Sincerely, 

Austin Barber


The CompTia Linux+ Architecture badge covers exam objectives in sections, 1.2, 2.2, 2.4, 2.5, 4.4.

##

<img width="278" alt="image" src="https://github.com/Austin44B/Linux-Credly-Badges/assets/134319619/d5a98fea-bf52-4f1d-bfba-51efcfdbbb61">

In earning the [Linux+ Troubleshooting](https://www.credly.com/badges/d8a5482d-93bf-4a72-a3fb-a8d38f61de78/public_url) badge : 

Kicking of the Troubleshooting badge for Linux+ skills, We take a look at managing file links by displaying and configuring hard and symbolic links to files. It is best practice to organize oneself, doing so by organizing the backup directory, particularly concerning log files. Even more in depth organization would be making subdirectories, each one a category that pertains to the backed-up logs, such as organizing logs by types like, Authentication logs, app logs, kernel logs and even by year generated. Additionally, rather than distinct copies of each log, we can link these files together so that they/re easier to manage. We can do things like linking home directories to a log in the backup directory and even create a home directory backup for authentication logs and turn those into hard and symbolic links. 

Another useful skill as a Linux Administrator is using file management commands, especially if entering a new company where you need to examine local configuration files to get an idea of user accounts, group accounts, security setttings, and other basic configuration information on the system. It is helpful to create a directory structure and populate with log files that are searched through using various commands, the touch command and redirectors are great commands for moving information around. 

Another powerful foundational skill as a Linux Administrator is knowing how to search for files based on various criteria. Configuration files, backups, user files, logs, and many other files can be lost or placed in unusual locations for security or other reasons. Using the find command we can locate files by name, owner, permissions, create date, and last accessed date, which will give us the ability to use commands like touch to redirect this information to new files to be archived.

Another important skill as a Linux Admin is becoming proficient in using a variety of text editors such as Vim, Nano, and Gedit. Each editor has its advantages and disadvantages, and you can install your editor of choice on your system, but note that Gedit is tpyically ( And recommended not to be ) installed on server systems as it is a GUI based editor. Vim is more difficult than nano, though offers more control and capabilities than nano, Vim is worth becoming proficient in, in the long run. 

( I keep using "Another", I'm just laughing at that ) 

Have you ever been working on something and forgot to save ? You know that feeling you get… Yeah, let's avoid that by taking responsibility as a Linux Admin by investing time into maintaining backups, Restore points, and using file compression for efficiency. Using the TAR command and other compression utilities to compress files, Is great for moving heavy backups to another location for archiving. Most commonly, /home, /etc, & /var/log are critical directories worth backing up via compressing so they consume less disk space when achieved. 

Learning how to manage .rpm software packages another useful skill for the toolbelt as a linux admin. In the case of me learning how, I used a Red Hat enterprise Linux-based system, to install, uninstall, manage, and query software using the RPM ( Red Hat Package Manager ) and the DNF ( Dandified Yum ) programs. Additionally I set up a local DNF repository and an Apache-based repository. By setting up local repositories it guarantees that corporate Linux systems access the latest stable software releases with reliable and fast LAN connectivity. 

In addition to managing .rpm packages, it is also important as a Linux Admin to know how to manage DEB packages, seeing as how there are many ways to solve problems depending on the working environment. In the case of a Debian-based system such as Ubuntu, knowing how to install, uninstall, manage, and query software using the dpkg ( Debian Package Manager )  and the APT ( Advanced Package Tool ) programs, one can set up local apt repository and an Apache-based repository that guarantees that corporate Linux systems have access to the latest stable software releases over the local reliable and fast LAN. 

Not all software is made the same… Well at least for those of us whom use Linux. With that, knowing how to compile a program and installing the software is a common practice, and there are two most compelling reasons to as why this is important to understand, one being that there isn't a ready-made package (RPM) for a particular application or that an application needs to be customized beyond default options. Tarball is how one can extract software and then configure, compile, and install a program. 

If you have managed to make it this far with me, then I applaud you, It is quite a reading journey, But I assure you, non the less, live life to it's fullest, smile, laugh, and have fun, you only have one life, and it's to beautiful to waste on regretting what you could have done, whom you could have been, Say hi to people, get to know people, and practice a attitude of patience, compassion and understanding for all those whom you communicate with in life :)

Let's wrap up the Troubleshooting badge by reflecting on how awesome it is as a Linux Admin to know how to use commands, so that we can download files from a web server using the wget and curl commands, and at that deploy a web server that we can use to host those files ! A common basic web server used is Apache. An additional note, is that wget and curl are useful automation commands :) because, time is the most valuable un-renewable resource in existence, so learn skills to the degree that you can automate them, freeing up more time to invest and focus on learning and solving other experiences. 

Thank you for investing time in reading along with me, It's quite a interesting and fun experience writing, and not know whom may be reading one day, Have a blessed day, and never give up on what you believe in <3

Best Wishes and Sincerely,

Austin Barber


The CompTia Linux+ Troubleshooting badge covers exam objectives in sections, 1.1, 1.2, 1.5, 1.7,  3.1.

##

<img width="268" alt="image" src="https://github.com/Austin44B/Linux-Credly-Badges/assets/134319619/d35ef022-1fef-42c3-bd29-5bfd95d57091">

In earning the [Linux+ Networking](https://www.credly.com/badges/8210bc2b-c863-474b-a503-07a7c23d3c1d/public_url) badge : 

Kicking off the networking badge for Linux+, We will briefly touch on the importance of understanding how to deploy storage and LVM ( Logical Volume Mixer ) as a Linux Admin. There are a few things to pay mind to while deploying such as installation, detection, partitioning, formatting and mounting. There are many tools and commands to display drive information and manipulate storage space. A good systematic approach to the process is first listing all block devices to determine which ones are unused and available for use, then creating a new standard partition on a disk, creating a new file system on the disk, mounting the disk and configuring it as a permanent storage device on the system and as needed creating a logical volume. 

Ever wonder why your system may be performing more slowly ? Taking a look at and understanding how to manage processes by tracking, monitoring, starting, stopping, and restarting processes is a great basic skill to have. We can display and manipulate processes by using tools such as ps and top. Additionally depending on the tasks that are more priority than others, Linux Admins can prioritize and reprioritize processes as needed as well background process.  

Following up Processes we can also manage services. As a Linux Admin, it is important to understand how to stop and start services, configure services to start when the system boots, and configure the system to boot to the GUI or CLI. Think of SSH for example, if needing to change settings within the config file, it is important to also know how to restart the service, so that it reads the new changes made. It is also helpful to know how to configure a system to boot to the CLI over the GUI, which is common for linux servers as it free's up resources for the server's services. 

Now that we have a idea of managing services, we can move into deploying services, following common steps for a sysadmin we can use the following as reference when configuring centralized logging and deploying a webserver. 
	
 1. Install the service
	
 2. Edit configuration files

 3. Restart the services
	
 4. Configure the firewall

 5. Test the service

When working with a new Linux system a great first thing to look at is Network settings and configuring them as needed. There are a variety of native Linux commands and tools in order to check networking settings and configure them. 

And finally and probably a personal favorite about IT and Cybersecurity in particular is configuring Remote administration, so that while I work within a system as needed, I can look up from my computer screen at the blue skies stretching into the horizon of this fast bright blue ocean on a tropical sunny day with a freshly made cup of juice from fruit picked nearby :)

So Make sure to understand how to configure SSH and establish remote administrative access by using programs such as cockpit, so files can be transferred between systems while working. Pay attention to SSH best practices such as key-based authentication and blocking root access over SSH. Practice installing and configuring remote administration tools such as cockpit and learning about managing file transfers using SCP and rsync. 

Have a blessed sunny day, and may life guide you down a journey of Peace and inner joy :)

Best Wishes and Sincerely,

Austin Barber

The CompTia Linux+ Networking badge covers exam objectives in sections, 1.3, 1.4, 1.7, 2.4, 4.2, 4.3, 4.5.

##

<img width="265" alt="image" src="https://github.com/Austin44B/Linux-Credly-Badges/assets/134319619/c9bc7aa8-0e4e-4613-a03a-7b6d9a257b26">

In earning the [Linux+ Security](https://www.credly.com/badges/08965461-6dc3-4f9e-a940-b3f34755314c/public_url) badge : 

As much as we could wish the best behavior from all those around us, there are those who are interested in pushing beyond boundaries to see what lies beyond. And from this, perhaps there is some information we wouldn't like to give out freely, so let's take a look at the Security badge for Linux+.

Starting off with configuring a firewall to control inbound and outbound information, like in the case of a server that supports a website and custom applications using non-standard port number. A good tool to scan firewalls is the Nmap utulity.
Following up the configuration of a firewall, is using Wireshark and tcpdump to intercept and display relevant information on a local network. After setting up a firewall, it is useful for security assessments to interpret the output of network traffic using these tools. 
Another key fundamental in security as a Linux Admin is hardening a Linux system by managing processes, software, sshd daemon, and umask. It can be especially helpful to understand how to harden a linux system when evaluating the security configuration for a system that is a database server. Uninstalling software that does not meet a server's purpose, setting security controls on directories, altering a system's umask and limiting access to a system via multiple methods.
Verifying file integrity using hashes is also a security fundamental to have understanding of. Detecting whether files have changed which helps security administrators understand the integrity of the contents. One can discover whether files have changed by using MD5 and SHA1 hash algorithms. Managing potential unexpected changed to files is important as changes may result from edits made by users or changes that may have been made by malicious threat actors, even file corruption during online downloads is worth monitoring. 
Lastly we have Security-Enhanced Linux (SELinux) which is a Linux kernel security module that provides a mechanism for supporting access control security policies, including mandatory access controls (MAC). With SELiunx we can evaluate and correct a system's security be assessing a SELinux status, and permanently setting a system to enforcing even after being rebooted. 

As always, Thank you for investing time in reading my blurb on what I learned will earning badges towards a Linux+ understanding, Have a wonderful day, and best wishes :) remember that we are all friends in life, enemies only exist within ourselves, so apply moral and ethical behavior to time invested utilizing the internet :)

Best wishes and Sincerely,

Austin Barber  

The CompTia Linux+ Security badge covers exam objectives in sections, 1.5, 2.1, 2.3, 2.5, 4.2.

##

<img width="194" alt="image" src="https://github.com/Austin44B/Linux-Credly-Badges/assets/134319619/ead70fe1-dfe9-4ff5-8631-468618ad6557">

In earning the [Linux+ Automation](https://www.credly.com/badges/18cda913-5579-47a9-b707-59e70be910d6/public_url) badge : 

By now we all can probably agree that AI is increasingly part of society, and whom knows where it'll take society in time, Maybe will have Cortana style AI in our space suits one day. But until tech evolves to that degree, for now we have AI chat bots like ChatGPT and then the good ol human brain to write code to automate tasks for us :)

A simple place to start is displaying shell script elements that are managed, and using these managed scripts to automate simple but repetitive tasks to increase efficiency and productivity as a Linux or even windows admin.
Thankfully someone(s) whom back in the day probably managed more than a lot of scripts, had an ingenious idea to make their life easier by creating a automation tool such as Ansible. We can leverage Ansible to configure SSH key-based authentication to ease automate remote administration, as well use Ansible's ad-hox commands to accomplish configuration tasks on remotely-managed nodes. 

Outside using Github as a blog to record my learning journey through Cybersecurity, Git can also be used to aid in development projects by configuring Git repositories, By installing and configuring Git on a server, and on a developer workstation, we can create and or manage a Git project, and pull that project from other workstations as needed for editing and push updated versions back to Git for review by individuals or teams before deployment. 

I'm still learning a lot, but something quite fascinating that has been more popular is using Containers, especially in cloud as they are far more efficient than Virtual Machines. One such container engine is called "Podman". Though I have not dabbled to much with Containers, from what I have heard, read, and the little I've used them. Proficiency with containers is great if one has any interested in cloud based technology. Pulling a test image and deploying test containers containing basic linux distributions, as well creating custom images using a dockerfile and deploying containers from it as well, is great practice to broaden understanding within this rabbit hole. 

Using a Multiboot software like GRUB2 is great for hardening as it is very powerful and allows various configuration changes. One such being the ability to make settings changes password protected as part of system management. 
Wrapping up the automation badge, when deploying Linux systems like CentOS or Ubunto, 
Watch for the following traits:
	
 • Root password
	
 • Disk partitioning
	
 • Software selection

And remember that though hypervisors and virtual machines are the easy norm, we have the power to leverage containers and scripting to make the deployment of Linux systems far more efficient as a Administrator :)

In summery, Make life easy, enjoy the journey, you only have this one life as far as we know, don't make it more difficult than it needs to be, sit back, enjoy the sensation of breath as it enters and exits through the nostrils and bring your conscious awareness to the sensation of the diaphragm as it fills with air, and exhales air, we only have so many of those sensation in our lifetime, make each one as smooth and enjoyable as possible. Especially when so much of our time and effort is focused on creating and adding value to society around us.

Best Wishes and Sincerely,

Austin Barber


The CompTia Linux+ Automation badge covers exam objectives in sections, 1.1, 1.6, 3.1, 3.2, 3.3, 3.4, 3.5.![image](https://github.com/Austin44B/Linux-Credly-Badges/assets/134319619/2f50a191-e777-4abc-8aa6-f41cc9ecfd02)
