# Proposal GSoC 2020 

# Writing an Analyzer for Arduino libraries.

# Abstract
The Goal of this project will be, to make a program that performs checks onto arduino libraries to assure its quality and generate a detailed summary that gives all the information about it.
# Technical Details
A General/Simple overlook of this Project in my mind looks something like this.

Step 1: Get the Library.

Step 2: Analyze the Library just like a compiler would read the code.

Step 3: Generate a Detailed Summary of the Findings.

Now I know it’s not that easy but it’s the most abstract form of the problem and I’m going to use these steps and break this problem down into more little problems and then solve it from bottom up.

For Step 1, I need to get the Library that I want to analyze. But the Libraries are not in one place they are scattered throughout the whole website. For that I need some kind of a search engine that would help me find these libraries. The solution to that would be to make a crawler that searches Github for Arduino Libraries that are not in the Library Manager Index and also finds the Bundled Libraries that come with most Arduino Boards Platform. This Script would be written in python and would use Scrapy to crawl through github and find these Libraries.

I’ve found this tutorial to be the most helpful for building a Crawler with Scrapy. And I’ll use this as a base for building my own Crawler.

For Step 2, Once I have the Crawler working. The metadata generated from the crawler would be used to grab a library and process it through my analyzer code. The C++ Static analyzer would be written in C++ as I’m more comfortable with it  and it would look though the code for common errors and these following things.
 
 
# Schedule of Deliverables

Here should come a list of your milestones. This list is a start based on the difference phases of GSoC. Use it as a start. You can/should add more details for each phase by breaking it down into weeks or set specific targets for each phase. Each target should be split into sub task with a time estimate, work breakdown structures are helpful here.

# Community Bonding Period

Getting acquainted with the code base and the procedure that needs to be followed to submit code and get it reviewed
# Phase 1
Deliverable 1
Deliverable 2
...
# Phase 2
Deliverable 1
Deliverable 2
...
# Final Week

At this stage you should finish up your project. At this stage you should make sure that you have code submitted to your organization. Our criteria to mark your project as a success is to submit code before the end of GSoC.
Development Experience

# Do you have code on GitHub? Can you show previous contributions to other projects? 
I have previously participated in Hacktoberfest 2018 during my junior high school year and contributed to github projects.

For this Proposal I submitted a pull request to the Arduino Servo Library.

https://github.com/arduino-libraries/Servo/pull/44
 
# Did you do other code related projects or university courses?

I had made a game in the previous semester for my Programming Course final Project.
https://github.com/hmzakhalid/Dodge-Em
 
# Do you have experience with Arduino?

Yes, I’ve used Arduino Uno last year for a High School science fair where I made a line following and object detection robot. It was my first time working with hardware and it was a complete blessing to use. It was the best experience ever.

Here’s a Picture of my Robot: https://i.imgur.com/UNTtIj1.jpg
# Other Experiences

I have always been interested in everything, I started out with Graphic Design and Web Development. I have 5 Years of Experience in Photoshop and Graphic/Web Design. The Biggest Project I worked on is NaSCon. It’s an Annual Event of my University. I have made this whole website Dynamic using Django and reduced the amount of code written tremendously. It was my first time working with Django and I learned it by doing it practically.

# Why this project?

I chose this project because it’s challenging and i’ve never done something like this before. This project is a good opportunity for me to announce myself to the Open Source community 

# Do you have any other commitments during the GSoC period?

I would have been completely available during the Summer from (May 18th to August 17th) but due to the recent COVID-19. All the educational Institution have been closed till 31st of May. Though we do have Online classes going on right now but there’s no telling that soon they will stop that and give an early summer break till 31st May and resume the semester from June 1st. So I have no idea what would happen. But even with all of my Studies. I can manage this project and i can assure you that they won’t slow me down or interfere in any way. 

