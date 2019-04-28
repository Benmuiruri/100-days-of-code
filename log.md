# 100 Days Of Code - Log
Hi, My name is Ben but I like to call myself OptimizePrime (https://twitter.com/ed_kinging). Welcome to my #100daysofcode journey. This log contains entries of my journey to become a self-taught Full-stack web developer. 

First off.. big shout out to Haley (https://github.com/haley-dvlpr) from whom I forked this repo, and who also has a well detailed Log I recommend people to use as a starting point. 

So.... I am 27 years old guy who vowed to himself that by mid year (June/July) I will have completed the tutorials I need to get myself started on working on a real project towards the end of the year. From the beginning of the year I started my journey by completing the following five courses at https://codecademy.com/
1. Introduction to Git 
2. Introduction to HTML 
3. Introduction to CSS
4. Introduction to Javascript 
5. Learn Javascipt. 

With those courses done, I joined the famous Learn Enough Society (https://t.co/cdsJ2dLRqp) by Michael Hartl (https://twitter.com/mhartl) which in my opinion is one of the most complete way to learn how to be an all round developer. 
At Learn Enough I did the tutorials for:
1. The command line
2. Git
3. HTML 
4. CSS and Layout 
5. Javascript 
6. Ruby 

Just as I started the Ruby on Rails tutorial is when I stumbled on the 100 days of Code challenge. And it naturally became the real test to all the HTML, CSS and JavaScript I have learned so far. 

And that is basically my story. So starting today, this log will contain my daily coding log. Let's Get it!! 



### Day 1: April 24, 2019
##### (freeCodeCamp - Responsive Web Design Projects - Build a Tribute page)

**Today's Progress**: I used a test driven development method... well kind of. I first wrote the skeleton HTML that would pass most of the tests of the project. Once I had the layout that passed 8 of the 10 tests, I started fleshing in the content. Since I still don't have enough real world practice on how to actually start working on designing a web page. I started with adding content for the footer and the container image. 

**Thoughts:** It was a big struggle deciding on where to start. I knew what I wanted to do but where do I start was the big question. Nevertheless, I started so Hoorah!!.

**Link to work:** [Github](https://github.com/Benmuiruri/Wangari-Maathai-Tribute/commit/9e8d20813d3fd69c51335b961270f9b1ec29a95a)

### Day 2: April 25, 2019
##### (freeCodeCamp - Responsive Web Design Projects - Build a Tribute page)

**Today's Progress**: Today I started working on the aesthetics of the page by creating the right layout. Yesterday (April 24, 2019) I wrote about not knowing where to start despite knowing what I want to do. Well as luck would have it I stumbled on this twitter post (https://twitter.com/acopycreative/status/1121046841607503873) by Ornella (https://twitter.com/acopycreative) I suggest giving her a follow she is awesome peeps to follow on this challenge. So anyway her post (if you have not checked it out) is how she sketched out a wireframe using pen and paper for her tribute page. Just like that she solved the *Where do I start* problem that I had. So I sketched my tribute page on piece of paper then knowing which divs I will have I started coding the divs and using flexboxes to design the layout. I also added an image that i will appear on the header. 

**Thoughts:** Doing challenges, reading tutorials, and all that is radically different from working on a project from scratch. It's challenging but... rewarding, once you learn how to think like a developer from all the tutorials you have done. 

**Links to completed work:**   
[Github Page](https://github.com/Benmuiruri/Wangari-Maathai-Tribute/commit/c419ef5416912405c95708a4e9b172667a0a11b4)

### Day 3: April 26-27-28, 2019
##### (freeCodeCamp - Responsive Web Design Projects - Build a Personal Portfolio Webpage)

**Today's Progress**: Finally after 12 hours stretching from Wednesday to today Sunday, I have finished the FCC tribute page project. I am very excited that I have managed to complete the project. So excited to get on with the Survey form because I am finally getting the hang of things. 

**Thoughts:** I have noticed I know how to move things around to get the layout I desire, but I need to read up on responsive design using rem,em, vh and the like. creating a responsive website is a MUST for any dev.

**Links to completed work:**  https://codepen.io/Benmuiruri/full/vMVoxX

### Day 4: April 5, 2019
##### (freeCodeCamp - Responsive Web Design Projects - Build a Personal Portfolio Webpage)

**Today's Progress**: I created the front part of my portfolio, with a bit of animation. I'm trying to go for a minimalist design here. Still didn't write the About Me section. Also I'm thinking about adding a scroll up transition (btw is that what they call it?) from the welcome section to the About Me. Anyway, this is what I have so far (minus media query):

![portfolio sample](https://res.cloudinary.com/dzqqlj7am/image/upload/v1554492203/63.png)

**Link to work (Let me know what you think):** [Github Page](https://haley-dvlpr.github.io/Portfolio-Page/)

### Day 5: April 6, 2019
##### (freeCodeCamp - Responsive Web Design Projects - Build a Personal Portfolio Webpage)

**Today's Progress**: I'm taking too long on this one, eh? Well, I've been busy.. with life. I got to attend a Women Techmakers event today (yay!), it was a great networking opportunity. I'm very tired and sleepy and I'm trying to present my 4 portfolio projects in a nice 2x2 grid. Using <code> display: grid; </code> was tricky. So I set the template using<code>grid-template-columns: repeat(2, 1fr);</code>. I need to know how I can clearly assign rows... unless it's somehow automatic (??). I'm also open to using flexbox, but I also want to control number of items per row. I think I'll have to introduce <code>calc()</code> property. Will definitely search on Youtube about the best method for my 2x2. Hoping to finalize my portfolio tomorrow.

**Link to work**: I'd rather not? It's a mess. 🙈
.
### Day 6: April 7, 2019
##### (freeCodeCamp - Responsive Web Design Projects - Build a Personal Portfolio Webpage: COMPLETED)

**Today's Progress:** I'm done! I didn't feel the time but it was so worth every minute and every leg cramp lol. I started out by fixing the grid (yes I finally decided on grid). Followed a guy's tutorial on YouTube and it worked! I chose grid over flexbox because the latter is one-dimensional, so having a 2x2 will require nested divs (or so I think?). I have only ONE big breakpoint, and it ends at iPad Pro (so anything less than 1024px will be considered a phone/tablet lol). Reason is, I wanted to make my css shorter and simplifed because honestly I don't have much content in my portfolio anyway. I'll revisit it however, as I continue to work on projects 😉. Also, I spent so much time fixing typos, and being confused about smooth animated scrolling. I tried to do it with jQuery but for some reason the smooth part was just not happening. So I just added <code>html { scroll-behavior: smooth; }</code>, which did the trick. If I had known that such property existed, I wouldn't have spent 2 hours trying to make the scrolltop animate thing on JS work. But I guess that's going to be brought up soon anyway. Last but not least, Codepen's viewport is smaller than the actual browser viewport size (duh!), so I kept getting 11/12 score on my portfolio. It said my welcome-section height isn't equal to the viewport height. For some reason it kept ignoring my <code>height: 100vh;</code> 😑 So I set <code>min-height: 262px;</code>, and adjusted the 100vh to become the max-height. So yeah that was about it, got my certificate. Feeling great! 

**Link to work:**   
[Codepen](https://codepen.io/haley-dvlpr/pen/qwaVrx),  
[Github Page](https://haley-dvlpr.github.io/Portfolio-Page/).  

![fcc-certificate](https://res.cloudinary.com/dzqqlj7am/image/upload/v1554687222/Responsive_Design_Certificate.png)
![codepen-test](https://res.cloudinary.com/dzqqlj7am/image/upload/v1554687307/89.png)

### Day 7: April 8, 2019
##### (freeCodeCamp - Javascript Algorithms And Data Structures Certification - Introduction to Javascript)

**Today's Progress:** Today was slow and quiet. I started with Js lessons on freeCodeCamp. I wanted to start with the Js section in the [Udemy course that I'm taking](https://www.udemy.com/the-complete-web-development-bootcamp/) as well, but I just **did not feel the audio-visual learner** in me today. So I skimmed through examples on freeCodeCamp and (strangely enough) the syntax and logic reminded me of Python. I took few Python tutorials couple of months ago and I found Python amazing. But I just don't see yet where I could apply it; knowing that I'm mainly interested in Front End. I prefer to dedicate my time to Js for now. Once I'm well-acquainted with Front-End languages, libraries and frameworks, I'll think about Python. 

### Day 8: April 9, 2019
##### [(The Complete 2019 Web Development Bootcamp)](https://www.udemy.com/the-complete-web-development-bootcamp/) 

**Today's Progress:** Watched lectures 1)Introduction to Javascript 2)Javascript Alerts - Adding Behaviour to Websites 3)Data Types. Got to see a new side of developer tools on Chrome (Console). 99% of today's content was theory. But I hope I'll work on practical examples tomorrow. 🤷‍♀️🙆‍♀️

### Day 9: April 10, 2019
#####  [(The Complete 2019 Web Development Bootcamp)](https://www.udemy.com/the-complete-web-development-bootcamp/) + Random ES6 YouTube tutorial

**Today's Progress:** Today was part theory (as in lessons from the Udemy course), and part applying random cool tutorial from Youtube 😉💻😁. One interesting idea was to generate a customized welcome message based on time/hour (i.e. Good morning, Good day, etc), just like the [Momentum extension](https://chrome.google.com/webstore/detail/momentum/laookkfknpbbblfpciffpaejjkokdgca) for Chrome (my favorite To Do app next to [Trello](https://trello.com/))! 

I found out -for the first time- that you **REALLY CAN** create elements inside the html body using javascript!! So today was about creating an h1 element. I think I want to use this on my portfolio, you know, just to customize my greeting a bit. Hence, I create a repository especially for this, so I can add more to it each time. I wonder if I can assign to it an existing class, that would be terrific! Also in my case I'd like to concatenate it with an existing h1 element, rather than creating an entirely new one.  

Oh, and I learned how to add snippets in the Sources tab inside Chrome Developer Tools. So I wrote (hopeful) prompts, one of them is about me getting acceptance from my dream school in Barcelona! 🤣

![prompt 1](https://res.cloudinary.com/dzqqlj7am/image/upload/v1554930225/hs.png)
![prompt 2](https://res.cloudinary.com/dzqqlj7am/image/upload/v1554930224/hs2.png)

**Link to work:** [Dynamic Welcoming Message](https://github.com/haley-dvlpr/Dynamic-Welcome-Message/tree/master/Dynamic%20Welcoming%20Message)


### Day 10: April 11, 2019
##### freeCodeCamp - Basic Javascript

**Today's Progress:** I tried to quickly cover some lessons from the curriculum today. I've been busy this entire week and honestly I don't feel that I'm focused 😥. Got family visiting from home, helping prep for a women's tech conference (😉 which is exciting!) AND hanging out with my sister who took a week off from work 🙄. Yeah, this file was not meant for rants, I know. But I managed to do 30 minutes today (which kind of breaks the rules of the challenge?) But to be fair on most days I dedicate 3+ hrs a day, sometimes it can reach 12 hrs with debugging.  
 
**Here's what I covered today:**  
Escaping Literal Quotes in Strings  
Quoting Strings with Single Quotes  
Escape Sequences in Strings  
Concatenating Strings with Plus Operator  
Concatenating Strings with the Plus Equals Operator  
Constructing Strings with Variables  
Appending Variables to Strings  


### Day 11: April 12, 2019
##### [(The Complete 2019 Web Development Bootcamp)](https://www.udemy.com/the-complete-web-development-bootcamp/)

**Today's Progress:** Learned about string lengths (retrieving number of characters), slicing strings, changing string casing, and lastly basic arithmetic operations in Javascript. I also did interesting exercises, such as how to capitalize user's name (given through prompt). So, if I type in "halima", "hALIMA" or even "HALIMA", it would still give me an alert of "Hi, Halima!". This was a combination of slice, uppercase and lowercase methods. I also did a prompt exercise where you'd enter your dog's age, and it would give you back its age in human years. I then came up with a conversion formula for lovebirds (since I'm a lovebirds mommy). Turns out, my lutino lovebired (Ponyo) is 7 years old, while my green lovebird (Kiwi) is around 2 years old in human age. WOW. 

### Day 12: April 13, 2019
#####  freeCodeCamp - Basic Javascript

**Today's Progress:** I didn't dedicate adequate time for coding today y'all so much is going on, starting a new job + recent previous rants above. I only practiced few bracket notation and concatenation lessons to keep up with the Udemy course. So yesterday it was about referring to character index inside a method's brackets, this time it was getting the value of string character by <code>firstNameFirstLetter = firstname[0];</code>. I don't know if Udemy's instructor was going to cover that but it was good to know. Anyway I'll try to finish basic JS section tomorrow🥺💪🏽💻 Peace✌🏽

### Day 13: April 14, 2019
##### freeCodeCamp - Basic Javascript 

**Today's Progress:** I liked how FCC is concerned about the ethics of coding. Like (for example) this was so cool: "There shouldn't be any spaces between the array name and the square brackets, like <code>array [0][0]</code> and even this <code>array [0] [0]</code> is not allowed. Although JavaScript is able to process this correctly, this may confuse other programmers reading your code". Great tips for practicing coding professionally! I covered a good number of lessons today, surprisingly; the section is actually long (who was I kidding when I said I'll finish it today?). Oh and then it took me a while to wrap my head around some of the lessons/new information. Here's the highlight of what I learned today:  

- The word "function" used to scare me back when I knew nothing about ES6. Functions are our friends, they help us write reusable code. (I mean isn't that what functions do, mainly, in all programming languages?🤦‍♀️).  
  
- Parameters (inside functions) are variables..  <code>
function testFun(param1, param2) {  
  console.log(param1, param2);  
}</code>
  
- Variables which are declared within a function, as well as the function parameters, have local scope. That means, they are only visible within that function. Variables outside the function have global scope.  
  
- It is possible to have both local and global variables with the same name. When you do this, the local variable takes precedence over the global variable.  

- I don't get the use of the <code>return</code> statement, like why not just declare... wait no I think I get it now. Nvm. 

- I searched about mutable and non-mutable data types, [cool MDN quick tip here](https://developer.mozilla.org/en-US/docs/Glossary/Mutable).  

That's about it. I cannot wait for this week to be over. But I'm also busy the week after. And the one after that. I hope I can at least wrap up the lessons (aside from projects) by this month. Fingers crossed.


### Day 14: April 15, 2019
##### freeCodeCamp - Basic Javascript

**Today's Progress:** Topics covered:  
- Understanding Undefined Value returned from a Function | This happens when you don't use a return statement within the function, nor declare a variable or assign a value to it.
- Stand in Line | The problem statement was a bit confusing, and mind you, I've encountered this issue with fcc lessons on numerous occasions. That being said, the solution was extremely easy. This has certainly something to do with that JSON thing (which I haven't learned yet but had previously worked with - do not ask how 🤣).  

![stand in line exercise](https://res.cloudinary.com/dzqqlj7am/image/upload/v1555365602/stand_inline.png)  
- Understanding Boolean Values | True! (get it ;D ?)
- Use Conditional Logic with If Statements 
- Comparison with the Equality Operator | Okayyy so I didn't know type coercion could take place inside the condition. Interesting.  

![equality operator](https://res.cloudinary.com/dzqqlj7am/image/upload/v1555364167/fcc_coersion.png)  
- Comparison with the Strict Equality Operator | I'm placing select photos in my daily logs so that I keep these rules in mind btw.  

![strict equality operator](https://res.cloudinary.com/dzqqlj7am/image/upload/v1555365092/fcc.png)  

**Other Highlights:**  
- We can take the return value of a function and assign it to a variable.
- Comparison Operators: Note that equality is different from assignment (=), which assigns the value at the right of the operator to a variable in the left.

**Useful Links:**  
- [JavaScript type coercion explained](https://medium.freecodecamp.org/js-type-coercion-explained-27ba3d9a2839)
- [What exactly is Type Coercion in Javascript?](https://stackoverflow.com/questions/19915688/what-exactly-is-type-coercion-in-javascript)
- [9 Ways to Remove Elements From A JavaScript Array](https://love2dev.com/blog/javascript-remove-from-array/)


### Day 15: April 16, 2019
##### freeCodeCamp - Basic Javascript

**Today's Progress:** Topics covered:  
- Practice comparing different values  
- Comparison with the Inequality Operator  
- Comparison with the Strict Inequality Operator  
- Comparison with the Greater Than Operator  
- Comparison with the Greater Than Or Equal To Operator  
- Comparison with the Less Than Operator  
- Comparison with the Less Than Or Equal To Operator  
- Comparisons with the Logical And Operator  
- Comparisons with the Logical Or Operator  
- Introducing Else Statements  
- Introducing Else If Statements  .

**Comments:** Great refersher for concepts covered in school IT class.

### Day 16: April 17, 2019
##### freeCodeCamp - Basic Javascript 

**Today's Progress:**
- Logical Order in If Else Statements
- Chaining If Else Statements
- Golf Code
- Selecting from Many Options with Switch Statements
- Adding a Default Option in Switch Statements

**Highlights:** <code>case</code> values are tested with strict equality <code>(===)</code>. The break tells JavaScript to stop executing statements. If the <code>break</code> is omitted, the next statement will be executed. Also, <code>default</code> is the equivalent of <code>else if</code>.

### Day 17: April 18, 2019 + Day 18: April 19, 2019
##### freeCodeCamp - Basic Javascript 

**Two days Progress**: 

I've been so busy and multitasking as we near the conference (tomorrow!) I still have few more lessons to finish up. And to be honest I didn't do external work but I watched few videos about object/nested objects/nested arrays... etc. I was a bit confused. 

- Multiple Identical Options in Switch Statements
- Replacing If Else Chains with Switch
- Returning Boolean Values from Functions
- Return Early Pattern for Functions
- Counting Cards
- Build JavaScript Objects
- Accessing Object Properties with Dot Notation
- Accessing Object Properties with Bracket Notation
- Accessing Object Properties with Variables
- Updating Object Properties
- Add New Properties to a JavaScript Object
- Delete Properties from a JavaScript Object
- Using Objects for Lookups
- Testing Objects for Properties

**Highlights:** 

- When a return statement is reached, the execution of the current function stops and control returns to the calling location.
- Objects: If your object has any non-string properties, JavaScript will automatically typecast them as strings.
There are two ways to access the properties of an object: dot notation (.) and bracket notation ([]), similar to an array.
- Object properties: There are two ways to access the properties of an object: dot notation (.) and bracket notation ([]), similar to an array.
<code>
var myObj = {
  prop1: "val1",
  prop2: "val2"
};
var prop1val = myObj.prop1; // val1
var prop2val = myObj.prop2; // val2
</code>
- If the property of the object you are trying to access has a space in its name, you will need to use bracket notation.
- We can use the .hasOwnProperty(propname) method of objects to determine if that object has the given property name. 
- JavaScript Object Notation or JSON is a related data interchange format used to store data.
- Manipulating Complex Objects
- Accessing Nested Objects

There was one thing that didn't make sense to me:

![1](https://res.cloudinary.com/dzqqlj7am/image/upload/v1555706609/objects2.png)
![2](https://res.cloudinary.com/dzqqlj7am/image/upload/v1555707120/%D8%AE%D9%84%D8%A7%D8%AA%D8%AB%D8%A4%D9%81.png)


Ok I completely forgot how index counting goes in programming languages lol.. I kept thinking that the index referred in the above example should be 2 (as second)... I forgot that index counting always starts with 0.


### Day 19: April 20, 2019 + Day 20: April 21, 2019
##### freeCodeCamp - Basic Javascript - Completed

**Two days Progress**: 

Manipulating Complex Objects  
Accessing Nested Objects  
Accessing Nested Arrays  
Record Collection  
Iterate with JavaScript While Loops  
Iterate with JavaScript For Loops  
Iterate Odd Numbers With a For Loop  
Count Backwards With a For Loop  
Iterate Through an Array with a For Loop  
Nesting For Loops  
Iterate with JavaScript Do...While Loops  
Profile Lookup  
Generate Random Fractions with JavaScript  
Generate Random Whole Numbers with JavaScript  
Generate Random Whole Numbers within a Range  
Use the parseInt Function  
Use the parseInt Function with a Radix  
Use the Conditional (Ternary) Operator  
Use Multiple Conditional (Ternary) Operators  

**Highlights**: Definitely want to revisit Radix and that record collection exercise.  
Now that I finished JS basics, I will go back to the Udemy course for more examples and trying to understand from another's perspective.

### Day 21: April 22, 2019 + Day 22: April 23 - 21, 2019
##### freeCodeCamp - ES6 +  [(The Complete 2019 Web Development Bootcamp)](https://www.udemy.com/the-complete-web-development-bootcamp/)

**Two days Progress**:  
I haven't covered much... but I learned about let vs. var declaration types. And on the Udemy side, the ES6 chapter is more of basics of Javascript. So I got the chance to revisit some important concepts. I'll definitely try to find a mini-project for Js by this weekend. Ciao!

