### Tips For Instructors

This page has an assortment of practical tips for instructors.  

#### Handling Software Installation

Installing software on laptops has gotten a lot better over the years, but it can still be a huge challenge at the start of a workshop.  Here are some suggestions for making the process go as smoothly as possible.  
Software installation can be frustrating, but in the end, it almost always gets done.  Be positive, and when it finally works, you can feel proud.  

**What you can do in advance:**

* Plan for installation help at the start of both workshop days.  Put it on the schedule and make sure it is clear that people can and should show up during that time.  
* Email the participants a week in advance and the day before to remind them to install the needed software before the workshops.  
* If possible, recruit  helpers who use Linux, Mac, and Windows operating systems.
* If you/helpers/instructors have time, test the install instructions on a fresh user account on your computer.
* If you anticipate issues (or want to be extra prepared), have some of the emergency options listed below ready to go.  
* If you are teaching for an organisation where participants are bringing work laptops where they do not have administrative access (common in government organisations) -- ask about it.  Try to plan ahead either with their central IT organisation or with the "emergency exits" listed below.  
* Will you have decent Wi-Fi?  A bunch of people installing software at once can kill a poor internet connection.  If this is the case, prep a few flash drives with the relevant installers.  
* Attend a [Community Discussion session](https://pad.carpentries.org/community-discussions), where you can talk to other Instructors to ask questions and get feedback to help you prepare to teach.  

**On the day of:**

* Refer to our [Wiki page with common problems](https://github.com/swcarpentry/workshop-template/wiki/Configuration-Problems-and-Solutions)
* If someone has come in early and the software still cannot be installed by the time the workshop starts, try one of the "emergency exits" below or keep working with them one-on-one until they are able to start.
* If someone comes in late or is having such trouble with installation that they cannot start, have them watch (and maybe work with a neighbour) until the first coffee break, when you can keep working on installation issues.  

**"Emergency Exits"**

If there is absolutely no way that you will be able to install the software locally on someone's computer, consider using the [following solutions](https://github.com/carpentries/scaffolds/blob/main/instructions/workshop-coordination.md#supporting-learners-with-carpentries-scaffolds):

> Read our [blog post, "Scaffolding Installation for Online Workshops"](https://carpentries.org/blog/2020/04/scaffolds/)

* Pre-configured "scaffolds" for [RStudio Cloud](https://github.com/carpentries/scaffolds/blob/main/instructions/workshop-coordination.md#rstudio-cloud) and [My Binder](https://github.com/carpentries/scaffolds/blob/main/instructions/workshop-coordination.md#my-binder) (hosting Jupyter and OpenRefine).
* [Microsoft Azure](https://notebooks.azure.com/) gives you a cloud based Jupyter notebook with many languages and platforms installed.  It also includes a shell terminal with git.
* If your institution's library does laptop rentals, rent 1-2 laptops and set them up with the software before the workshop and keep them on hand as loaners during the workshop.  

#### Talking About the Code of Conduct

The [Carpentries Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html) is a key tool for fostering and upholding an inclusive, respectful learning environment.  But for people who are new to the idea of a Code of Conduct, it can be a little awkward to talk about.  Here is a sample of how you might introduce the Code of Conduct -- please do not use this verbatim, but adapt it to your own audience and style of introduction:

> The Carpentries is a community-led project. We value the involvement of everyone in the community. We are committed to creating a friendly and respectful place for learning, teaching and contributing. All participants in our events and communications are expected to show respect and courtesy to others.
>
> What kinds of behaviours are expected?
>
> All interactions should be professional regardless of platform: either online or in-person. In order to foster a positive and professional learning environment we encourage the following kinds of behaviours in all Carpentries events and platforms:
>
> * Use welcoming and inclusive language
> * Be respectful of different viewpoints and experiences
> * Gracefully accept constructive criticism
> * Focus on what is best for the community
> * Show courtesy and respect towards other community members
>
> Examples of unacceptable behaviour by participants at any Carpentries event/platform can be found in the [Code of Conduct](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html#reporting-guidelines). We Instructors take the Code of Conduct very seriously, and we have a process for dealing with violations and complaints. Read the [Reporting Guidelines section](https://docs.carpentries.org/topic_folders/policies/code-of-conduct.html#reporting-guidelines) for the  details on how to handle Code of Conduct violations.

#### Using Exercises

When teaching a lesson, it is a very good idea to go through the lesson in advance and choose which exercises you want participants to try.  

Once you have selected exercises, there are several ways to actually display them to the participants during the workshop.  Any of these options may be the best choice depending on the tool you are using or the kind of exercises you want to use.  

* From the lesson website (zoomed in)
	* This is the least effort, but requires having the right lesson page open + finding the right exercise
* Make slides
	* More effort, but easy to flip forward to the next one
* Have a document of some kind with all the exercises in it
	* More effort, but exercises are all in one place.  
* Put exercises in the Etherpad
	* If you do this in advance, pretty low-effort.
	* Can also use this with any of the other strategies so people can find the exercise in two places.  
* Online tool, like [Socrative](https://www.socrative.com/)
	* Requires time to set up, but is great for multiple choice and T/F questions and promotes participation

In all of these examples, you will have to switch from the tool you are using for live coding to however you are showing the exercises.  For something like R or Python, one way to reduce the amount of switching is to put all the exercises in an R script / Python notebook and have that open alongside your main working script/notebook so that it is relatively easy to switch back and forth.  

#### General Tips

**Introductions**

The introduction is one of the most important pieces of the workshop!  It sets the tone for the day.  See the [instructor training material](https://carpentries.github.io/instructor-training/23-introductions.html) for some suggestions of how to build a good workshop introduction.  

**Accessibility Check-In**

Before you start, review our  [accessibility checklist.](workshop_needs.html#accessibility).

Set up your computer and go to the back of the room.  Is your font big enough?  

If your room has a mic, use it, and have a helper stand in the back of the room as you start to confirm that you can be heard.  

<!---
**Classroom Management**
To be expanded, how to handle:
- someone asking very specific questions
- interruptions
- people not talking to each other
-->

**Varying Skill Level**

Carpentries workshops frequently include many people with widely varying skills and experiences.  See the end of The Carpentries Instructor Training on [Carpentries teaching practices](https://carpentries.github.io/instructor-training/24-practices.html) for some strategies to deal with a diverse classroom.  

#### Preparing to Teach

It can be daunting to look at a Carpentries lesson and figure out just exactly how you are going to teach it.  Here are some suggestions for tackling a new lesson that you have never taught before:

**Read through the Instructor Guide for the Lesson**

Most Carpentries lessons include a guide for instructors. These are great for novices preparing to teach a lesson for the first time. As an example, see the [instructor notes](http://swcarpentry.github.io/shell-novice/guide/) for the Software Carpentry [Unix Shell](http://swcarpentry.github.io/shell-novice/) lesson. Find instructor notes for other lessons through the **Extras** menu on each lesson's home page.

**Pick Exercises**

Most of the lessons have more exercises than you will want to use.  Go through the lesson and pick the ones that you think will be most helpful for your audience.  If you anticipate mostly novices, look for easier or more scaffolded exercises.  For a more advanced audience, a more general exercise might be better.  If you will have both, have an option for each!  

You will not want to use *all* the exercises, but make sure that in this process, you commit to actually doing exercises.  Exercises are time-consuming and it can be tempting (in the moment) to talk instead of taking the time to do an exercise.  However, doing exercises is a huge part of the hands-on Carpentries model and also gives people a chance to chat with their neighbours, so it should be prioritised.  

Speaking of priorities...

**Prioritise**

All of The Carpentries lessons have more material than you can easily cover in the time allotted, especially with a novice group.  The Data Carpentry materials are closer to realistic workshop time estimates, but can still run slowly depending on the group.  

So no matter what, go through the lesson in advance and decide what is most important to cover and what you would feel okay skipping (either skipping outright, or dropping it if you do not have time).  

As an example: the shell lesson has 7 sections -- the first three are about basic file system navigation and file operations and the last four are about ways to use simple shell tools in more powerful ways.  Often a workshop will cover the first three and then three out of the last four.  

**Practice**

* At the very least, do a dry run of all the commands you will be running / code you will be writing so that you know they work on your computer.
* Hook your computer up to a projector and figure out how you are going to manage your screen real estate, especially if everything is magnified.
	* RStudio: RStudio can be particularly challenging because of all the panes.  Reducing the size of the two right panes is usually needed to have enough space in the script/console panes.
	* Jupyter notebooks: you can toggle the headers/toolbar off so that you have more scripting space
* If you have the time, doing a full run-through where you actually practice what you are going to say can be extremely valuable.  Words are hard when you are also trying to type and manage a classroom, so having said them once in practice gives you one less new thing to think about.  

**Join a community discussion**

* Joining a [community discussion before your workshop](https://pad.carpentries.org/community-discussions) is a great way to ask/resolve your questions about your coming workshop and also learn from the experience of other instructors!
