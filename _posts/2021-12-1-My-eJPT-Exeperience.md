---
layout: post
title:  "My eJPT Experience"
date:   2021-12-1 20:00
categories: blog, certification, eJPT
---

## A Practical Test of My Knowledge

<img src="/assets/certs/eJPT_cert.png">

When I moved and then took a job in help desk, I was not sure if I was going to be able to keep up with the course work necessary to take the OSCP. As a way of testing the waters I decided I was going to take the INE Pentetration Testing Student course and take the eJPT. My reasoning for this is that it was a similar format, an online take at your own pace course followed by a practical examination, and the fact that as I have delved further into Cyber Security, I have found my self enjoying the offensive side of it and wanted to pursue a certification that is geared towards that. INE and eLearnSecurity, offer a free introduction course called Penetration Testing Student on their platform, which also helped convince me to give this a shot. I had heard really good things about the course as well, which was also a deciding factor as well.

## Penetration Testing Student Course

To sign up to the course, I went to INE's site and created an account. Once my account was created it gave me the option to choose various types of paths. I definitely saw some others I was interested in, but my goal for this was the PTS course and the eJPT, so I selected the Cyber Security Path. Upon selecting the path the PTS course was added to my account and I began my course. The course consisted of three sections; Pentetration Testing Prerequisites, Preliminary Skills and Programming, and Penetration Testing Basics. All three sections were well organized, as well as interesting. The material was covered in slides and then further delved into in videos. I found this worked well in teaching me the concepts.

Since there was a lot of content, I will highlight some of the concepts that helped me during the exam. One of the most useful lessons in the Prerequisites section was definitely the networking section. This helped me solidify some concepts like subnetting and routing. The routing section really came in handy when taking the exam, so if you are attempting to take the exam, I would make sure you understand the "Secret Server" lab. One of my favorite sections covered in this section was the data exfilitration via DNS. In my previous learnings, exfilitration was briefly covered, but not as in depth as this. It really had me see the creativty that is involved with offensive security.

The second section, Prelimiary Skills and Programming, was informative, as well as my favorite section of the course, however I did not use the skills i learned during this on the exam. I loved being able to write my exploits and malware. I ended up spending an entire night on the C++ making my own implant to steal information and even do more than the assignment needed. The third section was the meat and potatos when it came to the exam. The grand majority of the topics covered were all useful during the exam. Some of the section I would focus on would be the SQLinjection and SQLmap as well as well as the scanning and enumeration sections. I had previous taken multiple courses on offensive security, so the majority of it was a review, but I have found that absorbing material from different sources has helped me understand concepts at a deeper level.

The highlight of this course was definitely the labs. The labs would usually follow the coverage of a topic and would give you a challenge to solve. These challenges weren't just a rehash of the previous material, but instead applied it at a deeper level that required a little bit of thinking. They also provide the solution and it was interesting to see how I was able to sometimes reach the same end through different means. It defintely taught me a couple of new methods and ways to approach some challenges.

The entire course caps off with 3 black box assessments. These were very fun for me and really wrapped up the class as a whole tying together concepts from most of the lessons. The lab environment was easy to connect to and ran really well (the best out of all the other courses I have taken). The assessments have solutions to them included which again showed me some alternate ways to get to the end goal of compromising the machines. I must say that these were a great preparation for the eJPT test. They were defintely more challenging and pulled in some more advanced concepts, so if you get stuck on the labs, I wouldn't worry too much.

## The eJPT Exam

