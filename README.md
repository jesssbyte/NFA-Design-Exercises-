# NFA-Design-Exercises- Reflection

## Question 1
Problems that gave me most trouble were ones towards the bottom of the list. I attempted numbers 20-23 but got stuck when given an 'or' and 'and'
scenario. Though I attempted, I decided to skip the questions for this assignment for the sake of time. I did use Ai at times to help guide me through questions when I got stuck. 

## Question 2
One that surpised me was when I worked on question 11. I predicted that `1101` would be accepted, but JFLAP rejected it. The string has 1's near the end, and I could see a path that reached q2 after the second `1`. I followed that one path in my head and stopped there. I forgot that q2 dies when another symbol arrives. I treated "reaching q2" as the same as "accepting," but a string is accepted only if a branch is in q2. I also test `110` alongside `1101`. They look almost identical, but `110` is accepted, which shows that the last symbol decides the result.

For questions 12 and 13 I also ran into some issues where I either forgot to add or added too many loops. I will learn to overcome this by writing the full set of alive states after every symbol, and I mark a state ✗ when it has no transition for the next symbol. Also will be testing different patterns then the ones I orginally started with to get a genuine sense to see if my NFA worked.  

## Question 3
I would say this assignment was a bit challenging. I'm still getting used to utilizing Github but this assignment has forced me to put myself in situations where I had to do additional research to complete the deliverables. Overall, it was good practice and will be continuing the practice the problem sets. 

