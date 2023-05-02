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

**Today's Progress** : - Learned that constants in Python are declared with uppercase letters, but it is not a convention that Python actually enforces. It create a constant variable which will have a value that we cannot change, we must import Final from the typing module adn then when we create a constant we would write it like so >>> IRONMAN_ATTACK_POWER: Final[int] = 250. Created a silly little game using while loops, conditional statements and input() function.

**Thoughts** :  I love learning Python

**Link(s) to work** : 

## Day 14, 3.11.23 Saturday: 

**Today's Progress** : - Learned that constants in Python are declared with uppercase letters, but it is not a convention that Python actually enforces. It create a constant variable which will have a value that we cannot change, we must import Final from the typing module adn then when we create a constant we would write it like so >>> IRONMAN_ATTACK_POWER: Final[int] = 250. Created a silly little game using while loops, conditional statements and input() function.

**Thoughts** :  I love learning Python

### Day 15 : I did more Python but I forgot to talk about it, though I did post about it

**Today's Progress** : learning python yayy

**Thoughts** :  

**Link(s) to work** :

### Day 16: 3.15.23 Wednesday

**Today's Progress** : Today I finished up on Lists and moved onto Tuples and Dictionaries. 
Lists and tuples are similar except that tuples are not mutable. However if you want to add more element to a tuple, you can initialize a new variable containing what you want to add, and then another variable will literally + both tuples together. Tuples use () and can have mixed types of data. We can use if/else are lists and tuples to check in certain element exist. We can use for/in loops to iterate over the elements. Dictionaries are like object in Python, they contain key/value pairs. Using a for/in loop you can iterate over the keys specifically by using for subject in dictionary.key(): and use the same thing for values, so for element in marks.values(): and if you want to utilize both the key and value, you can do for key, value in dictionary.items(): You should use bracket notation to reassigne values to keys and to to add new pairs. When searching for a specific element that does not exist, it is best practice to use the .get("key") method because it will return none instead of an error that blocks your code from running.
**Thoughts** :  
I am feeling behind like always and feeling embarassed to post about this on LinkedIn, but we must be brave and we must show others our progress. It is MY progress, not theirs. And that is okay.
**Link(s) to work** : just the same video on YouTube, Learning Python through Types.

### Day 17 3.28.23 Tuesday: 

**Today's Progress** : Finally started getting back in the game. I am proud of myself for coming into Flatiron today. Started working on my DSA with JavaScript structured class. I learned how to use built-in timer functions in my code so I can review how long it take to execute. Initialize a variable for performance.now() before and after running the function then subtract those two from one another and divide by 1000 to get the time passed to make sure it is in seconds, not milliseconds.

**Thoughts** :  

**Link(s) to work** :

### Day 18 4.10.23 Monday: 

**Today's Progress** : Learned how to use p5.js which is very beginner friendly and offeres a library of built-in functions to help create animations and sketches. Super cool!Create a little panda whose nose will become animated as the volume of the mp3 file changes. 

**Thoughts** :  I will def be using this when tutoring and would like to learn more about it. 

**Link(s) to work** : https://www.loom.com/share/05e451f1300641aa859035b805e674d4


### Day 19 4.17.23 Monday: 

**Today's Progress** : Learn more about machine learning using Google's Teachable Machine which allows users to train a model using images, sounds, or postures. Once you have trained the model with the input and assigned the input labels, you can then plug in the URL for your model into any code you want. We created a simple snake game which would take in input from my webcam and move the snake based on that input. 

**Thoughts** :  Machine learning is fascinating and I am so glad that they have created ways for beginners to really understand how machine learning works and a way for them to try it out myself. In this case, both me and my student were learning material we had never covered before. 

**Link(s) to work** : https://www.loom.com/share/05e451f1300641aa859035b805e674d4

### Day 20 4.17.23 Monday: 

**Today's Progress** : Learned about generative art 

**Thoughts** :  

**Link(s) to work** : 

### Day 21  5.2.23 Monday: 

**Today's Progress** : learned about noise() and created more generative art

**Thoughts** :  fun but I hate working with Nicole and I cannot wait until this is over

**Link(s) to work** : 
