---
layout: post
title: My first Software Carpentry Workshop
categories:
 - teaching
 - carpentries
---

Last month, I spent a weekend across the bay at UCSF teaching introductory python with the [SWC Python Gapminder](http://swcarpentry.github.io/python-novice-gapminder/) in a workshop hosted by the [UCSF Library](https://gboushey.github.io/2017-03-10-UCSF-Python/). My first experience teaching with the carpentries went well, I think. It was fun and exhausting.  After the second day, I turned down meeting friends in SF doing tourist things and instead went home and sat. In the dark. In silence.  Despite the fact that I find teaching fun, I also identify strongly as an introvert and find interacting with people for long periods of time exhausting.  I recharge by being alone.  

Now that I've had some time to recover, and to recover from the things I had booked too many back to back, I've sorted through my thoughts and want to share about my first teaching experience.  

## Preparing to teach

I had plenty of time to prepare to teach for this, I had even set aside some time well in advance to review the specific curriculum.  Then I didn't, until the day before. There were two main things I felt like I needed to prepare to be able to teach.  First  I wanted to be familiar with the specific dataset we were going to work with and the order of the content in the lesson and second, I didn't know logistically how to handle exercises.  I was confident that I was ok with the material, but knowing the order makes answering questions and providing extra context easier.  I also didn't want to be reading too much from the notes. How to handle the exercises was important to me because I wanted to have an idea of how things would work.  

I ended up only going through the material in depth the afternoon before.  I spent about 4 hours reading through it all and preparing.  For teaching 6 hours, that's a reasonable amount of preparation, if I can walk myself through in much less time, then there's a chance of reaching it with novices.  More time would have only left me making up more content that we would never reach and being over prepared.

I prepared by forking the lesson material and making notes in my own copy about what additional things I wanted to do or any changes that I wanted to make.  I then pushed my changes to my fork and [served them](http://sarahmbrown.org/python-novice-gapminder/).  Inspired by on a tip I got during my instructor training, during the workshop I pointed my tablet to my version of the lesson material.  That worked well for me.  I had notes visible to me and could still leave my whole screen for the students.

## Preparing Exercises

For the exercises, I was preparing to teach this workshop while also preparing to teach a mini version of the Ecology lesson at the NSBE Convention.  For the 90 minute time constraint, I had found out about the `%load` magic of jupyter notebooks- which allows reading in a file(or excerpt of one) into a notebook cell for editing.  I decided to use this for the exercises of this workshop too. As i went through the material, I also copied the exercises into separate `.py` files for this purpose.  I set them all up in a separate github repository that also had a data folder.

Since github also allows people to download a `.zip` of the respository, using git to host it meant that I could keep my workflow what I'm comfortable with, including last minute updates and still allow the learners to download only a file that they were already familiar with.  I shortened the url to `.zip` file for the repository on a branch that I made to be a snapshot of the content prior to the start of the workshop. At the workshop, I shared the shortened url that allowed learners to download the file, had them unzip and move it to a working location and then set that to their working directory to start the lesson.  After the first day, I made a new branch added the materials that I generated day 1, fixed a few exercises for day 2 and then `.gitignore`d the files that were not changed on the new branch, so the learners could download just the new material.  When the workshop was over, they had learned git so I directed them to the actual [repository page](https://github.com/brownsarahm/python-novice-gapminder-files/tree/ucsfpostworkshop) of a postworkshop branch to download my final materials.  After the workshop, I made a [jupyter notebook](https://github.com/brownsarahm/python-novice-gapminder-files/blob/master/instructor_resources/create_workshop_branch.ipynb) outlining this whole process so that I can reuse it.

## Actually teaching

I started a little fast, but the helpers, who had more Carpentries experience than me and the stickies-system helped me slow down as we went. In the Carpentries, we provide all learners with sticky notes in two colors at the beginning of the workshop.  We then instruct learners to put a red sticky on their laptop, like a flag visible from both in front and behind them, when they have trouble.  When we break for exercises, we can also instruct learners to put the blue (or green, ideally) sticky up when they're ready to move on.  

Using load magic to the exercises worked pretty well. Getting used to some features of the notebooks was a little hard. Some of the activities required and others were just easier, if the learners split the imported `.py` file into multiple notebook cells, that was a bit hard.  A few activities were to enforce concepts more than actually writing code, so those were best formatted as markdown cells instead of python cells, switching types also caused some friction at the beginning.  By the second day though, most seemed comfortable with these activities and I hope that that push to learn a little bit more about manipulating Jupyter notebooks makes using them in their own work that much more accessible.  

We were running behind, the day two getting everyone started in the same place again took more time than I expected as did many of the exercises.  The team at UCSF runs a lot of workshops and has found that the advanced part of the git lesson tends to frustrate and demotivate learners at the end of the day.  Instead, they offered me extra time to continue python.  We still didn't finish, but made it somewhat farther with the extra hour.  

Overall it was a great first experience and I'm excited to be a member of the carpentries community.
