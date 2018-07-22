# 100 Days Of Code - Log

### Day 36 - 37 -  20th & 22nd July 2018!

**Today's Progress** : Chrome Extension

**Thoughts** So I've continued with the Chrome extension I'm working on and it's coming along well!

I'm trying to use Github, along with Sourcetree, to properly manage issues, and branching of my dev to work on each in isolation then merging back in. It's what we do at work and seems a good way to manage it, but the issues on Github don't link to branches as well as Jira / Sourcetree do.

The app is coming along well, and I've been working on the UI elements. The extension icon is now active on the relevant pages, and when clicked, shows a lil pop up page with a field to add users to the block list, and shows a list of blocked users, along with a button to unblock them. 

I struggled getting the popup to activate on the page - I'd logged it in the manifest properly, but hadn't set up the background.js to  
use a listener with declarativeContent. Eventually got that sorted, and then struggled with the JS for the list.. Managed to make it dynamic - so a template is defined in the HTML. The JS file then gets the block list, and for each, clones the template, populates the name field and creates an event listener linked to that user. 

So, the extension is now at mvp point where it has the basic block function and users can be added or removed. I want to continue on with the other issues I've got - an inline block button, comment replacement instead of removal and should work on other newsquest sites. 

I'm finding it slower going to make the extension and thought it would be simpler. I can see that I don't know much about JS, DOM manipulation, and the Chrome API. So it's stuff I'm learning as I go, but also feel like it's better to do that making a functional product than just following tutorials.

**Links to Work**

1. https://github.com/scooby359/ChromeExtension-LTCommentBlock

### Day 35 - 16th July 2018!

**Today's Progress**: Chrome extension 

**Thoughts** Skipped coding yesterday - was knackered and really bad headache! So did some tonight, working on the chrome extension I'm making. Thought I had my head around this from the tutorial, but actually really confused what goes where! So starting slowly, getting JS to run when an element changes (bit I want to filter loads up while scrolling the page), then it gets all elements meeting a class type, then I can match off those which meet a specific filter. That's where I'm up to..

So next step will be to get the parent of those nodes, and delete them from the page, or replace them with a different div. Then further work to allow easily adding to the filters, initially manually by adding to an input field, but would be better to add a button to the page elements to make it easier to do.... Lots for the back log!

**Links to Work**

1. https://github.com/scooby359/ChromeExtension-LTCommentBlock

### Day 34 - 13th July 2018!

**Today's Progress**: Chrome extension tutorial 

**Thoughts** Firstly - met someone in Manchester who's also doing 100 Days of Code - hey Leila! 😁

Tonight, did a tutorial on writing Chrome extensions. Have an idea I want to make, so that'll be my weekend project.. want to be able to block users on the comments section of a local newspaper.. thinking it should just be selecting usernames (As a string), then finding divs which contain that, then hide them, or delete them from the dom.. or similar. So done the tutorial, fairly straight forward, but lots of JS again, and a big chrome library, but no intelisense to populate it for me! So I'll have to read the documentation a bit closer 😀

**Links to Work**
1. https://developer.chrome.com/extensions/getstarted
2. https://github.com/scooby359/ChromeExtension-LTCommentBlock

### Day 33 - 8th July 2018!

**Today's Progress**: Mean stack tutorial 

**Thoughts** Trying to have a look at more of a full stack approach - front end, apis and database, so found a YouTube tutorial which had good feedback, using angular, mongodb and a few other bits.. Started it off and got a couple of videos in. Bits I'm stuck with - VS code linting throwing up loads of stupid errors which I don't understand! And keeping up with the videos - lots of JS actions I'm not familiar with, like the http responses, assigning libraries to variables, and the use of node modules I'm not familiar with. But, I'll stick with it and it helps to pause the video and look through what we've done, and look into some of the things before I continue. So gone well, and will pick it up next week!

**Links to Work**
1. https://youtu.be/uONz0lEWft0
2. https://github.com/scooby359/meanstacktutorial

### Day 32 - 7th July 2018!

**Today's Progress**: .Net Core - Web Api 

