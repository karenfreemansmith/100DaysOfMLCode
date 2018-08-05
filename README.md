exaggeration# 100 Days Of ML Code Log
I've been working through the courses at DataCamp.com for the past month or two and am getting close to finishing the "Data Scientist Certificate" there... AND I'm working on an ML project at work (which is why I signed up at DataCamp in the first place). For this challenge I intend to do an hour of NOT WORK related ML coding each day.

### Day 32: August 5, 2018
**Today's Progress**: Cleaning up my messes, getting different experiments onto different branches, debugging the database stuff that isn't working as expected.

**Thoughts**
GIT is the best thing ever! I liked it before, but right now I have like 4 different bots that I can run in test mode just by doing a "git checkout". It's pretty cool to be able to kind of compare them side by side like that.

It's funny how fast complexity can sneak up on you... and how tangled your ideas can get when you stay up all night trying to get "just one more thing" working before you go to sleep. Okay, maybe not that funny...

**Link(s) to work**
* https://www.facebook.com/microacademybot


### Day 31: August 4, 2018
**Today's Progress**: Read about NLTK (Natural Language Toolkit) and played around with it half the day, then spend the other half trying to parse some text from Project Gutenberg into a database to give my bot a better vocabulary. Mixed results. Lots of words, but still not making sense in a conversation.

So I'm trying another idea starting from a completely blank slate and training the both through actual conversations. It's still a work in progress.

**Thoughts**
Wow, the day went by fast....I barely took a break all day long and now it's after midnight. I've got some text still being loaded into one of my databases that I can use for my chatbot, and I'm working on another one, just fresh because I want to see if the bot can learn "appropriate" responses from a conversation or not. I hope to have one or both of these ideas added to my bot tomorrow, well today now, I wanted to get it before I went to bed, but that doesn't seem likely now.

**Link(s) to work**
* https://www.facebook.com/microacademybot


### Day 30: August 3, 2018
**Today's Progress**: After watching a few people interact with my bot, I made some changes to make the conversation flow better. Added a bunch of emoji to my list of default responses. It's amazing how versatile a smiley face can be in conversation. Next up is to try to create some kind of memory that lasts at least as long as any given conversation.

Finished Chatbot course on DataCamp. Final chapter focused on using state to maintain a context for interpreting messages based on the point in the conversation (example was ordering coffee).

Also read over the first chatbot in my book. They built it with a service called "Chatfuel" that has you build your bot with cards of various kinds... and then you create a program flow between the cards.

**Thoughts**
This DataCamp course seemed poorly put together. I spent a lot of time debugging code from their tutorials to actually get my bot to work. The other complaint I have about DataCamp in general is that the lessons are kind of hit and miss. They have exercises (good), but you only fill in the blanks to get their code to run. You CAN sometimes run the code as it's written, but a lot of the exercises seem to depend on background code that only runs when you submit the exercise (and you never actually see...) so it's hard to know exactly what you need to do in a real life situation. And they don't allow for any kind of modification or playing with the code to see how different changes may (or may not) work. It leaves me feeling like I didn't learn as much as I'd like.

