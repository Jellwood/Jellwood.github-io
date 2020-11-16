_**HW7**: Chapter 5 and 6_  
[5.3](CSCI362 Activity Diagram1.pdf)  
[5.5](CSCI362 Sequence Diagram1.pdf)  
[5.7](CSCI362 Activity Diagram2.pdf)  
[5.8](CSCI362 Sequence Diagram2.pdf)  

_**HW8**: Mythical Man-month Response_  
The Mythical Man-Month provides a potential answer for the 
burning questions surrounding software engineering. How do
managers contend with the potential issues concerning software
development. The first four chapters mention some extremely good
points with regards to how to manage a project that is behind on 
project deadlines and the steps a manager should take to either
rectify the problem or prevent the problem in the first place. In the
response, the author notes a significant problem with the idea of
staffing up in response to a deadline that has passed. In doing so,
the author challenges the idea of a man-month, the idea that a man
can do so much work in a month, and that, in increasing the amount of
man-power on a project, the project can be completed faster. While
this approach works for work that can be done asynchronously, the author
notes that there are problems with this approach in software development.
This echoes the famous saying that too many cooks spoil the broth, 
a mirror to software engineering. If the problem is that one component
does not work, adding ten more people to fix the problem will not solve
the problem because the problem can only be solved by one person.
Adding more people could never solve the problem because in the 
time that it takes to train the new people in the problem, the few people
that were previously solving the problem could have just solved it.
This presents an interesting dilemma, if there is no way to solve the
problem of going over the schedule, then how do managers deal with
the team going over the schedule? In this lies where the book begins
to deviate from an expected claim. The author claims an elite team of
engineers where one engineer is the "lead," and develops the code
mostly independently, where the head engineer is akin to a surgeon, and 
the other members of the team support them. This follows from
the idea that adding more people to a team venture will cause a 
project to slow down, then removing people would speed it up. However, 
this hierarchical structure in which only the more experienced 
engineers construct software and the younger engineers merely observe 
and check over the work. For safety-critical work, this very well may 
be the best option, however, even the author mentions that the 
younger engineers may present much more innovative solutions, which 
would be lost in this hierarchy. Not to mention, an older, more 
experienced programmer does not equate to less mistakes. In fact, an older
programmer is just as prone to mistakes as the younger one, albeit that 
an older programmer may be able to solve the issue quicker, using 
techniques that have worked for them in the past. Does this equate to
the idea that we should just leave the younger programmers behind and 
allow the older programmers to just take over? There are a variety of 
reasons why this is a bad idea, but the best solution is to have 
the older programmers mentor but allow the younger programmers to also
implement their own practices. Given that this was written in 1975, 
distributed version control systems had not been adopted in full, which
exacerbates the problem. In today's world with Git and other such version
control, it becomes much easier to trace where specific problems lay and
who is implementing this. This makes it much easier to solve these types 
of issues. Ultimately, the best solution is to create an ecosystem where
everyone is held accountable for their mistakes and implement ways to 
ensure that everyone knows their parts.  

_**HW9**: Chapter 8 and reflections on testing_  
_8.7_: A scenario that could be used for testing of the wilderness weather 
station system would be that a storm is coming into the area that the 
station is located in. The station goes into power save mode to ensure 
that the station is not without power, and reports the weather.  

_8.10_: The ethics of exhausting the testing budget is an extremely 
risky decision, especially if it is being delivered to an external 
customer. Given that budgeting decisions are rarely made at the software 
engineer level, they are given the budget to make the product. However, 
spending additional money that may not affect the final condition of the 
product is a move that is likely to decrease faith in the company. More 
time testing does not equate to a better product. Because of this, 
it is unethical to spend more money that may not affect the product after.

_Reflections_: Testing is a vital part of software engineering and 
software development. Without testing, programs that are released 
are extremely likely to have errors that would potentially result 
in death or serious injury to others. Without testing, software engineers 
have the potential to destroy society as we know it. Just as engineers 
have to get their plans approved, software engineers have the 
requirement to make sure their software is as strong as they can to ensure 
that they do not hurt people. Without proper testing, software engineers 
cannot create programs with any shred of confidence in their work.