**Thoughts** Finished the Web API tutorial! 😁 Managed to follow it through this time and got the system working. Seems pretty straight forward, but confused about the C# attributes - the bits in sqaure brackets before function and class declarations.. So that's something to have a look at, and I'll try a bit more with the web api tomorrow 

**Links to Work**

1. https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-2.1

### Day 30 / 31: 30th June / 1st July 2018!

**Today's Progress**: .Net Core - Web Api 

**Thoughts** Tried to follow thr .Net core tutorial on MSDN to create a simple web api. Spent a lot of time reading and following along, then realised I had the wrong version of .Net installed so it wouldn't work, then spent ages installing that, updating VS to then be told the project wasn't configured correctly. Eventually gave up.. a lot of time wasted!

Also did some reading on CSS layouts, particularly grids, and Angular

**Links to Work**

1. https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-2.1
2. https://angular.io/
3. https://css-tricks.com/snippets/css/complete-guide-grid/

### Day 29: 23rd June 2018!

**Today's Progress**: Typescript 

**Thoughts** So finished that week in Scotland, then a week in Belgium with no computer at all! Then I've started my placement job as a Software Dev this week! So no chance for #100DaysOfCode the past couple of weeks (or not been up for it!), and now with the time I'm spending on my new job, it's likely this will become just a weekend project.. probably.

So, reassessed my priorities, and will be doing more front end web work, as it's more relevant to what I think I'll be doing over the next year. Spent this evening reading through a guide to Typescript - I now know that it's related to JavaScript, but with extras! And simpler to type, more like the C++ I'm used to.

**Links to Work**

1. https://www.tutorialspoint.com/typescript/index.htm

### Day 22-28 : to 6th June 2018

**Today's Progress**: Games on Android 

