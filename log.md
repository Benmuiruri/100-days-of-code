# 100 Days Of Code - Log
Hi, I'm Haley! Welcome to my #100daysofcode journey. I am a self-taught Front-end web developer in the making. 😁💻

An important note to mention before I start with my first day on Github: I had already started the #100daysofcode challenge on Twitter. And as of April 2nd, 2019 I am at Day 11. However, it occurred to me that posting brief tweets about my daily progress would not help me reflect properly on what I've learned and what I've struggled with. I find this crucial to when the lessons become more complicated (i.e when Javascript and its frameworks are introduced). Since I already push my projects to Github, I thought I might as well fork the famous existing repository and log my progress here everyday. Currently, I am becoming more comfortable with HTML and CSS. My learning sources are:
1. freeCodeCamp: I am currently finishing the Responsive Web Design projects.
2. [The Complete 2019 Web Development Bootcamp by Angela Yu (Udemy)](https://www.udemy.com/the-complete-web-development-bootcamp/): I currently paused at Javascript (I haven't started it), I will once I receive the first certificate from freeCodeCamp.

I will continue with the old count on twitter only. For details about my progress in the last 10 days, check out my [twitter](https://twitter.com/haley_dvlpr) account (Pinned tweet). Let's start this challenge!

### Day 1: April 2, 2019
##### (freeCodeCamp - Responsive Web Design Projects - Build a Technical Documentation Page)

**Today's Progress**: Filled the HTML Skeleton. Nothing more. Actually, it was more challenging than doing main CSS styles and breakpoints, because finding content was challenging. You don't want random irrelevant paragraphs, but you also don't have the time to include all the little details of the documentation you're trying to mock (in my case, C#). I salute the people who work on technical documentation. It was my first time ever including <code>code</code> element in my HTML.

**Thoughts:** No big struggle. But it took a while to simplify and shed off alot of content. 

**Link to work:** [Codepen.io](https://codepen.io/haley-dvlpr/pen/bJEpEX)

### Day 2: April 3, 2019
##### (freeCodeCamp - Responsive Web Design Projects - Build a Technical Documentation Page: COMPLETED)

**Today's Progress**: So this was easy, and I liked the dark theme with the touch of pink. I found two pseudo class selectors useful today: <code>:not(:last-child)</code> and <code>:first-child</code>. I also learned about the pre element **(by accident, lol)**, and I wrapped my code inside it because I wanted to group multiple code lines and style them as one big <code>code</code> element. The pre element apparently shows the whitespace in the HTML doc by default. So according to this [Stackoverflow post](https://stackoverflow.com/questions/31753617/how-can-i-remove-leading-whitespace-in-my-pre-code-block-without-removing-in), whitespace can be removed by adding this property: <code>white-space: normal;</code>. So I did that.

**Thoughts:** I guess the code arrangement could use a fix and syntax highlighting could have been added, **but**, given that I don't know C# (yet), I didn't bother looking for extensions that would take care of that. Too soon.

**Links to completed work:**   
[Github Page](https://haley-dvlpr.github.io/FCC-Technical-Documentation/)  
[Codepen.io](https://codepen.io/haley-dvlpr/pen/bJEpEX)

### Day 3: April 4, 2019
##### (freeCodeCamp - Responsive Web Design Projects - Build a Personal Portfolio Webpage)

**Today's Progress**: Today I spent about 2 hours just looking for that perfect portfolio layout/design. I guess I'm stressing about it being perfect and looking professional, even though I'm technically a web dev newbie. I also realized that I'm pretty sure I want to do UI/UX + Front end development. I'm interested in learning about interaction design and enhancing users' accessibility and satisfaction. Anyway, back to the portfolio. I barely wrote any code. Just a skeleton. Not even going to refer to its link but it's there in my repositories section. Here are some of the portfolio ideas that I liked so far:

![portfolio sample](https://res.cloudinary.com/dzqqlj7am/image/upload/v1554415097/22.png)

![portfolio sample](https://res.cloudinary.com/dzqqlj7am/image/upload/v1554415097/24.png)

![portfolio sample](https://res.cloudinary.com/dzqqlj7am/image/upload/v1554415097/20.png)

I very much hope I figure out and finalize my portfolio's design by tomorrow afternoon. Can't wait for that FCC Responsive Web Design completion certificate!

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


### Day 9: April 10, 2019
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