_**HW10**: Chapter 15_  
_15.10_: The reuse of software provides a number of issues legally, 
especially with regards to copyright. The issue with the idea that the 
contractor has a right or no right to reuse the code primarily lays with 
the responsibility of the contractor to determine this conflict. 
Given that the contractor knows and is responsible for their own 
profession, the contractor is responsible to determine who legally 
possess the code, whether it be independently or through a legal 
department with regards to a corporate entity. Given that many 
companies employ an intellectual protection clause, the code is, at the 
very least, the property of the company that the contractor is 
employed at. For a dispute, in the event that the contractor did not 
take precautions to mitigate this issue, the determining factor would have 
to be whether the software was contracted to sell or develop. In the case 
of sale, the customer should retain all legal rights to the software, 
unless stated otherwise.  
As well, the issue with regards to whether the developer has the right 
to reuse the code in a generic capacity relies on who the property 
is attributed to. In the instance where the property is owned by the 
company, provided that the company still employs the developer, it is 
not a breach of intellectual property. As such, the developer is free 
to do so, provided the company allows this.  

_**HW11**: Chapter 9_  
_9.8_:  
The first type of maintenance is "Corrective Maintenance," which 
is maintenance where the developer corrects any faults in the code. This 
results in code repairs to prevent incorrect operation of the program. 
This is generally much more urgent, depending on the type of program 
being maintained. "Adaptive Maintenance" is the process of having the 
program being integrated into the environment better and creating 
a better environment, while also potentially adapting to new requirements. 
"Perfective Maintenance" is perfecting the program and implementing new 
requirements. These are hard to distinguish because primarily, the act of 
doing one type of maintenance usually implies the others. In correcting 
the code, it is very likely you will have to integrate it into the 
environment much better, as well as perfecting it to ensure that further 
maintenance does not become required further on.  

_9.10_:  
Developers do have a professional responsibilty to develop code that can 
be easily maintained, even if there is not an explicit demand to do so. 
This is mostly due to the fact that in professional work, it is 
certain that any developer would likely encounter code that was developed 
by someone else and that developer would be out of straits if they were 
forced to figure out and decipher unintelligible code to then maintain it. 
Regardless of how the publishing of code that is of poor quality reflects 
on the developer, it is also very true that paying forward good quality 
code generally puts other developers in a better case in terms of 
maintaining their code in the future. In creating this ecosystem of 
maintainable code, it becomes possible to create a positive impact on 
the quality of code in the world.  

_**HW12**: Chapter 16_:  
Call-logging component:  
Requires: Phone number (String), Name (String), Date call made (Date), 
Time call made (Time), Description (String), CallID (int)  
Provides: Log Entry (File)  
Methods:  
createFile(String Name, String phoneNumber, DateTime time, String Description)
returnFile(int CallID)  

Vehicle Discovery Component  
Requires: Postal Code (String), Incident Type (String)  
Provides: Vehicle ID (Int), Vehicle Type (String)  
Methods:  
stripPostalCode(String postalCode)  
getListofVehicles(String incidentType)  
calculateClosestVehicle(String vehicleType)  

_**HW13**: Chapter 17_  
One of the biggest risks moving to accessing the services remotely would 
be resources to access these functionalities in the workspace. Provided 
that all of the computers are on the company internet network, as would 
be expected, if there is not enough bandwidth to access these 
functionalities, workers can experience a decrease in performance. The 
best way to mitigate this would be to stress test the network prior to 
switching to make sure that the added stress would not break the 
network.   
Another risk inherent in switching over would be the training in catching 
up employees to the new functionalities. Even if the application and 
services are identical in functionality, the new way of accessing them and 
performing work flow with them may be disrupted, especially if there are 
some employees who use custom automated tools to perform very repetitive 
tasks. These new services may not work well with these tools and 
resistance may be met with switching over. The best way to handle this is 
to perform a training seminar going over some basic functionalities and 
help the employees find more advanced functionalities.  
The third risk inherent in switching is the updating of the service. With 
a desktop application, updating is something that can be done 
automatically from a remote connection with the administrator. A remote 
service, however, is updated by the vendor, and any updates that may be 
needed (especially for bugs that leak information) may take longer to 
repair, whereas a desktop application could be rolled back to an earlier 
version. The best way to mitigate these risks would be to be aware of 
new versions coming out and be prepared to adapt to an environment that 
may change based on vulnerabilities.  