**Thoughts** In Scotland so no internet! (Ha, like it's the whole country 😅) so I've been working offline with an ebook - Learning Java with Games on Android. I remember doing some of this last year (?) so some of the exercises are familiar, but they definitely make more sense this time round, and I've done a cool pong game with a manually drawn surfaceview instead of a usual layout, so that's been interesting to see what can be done.

Today, I'm going to continue on the pong style game I did last night - followed the tutorial through, but the game's quite basic, e.g. bad code layout, no classes, repeated variables, bad behaviour (e.g. bat can fly off the screen) so I want to extend the tutorial now and refactor and improve the code using my own knowledge.

**Links to Work**

1. Unable to upload! 

#### Tweets Sent - intermittent, mainly just likes where possible


### Day 21: 29th May 2018

**Today's Progress**: #100DaysOfCode Twitter app - Testing 

**Thoughts** Ugh.. Not much time on this today, but spent it trying to do the test for the presenter class. One function.. should be simple..? Nope.. because I need to validate a function call on another class, so in looking it up, I've ended up on Mockito and injection and factories and more in depth TDD styling. So what I thought would be simple opened a much more complicated process which I haven't got time to go into detail with tonight..

So, learning from this though is that I need to read a bit more into it! And maybe split my work a little - a simple app with TDD style, and a simpler MVP app that's not relying on the Twitter SDK, like a simple press a button and something happens on screen app, just to get my head around all this better?

**Links to Work**
1. [#100DaysOfCode App](https://github.com/scooby359/100DaysMobileApp)

#### Tweets Sent - ✓

### Day 20: 28th May 2018

**Today's Progress**: #100DaysOfCode Twitter app - Testing 

**Thoughts** Wrote some Espresso tests today! They validate that the reyclerview is visible, that the refresh makes the snackback appear, and that the progress bar is hidden... Simple but it's a start! Was trying to validate that the recyclerview had the expected content, but couldn't figure out how to check it.. all the tests were just returning the reyclerview itself, not it's contents..

Still some things I'm not sure of and feel like they should be testable - like when refresh is pressed, it calsl the refresh function. Should I be able to test that this call has happened? Not sure how though.. Will work on that later! And want to do the JUnit test for the logic side, that when the Twitter request is made, that I get a list of tweets back. Again, think that using Twitter's SDK might make that hard as returns a custom SearchTimeline object which is just managed by the the adapter. Not sure how I can get access to be able to check the size or contents to be able to verify that something is loaded from the functional side... Will play about later!

**Links to Work**
1. [#100DaysOfCode App](https://github.com/scooby359/100DaysMobileApp)

#### Tweets Sent - ✓

### Day 19: 27th May 2018

**Today's Progress**: #100DaysOfCode Twitter app - MVP 

**Thoughts** Back in at the deep end apparently! Spent three-ish hours reworking the Twitter app I started a while back, to display the #100DaysOfCode Tweets.

The app is now in MVP style - seperated into the view, a presenter and the data model, held together with an interface contract. This allows the view to call for data, which the presenter gets from the data model. The presenter can then send this back to the view which can use it to update the tweets being displayed.

Challenges were in linking everything together - the way that constructors need to be set up, and getting my head around how data objects are passed around. I'm also missing a bit around callbacks and data querys - I'm using the Twitter SDK which is nice because it just handles the search query.. but I don't seem to have access to onRequest / onWait / onSuccess / onFail functions, so I'm limited to how much I can adjust the view.. Might be missing something, or might need to construct the queries manually to gain more control... Not an issue right now as that's not an aim of the project.

Tomorrow's aim is to work on automated testing, and using what I learnt about JUnit and Espresso to test the view functions, eg when refresh is pressed, does the proper function trigger (and I don't need to worry about the result because it's all seperated by mvp!), and when the presenter logic is run, does it function as expected... Tomorrow's job!

**Links to Work**
1. [#100DaysOfCode App](https://github.com/scooby359/100DaysMobileApp)

#### Tweets Sent - ✓

### Day 18: 26th May 2018

**Today's Progress**: Google Codelab - MVP / Testing 

**Thoughts** Back at it!! Had a break with exams and revision - needed to put that first, then was a bit frazzled so didn't want to then be coding and not getting a break. But I'm back and picking up where I left off!

Trying to get my head around MVP architecture and the benefits it brings to automated testing. Completed the Google Codelab on Android Testing which goes through MVP architecture and an example app, along with JUnit and Espresso testing - JUnit is for functional Java logic code - it works well with MVP as it reduces dependencies, so you can just test straight forward functions without the need for views and layouts for grabbing values or outputting results, which is a problem with using one Java file for the interface and business logic. Espresso simulates the Android UI, allowing you to reference objects on screen and interact and test values. It's good, for example, for testing user inputs and that actions are called when buttons pressed, etc. 

So I've a better idea of how MVP structuring works, so I need to have a go at some now, and could do with a bit more reading to try and embed it. That can then be used back in the #100DaysOfCode app I was working on, so that I can work on automated testing alongside building it - as a simple app, it should be a good place to start trying out what I've learnt.

**Links to Work**
1. [Google Codelab - Android Testing](https://codelabs.developers.google.com/codelabs/android-testing/index.html)

#### Tweets Sent - ✓

### Day 17: 29th April 2018

**Today's Progress**: #100DaysOfCode Mobile App 

**Thoughts** HAd a few days off, between hectic last week at uni and feeling awful from hayfever tablets... Been doing bits of JS on Grasshopper though, and done some Android reading when I could. Spent a lot of time today reading about design structures, Play Services and Android Support Libraries. Wanted to try and build an app for #100DaysOfCode using thw Twitter API... spent an hour and a half on it, but it wouldn't work.. think I put a # symbol in the project name which seems so have had weird side effects throughout the code. So after messing for a while, I've deleted and will start again. Kind of a lost programming session, but lesson learnt on using symbols! And I've had a playw ith the Twitter API stuff so that's been useful.

**Links to Work**
1. [#100DaysOfCode App](https://github.com/scooby359/100DaysMobileApp)

#### Tweets Sent - ✓

### Day 16: 23rd April 2018

**Today's Progress**: Firebase in a Weekend - Part 2! 

**Thoughts** Head's frazzled after spending a few hours on this. And it was really just the Functions with JS at the end that did it! Some really cool features in Firebase though, especially the push notifications, online storage and remote config. Completed the tutorial, so need to think about how I could use some of the features in a personal project..

**Links to Work**
1. [My GitHub Repo for the Work](https://github.com/scooby359/and-nd-firebase)
2. [Firebase in a Weekend (Udacity)](https://classroom.udacity.com/courses/ud0352)

#### Tweets Sent - ✓

### Day 15: 22nd April 2018

**Today's Progress**: Firebase in a Weekend. 

**Thoughts** Working through a Google course on learning Firebase in a weekend! Was one of the things on my wishlist and someone on linked to the course with the #100DaysOfCode tag. It's a guided course, making a simple online messaging app. So far, I've forked the basic code for the chat app, then I've created a project in Firebase, implemented a realtime database for the messages and user authentication using FirebaseUI. There's a couple more days to go with it, but each day is about 4 hours of work. So good progress with it today, and I've figured out how to fork the code so I have my own version on GitHub! Will continue this for the next couple of days as it goes into online storage, analytics and testing, as these will be useful in future projects.

**Links to Work**
1. [My GitHub Repo for the Work](https://github.com/scooby359/and-nd-firebase)
2. [Firebase in a Weekend (Udacity)](https://classroom.udacity.com/courses/ud0352)

#### Tweets Sent - ✓

### Day 14: 21st April 2018

**Today's Progress**: Android A6 project. 

**Thoughts** Spent a few hours on this tonight! Worked on exporting the data to a CSV file. Had to work through the process of creating the file and appending the string contents to it, and then was held up by file permissions, as the newer Android APIs don't let you just declare it in the manifest, it also needs explicit user consent gaining. So I worked through that and the settings now asks for write permission when the button is pressed, then creates the export if permission given. Then did some tidying up - used the code analyser to pick up any bad habits, like variables which could be private, or unused code. Tested it all with a real data set, and I'm now happy that it does what I need :)

Thinking that there are a few small touches that could be added, like an improved layout design, ability to select many notes for deletion at once, and using snackbars instead of toasts. But... it also feels like I'd be spending a lot of time doing little niggly things that don't make a big difference.. maybe valuable in a real customer project, but for the sake of the 100 Days of Code project, feel like I'd be wasting time on trivial bits. So, that being the case, I'm going to close this app off - I can use it myself now as it meets the needs I had for it, and I can move on to something else on my 100 Days of Code wishlist.

**Links to Work**
1. [A6v3 GitHub](https://github.com/scooby359/A6v3)

#### Tweets Sent - ✓

### Day 13: 20th April 2018

**Today's Progress**: Android A6 project. 

**Thoughts** Missed another day yesterday and didn't get anything done tonight.. so tired! Think it's the hayfever tablets making me so sleepy. But.. I did get a load done this afternoon so was working on my Android project. Working much better since I changed the folders with less build errors. So Wednesday, I managed to load the Android file access thing and got a URI link. Today, I've worked on opening the file, working incrementally.. first logging the contents to the console, then appending on screen, and now I've modified the class entity to accept strings in a constructor, so I can make objects which are now importable to the database. So the next bit to work on is exporting the database, which I don't think will be that hard, and probably similar to what I've done today.

**Links to Work**
1. [A6v3 GitHub](https://github.com/scooby359/A6v3)

#### Tweets Sent - ✓

### Day 12: 18th April 2018

**Today's Progress**: FreeCodeCamp Basic Javascript Algorithms and Android A6 project. 

**Thoughts** Had some free time at work today, but no laptop, so did some FreeCodeCamp tasks with JavaScript. It's not my main focus for the #100DaysOfCode project, but I do want to get round to some server stuff, so JS will be helpful, and it was still some coding and still thinking about breaking problems down. Later on, tried to do some Android work but AndroidStudio keeps playing up - tried to delete files and re-pull from Git - that usually works with Unity, but in this case, Android Studio won't create any new files... But I'm way too tired, falling asleep and can't think straight so leaving it there for the night. 

**Links to Work**
1. [A6v3 GitHub](https://github.com/scooby359/A6v3)
2. [FreeCodeCamp](https://www.freecodecamp.org/scooby359)

#### Tweets Sent - ✓

### Day 11: 17th April 2018

**Today's Progress**: Android A6 project. 

**Thoughts** Missed yesterday, needed me time! Spent time today (and yest) reading up on Android automated testing. Founce some resources on how testing should be done, benefits and coding style, and some on the actual coding with JUnit and Mockito. Had a play and created some unit tests for my database and note class. Written some notes up to help me remember! 

**Links to Work**
1. [A6v3 GitHub](https://github.com/scooby359/A6v3)

#### Tweets Sent - ✓

### Day 10: 15th April 2018

**Today's Progress**: Android A6 project. 

**Thoughts** Lots done on this today and last night after my log! The basic app is done - all functionality is complete, including listing notes, search of notes, creating new notes from blank or from input search text, edit existing notes and delete notes. Checks created for cancelling edits or deleting to confirm user wants this (they take a lot of time, thinking of all situations and writing lots of little bits to cover them). Local backup also works which I've tested with ADB. I'm now going to fork it two ways - I want to set up some automated testing and have a play with that, and I want to work on import / export of entries so I need to work with external storage and generating a file from the database output. 

***Update***  - Spent loads of time on this today and also had a play around with the IDE to learn it better and customise. Using Twitter more to engage with community - finding useful pages, interesting people to follow, etc. Also set up a useful pages link on Git of things I've found which are useful and I want to come back to or share with others.

**Links to Work**
1. [A6v3 GitHub](https://github.com/scooby359/A6v3)
2. [Useful Pages](https://github.com/scooby359/100-days-of-code/blob/master/Useful%20Pages.md)

#### Tweets Sent - ✓

### Day 8-9: 13/14th April 2018

**Today's Progress**: Android A6 project. 

**Thoughts** Spent a lil time on this on Friday but was so tired I gave up after a short while. Picked it up on Sat though and spent most the evening on it. Lots done - db works, listview works, clicking on item takes through to editing with prepopulated fields, back then checks for changes and prompts to save, or can use the save button. Search implemented on main list - list updates but status icon gets removed from all entries.. not sure why. And while trying to fix that, other things are breaking.. can't get XML design mode to work now, it's not showing an SDK, and I keep being forced to rebuild the project grr!

**Links to Work**
1. [A6v3 GitHub](https://github.com/scooby359/A6v3)

#### Tweets Sent - ✓

### Day 7: 12th April 2018

**Today's Progress**: Uni work - C++ (C11, pointers) and Android A6 project. 

**Thoughts** Spent an hour or so on some class work for Uni playing with C11 unique pointers and functors. Then tried to get back to an Android project I started a couple of months ago and left... Didn't realise how rusty I'd be on it! Also played with the Room database manager instead of raw SQLiteDBHelper, so that took a bit of learning on top of remembering my work. But, spent a good hour with build errors and update installations and blah.. so gave up on and will pick it up tomorrow.

**Links to Work**
1. [A6v3 GitHub](https://github.com/scooby359/A6v3)

#### Tweets Sent - ✓

### Day 6: 11th April 2018

**Today's Progress**: Completed some JavaScript training on FreeCodeCamp. 

**Thoughts** Firstly, I missed coding yesterday - being at uni all day, gym at night and trying to have some time for me meant it just didn't happen. And was going to do some tonight, but it's not happened either as I've been at Uni and the gym again so it leaves little free time... So, taking stock somewhat, I accept that there are some days it's just not going to be practical to get an hour of coding in. I'm making a point of recognising that now as it's going to happen again, and I specifically don't want to get beat up by it as that's just how it is, as long as I'm making the effort when possible. And I'm cool with that :)

That said, I did have some free time during the day today so spent it on the JavaScript exercises on FreeCodeCamp. Have done JS before, but years ago, so it was good to have a refresher and once I realised how similar it was to the languages I've been using lately, I skipped over to the more complex bits. Completed some of the practial challenges and had a play with arrays and regex.

**Links to Work**
1. [FreeCodeCamp](https://www.freecodecamp.org/scooby359)

#### Tweets Sent - ✓

### Day 5: 9th April 2018

**Today's Progress**: Completed Portfolio Site. 

**Thoughts** Finished my portfolio! Looked at a few portfolios online last night and took some ideas to change my contacts and about section. Also found a new Bootstrap theme which I like more, and I've filled out the examples so the cards now open modals with an image and details of the example project. Deployed to Azure, put Google analytics in for some basic tracking, and Azure seems to have put SSL on! (not sure how or why!). Ready to move on, and update as needed. Also need to put some of the games assignments on - would like to link to code, but wary or uploading assignment code due to collusion/plagirism issues - will have to just do this for personal projects.

**Links to Work**
1. [My Portfolio Site!](https://chriswalton.azurewebsites.net/)
2. [GitHub Repo](https://github.com/scooby359/PortfolioSite)

#### Tweets Sent - ✓

### Day 4: 8th April 2018

**Today's Progress**: Worked on Portfolio Site. 

**Thoughts** Worked on my Portfolio site, using the ideas I had yesterday. The cards on the home screen now open a modal when clicked, so I can use this to provide more information on each project without cluttering the page. Also done the contacts section with links and embedded mt Twitter feed. Not keen on how the contacts section looks though. Just sussed out Azure web app deployment and uploaded files - I'm online!!! To do - fill in project information and create template for easy updating; sort contacts section (have a look at others pages for ideas)

**Links to Work**
1. [My Portfolio Site!](https://chriswalton.azurewebsites.net/)
2. [GitHub Repo](https://github.com/scooby359/PortfolioSite)

#### Tweets Sent - ✓

### Day 3: 7th April 2018

**Today's Progress**: Completed the FreeCodeCamp Tribute Page challenge. 

**Thoughts** Short day - still suffering migrane effects so just did a bit late on. Did the tribute page to Alan turing, used Bootstrap, CSS and HTML elements. Uploaded code to GitHub. Also made some notes in my journal about the jQuery functions / format for reference. Next challenge on CodeCamp is portfolio - fits in to what I started a few days ago so will continue to work on that next, using a simple one page format. Can come back and improve on it later - > use modals to pop up info about individual projects, keeps on one page but allows me to embed more detail and take advantage of more Bootstrap tools?

**Links to Work**
1. [CodePen project](https://codepen.io/scooby359/pen/PRyvwr)
2. [GitHub Repo](https://github.com/scooby359/FreeCodeCamp-TributePage)

#### Tweets Sent - ✓

### Day 2: 6th April 2018

**Today's Progress**: Working through the website stuff on [freeCodeCamp](https://www.freecodecamp.org/). Up to 100 points and refreshed on HTML, CSS, Bootstrap and jQuery. 

**Thoughts** Good to have a refresher on the website stuff, been a couple of years since I've worked with it so there were bits I'd forgotten but it came back quick. Got to do the Tribute page task - will do on Alan Turing. Migraine kicked in though so had to give up for the day. Need to make some written notes to help what I've learnt stick, and also so I can flick back if needed for a reminder - will do tomorrow.

#### Tweets Sent - ✓

### Day 1: 5th April 2018

**Today's Progress**: Started building a portfolio site with HTML and Bootstrap. Set up Git, Visual Studio Code and started on homepage.

**Thoughts** Not done any HTML for a while so having to reference quite a bit. Page is just static html at the moment. Want to develop to support 100 days of code log as well as portfolio of work

#### Tweets Sent - ✓

**Link(s) to work**
1. [PortfolioSite](https://github.com/scooby359/PortfolioSite)

### Day 0: 3rd April 2018

**Today's Progress**: Reading up on 100 Days of Code project, listed some ideas.

**Thoughts:** Want to commit to project but also worried of running out of steam or not knowing what to do next. Come up with a list of ideas of things I'd like to do, or that fit with other work I'm doing and worth exploring. Thinking 10 projects / 10 days to fill up 100 days?
