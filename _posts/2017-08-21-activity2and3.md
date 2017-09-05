---
layout: page
title: "Activity 2 and 3 - Introduction to Programming with Arduino"
teaser: "Students write a program to control their LED light circuits."
header: no
image: 
    title: /activity2and3/title.jpg
    thumb: /activity2and3/thumb.jpg
    caption: Grade 3 and 4 girls get their LED light blinking.
category:
    - nepal
gallery:
    - image_url: /activity2and3/0001.jpg
      caption: 
    - image_url: /activity2and3/0002.jpg
      caption: 
    - image_url: /activity2and3/0003.jpg
      caption: 
    - image_url: /activity2and3/0004.jpg
      caption: 
    - image_url: /activity2and3/0005.jpg
      caption: 
    - image_url: /activity2and3/0006.jpg
      caption: 
    - image_url: /activity2and3/0007.jpg
      caption: 
    - image_url: /activity2and3/0008.jpg
      caption:       
---

This past weekend the students got an introduction to programming by using a microcontroller board to blink the LED light circuits that they built in the [first activity][1]. As we took attendance on Saturday there was one girl who looked rather sheepish. She revealed that she is a Grade 3 student, though the activities are only open for Grades 4 to 9. We were happy to have her, and by the end of the class she had put together her first program to successfully control the LED circuit. Not bad, considering she hasn't learned to type yet! We told her she could invite her friends for Activity 3, and three of them showed up on Sunday. It was nice to see their interest and enthusiasm, but their presence also highlighted the need to evaluate students' progress towards the learning outcomes of each activity. The exploration challenges in each lesson test the students' understanding of the material. We'll use these to keep a close eye on the younger kids and make sure they're not in over their heads.

During Activity 2 on Saturday the students used a visual programming tool to build their instructions for the [Arduino][] [UNO][] microcontroller board. On Sunday, for Activity 3, they extended their programs to control a Red-Green-Blue LED. We had 111 students express interest in attending. Activity 2 had 72 participants, followed by 69 for Activity 3, with a gender distribution of 58 boys and 84 girls (41%:59%)[^1]. On each day we divided them into four 1-hour sessions by grade. Eight teaching sessions made for a fast-paced weekend.

The activities have been created as [Free Cultural Works][] and are available for use and adaption under the [CC BY-SA 4.0][] license:

*	[**Activity 2 Lesson Plan**][lesson plan 2]
*	[**Activity 2 Student Handout**][handout 2]
*	[**Activity 3 Lesson Plan**][lesson plan 3]
*	[**Activity 3 Student Handout**][handout 3]

We weren't able to get around the need for computers, but other part-costs were less than $8.30 CAD  per kit for both activities, with only 18 cents of parts likely to be consumed. Having used 10 kits 141 times, the cost per student was $0.59 CAD. Part details and supplier recommendations are in the lesson plans.

The activities were a good reminder of how challenging the idea of programming can be for beginners. After reviewing Activity 1, we introduced the Arduino board and some basic programming concepts, then wrote an example program on the board. In the first session, we had the oldest students (Grade 8-9) write their code manually. However, the syntax of the code and the mixed typing abilities of the students made this slow and laborious. From that point on, we used [BlocklyDuino][2] for all age groups. It allows the students to pull together visual blocks that represent instructions for the Arduino, and it generates the corresponding code. This helped overcome the syntax and typing-speed hindrances, while still allowing the students to get a taste of programming. Activity 3 allowed us to revisit the concepts introduced in Activity 2, and extend them to control multiple LED colours at once.

{% include gallery %}

These were our first activities using the computer lab at the school, and that turned out to be a difficult process. [Shree Mangal Dvip Boarding School (SMD)][SMD] has about 10 computers with operating systems that are less than 10 years old. They're not connected to the web, so we needed to install the programs for the activity using a USB drive. That would be a simple process if not for the viruses riddling the computers that like to spread through USB drives. We got a new USB drive to use specifically with these infected computers. This too had viruses on it, direct from the "manufacturer." With a bit of patience we were able to get a total of 5 computers working. We augmented that with 3 of our own laptop computers, so we could organize the students into groups of 3 or 4 per computer. In the future, we will use the computer lab's monitors, mice, and keyboards with the 7 small [Raspberry Pi][] computers that I brought, and avoid [SMD][]'s computers all together.

During the next two weeks students are writing their term exams, so we will resume the activities on Saturday September 2nd.

[^1]: Activity 2 had 32 boys and 41 girls. Activity 3 had 26 boys and 43. SMD has a nearly equal gender distribution among boarding students, with 175 boys and 174 girls.

[SMD]:https://www.himalayanchildren.org/
[1]: /nepal/activityoneled/
[Arduino]: https://www.arduino.cc/en/Main/AboutUs
[UNO]: https://store.arduino.cc/usa/arduino-uno-rev3
[2]: https://blocklyduino.github.io/BlocklyDuino/blockly/apps/blocklyduino/
[CC BY-SA 4.0]: https://creativecommons.org/licenses/by-sa/4.0/
[Free Cultural Works]: https://creativecommons.org/share-your-work/public-domain/freeworks/
[lesson plan 2]: /files/Activity 2 - Lesson Plan.pdf
[handout 2]: /files/Activity 2 - Student Handout.pdf
[lesson plan 3]: /files/Activity 3 - Lesson Plan.pdf
[handout 3]: /files/Activity 3 - Student Handout.pdf
[Raspberry Pi]: https://www.raspberrypi.org/about/

