---
refresh: 6000
tags:
  - coding
props:
  startDate: 12-26-2019
computed:
  daysIn: Math.ceil(((new Date()).getTime() - (new Date('${startDate}')).getTime()) / (1000 * 3600 * 24))
  daysToGo: 100 - Number(${daysIn})
  startDay: (new Date('${startDate}')).toDateString()
  today: (new Date()).toDateString()
  now: (new Date()).getTime()
template: >
  # :100: Days of code, Day ${daysIn}: ${today}
  
  :rocket: **Progress:**  
  
  :thought_balloon: **Thoughts:**  

  :link: **Links to work:**  

  #100DaysOfCode
links:
  - pack: fab # Can be fab or fas https://fontawesome.com/how-to-use/on-the-web/referencing-icons/basic-use
    icon: twitter # The font-awesome icon to use 
    title: Tweet this card
    href: https://twitter.com/intent/tweet?text=${encodedText}%0ATweeted%20with%20@imdoneio
---

# 100 Days Of Code - Log
<!-- 
#NOTE:0 # :100: Days of code: Day ${daysIn}
**Now: ${now}**
**Days to go: ${daysToGo}**
**Started on: ${startDay}**
- [Edit My 100 Days of Code log](log.md:0:1)
- [#100DaysOfCode on Twitter](https://twitter.com/search?q=%23100DaysOfCode)
-->

### Day 0: February 30, 2016 (Example 1)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts:** I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link to work:** [Calculator App](http://www.example.com)

### Day 0: February 30, 2016 (Example 2)
##### (delete me or comment me out)

**Today's Progress**: Fixed CSS, worked on canvas functionality for the app.

**Thoughts**: I really struggled with CSS, but, overall, I feel like I am slowly getting better at it. Canvas is still new for me, but I managed to figure out some basic functionality.

**Link(s) to work**: [Calculator App](http://www.example.com)


### Day 1: June 27, Monday

**Today's Progress**: I've gone through many exercises on FreeCodeCamp.

**Thoughts** I've recently started coding, and it's a great feeling when I finally solve an algorithm challenge after a lot of attempts and hours spent.

**Link(s) to work**
1. [Find the Longest Word in a String](https://www.freecodecamp.com/challenges/find-the-longest-word-in-a-string)
2. [Title Case a Sentence](https://www.freecodecamp.com/challenges/title-case-a-sentence)

### #DONE:30 # :100: Days of code: Day 2
#100DaysOfCode
- imdone: Added new card template in frontMatter for 100DaysOfCode

### #DONE:10 # :100: Days of code: Day 3
#100DaysOfCode
- Added tweet button from log.md frontMatter to easily tweet progress

### #DONE:20 # :100: Days of code: Day 3
#100DaysOfCode
- Added frontMatter variables to imdone to automatically show day's progress

### #DONE:2.5 # :100: Days of code, Day 3: Sat Dec 28 2019
**Today's Progress:** Added the standard log.md entry as task template  
**Thoughts:** Looking good so far, hopefully release by monday!  
**Link to work:** [imdone.io](http://imdone.io)
#100DaysOfCode

### #DONE:1.25 # :100: Days of code, Day 4: Sun Dec 29 2019
**Today's Progress:** Implemented YAML config for imdone  
**Thoughts:** Much cleaner layout and consistent with use of frontMatter  
**Link to work:** [imdone](https://imdone.io)
#100DaysOfCode

### #DONE:0.625 # :100: Days of code, Day 5: Mon Dec 30 2019
**Today's Progress:**
- Added maxLines config setting for imdone
- Fixed bug allowing cards with no title
----
**Thoughts:**
Day job is keeping me from releasing imdone templates today
**Link to work:**
#100DaysOfCode

### #DONE:0.3125 # :100: Days of code, Day 6: Tue Dec 31 2019
**Today's Progress:**
- Worked on imdone release 1.4.4
**Thoughts:**
- Still not ready to release 100DaysOfCode template, but getting close
**Link to work:** imdone.io
#100DaysOfCode

### #DONE:0.15625 # :100: Days of code, Day 7: Wed Jan 01 2020
**Today's Progress:**
:hankey: Added much needed restartWorker() to imdone.  
**Thoughts:**
:hankey: Woke up to find my imdoneboard wasn't working due to the proces dying overnite.  
**Link to work:**
imdone.io
#100DaysOfCode #EatYourOwnDogfood

### #DONE:0.078125 # :100: Days of code, Day 8: Thu Jan 02 2020
**Today's Progress:**
:rocket: Made imdone journal respect single file in config for 100-days-of-code template  
**Thoughts:** Now on to adding new projects from templates  
**Link to work:** imdone.io  
#100DaysOfCode

### #DONE:0 # :100: Days of code, Day 8: Thu Jan 02 2020
:rocket: **Progress:** imdone is now pulling in github:imdone/templates readme
:thought_balloon: **Thoughts:** Trying to make it easy for community template creation
:link: **Links to work:** https://github.com/imdone/templates
#100DaysOfCode


### #DOING:0 # :100: Days of code, Day 10: Sat Jan 04 2020
:rocket: **Progress:** Finished ability to add projects from template in imdone.
:thought_balloon: **Thoughts:** Continue working on pre-populated board for people new to coding.
:link: **Links to work:** https://github.com/imdone/templates
#100DaysOfCode

