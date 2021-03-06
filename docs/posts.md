**Posts**

Welcome to my posts page!

_**HW0**: Introduction_

I am a senior at College of Charleston, pursuing a B.S. in Computer Science
as well as minors in math and Russian studies. I have committed to a job
for after graduation in Columbia! In my free time, I like to play video 
games and watch Hulu. I also work part-time as a math tutor, which eats up 
a lot of time! I have been reading a book currently named _The Madonnas of
Leningrad_, which shows just how much I love Russian culture! I am also
very passionate about cooking and trying to see what new combinations I can
create. My favorite scent is chamomile and mint tea is one of my favorite 
drinks! Overall, I am very much looking forward to this semester and 
finishing up college!  

_**HW1**: Reflections on FOSS_  
The FOSS model works as a ideal of software development where the code and development  
is shared throughout the internet and where everyone is able to see the source code.  
From this, the ideal of solving problems relies on the community at large, as opposed to  
a small group of developers in a company. Prior to Red Hat, this business model had been  
totally untried and untested, which resulted in a large impact when this model was tried  
with Linux distributions. This impact led to attempts to make this model work with  
other projects. The ultimate problem with this is that this model works when the project  
is developed with that intention in mind. Looking at how Linus Torvalds managed to create  
the initial Linux operating system, the creation of Linux utilized quick releases and  
community support to leverage bug fixes quickly and easily. In utilizing the community  
as a resource, Linus was able to generate a significant operating system by, as he put,  
"I'm basically a very lazy person who likes to get credit for things other people actually  
do." From this, we can see that the idea of open source works well when the people in charge  
work to generate a model that works with this idea. Looking at other projects that do not  
fall under this umbrella of open source, it is very easy to see that not all projects work  
for this format. The question, then, posited in "The Cathedral and The Bazaar", is what  
makes this process work and how can this model can be leveraged to make projects work in  
different settings. As it was previously mentioned, the biggest way that open source  
projects are able to maintain user presence is by being active and cultivating a  
community of active users. As it was mentioned in "The Cathedral and The Bazaar," Linus  
Torvalds was able to release more than one kernel a day, implementing fixes and features  
from the user suggestions. This activity made it very clear to the users coding for these  
features that their contributions were valued by the community. Not to mention that these  
fixes and features were of a high quality because these users were committed to the project,  
highlighting how important passion is in this field of work. Open Source Projects rely on  
the knowledge that there will always be developers that develop software to be a part of  
a community and work on software that can positively impact the lives of others. As a  
result, the community thrives off of the activity of others, a fact not lost on many  
projects. A consequence of this action is that a lot of open source projects have a very  
welcoming community that pushes along the development process. The new contributors  
then become a member that will eventually welcome new members in, and they are guaranteed  
to be interested in the project due to the fact that this was entirely voluntary on  
their part. The users will eventually lost interest, but their contribution to the code  
and the community are what will inevitably remain, and their duty, as stated in "The  
Cathedral and The Bazaar," is to find a successor when they inevitably leave. This cycle  
keeps Open Source projects alive and thriving, which guarantees free and open source  
software for the world at large.  

_**HW2**: Reflections on Open Source in Today's World_  
For the readings, I decided to take a different direction and explore options to customize and personalize my 
workstation with regards to the terminal environment. For the entirety of my career in the computer science 
department, I had spent the entirety of my time developing programs as needed and spending as little time 
in my development environment after turning the IDE into dark mode. I never really spent a significant amount of time 
customizing anything past that, nor did I ever feel a reason to do so. Reading both the articles "How I customize 
my Mac terminal with open source tools" and "Drop bash for fish shell to get beautiful defaults," I determined that 
perhaps I had not spent enough time developing my environment to get the most out of my time using the terminal. 
Within a day of reading through the article championing FISh, I installed and looked around the features of FISh. 
For one, the automatic complete based on history started working instantly, using my BASh history to determine 
what commands I use the most often and even displaying a ghost of what the command should be. On top of this, any command 
that was not valid is highlighted in red, changing to blue when a valid command is typed. The first thing that I tried 
to do was to change to another directory and tabbing to autocomplete with multiple valid results, it displays all 
possible commands. Of course, any quick search can talk about the features of FISh, this is to talk about what 
these articles have to show about terminal customization and the bevy of features that can be customized. I had no 
idea that the terminal could be customized to the extent that it could be. Within a few minutes of looking around, 
FISh showed a significant amount of improvements to the BASh terminal that I had been accustomed to. This shift 
opened my eyes to just how much I could change about my environment. Screenshots from the first article showed a 
terminal that displayed the working directory and the branch of the git repository that the user was in, while 
each of these displays had different colored backdrops for ease of view. As I type this blog post, the terminal, 
now in FISh, displays master in parentheses, so I never forget which branch I am currently in. These little things 
have accumulated into a mass of options to make my life easier. This is definitely just the beginning, as there is an 
entire application to control the appearance of this terminal. Other options that were shown were zsh, which will 
also be another consideration. On top of this, I can guarantee that my default shell will not be BASh by the end of 
this semester.  

