---
tags:
  - 100-days-log
props: # These are static variables that can be referenced in cards and templates
  startDate: 1-5-2020
computed: # These are computed variables that can be referenced in cards and templates
  daysIn: Math.ceil(((new Date()).getTime() - (new Date('${startDate}')).getTime()) / (1000 * 3600 * 24))
  daysToGo: 100 - Number(${daysIn})
  startDay: (new Date('${startDate}')).toDateString()
  today: (new Date()).toDateString()
  now: (new Date()).getTime()
template: > # This is the template for new cards
  # :100: Days of code, Day ${daysIn}: ${today}
  
  :rocket: **Progress:**  your progress here
  
  :thought_balloon: **Thoughts:**  your thoughts here

  :link: **Links to work:**  your links here

  #100DaysOfCode
links: # These are links that can be added to cards.  Notice how href is using a built in variable "encodedText"
  - pack: fab # Can be fab or fas https://fontawesome.com/how-to-use/on-the-web/referencing-icons/basic-use
    icon: twitter # The font-awesome icon to use 
    title: Tweet this card
    href: https://twitter.com/intent/tweet?text=${encodedText}%0ATweeted%20with%20@imdoneio
---

# 100 Days Of Code - Log
<!-- 
#NOTE:0 # :100: Days of code: Day ${daysIn} expand:1
**Days to go: ${daysToGo}**
**Started on: ${startDay}**
- [#100DaysOfCode Official Website](https://www.100daysofcode.com/)
- [#100DaysOfCode on Twitter](https://twitter.com/search?q=%23100DaysOfCode)
- [Edit My 100 Days of Code log](log.md:0:1)
-->

