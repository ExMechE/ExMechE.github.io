# Next It Application

## Weekly Updates
### Week 15
Last week, I finished all the documentation tasks for continuing the project beyond this class. I also finished up work for other classes, including assignments and exams. Glad to be done!

This week, I will finish up the report, add anything related to feedback, and reflect on the class as a whole and plan when to continue the project.

No, everything has been really smooth and this week. The last couple weeks were really hectic but it is winding down finally.

Throughout this class, I was motivated to write reflections and make weekly project posts because they are for a grade. However, I need to continue to stay motivated to write similar things in the future because there have been a number of good ideas that have come to my mind while writing them.

### Week 14
What did you do last week?
Last week, I pointed the remaining stories I will assign myself the last week of the semester. Most of this is related to documentation but still important nonetheless. I am also have quite a few final exam/final project work to get done so will be balancing my time between those responsibilities.

What do you plan to do this week?
This week, I will finish up the documentation and update the repo to the latest tags.

Are there any impediments in your way?
No, things are winding down and I am mostly done with the main things.

Reflection on the process you used last week, how can you make the process work better?
The process has been smooth so far, hoping to continue this focus until the last day.

### Week 13
What did you do last week?
Last week, I refined data storage and processing in the application, leading to less buggy transitions.

What do you plan to do this week?

I plan to integrate some other unique features of flutter packages related to UI.

Are there any impediments in your way?

No, not that I can think of.

Reflection on the process you used last week, how can you make the process work better?
I have been so engrossed in this project that I wasn't able to put in as much focus into my other class. I will be more balanced this time.

### Week 12
Last week , I ran into several issues with storing user data related to google maps searches. I did some basic debugging without much luck so that is to be continued.

Next week, I will continue debugging the issues that I had above and maybe set up a better system for data management. I am not sure how long this will take but this will be an important step in scaling up the application to store a lot of attributes at the same time.

I don't really have that many impediments. After narrowing the scope a bit in the last couple weeks, I will likely not have an issue excelling in all my objectives, and this will give me a great direction for finishing it in the months after the class is over.

 
I definitely have a good plan for the next couple weeks and my motivation has been sustained and will continue to snowball through the end of the semester. I have learned that a little bit of pressure is effective for helping me attain my goals.

### Week 11
I took advantage of last week to reset and take a break so that I can re-enter the project with a set of refreshed eyes. 

This week, I plan to add additional flutter plugins to the project to enhance functionality and UI. These include a refreshed navigation bar and storage of past searches. If there is time, I also expect to update my repo on github to make sure everything is being updated and documented properly.

I don't foresee any impediments in my way. However, there always exists the potential for debugging to take up more of my time than expected. Hopefully, the tasks I have assigned this week aren't too heavy.

Last week was a good time to reset. I think if I find myself struggling to come up with some ideas I should take a break for a day.

### Week 10
Last week, I completed initial implementation of google maps integration, allowing users to search for a location and giving a preview. This took quite a bit of trial and error.

This week, I plan to test the functionality of the google maps integration, including storage limitations and optimizing the speed of this feature if possible.

As for any impediments that might exist in the near future, I don't think there should be any concern. I plan to use Spring Break to rest and do a planning poker like session with the rest of the work left.

So far, I think one way to improve is to spend a little bit of time every couple of days for ideation. Sometimes, while working, I get a few random ideas and then I forget them a day or two later. I need to take some time to record these ideas and expand on them if possible.

### Week 9
Last week, I started implementing google maps API into my project but ran into quite a few issues which slowed down my progress. There seem to be some issues connecting to the service but I will devote the next week to smoothing out this part.

This week, as mentioned above, I need to resolve all the issues with implementing google maps API and starting on the restaurant recommendation process. This will also be a good time to reflect on my progress so far through the Project Update Report. This may give me additional ideas for how to troubleshoot and the next steps.

I don't foresee any impediments in the way of my project this week, but I can definitely see there being an issue with data management. Even with limited functionality, there seems to be a warning of too much work being done on the main thread of the application. I will have to devote some time to optimizing the stack of the application. I will also need to look into best practices surrounding app development.

As for how to make this process work better, I can plan out the work a little bit more conservatively, too make time for debugging. This next feature has the potential to take up quite a bit of time.

### Week 8
Last week, I had I troubleshooted the errors I was getting when trying to implement a database. I resolved all the errors and tested storing instances of restaurant searches. I stored these by time initiated and they contain several attributes such as category and price. There are still several optimizations I want to do related to data management and I need to separate some of the database operations into separate files.

This week, I plan to continue exploring more of the applications of google maps API in this project. I am planning to implement filters for distance and top x restaurants in the area, among others. Time permitting, I will test all this functionality and make modifications to the UI for these steps.

As of now, there aren't any obvious impediments. As always, there could be unexpected things come up, such as issues with how data is stored or transitions between the screens. This is why I became more conservative in what I schedule to get done in a week.

One thing I plan to do to make this process work better is to do a bit more planning prior to implementation. In the last couple weeks, I started coding right away and ended up with a messy file that will need to be organized soon. This became more difficult to debug.

### Week 7
Last week, I planned to integrate location services into my application but I ran into some issues with heap memory when trying to integrate some basic data storage for testing purposes. Therefore, I had to pivot to implementing a database to store instances of user requests. I started implementing this via SQLite and moving a lot of the operations to background processes. I did not finish this as I am still troubleshooting this. 

As mentioned above, I will still be troubleshooting and implementing this database storage. Time permitting, I will then resume the location services implementation. I am taking a break from UI refinements to quickly get the functionality of this application up and running. 

