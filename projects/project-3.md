---
layout: project
type: project
image: images/abimage.PNG
title: Address Book Application
permalink: projects/addressbook
date: 2015
labels:
  - C
  - Software Engineering
  - Unix Shell
summary: An Address Book application that I had created for ICS 212.
---

This address book application was one of the major projects for ICS 212, a program structure class at the University of Hawaii at Manoa. The address book in question was to be programmed in C and would be run in a computer's terminal, in this case, a remote unix shell was the basis of the address book. Because fo this, the program utilizes a simple text based interface. 

The main functions of the application include the features to add new records which hold important pieces information for a person, search for records, delete and modify records. On termination of the program, a save file will be created to hold the records that have been added during the program's run time. Upon starting the program, it will check for the file. If there is one, then it will read that file and load all the records kept on it; otherwise, the program will start with no records. During runtime of the program, the records are held in a linked list.

Beyond the aforementioned features, there is also a debug mode which can activated upon executing the program. Being in this mode prints important information pertaining to the run time of the program, such as the parameters that have been passed into the functions that make up the different features of the program. 

As this program was developed for use in a unix shell, it was also developed within the shell. The program was compiled and linked using shell commands, and a .make file was created to make compilation of the code less redundant. 

From this project I had learned how to organize a program and implement one in C. I had achieved an understanding of how programs are structured and how a program is designed with the user in mind. With each option that the user wishes to perform, there is always a feedback confirming what has happened. This was also an excellent experience in working in a unix shell, which is entirely controlled by commands. These commands can be taken further with scripts, that can create enhanced commands specific to what one is doing in the shell. As this was a solo project, all of the problems I had learned to solve myself. 



You can find the source code here: <a href="https://github.com/russellomo/Address-Book-ICS212"><i class="large github icon "></i>AddressBook</a>


