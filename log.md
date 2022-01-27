---
tags: # These tags will be added to all cards
  - 100-days-log
props: # These are static variables that can be referenced in cards and templates.
  startDate: 01-27-2022
computed: # These are computed variables that can be referenced in cards and templates
  daysIn: ${Math.ceil(((new Date()).getTime() - (new Date(startDate)).getTime()) / (1000 * 3600 * 24))}
  daysToGo: ${100 - Number(daysIn)}
  startDay: ${(new Date(startDate)).toDateString()}
  today: ${(new Date()).toDateString()}
  now: ${(new Date()).getTime()}
  timestamp: ${(new Date()).toISOString()}
template: | # This is the template for new cards
  :100: Days of code, Day ${daysIn}: ${today}
  :rocket: **Progress:**  your progress here
  :thought_balloon: **Thoughts:**  your thoughts here
  :link: **Links to work:**  your links here
  #100DaysOfCode
  <!-- created: ${timestamp} -->
---

# 100 Days Of Code - Log
<!-- 
#NOTE:0 # :100: Days of code: Day ${daysIn} expand:1 refresh:300000
**Days to go: ${daysToGo}**
**Started on: ${startDay}**
- [Rules](rules.md)
- [Log - click here to see my progress](log.md)
- [FAQ](FAQ.md)
- [Resources](resources.md)
- [#100DaysOfCode Official Website](https://www.100daysofcode.com/)
- [#100DaysOfCode on Twitter](https://twitter.com/search?q=%23100DaysOfCode)
- [Edit My 100 Days of Code log](log.md:0:1)
-->