__This Bugs Me__: The oldest bug is actually testing and documentation fixes for a specific portion of the Feedback functionality of Teammates. My leading theory as to why 
this has not been resolved yet is two-fold: firstly, the project is designed for students in a class such as this, to where it is a revolving door
of contributors, in addition to the fact that documentation is usually pretty low on the list for what most developers want to do. This bug leads back to
2014.
I already have an account on the bug tracking website used to track the bugs and issues for the Teammates project, as it is utilizing Github to track 
active bugs as well as version control. 
Looking at the bug that I had identified as a problem to work on, I am having trouble getting the bug to reproduce, however, some more work 
will easily reproduce it.
Bug triage is a little bit of an issue at the current time as the development environment that I am working on is having some issues with properly
tracking instructors being added to the development server. As a result, the ability to fix bugs in the environment is being tested.
The biggest issue currently facing the fix of relevant bugs is getting the development environment restarted and getting instructors added to the program.
Once that issue is resolved, work should progress significantly faster. This weekend will be a huge resource towards getting things working as intended. The front end and back end are 
currently working together as far as things seem. There is a potential case to be made that 
this is a fix for the issue is ensuring that the front end and back end are working together 
properly. This restarting of this setup should hopefully result in a fix. In the case that 
this does not work, the next step will be public outreach. The bug in question would 
be the issue that a button will say "Save questions" regardless of how many questions are 
actually entered. Because of this, it is important that the front end and back end are 
cooperating, as questions can only be entered by instructors, not admins. Further testing 
will be done to ensure this parity between the two and make sure both sides are communicating.
Similarly, the breadth of bugs does not span just this issue, honestly, documentation fixes 
are looking more and more appealing to work on, as the project is documented fairly well, but 
the issues tracker mentions more and more testing should be done. As testing is a very 
difficult skill to maintain, the use of this opportunity to develop this skill may be useful.
As well, the front-end, built in HTML and Angular, is another great opportunity to hone 
more skills, as front end development is a skill that, as a computer science major, I had 
had no event to work on.  

__What's Happening?__  
For the article that I read through the IEEE Software journal, I read an article 
discussing the issues and problems facing the peer-review process in the Software 
Engineering field, and looking at the potential fixes for these issues. The editor 
in chief mentions that a large part of the issue stems from the fact that either 
reviewers are too busy to perform a high-quality review of the paper or that the metric 
that judges how productive the scientific society is is flawed in some fashion. 
Intrigued by this, the first thing I did after reading this article was to figure out 
how the process works for the other sciences primarily. The first article I found was 
an article about how the peer-review process for biological sciences is on the verge 
of destruction from 2016. This was a result of fear that many researchers turning down 
papers meant that the ones that were reviewing were actually providing high-quality 
reviews, as well as a concern that the number of papers to be reviewed was reaching 
a critical point, where reviewers would not be able to keep up. It is interesting that 
these problems in other fields mirror the Software Engineering problems to the extent 
that they do. However, I believe that there is a significant difference in computer 
science from some other sciences, particularly those like biology and environmental 
sciences. For example, in a quick search, I found a journal talking about synthetic 
biology, a field focused on both turning unnatural chemistry into natural chemistry and 
vice versa. One point of interest primarily is the ability to study Darwinian evolution 
in an unnatural system. While this is focused on the changes over time, it does show a 
very important point, the researcher has to observe changes, but in the time that it 
takes for these changes to happen, it is possible to review papers, especially if the 
changes occur over multiple days or even weeks. As a comparison, I would like to bring 
in my own experiences performing researching for the College this summer. When 
researching, there was very little "down-time". In addition, my advisor would 
consistently highlight other papers for me to read as well, in addition to the other 
students who were also working with him during the summer. This highlights a very 
large problem: Provided that the reviewers are doing similar activities, when do the 
reviewers place their review duties over their own research? As a result, I believe the 
best course of action is to re-determine what success is in the Software Engineering 
research community. A robust community of reviewers that may be smaller, yet provide 
high-quality review may hurt in the short-term. Given the diverse nature of any 
scientific field, including Computer Science, there will be gaps in the reviewers' 
knowledge if the review community decides to shrink its' numbers. However, to say 
that having this community will inevitably attract many more reviewers is a very likely 
claim. Those who are passionate about research and can see that the community revolves 
around making sure that reviews are accurate, helpful and high-quality will ultimately 
recover the initial losses. I believe this is just a symptom of Computer Science still 
being a relatively younger field of science and attempting to catch up to much more 
older and more robust fields. As such, I believe a redefinition of success is much 
more viable to protect the life and soul of Computer Science research.  

