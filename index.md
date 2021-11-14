# MUSI 3770 Assignment #3 | Ripken Walker

---

# Interview with iOS Developer/Music Technologist Daniel Kuntz

Daniel Kuntz is an award-winning iOS application developer based in Atlanta, GA. Daniel is the founder of **[Coda Labs]**(https://codalabs.io/), a company that focuses on developing music-oriented iOS applications. When he is not working on apps for Coda Labs, Daniel also works on fitness tracking iOS app _[Any Distance]_(https://anydistance.club/). Daniel also previously studied Music Technology at the Georgia Institute of Technology. 

###### Author's Note

I have been lucky enough to play music with Daniel over the past year in the same band. Although we have seen each other many times and talked about music before, we have never had much of a chance to discuss aspects of his career in iOS development. I have personally used Daniel's applications and am grateful we could talk more about his career.

---

##### What are some of your current jobs right now?

I spend most of my time on this app called _Any Distance_, which is a fitness app. It’s not music technology, but I do have a collection of music technology apps available under my company **[Coda Labs]**(https://codalabs.io/). Those apps are primarily tools for musicians. Both of those projects occupy most of my time currently.

##### For this interview specifically, we will focus on your work with Coda Labs. I want to begin by talking about your introduction into computer science and music technology. What started that pathway for you?

I started playing guitar when I was about 10 or 11. I started playing piano as well as other instruments throughout middle school and high school. During high school, I wanted to find a way to make extra money and discovered some freelance development websites that pay you something crazy like $70 to add a button to an iOS app. I thought that was simple enough to learn how to do, so over a couple of years, I gradually developed my skills within iOS development while working on these freelance jobs.

Eventually, I started making my own apps. My first app was a metronome app called _Pulse_. I wanted to make a friendly and straightforward interface since many other metronome apps had complicated and ugly interfaces. The app was received well, and since it was so fun, I thought it would be fun to continue developing other apps. I made other tools like a tuner, a pitch training app, and an AR-based app that showed chords on a piano. Throughout all of this, my catalog of music apps kept growing.

My apps were free and were getting a lot of downloads, but I wasn’t making money. I wanted to create my own business out of the apps and start charging for premium features. Charging for premium features turned out to be a great idea, and it allowed me to have a full-time job developing these apps, which is really cool.

##### I want to go back to the very beginning of your career. What was the benefit of choosing iOS development over other operating systems like Android?

I think iOS was a lot more accessible to learn at the time. Swift wasn’t created yet, but it was the later days of using Objective-C. I’m not actually quite sure why I chose iOS. I had an Android phone at the time, and since I was doing iOS development, I could only test my apps with the simulator on my Mac. Maybe iOS just seemed nicer to me. I’m glad I did pick iOS since it is easier to make apps for it. Specifically for music apps, the audio engine is a lot more stable and predictable. It has its own issues, but as far as I know, it is much easier to use when dealing with issues like latency.

##### Since you only make iOS apps, have you had a lot of people ask about Android versions of your apps?

Yeah, a lot of people ask about that. I worked with someone who tried to remake one of my apps on Android and they had a ridicuously hard time trying to sync the screen animations with the audio engine. It seemed that different Android devices had various latency issues with their audio engine, which made the development very difficult and not very fun. 

##### I suppose that's why a lot of bigger companies will have developers that specialize in a certain operating system rather than one person doing everything. 

Exactly. Knowing all of the iOS APIs and Android APIs is just a lot to do. You can do a cross-platform thing like React Native or Xamarin, but I feel like you don’t end up with a good enough product that feels right. I just want to make something good from the beginning on iOS.

##### What was your primary source of learning how to program within iOS?

I used a lot of Stack Overflow, Youtube, a website with iOS tutorials called raywenderlich.com, and I may have bought a Swift course on Udemy. Most of my learning has been through finding an issue and then Googling it to try and solve it. Eventually, you figure out enough stuff so don’t have to Google anything nearly as often. 
 
##### When you are deciding to start building an app, how long do you think it takes you from beginning to release date for one of your apps?

On average, I think it has been about 2-3 months. A lot of it depends on how motivated I am for the app and also how complicated it is. Some are definitely more complicated than others, but you can really make anything as complex as you want it to be.

##### Is there one off the top of your head that took you longer than others?

Yes, I think the looper I made took the longest. I wrote a real-time audio engine that mixed tracks together with effects while also writing and reading from the file system. All of that was in real-time, which made it a very complicated and new experience for me.

##### Is there documentation for something similar that helped you out while making that looper?

For that specifically, I had to do a lot of guessing and reaching out to people. I reached out to a lot of people on the AudioKit forum. AudioKit is an iOS audio framework that makes it a lot easier to do simple development things. A lot of the people there work at plugin companies, DAW companies, and other places. Overall, building a DAW-like software is very complicated, and I’m still learning more about it.

##### When you are working on these apps (before Any Distance), did you maintain any sort of specific schedule for developing your apps.

Kinda; I would have to-do’s where I would want to get something done on a day, but I wouldn’t have a specific schedule for development. I have more of a task-oriented approach, so I will get a task done in however long it takes me. Doing a task-based approach still won’t take me too long, but it can definitely depend on the specific task.

##### What is one of your favorite apps you have made?

I think the one I’m working on now, _Any Distance_, is one of my favorites. _Impulse_, the metronome app I made is also a favorite. I think it was very unique in terms of functionality, and I still haven’t found anything that replicates it. Now that I think about it, I found a copy-cat of Impulse where they took the same interface I made and put it into another metronome app. I like Impulse a lot since it looks very elegant and people seem to pick it up easily. 

##### When you are deciding what app to build, why make another thing that exists like a metronome or tuner?

Early on, I was inspired since many of those apps did not look very nice and had been around for a long time. They were created for earlier versions of iOS, like around iOS 3 or 4, so they were designed to look good on those old operating systems. Apple made a huge update at iOS 7, which made all of those apps look very outdated. I just wanted to make a more modern version of those. 

##### A lot of these questions have been focused on the algorithmic approach for your apps, but you also do the design for your apps correct?

Yeah, I do the design in Sketch. That part is enjoyable for me too.  I treat them like miniature works of art. I draw all of the icons and screens from scratch; I don’t necessarily have to do them from scratch, but that part is still fun to do.

##### We have talked about a lot of your apps that are music related. You have worked on other apps as well. What was your inspiration behind making those non-music apps? 

In the end, I just enjoy coding stuff. I will get an idea for something and think "Why don’t I make something like that?" While I love music, I don’t want to restrict myself to just making music apps; it’s fun to do side projects as well.

##### One of the biggest questions I have for you: do you have any advice for someone trying to get into software development? 

Of course. I think you should try to make something “real” as soon as possible. Have a real idea for something you want to make of something that may be useful to you. It is a lot more exciting to build something real rather than creating something from a tutorial. Tutorials are fine, but eventually being able to have your own idea for a project and building it from scratch is such a rewarding experience. You learn a lot by doing that while also ending up with a product that actually works for you rather than a only being a tutorial.

---

## November 13th, 2021 | Atlanta, GA