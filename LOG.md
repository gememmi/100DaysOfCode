# 100 Days Of Code - Log


### Day 1: February 20, 2023 Monday

**Today's Progress** : starting learning the problem solving process for algorithms. I started with the isPalindrome function. My notes are also on my Notion, but the big take away was the following:
1. Rewrite the Problem in your own Words. What kind of data input and output?
2. Write your own test cases, basically just identifying what should be input and output
3. Write out pseudcode, maybe think of additional solutions
4. Code and make it work, make it DRY and easy to read. Each function should have one task, create helper functions as needed.
There are many ways to solve this problem, I have only done the first one so far. 

**Thoughts** : I felt silly posting about this on LinkedIn. I feel like I am exposing myself for being so far behind on DSA. But fuck it, LinkedIn is stupid and posting publicly is literally part of the process-- getting more comfortable with being public and being honest and trying to connect with others. Besides, I think that my post could bring people some peace of mind if they have also been working on other topics during this time, instead of focusing on DSA.

**Link(s) to work** : https://github.com/gememmi/DSALearning
https://www.linkedin.com/posts/em-daniels_100daysofcode-activity-7033520149164892160-zxPg?utm_source=share&utm_medium=member_desktop

### Day 2: February 22, 2023 Tuesday

**Today's Progress** : completed the first algorithm from the Flatiron curriculum from Phase 1! Maybe I should skip ahead to acutally DSA module though...
In this solution, we used two functions in order to first turn the string into an array and reverse it and call that function within the isPalindrome function. 

**Thoughts** : chuggin along.  

**Link(s) to work** :  https://github.com/gememmi/DSALearning



### Day 3: February 24, 2023 Thursday

**Today's Progress** : didn't get so far today becuase I was burnt out from working on career prep and taking meetings. But I did go over the second solution for the isPalindrome function, this time using a for loop to iterate over the string. I compared the i index as it starts from the beginning of the word and the j index which I set to the lenght of the string divided by 2 minus the i index. This will give us the corresponding index to compare. Then I compared the two indexes and if they did not match, the function retured false. And if they continued to match as the loop iterated through, it returned true

**Thoughts** : I have once again taken away from my coding time by focusing too much on career stuff. I think just having Kim there to keep my accountable has been so great and really motivates me to get my shit done. I suppose posting publicly about my progress on LinkedIn is accountability, but I really think I should be doing is having a set amount of work I want to cover and accomplish that. 

**Link(s) to work** :  https://github.com/gememmi/DSALearning
https://www.linkedin.com/posts/em-daniels_100daysofcode-activity-7034651626774654976-Fjrk?utm_source=share&utm_medium=member_desktop

### Day 4: February 24, 2023 Friday

**Today's Progress** : went into Flatiron to get some stuff done. I focused on Linkedin and DSA, this time working through a problem which asked for a function which would identify a duplicate in the array. I tried super hard and went step by step by ulitmately my logic was incorrect.

**Thoughts** :  I feel really proud of myself for trying so hard to come up with a well thought out answer. I really put in the time for this problem and maybe I truthfully took too much time. Perhaps it is time to start only allowing my self to work on problems for 25-30 minutes before looking for a solution. I no longer want to spend a full day on one problem.  

**Link(s) to work** :  em-daniels_100daysofcode-activity-7034651626774654976-Fjrk?utm_source=share&utm_medium=member_desktop

### Day 5: February 27, 2023 Monday

**Today's Progress** : I started this on Sunday, but only got throught 25minutes of the duplicates solution which I did not understand and then fell asleep bc my period knocked my out. So I am going back today, Monday. I finished this session on Tuesday. I learned about the built-in JS method called lastIndexOf() which will return the last occurrence (index) of the index or element passed as an argument. I used this method in my duplicates function, in my for loop. I called this method on the array passed in my function and used the arr[i] as a parameter and said that if the last occurance of this element is not the index we are currently on, then it must already be in the array and is a duplicate. In this case, I returned arr[i], which will return us the element. If the functino is able to iterate over the array without encountering any duplicats then the function will return -1

**Thoughts** :  This one really threw me for a loop and it required me to draw out my function on paper and to use ChatGBT to understand what was being asked of me

**Link(s) to work** :  

### Day 6: 

**Today's Progress** : 

**Thoughts** :  

**Link(s) to work** : 

### Day 7: 

**Today's Progress** : 

**Thoughts** :  

**Link(s) to work** : 

### Day 8: 

**Today's Progress** : 

**Thoughts** :  

**Link(s) to work** :


### Day 9: 

**Today's Progress** : 

**Thoughts** :  

**Link(s) to work** :

### Day 10, March 5, 2023 Sunday: 

**Today's Progress** : I started working on sortedArray function, tried a few things that didn't work until I realized I could just use the 
.sort method in JavaScript and it works everytime -_-. The real problem to solve is how to calculate the run time of this function. They gave us the pseudocode, but it feels wayyyy over my head. I will look further into this tomorrow.

**Thoughts** :  I have no idea how to calcuate run time , but I will. I will focus on this.

**Link(s) to work** :
-file:///Users/emilydaniels/Documents/FLATIRON/COURSE%20WORK/Data-Structures-and-Algorithms-2023-Feb-13_15-41-13-097/index.html#!/content/g9237672ea4507a5f970435f01a10881b
-https://chat.openai.com/chat 

### Day 11 3.7.23 Tuesday: 

**Today's Progress** : Got further in my python video and learned more about flow control. We covered if, else, elif, for loops, and while loops. I learned that you can iterate through a string. I also learned about the built in Python function called input() which allows you to open up an input field in the shell. I also learned about .lower() which is just like .toLower() in JavaScript. I also touched on while loops, which I haven't had exposure to in a while. hehe. Basically the while expression will execute until it is no longer true (or whatever the condition is).I alos learned about match which is like Switch/case in JavaScript. The switch expression is evaluated once, the value of the expression is compared with valued of the cases. If there is a match,, the associated block of code will run. If there no matches, than the default block of code will be executed.

**Thoughts** : I think I did a really good job today in focusing. I am grateful for my new meds too. I am having a fun time learning about Python and I am happy that I switched to this video tutorial. I might still look over the Flatiron stuff since I know its more thorough. Shoud I do them in tandem? 

**Link(s) to work** :
-https://www.youtube.com/watch?v=jH85McHenvw&ab_channel=freeCodeCamp.org

### Day 13 3.8.23 Wednesday: 

**Today's Progress** : worked on LeetCode with Raman, first time encountering using two reference points like heads and tails.

**Thoughts** :  I am sooo thankfulf or Raman for showing me how to do some LeetCode problems and how to approach them

**Link(s) to work** : https://www.youtube.com/watch?v=rlfsnRY0S9k&ab_channel=TerribleWhiteboard

### Day 14, 3.11.23 Saturday: 

**Today's Progress** : - Learned that constants in Python are declared with uppercase letters. Created a silly little game using while loops, conditional statements and input() function.

**Thoughts** :  I love learning Python

**Link(s) to work** : 