I liked looking at the Chatfuel system and seeing how they built their bot. I don't think I'd want to build my bot with their software because it really does take the fun out of it. But there were some great ideas about how a bot application could work (like buttons for standard responses) and an overview of how all the pieces fit together - or the conversation flow. Glancing ahead it looks like the upcoming chapters may have some interesting deployment ideas and the variety of bots they build is interesting as well. (I'm reading this on SafariBooksOnline which costs as much per month as this ONE book costs on Amazon. I know it's still a lot for some people, especially if you live outside of the US, but it's been a big money saver for me to NOT buy a book a week anymore. Including both links to the book for those that might be interested.)

**Link(s) to work**
* https://datacamp-karenfreemansmith.notebooks.azure.com/nb/notebooks/DC24_BuildingChatbotPython.ipynb
* https://www.safaribooksonline.com/library/view/hands-on-chatbots-and/9781788294669/
* https://www.amazon.com/Hands-Chatbots-Conversational-Development-interfaces/dp/1788294661/ref=sr_1_1?ie=UTF8&qid=1533353864&sr=8-1&keywords=Hands-On+Chatbots+and+Conversational+UI+Development+Hands-On+Chatbots+and+Conversational+UI+Development


### Day 29: August 2, 2018
**Today's Progress**: It's alive! (It's still on an ngrok tunnel that collapses every few hours...but it's alive on Facebook when the tunnel is working.)

Skipped my lesson on DataCamp in favor of starting a book on Chatbots. 8 chapters of sample chatbots to read through in the upcoming days. Watched a couple of Siraj videos about chatbots as well, some reinforcement of what I'd just been reading there.  

**Thoughts**
These chatbots seem to be build on systems provided by others that do all the heavy lifting, you just hook them up to your favorite messenger service. That may be a little bit of an exaggeration, but it is a little discouraging that they don't seem to get into the actual coding fun of building the bot.

**Link(s) to work**
* https://www.facebook.com/Micro-Academy-Bot-784488255274717


### Day 28: August 1, 2018
**Today's Progress**: Chapter 3 of the Chatbot course about using databases and turning natural language into queries. Still trying to get this thing to be live online

**Thoughts**
Still too many recruiters calling all day long. It's hard to concentrate and actually sit down and spend a whole hour uninterrupted. Sometimes it's disappointing how badly the jobs actually fit my interests right now. They always want something that I did last year or 10 years ago instead. On one hand, whatever pays the bills, but it will take at least a little ML in the job description to get excited about any of these jobs.

**Link(s) to work**
* https://www.facebook.com/Micro-Academy-Bot-784488255274717


### Day 27: July 31, 2018
**Today's Progress**: Chapter 2 of the Chatbot course got into actually using ML for the chatbot. Word vectors, sklearn, spaCy, RasaNLU. Did all the exercises, but ran out of time to apply any of it to my chatbot.

**Thoughts**
Too many recruiters calling all day, it's hard to get anything done. I mean, a job would be nice, but I'm feeling overwhelmed by all the attention. And I expected that being unemployed would give me more time to study and build things...

**Link(s) to work**
* https://www.facebook.com/Micro-Academy-Bot-784488255274717


### Day 26: July 30, 2018
**Today's Progress**: Reviewed the first section of the chatbot course and tweaked my chatbot logic a little. I also got the chatbot running in a docker container on my computer. Still trying to figure out how this elastic beanstalk works. I seem to be missing some file that it wants.

**Thoughts**
At this point I'm thinking EC2 would be "easier" than their "easy" solution. I've done this with CLI tools on a server before and so at least know my way around once I get the ssh connection to the server. Frustrating that "easy" has to be so confusing. I've seen a couple friends try to talk to my bot so I'm anxious to get it up and chatting back asap.

**Link(s) to work**
* https://www.facebook.com/Micro-Academy-Bot-784488255274717


### Day 25: July 29, 2018
**Today's Progress**: Got my chatbot tested and deployed in developer mode on Facebook. It's fun to play with it, but was disappointed to learn that no one else can interact with it.

**Thoughts**
I suppose because it isn't "public" yet, but I don't know that I'm ready to flip that switch - at least not until I have a permanent IP. I'm using this ngrok program to expose my localhost port to the world, but it assigns a new IP each time it restarts.

**Link(s) to work**
* https://www.facebook.com/Micro-Academy-Bot-784488255274717


### Day 24: July 28, 2018
**Today's Progress**: Worked on a Facebook messenger chatbot tutorial until the power went out, might not have been the whole hour I planned.

**Thoughts**
I was so close to "done" but now I have to figure out what I lost with the power outage. Grr. Anyway, planning to do chatbots all week and NLP next week. I'm officially looking for work now too, at least until they decide if I'm eligible for unemployment or not. If I'm not then maybe I'll look for business ideas instead of a JOB.

**Link(s) to work**
* https://github.com/karenfreemansmith/Facebook-Bot


### Day 23: July 27, 2018
**Today's Progress**: Coded along with the @kaggle video by @sirajraval ... some familiar stuff(pandas, sklearn) made the new stuff(xgboost, bagging and boosting) easier to appreciate.

**Thoughts**
Got to watch more of these! I learned a little about some new types of machine learning algorithms and libraries I did not know about. Videos aren't as good as hands on practice, and I'm trying to code along with the video, but they are good to expand your knowledge of what's possible. Now that I'm unemployed I think I may devote an extra hour a day or so to watching more of these videos by Siraj and others on data science and machine learning topics.

**Link(s) to work**
* http://youtu.be/suRd3UzdBeo?a


### Day 22: July 26, 2018
**Today's Progress**: Oh, so much progress today. I got the app RUNNING on a server, in a docker container. Took me all day and it WAS a work project (even though it also was a ML project) so I really shouldn't count today. But you know what, 5 minutes after I got the thing running they fired me. So I'm counting the day anyway.

**Thoughts**
I love building things. I like seeing software that works, and like it even more when it gets deployed and the rest of the world (or company in this case) can see it too. I hate that my obsessive nature and inability to just smile and lie and say everything is good all the time gets me fired. I've really got to quit working for other people I think and find something that people will want that I can build and go into business for myself. I'm kind of out of ideas at the moment though. The reality that I have no job and the paychecks will be stopping soon too is beginning to sink in.

**Link(s) to work**
* private intranet, sorry, cause it works and it's cool...


### Day 21: July 25, 2018
**Today's Progress**: Watched the "Using Docker on AWS" course on PluralSight

**Thoughts**
Best PluralSight author I've watched so far. I feel like his courses and the notes on his website have been super helpful in getting up to speed on docker.

**Link(s) to work**
* [Using Docker on AWS](https://app.pluralsight.com/library/courses/docker-aws-using/table-of-contents) by David Clinton


### Day 20: July 24, 2018
**Today's Progress**: More Docker, some Jenkins. Lots of code review at work. How do you test ML applications?

**Thoughts**
Feeling pretty good today. I installed Docker on a new server at work and I think this may be a way to be seen as a wizard for sure. All this infrastructure is so boring and no one wants to learn how to do it (including me), so when you can just make things work it seems like magic. Hope the magic doesn't run out tomorrow when I try to run our app on the server inside of Docker. Most of my not work time is going to learning the background information about how these programs work and what the best practices are to set them up. Looking forward to getting back to actually writing code soon.

**Link(s) to work**
* None


### Day 19: July 23, 2018
**Today's Progress**: Docker on AWS...looking at more information about building chatbots.

**Thoughts**
Lots of missteps along the way. I need to do this again and write down the steps that were not mistakes so I can repeat it whenever I want. I've also got the card for building a server with Docker to deploy our ML app at work. Not sure how I feel about that. I know it needs to be done, and appreciate the chance to know how to do it, but it also means I won't be coding any actual ML stuff for another week or more. :(

**Link(s) to work**
* None


### Day 17-18: July 20, 2018 - July 22, 2018
**Today's Progress**: Looking into how to deploy Python apps with Flask & Docker. Took all day Saturday, and hours of videos and reading documentation to finally come up with a dockerfile that would run so that I could access it in my browser. Been playing around with GoDaddy server and AWS all day. Still no Docker container deployed anywhere, but I did get a Node.js app up and running on an AWS instance (with the help of a PluralSight course)...and that gave me enough to kind of sorta think I could run the Python code on AWS (without Docker).

**Thoughts**
Not a fan of installing stuff, but there's no point in writing software unless you can deploy it. It's so frustrating when it's not working, but then it does and it's the best feeling of all. Lots of version issues with Linux and CentOS/RedHat. They need to be version 7 to run Docker, but lost of places (both GoDaddy and AWS are still on 6.x). Turns out even getting Python 3 with Centos 6 is a challenge...

**Link(s) to work**
* [Flasky Tutorial](https://github.com/karenfreemansmith/flasky-tutorial)


### Day 16: July 19, 2018 (evening) - July 20, 2018 (morning)
**Today's Progress**: Completed a beta project for DataCamp that focused on image processing. Finished the network analysis course and the Git course

**Thoughts**
This is an interesting way to extend limited sets of image data, you can modify size, color, zoom in on parts of images, rotate them, make them black and white... I can see how these additional images could help train for image recognition applications. Images are fun, but I got distracted by the project and then didn't have enough time to complete the lesson I planned to. Missed work today from being too tired to drive in this morning though, so need to get some sleep tonight. Feeling better this morning, glad I stayed home yesterday as I will probably get twice the work done today now that I'm feeling better (and doubt I would have got anything done yesterday or today if I was still worn out). Feels good to be finishing up these courses too. This weekend I plan to figure out Docker containers and deploy something.

**Link(s) to work**
* [DataCamp Naive Bees Image Processing Project](https://datacamp-karenfreemansmith.notebooks.azure.com/nb/notebooks/3DC_Project_ImageProcessingProject/notebook.ipynb)
* [DataCamp Network Analysis II Notes](https://datacamp-karenfreemansmith.notebooks.azure.com/nb/notebooks/DC23_NetworkAnalysisPython2.ipynb)


### Day 15: July 19, 2018 (morning)
**Today's Progress**: Finished 3rd chapter of DataCamp's Network Analysis II course and started the last one: analyzing graph data for posts in a student forum.

**Thoughts**
The week is getting to me and I'm super tired. I feel like I'm almost on the edge of actually learning something, but can't quite break through. Two more days of work and then a weekend to play some more. I feel like I have some of the missing pieces I needed a week ago to be able to apply graphs to a dataset without a tutorial to help me.

**Link(s) to work**
* [DataCamp Network Analysis II Notes](https://datacamp-karenfreemansmith.notebooks.azure.com/nb/notebooks/DC23_NetworkAnalysisPython2.ipynb)


### Day 14: July 18, 2018
**Today's Progress**: Worked on 3rd chapter of DataCamp's Network Analysis II course...time series graph analysis.

**Thoughts**
It's interesting to think about how graphs change over time and I'm wondering how we might be able to use that to solve our big problem at work.

**Link(s) to work**
* [DataCamp Network Analysis II Notes](https://datacamp-karenfreemansmith.notebooks.azure.com/nb/notebooks/DC23_NetworkAnalysisPython2.ipynb)


### Day 13: July 17, 2018
**Today's Progress**: Finished 2nd chapter of DataCamp's Network Analysis II course.

**Thoughts**
I'm excited that they started (finally) talking about how to get graph information in and out of files today. I think that some of this will help immediately with the data scraping project I have at work. And also the projection stuff will help to reshape some of the data I'm going to be playing with on my side projects.

**Link(s) to work**
* [DataCamp Network Analysis II Notes](https://datacamp-karenfreemansmith.notebooks.azure.com/nb/notebooks/DC23_NetworkAnalysisPython2.ipynb)


### Day 12: July 16, 2018
**Today's Progress**: Made a cool graph for the Titanic data to help speculate about what factors played into the survival rates. Also finished a chapter of DataCamp's 2nd Network Analysis course.

**Thoughts**
I'm a little frustrated about how long I spent playing with that graph (more than an hour...possibly closer to 3 hours, on ONE graph!... and it's still not what I was hoping it would be.) I am hoping to rotate through my 6 projects each week. So today was the easiest, the Titanic data, and I'll be trying to repeat what I did today on the other datasets and see if I can bring that 3 hours to make a graph down to a more reasonable number. I'm also hoping to start integrating some Network Analysis into my explorations soon. It's the most interesting branch of ML for me at the moment.

**Link(s) to work**
* [DataCamp Network Analysis II Notes](https://datacamp-karenfreemansmith.notebooks.azure.com/nb/notebooks/DC23_NetworkAnalysisPython2.ipynb)


### Day 11: July 15, 2018
**Today's Progress**: Working through the ASOIF project on DataCamp - exploring network analysis with the characters from Game of Thrones.

**Thoughts**
I'm disappointed there wasn't something more to the project. I'd like to see more of what network analysis can do, maybe predict who will finally sit the iron throne? (LOL) At the very least, recommend some friends for our book characters or something of that nature. I'll be working more with the dataset to try to do some of those things. The one thing that really ate up my time today was trying to get more variety of colors on the plt.plot() of main characters. The colors cycled through twice, so you can't really tell which characters are the most connected by looking at the graph. That just seems wrong. But trying to find a solution (at least for this type of graph) was fruitless.

**Link(s) to work**
* [ASOIAF Experiments](https://github.com/karenfreemansmith/ML-ASOIAF)


### Day 10: July 14, 2018
**Today's Progress**: First look at the data. Basic pandas stuff: .info(), .description(), .head() and histograms/scattergraphs where possible.

**Thoughts**
I'm disappointed that this initial look didn't reveal any real revelations beyond the shape and size of the data available. Some of my plots look pretty bad, and some of the data needs a lot of scrubbing to make it useful. I'm happy about those results because they mean I have some good practical experience ahead of me in the next few weeks to try to sort out the data and get something useful to use later. I think the data preparation gets ignored a lot because it's not as sexy as fitting a model.  But how hard is it to type in "model.fit()"? It seems that preparing the data is really the tricky part of the process. (I say to myself as I start to panic that there is so much prep work between me and that first model.fit())

**Link(s) to work**
* None


### Day 9: July 13, 2018
**Today's Progress**: Finished my initial data collection process.

**Thoughts**
I have 6 vastly different datasets to work with now. I want to experiment with all the different kinds of analysis and machine learning techniques I've just finished learning. I tried to get a variety of data so that there would be some good/bad fit for various processes because I want to see what happens if I, say, try network analysis to solve the Titanic problem... but also, what can regression or classification do with the ASOIAF network data - anything?

**Link(s) to work**
* None


### Day 8: July 12, 2018
**Today's Progress**: Finding and taking a first look at some more datasets. I'm looking at legos, credit data, school budgets, and characters from ASOIAF. (evening) Completed the Lego project at DataCamp.

**Thoughts**
I'm pretty happy with the variety of the data I've got to start with. I've got large and small, and some sets that are intended for different types of ML. I want to be able to experiment a little with using different models and approaches with different types of data. The legos set is most similar to the problems we are looking at on the job. The job itself continues to be frustrating. I want to write code, but I keep getting directed toward setup tasks and other busy work that often seems irrelevant. Was a little disappointed there wasn't more to the Lego project...I hope to do more with my own Lego project. It was, maybe, a good starting point to help think about the datasets I'll be working with on the side.

**Link(s) to work**
* [Kaggle Credit Analysis](https://www.kaggle.com/c/home-credit-default-risk)
* [DrivenData School Budgets](https://www.drivendata.org/competitions/46/box-plots-for-education-reboot/data/)
* [DataCamp/Rebrickable Legos](https://rebrickable.com/downloads/)
* [DataCamp ASOIAF](https://www.datacamp.com/projects/10)
* [Lego Experiments](https://github.com/karenfreemansmith/ML-legos)


### Day 7: July 11, 2018
**Today's Progress**: Research - Looking at the documentation for Bokeh and trying to troubleshoot my charts in Jupyter. Also looking at some machine learning competitions and picking some datasets to work with.

**Thoughts**
Suffering from mid-week frustration at work and trying to fight it off enough to concentrate on learning activities. I don't want to install a server right now. I think this weekend I'll see what it would take to set up a docker container and figure out how to deploy it online somewhere. At some point we need to be able to do this at work as well, so like it or not, I should try to figure it out. Until then I'm going to look at some datasets from machine learning competitions and try to pick one or two to work on. I want to practice what I've been learning on my own projects. Started notebooks for the Titanic data from Kaggle and the DengAI data from DrivenData.


**Link(s) to work**
* [Titanic data from Kaggle](https://www.kaggle.com/c/titanic/data)
* [DengAI data from DrivenData](https://www.drivendata.org/competitions/44/dengai-predicting-disease-spread/)

### Day 6: July 10, 2018 (before work)
**Today's Progress**: None...  

**Thoughts**
I was trying to get the interactive graph to work locally, in a Jupyter notebook, the graph shows and the default tools "work", but the stuff I write in code just sits there like it's on a smoke break or something. Found a couple of things in the documentation that make me think it's supposed to be possible in a notebook. I'm really just trying to avoid the whole "set up a server" thing. That sounds like more than I can do in an hour, possibly a weekend task...

I'm also thinking all those notes I was taking for the DataCamp course could really be organized better, the files get too long and there is no good way to search for that one code snippet you are thinking of. I might need to transfer the exercises to a blog instead so I can find stuff easier.

**Link(s) to work**
* None


### Day 6: July 9, 2018 (after work)
**Today's Progress**: Finished! Finished the last course for the Data Scientist certificate, finished the interactive graph I was working on this morning...trying to get it to run in a Jupyter Notebook the same as it does in the DataCamp environment, but bedtime...because: work...

**Thoughts**
I'm excited about this interactive graph. I think it will be a killer EDA app for my 'real' projects. I'm trying to decide what comes next still, but whatever it is - this Bokeh stuff is cool and that's how I want to explore the data. Wish it was the weekend so I could have more time to work on it.

**Link(s) to work**
* [Interactive Visualizations with Bokeh Notebook](https://datacamp-karenfreemansmith.notebooks.azure.com/nb/notebooks/DC14_InteractiveDataVisualizationBokeh.ipynb)


### Day 5: July 9, 2018 (before work)
**Today's Progress**: Almost there, one exercise left, but I'm already running late for work so I have to leave it for now.

**Thoughts**
__work !$&^$%)__

**Link(s) to work**
* [Interactive Visualizations with Bokeh Notebook](https://datacamp-karenfreemansmith.notebooks.azure.com/nb/notebooks/DC14_InteractiveDataVisualizationBokeh.ipynb)


### Day 4: July 8, 2018
**Today's Progress**: Finished the DataCamp Deep Learning Network Analysis course and made some more progress on the Interactive Visualization course, should be able to finish it tomorrow and that will wrap up the DataCamp certificate

**Thoughts**
I'm glad to be so close to finished with this online course. I feel like I've learned a lot, but I'm dying to use it on something real. Thinking about possible projects to play around with next.

**Link(s) to work**
* [Newtork Analysis 1 Notebook](https://datacamp-karenfreemansmith.notebooks.azure.com/nb/notebooks/DC22_NetworkAnalysisPython1.ipynb)
* [Interactive Visualizations with Bokeh Notebook](https://datacamp-karenfreemansmith.notebooks.azure.com/nb/notebooks/DC14_InteractiveDataVisualizationBokeh.ipynb)


### Day 3: July 7, 2018
**Today's Progress**: Finished the second half of DataCamp Deep Learning course (Keras lessons), started working on the Network Analysis course.

**Thoughts** Keras makes it all seem so easy. I'm wondering how fast you use up the computer's resources adding tons of extra layers and nodes to the models. I expect to see this in action when I get back to work (at least that's the rumor I heard before vacation.) I'm really interested in the network analysis though as it seems to relate to the problem we are trying to solve better than either regression or classification. I can't help but notice they are handing us datasets that are not the Pandas DataFrames that we've been using with all the other courses - and I'm wondering what goes into preparing the data for Network Analysis.

**Link(s) to work**
* [Deep Learning Notebook](https://datacamp-karenfreemansmith.notebooks.azure.com/nb/notebooks/DC21_DeepLearningPython.ipynb)
* [Newtork Analysis 1 Notebook](https://datacamp-karenfreemansmith.notebooks.azure.com/nb/notebooks/DC22_NetworkAnalysisPython1.ipynb)


### Day 2: July 6, 2018
**Today's Progress**: Finished up the Unsupervised Learning course and started on Deep Learning. Walked through the code for building a simple (2 layers) neural network. Signed up for DrivenData and Kaggle to find some projects to try applying these concepts to. Ended up doing the first section of "Interactive Visualizations with Bokeh" in the evening.

**Thoughts** I feel like I've learned a ton from these DataCamp courses, but it's all so fast and I don't know when or how to apply it to real projects. I'm still trying to figure out if the project at work can be solved with machine learning or not (mainly due to lack of relevant data). I really like playing with the visualizations, but I can't seem to find the .html files it's supposed to be saving. :(

**Link(s) to work**
* [Unsupervised Learning Notebook](https://datacamp-karenfreemansmith.notebooks.azure.com/nb/notebooks/DC20_UnsupervisedLearningPython.ipynb)
* [Deep Learning Notebook](https://datacamp-karenfreemansmith.notebooks.azure.com/nb/notebooks/DC21_DeepLearningPython.ipynb)
* [Interactive Visualizations with Bokeh Notebook](https://datacamp-karenfreemansmith.notebooks.azure.com/nb/notebooks/DC14_InteractiveDataVisualizationBokeh.ipynb)


### Day 1: July 5, 2018
**Today's Progress**: Finally finished up the Statistics courses and got the "Data Analyst" certificate on DataCamp. Started the Unsupervised Learning course learning about KMeans and clustering.

**Thoughts** I can see how the statistics are useful for machine learning. I can remember the mean and standard deviation from a course in college, but the later topics are still confusing. I think I need a good book on statistics that makes it all a little more intuitive so I can figure out where to apply the knowledge.

**Link(s) to work**
* [Statistical Thinking 2 Notebook](https://datacamp-karenfreemansmith.notebooks.azure.com/nb/notebooks/DC16_StatisticalThinkingPython2.ipynb)
* [Unsupervised Learning Notebook](https://datacamp-karenfreemansmith.notebooks.azure.com/nb/notebooks/DC20_UnsupervisedLearningPython.ipynb)