Once the course was completed I immediately bought my eJPT exam and planned to take it that weekend. In preparation, I reviewed the labs, as well as some concepts that I knew were crucial to the exam thanks to various eJPT resources I found online (I'll include those below). I logged into the eLearnportal and configured everything that I needed for the exam so that I could just click start and immediately get cracking. I made sure my notes were in order, and finally made sure I had my red bull.

I started the exam through the INE portal and was given a zip file with the letter of engagement, a ovpn profile to connect and some additional files. I really enjoyed getting the Letter of Engagement as it simulated what a real pentest would actually start with. Once I had those, I began the process of the test.

Now due to the Terms of Service with INE and eLearnSecurity, I can't discuss the specifics of the test, however I will do my best to go over what I experienced with no spoilers as well as some things I struggled with.

I was able to move through and answer 14 of the questions with certainity about 5 hours into the test. The remaining six, I struggled with at first. Slowly I chipped away, and was sure of another 2, but I didnt want to submit it without trying to compromise what I thought was the entire exam. This was where I hit a wall. I struggled with these questions over the remaining time for the exam (2 Days!), until I went back through and rewent through my steps. I found my error right away and was quickly able to answer the remainder of the questions.

Basically what had occured was that on my initial look at the targets, I had found what I thought was a vulnerability on one box and tried one remote code execution exploit on the box, and when it didnt work, I moved onto other boxes on the network that I had confirmed were vulnerable. I never gave a second thought about the initial box I had looked at, and this was where the answers to the questions I was missing were. Instead of going back to this box, I fell down some major rabbit holes, that emerged on later compromises, and spent a lot of time learning some advanced tactics, however these did not yield anything. It was only when I stepped back I was able to refresh my brain and that ended up helping me pass.

## My Thoughts and Lessons learned


The eJPT is defintely my favorite certification process and test thus far. I really enjoyed the test and I feel as though I learned even more in the test itself.

Looking back on the test itself, I can see where I went wrong and that cost me a lot of time. I learned that I shouldnt just jump at the first remote code execution that pops up, and I should take the time to try and exploit a machine in as many ways as possible.

Another lesson I learned is that when doing something that can be frustrating, its a great idea to take a step back and do something else. I am the type of person that literally will pound away at something until it finally cracks, no matter how much hair I pull from my head, but I learned this isnt always the best approach. Taking a step back was huge for me, although I wasn't able to completely clear my mind of what I was working on, but when I went to work on Monday I was able to refresh my mind and take a new approach towards what I was working on during the exam.

Something I did really well during this test was my note taking. Due to the fact that this test took me the span of the alloted time, I did a lot of going back through and retrying things. Due to the fact that I had taken such refined and detailed notes, I was able to pick up without having to reexploit, or think too long on what I did hours before. I would highly recommend using a note taking app and a screen shot application. My personal recommendations are Joplin and Greenshot.

Overall I really can't recommend this course and exam to people hoping to break into penetration testing. I don't know whether it has the HR recognition yet, but the course material and the overall exam were such a positive experience I think it is well worth the money!

## Resources that I used

I am hoping to whip up my own eJPT cheat sheet from my notes, after I have neutered them from anything that would break terms of services. I am hoping to have that up on my github in the next couple of days (depending how busy work is), but for now here are the community resources I used:

### Note taking
- [Joplin](https://joplinapp.org/) - a great open source note taking app, you can self host and encrypt your notes, and did i mention its open source! The community is great and there are a bunch of plugins you can customize the app with!
- [Greenshot](https://getgreenshot.org/) - a screenshot app that allows you to use the print screen key to bring up a crosshair to screenshot sections. It comes with a built in image editor too!


### Cheat Sheets
These are some cheat sheets I used for preparing for the exam as well as a reference with commands, a lot of them are just the notes from the courses boiled down into a digestable and easily parseable format.

- https://github.com/JasonTurley/eJPT/blob/main/cheat-sheet.md
- https://infosecwriteups.com/ultimate-guide-to-pass-ejpt-in-the-first-attempt-by-mayur-parmar-75effc877394
- https://community.ine.com/t/just-passed-ejpt-tips-thoughts-4-10-2021/423
- https://pentest.blog/explore-hidden-networks-with-double-pivoting/
- https://githubmemory.com/repo/tejasanerao/eJPT-Cheatsheet