__Stupid or Solid?__  
S.O.L.I.D code, an acronym for the principles that should be used in developing code, 
is an interesting idea of how to easily remember these good coding principles. 
For the S, the Single Responsibility Principle, is a principle that states that each 
class should have one responsibility and do only one thing. This principle is 
something that ultimately is understated in a lot of early programming classes which 
leads to a very difficult learning curve for programmers looking to enhance their 
skills, at least in my experience. What makes this principle remarkably difficult 
to work with? First, a process of learning programming that focuses on learning THEN 
optimizing and improving is ultimately very detrimental to developing these skills. 
A relevant analogy would be teaching a doctor in medical school a specific way to 
perform an operation, then in their residency telling them a better way to do that 
same operation. The Single Responsibility Principle is without a doubt, one of the most 
important principles of S.O.L.I.D code.  
The O, the Open/Closed Principle, is a principle that focuses more on the privacy of 
attributes in a class. The idea behind it is that the class should be open to extension 
by interfaces and inheritance, but closed to modification, that every attribute should 
be private but allow access by getters and setters, where you can do more robust 
checking. The biggest reason this is an issue that is not taught very soon is that 
it seems a lot of early classes focus primarily on "Good-Faith Actors," any user that 
would not attempt to abuse any vulnerability for whatever gain they might procure. For 
a first level computer science class, where students may not have the skillset to 
properly verify inputs, this is okay, but at some point, this principle should be 
taught very early on, again, as "bad-faith actors" are innumerable, and developing 
software commercially opens the door to these actors exploiting vulnerabilities, 
something that this principle aims to dissuade.  
The Liskov Substitution Principle is a principle that states any use of a subclass 
should be able to work as a superclass use without breaking the program. This process 
works inheritance in a very interesting way, namely using the analogy of that a square 
is a rectangle but a rectangle is not always a square. Because of this, we can see that 
the Liskov Substitution Principle does not hold in this case, and in order to inherit 
correctly, they should not have this relationship, and whatever superclass they have 
should use be able to be used interchangeably. This alone is a very good view of 
inheritance that is a really easy way to understand it without obfuscating details of 
it.  
The I, Interface Segregation Principle, is a principle that focuses on the 
responsibilities of interfaces and how they work respectively with regards to classes 
that inherit from them. The idea behind it is that inheriting from multiple interfaces 
is better than just one overarching interface, and that makes the code more reusable. 
This aims to make the interfaces used more generalized and make it such that the 
interface is not specific to one use case. This achieves the ability to use the 
interface in multiple cases, and even be reised throughout the project. The biggest 
issue with this comes in the balancing act between this principle and the Single 
Responsibility Principle.  
The D, Dependency Inversion Principle, focuses again on interfaces and how the classes 
that implement them should behave. From a common sense standpoint, this is easily the 
most apparent principle, interfaces should be abstracted to the point of interfaces 
and concrete classes should be abstracted to the concrete level. Any interface can 
depend on another interface but using a concrete class in an interface greatly limits 
the amount of use cases for an interface. Because of this, interfaces should stay 
abstracted at the interface level.  
Ultimately, these principles are extremely important and makes a lot of sense to be 
teaching early on. Each of these principles creates a world where you are writing 
extremely robust and reusable code. From my perspective, that is the difference between 
a programmer and a software engineer, how much work is being put into writing 
code of a signficant quality.  

__Release Early and Often__  
When a software project is being developed for commercial use, the big name in the 
industry is "Agile," the principle that the client should be as involved with the 
product development as much as possible and that their feedback makes the development 
extremely easy to work with. The biggest ideal with this lies in the fact that this 
feedback is more and more pertinent the closer the development is to the session. This 
lies in the "Release Early and Release Often" ideal. The more involved a client is in 
the development, the happier the client will be at the end of the project, usually. With 
open source projects, this is the same ideal, except at a much larger scale. The only 
difference is that the client is the same community that is helping develop these 
projects. This comes with its own series of problems, namely that the client and the 
community are extremely spread out geographically and temporally. The thing that makes 
this particularly effective is the use of documentation in explaining what the code 
actually does. In any development team, there is actually a guarantee that each 
developer will be in some way different in thought process from another one on the team. 
Documentation is a way that these thought processes can be reconciled and that a project 
can be built. From a personal experience, this is extremely relevant to me, as I am not 
amazing at the documentation side, as my variable names and comments tend to leave room 
for improvement, something that I have been striving to fix. Looking through the open 
source project that I have been working on, TEAMMATES, I have found really extensive 
documentation which has helped a lot in getting me and my teammates acclimated to the 
project, especially since the project is so mature and has stuck around for quite some 
time. Obviously, there is no guarantee that the way done already is the right way or 
that there is no better way to achieve something, but the main aspect of being part of a 
team is figuring out those ways together, something that has been a very effective tool 
in determining difficult problems and finding the most effective way to deliver a 
functional product. This has really been a great exercise that the documentation has 
helped on and made the project much easier to work with. 
