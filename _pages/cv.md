---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /cv
---
PDF version available [<u>here</u>](https://piggy1228.github.io/files/CV_Kexin.pdf)
{% include base_path %}


Education
======
* [<u>University of Pennsylvania</u>](http://www.cis.upenn.edu/index.php), May 2020
    * Master of Science in Engineering: Computer & Information Science
    * GPA: 3.61/4.0

* [<u>Rensselaer Polytechnic Institute</u>](https://science.rpi.edu/computer-science), May 2018
    * Bachelor of Science: Computer Science dual Mathematics
    * GPA: 3.97/4.0 (Summa Cum laude)


Coursework/Skills
======
* Advanced Mathematics& Statistics: Linear Algebra, Mathematical Statistics, Mathematical Models of Operation Research, Computational Optimization
* Advanced Computer Science: Software Systems, Database & Info Systems, Big Data Analytics, Operating System, Machine Learning, Intro to Artificial Intelligence , Programming Language, Natural Language Processing
* Programming Languages: Proficient in Python,C++/C, Sql, MongoDB, Neo4j, Matlab, R, Java, Prolog, Haskell


Projects
=====
<ul>{% for post in site.portfolio %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>


Research
======
* __Iris Recognition (Python)__, [<u>Duke Kunshan University</u>](https://dukekunshan.edu.cn/zh), July 2018 - Aug 2018
    * Given an eye image, extracted the iris section and compared with original iris data to verify user identity
    * Used traditional computer vision method to recognize and capture the Iris from eye images
    * Removed noises, such as reflection in pupils and glasses by distinguishing relative pixel color

* __Circadian Rhythms (R)__, [<u>Rensselaer Polytechnic Institute</u>](https://science.rpi.edu/computer-science), June 2017 - Aug 2017
    * Analyzed three mouse genes' performance in forty-eight hours under control experiment
    * Wrote a bootstrapping R program to observe the same parameter properties of the three mice
    * Obtained the sampling distribution and confidence interval to analyze the circadian rhythms of mice

Professional Experience
======
* __Software engineering Intern__, [<u>Twitch</u>](https://www.twitch.tv/), San Francisco, Jun 2019 - Aug 2019
* Video Transcoder Team(Golang), software engineering Intern
    * Parsed closed captions from live streaming video to text format and sent to viewers through WebRTC on server
    side, received and displayed closed captions with video on client side
    * Triggered chrome to send transport feedback by adding extension header in RTP packet, parsed transport feedback
    from RTCP packet in WebRTC
    * Implemented congestion control algorithm, analyzed feedback of RTT, REMB and Packet loss from browser to
estimate the bandwidth in order to automatically switch renditions for viewers


* __Teaching Assistant__, [<u>Rensselaer Polytechnic Institute</u>](https://science.rpi.edu/computer-science), Jan 2017 - May 2018
    * Duties included: Mentoring Lab, Hold office hours and grading
    * Courses:
        - [<span class="underline-on-hover" style="color:#0000FF">CSCI-2200 Foundation of Computer Science</span>](http://www.cs.rpi.edu/academics/courses/spring17/focs/) ([Prof. Trinkle](http://www.cs.rpi.edu/~trink/))
        - [<span class="underline-on-hover" style="color:#0000FF">CSCI-2300 Introduction to Algorithm</span>](http://www.cs.rpi.edu/~zaki/www-new/pmwiki.php/IntroAlgorithms/Main) ([Prof. Zaki](http://www.cs.rpi.edu/~zaki/www-new/pmwiki.php/Main/HomePage))
        - [<span class="underline-on-hover" style="color:#0000FF">MATP-4620 Mathemtical Statistics</span>](https://www.coursehero.com/file/16237124/Course-Intro/) ([Prof. Chan](https://scholar.google.com/citations?user=tmYLtDgAAAAJ&hl=en))



<!--
Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>


Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Service and leadership
======
* Currently signed in to 43 different slack teams
-->
