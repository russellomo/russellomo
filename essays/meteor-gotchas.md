---
layout: essay
type: essay
title: Meteor Gotchas
date: 2017-03-09
labels:
  - Software Engineering
  - Meteor
---

## Nothing Ventured, Nothing Gained ##

So far into this Software Engineering journey, I've learned several different tools and techniques used in 
creating web applications. And while each subject on their own was not the most difficult experience to 
comprehend and apply, it was the bridging of these various skills which proved to be very rigourous and costed me
some hours of sleep this past week. The bridge itself you might ask? The Meteor Framework. While the framework 
itself is actually pretty straightforward, to actually make use of the framework is to bring all of your skills
together to actually lay something on it. Thus, there were bound to be complications. 

One such complication that I had ran into in recreating the digits application (a tutorial application in
which was used to apply my skills in Meteor, essentailly a contact book) and still have problems with is the 
tracking of file imports into both the server and the client javascript files. When working in an environment designed for implementing a web application, you'll be greeted with various directories and files that have simiar names. For example, in both  the client and the server directories of the digits application there exists a file "main.js". And while this  is a standard for web development in Meteor, it is nonetheless confusing for an amateur such as myself. 

Anyhow, in order for an application to work with all the files you write, those files must be imported to these main.js files, otherwise the application won't work properly, if not at all. This was an issue that can only be remediedby practice really. While I have been only recently making sure that all of my imports have been made, to get to this point was to understand the design of the application and careful attention to files that I have made. 

The second complication that I ran into was with the clash of three skills, MongoDB and HTML, in the implementation of the digits edit contact page. MongoDB, similar to SQL, uses schema to define the entries within the databese. And much like SQL, it is case sensitive. In the HTML of the page, the fields that are used to edit 
the page are directly linked to the fields in MongoDB. Needless to say that the reason why my fields never updated initailly was due to a lone captial letter. 

Though this experience in web development has been a little rough, its struggling through these things that really show where you can improve. 