_**HW14**: Chapter 18_  
Currency Converter API  
Input:   
value: double  
inCurrency: String  
outCurrency: String  

Methods:  
getConversionFactor(String, String) -> double  
validateCurrencyType(String) -> bool  
convertValue(double, double) -> double  

Outputs:  
convertedCurrency: double  

Exceptions:  
illegalCurrencyValue: inCurrency is less than or equal to 0  

Credit Checker API  
Inputs:  
SSN: String  
firstName: String  
lastName: String  
dateOfBirth: Date/Time  
creditUnion: String

Methods:  
validateInfo(String, String, String, Date/Time) -> Boolean  
getCreditScore(String) -> int
selectCreditUnion(String)  

Outputs:  
creditScore: int  

Exceptions:  
invalidInfo: User provides invalid information  
unableToValidate: Resources to validate are down  

_**HW15**: Chapter 19_:  
The problem with attempting to ascertain the emergent properties of 
a complex system based on the system components is that many of 
the emergent properties of a system primarily arise based on the 
user of the system itself, not the components that comprise the 
system. Because of that, the software engineers in charge of 
developing the software can only theorize what issues may arise in the 
use and deployment of the software.  

_**HW16**: Chapter 20_  
The ethics behind changing the interface in order to coerce users to pay 
more without notice is a very unethical decision. This is primarily 
because the companies that use the system of systems has entered in an 
agreement that the company providing the system will treat the customers 
in an ethical manner and any price raises will be telegraphed appropriately. 
Because of this, the provider of the system has unfairly and unethically 
treated the customers, and the customers are justified in seeking a new 
provider. The provider's employees likely will not be okay with this 
change, especially if, prior to that, the company had engaged in 
ethical behavior. As for the customers, it is very easy to see that they 
would not be okay with this, especially if the reason for the price hikes 
are extremely opaque or worse, horribly transparent with deception. 
The company's shareholders is a much more contentious issue. At the end of 
the day, shareholders buy stock in companies to gain money, and the 
bottom line is that they may be more interested in a short-term financial 
gain in an unexpected price hike than in a long-term financial gain from 
providing a better service. This is especially true if the service exists 
in a monopolistic environment, where there are not any good alternatives. 
Because of this, the shareholders may see no issue with a price hike.  

_**HW17**: Team Progress 1_  
Overall, the team work is progressing very nicely. The team has adjusted 
to the work dynamic and work is getting done when it needs to get done. 
There is definitely some difficulty with the COVID-19 restrictions that 
presents some issues for meeting, however, online meetings have in some 
ways made meeting during off times much easier. The work division has been 
a little bit harder to determine, seeing as the group members have had 
little experience with bash scripting, however, the group adapted and 
have produced a bash script that works as intended. Given that we have the 
files ready, extending from 5 files to 25 files should be no issue at 
all.

_**HW18**: Chapter 21 and Chapter 22_  
21.4: An object-oriented approach to real-time systems may not be suitable 
because object-oriented approaches use encapsulation, which means that 
multiple components have to interact which takes a significant amount 
of time (relative to the computer time). Real-time systems are evaluated 
on both accuracy and speed, so the slowing down due to data hiding usually 
ends up being a hindrance to ensuring the system is responsive enough.  
22.6: One significant addition to the risk is the outsoourcing to new 
developers and passing tasks to another group. That shift in 
responsibility may end up causing significant issues, especially if the 
contractors perform work that is hard to understand or unable to meet 
the specifications and more optimizations must be made. As well, the 
organization responsible for the contract may go out of business or have 
to reduce staff, which would also cause significant risk.  

_**HW19**: Chapter 23_  
[Schedule Timeline](CSCI362Diagram.pdf)  

_**HW20**: Team Progress II_  
Overall, the work in the team has been progressing along extremely well. 
The division of work is working very well, and the wide variety of skills 
between the team members makes shuffling tasks easier. Repositioning is 
something that has been very easy, especially among the tasks that are 
less intensive in learning. This allows for a significant amount of 
versatility in the team workload. Much more frequent conversation 
has helped in getting everyone on the same page, and scaling to 25 
test cases had no issues with the script itself. There were significant 
issues again with string comparisons, which have been slow going.