The main obstacle in my path is resolving how data is stored. Hopefully I can resolve as much as I can this week which will then enable future queries to be performed similarly.

Based on what happened last week, it is clear that I underestimated the time it would take to implement the location services package. In the future, in story point planning I think I need to have an "enabler" story to more accurately plan and estimate certain features of the application. For example, I wasn't sure how much time a database would take to implement. I will need to reevaluate features similar to that complexity.

### Week 6
Last week, I completed the implementation of the login page and home page of the application. I also put in a couple placeholder pages for "friends", "saved", and "profile". After doing some research, I realized that the steps for implementing google sign-on weren't too difficult so I ended up completing that part. For now, the UI is very unrefined, but that may be updated in a future sprint, time permitting. I put in pictures of my progress below.

This week, I plan to integrate location services into my application. Depending on how that goes, I will start working on the restaurant recommender portion of the application.

The main impediment I can think of is that currently, I am developing on a windows computer, which limits me to android and device development. Originally, I planned to develop for both iOS and android, but that would require a lot more resources. For now, I will change the scope to only android devices. If I find a friend willing to let me borrow an apple device, I can do some testing in the future.

I got a lot done this week so right now I need to try to maintain the momentum as much as possible.

### Week 5
Last week, I planned out most of the stories I expected to complete the first 2 sprints, including application layout and ideation. I also started work on designing the home page and login page of the application.

This week, I plan to complete the design and implementation of the login page and home page of the application. I will share progress and designs next week. I am also planning to integrate a basic credentials/login system. If I were to expand into compatibility with google login, I will explain that plan and next steps.

I am much more comfortable with using IDEs like Visual Studio Code than Android Studio so I made that transition last week. However, I ran into some emulator issues so I am still cleaning those up. However, that impediment should be resolved soon.

As for how I can improve my workflow, I need to reevaluate my pointing system for the stories I am working on. I plan to re-point the stories I have planned and will plan, and divide some larger stories into smaller less daunting tasks.

### Week 4
Last week I still was in the process of learning Flutter, spending time on several tutorials and other online resources. I also started focusing more on UI/UX, downloading other similar applications and getting inspiration for design features I would like to implement, given enough time. I also set up an Agile board as mentioned before to organize my thoughts, provide time estimates, and better plan future sprints. This board is located here: https://trello.com/b/CkbVt8Hk/next-it-application-trello

This week, I plan to complete the Flutter learning period, accepting that it is not smart to try and learn everything right now. The important thing is to cover the basics. I can choose to specialize in more specific things later as things come up. I also plan to finish my first official sprint, which covers the ground work for my first application feature.

As of now, I am struggling to come up with the best approach for implementing my first feature. I don't really know where to start. To mitigate this, I am planning to jump in with a few pieces at the time. I will focus on making things look nicer later.

I am a lot more organized as compared with two weeks ago. However, I struggle staying in a good rhythm. From now on, I am planning to set aside 1-2 hours 3 times a week, blocking off this time to focus solely on this project.

### Week 3
Last week, I finished setting up my flutter environment for my application and determined what functionality I wanted to include. I also finished writing my project proposal after getting feedback on some things I could potentially include in that proposal and project as a whole. I also started making a habit of writing things down as soon as I think of new ideas or features, and then evaluating how feasible each of them could be considering the time frame.

This week, I plan to continue experimenting with the flutter environment, the libraries, and the theme of my application. From there, I will see if I need more resources to understand the application development process!

Right now, I don't have any impediments with the exception of learning a completely new language and framework. I already anticipated this by giving myself several weeks to begin implementing one feature, which includes learning this new environment. But, this could be something I need to extend.

As for what I could improve, I mentioned setting up an agile story board of tasks and effort required, which I haven't set up yet but I will next week. 

## Project Proposal

### Vision statement: how will this project expand your professional skills and knowledge?
1. I will gain hands-on experience with application development frameworks
2. I will work with APIs related to location services and learn how to retrieve real-time data from various sources
3. I will develop experience with backend services for data storage and management

### Motivation: why is this project important to you?
For one, this application is meant to solve a problem that I have almost every weekend. I like doing spontaneous things but there is usually never an organized way to do things spontaneously. I am also curious about the entire process of developing an application which isn't something offered in my undergraduate work. This will be something that I can be proud of after creating it.

### Specific and measurable goals (learning objectives) for the project. Remember that a total of 45 hours will be dedicated to the course and project over the 16 week (or 12 week summer) semester. You want to limit the scope of your project based on that time limitation.
- Week 2-3: I will complete research into the framework, APIs, data handling, and additional plugins.
- Week 4: Create a complete set of user experience sketches/designs
- Week 5-8: Create a minimum viable product that can fetch and display nearby recommendations.
- Week 9: Bug testing and refine UI
- Week 10-11: Implement other features related to user data and credentials
- Week 12: Implement feature related to friend groups and social networking
- Week 13+: Extend as necessary previous sprints or investigate other features

### Risks to project completion, possibly including:
- I will need to learn a new framework
- No prior experience with APIs
- Financial limitations in utilizing some APIs or libraries
- Poor time estimation due to beginner knowledge

#### Mitigation Strategy for the risks listed above
- Utilize tutorials and documentation to becomes familiar with new softwares
- Utilize open source softwares along with free tiers of APIs or plugins
- Consult the CSPB community with certain roadblocks

### Project Assessments/Evaluation Criteria:
- Application is functional across both Android emulator and Android test devices
- Primary feature of event/restaurant recommendation is implemented and tested
- Secondary features of social network, user data, etc. are implemented
- Up-to-date project repository and all documentation complete
- Plan for future updates in place

Project portfolio link: https://exmeche.github.io/
