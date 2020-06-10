---
layout: post
title:  "10 linux commands you need to know for LFCS exam"
date:   2020-06-10 01:08:26 +0100
categories: coding
---

In this post, I will share ten "a bit more advanced" linux commands that I have encountered during my LFCS exam. Although these commands may not really be considered advanced, you will probably not meet them in any beginner linux tutorial. In terms of LFCS, most of them were necesarry in both of my LFCS exams for certain tasks. If you are preparing for the LFCS exam, you should definitely know these commands. By 'know' I mean that you should have experience using them and know what you are capable to do by combining different options.

1. `lsof`
    This bad boy can show a list of open files for a specific process. Tweaking the options, we can list only files for a specific service/port, which was one task in the exam.

2. `docker`
    is a all-in-one command for managing docker containers. Be sure to understand the whole procedure of running a container. That means searching for an image, pulling the image, creating, starting, detaching a container, listing all containers, removing a container and an image....

3. `virsh`
    is a all-in-one command for managing virtual machines. This includes creating a storage pool. Because installing and creating a virtual machine is not trivial, you will be given already created virtual machines, which you will have to configure.

4. `setenforce`/`getenforce`
    commands are used to set and get the SELinux modes. Because SELinux is more for LFCE, you are asked only to change the mode.

5. `chage`
    is used to change user password expiration. To force the user to change its password at the next login, set its expiry date to somewhere in the past.

6. `netstat`
    This very powerful command is used to print network connections and their statistics. It is being superseeded by the `ss` command.

7. `firewall-cmd`
   is a command line client of the firewalld daemon. It is used to manage runtime and permanent firewall configuration. This includes opening ports and assigning network devices to different zones,  

8. `mdadm`
    To manage raid devices, this is the only command you need to master.
    Be sure to know how to add a spare device and save the raid configuration to a file.

9. `cryptsetup`
    command is used to create/open/close an encrypted partition. 

10. `setfacl`/`getfacl` 
    are used to manage ACLs (Access Control List) on a linux machine.





