**Posts**

Welcome to my posts page!

_**HW0**: Introduction_

I am a senior at College of Charleston, pursuing a B.S. in Computer Science
as well as minors in math and Russian studies. I intend to go into software
engineering post-graduation, however, cybersecurity and infosec are also
two of my passions as well! I also enjoy gaming in my free time in addition
to playing D&D.

_**HW1**: Chapter 1_

1.3: The four essential attributes of professional software are Acceptability, Dependability, Efficiency and Maintainability. In addition, some other attributes  that are important to professional software is Scalability, Readability, Completeness, and Portability.

Scalability is important so that a solution to a problem can terminate correctly when the program experiences a problem of larger and larger sizes. Readability is important, so that any future developers can expand and reuse the code without having to decipher extensively. Completeness refers to the ability of the code to experience different types of the problem it was designed to solve without crashing or terminating incorrectly, while portability refers to the ability to move the software to multiple types of machines without sacrificing functionality.

1.8: Professional software engineers should be licensed in the same way as doctors and lawyers. The reasoning for this is that software engineers have a moral obligation to the society in which they develop software to work on projects that bring a moral good to the world. As such, a sort of license would serve as a sort of safeguard to ensure that professionals are upholding their obligation to society.

1.9: Each of the clauses of the ACM Code of Ethics will be exemplified below!

_Public:_ A software engineering firm is asked to develop software to be used in a voting machine. However, the specifications allow for an independent actor to change the vote of any vote cast with no authentication allowed. Given that voter suppression and voting fraud is inconsistent with the public interest, the firm refuses the contract and does not develop the software.

_Client and Employer:_ A software engineer works for a firm that is developing software for a hospital to track doses of medication throughout the hospital and update the hospital inventory as it does this. The software is close to release, however, there is a bug where the inventory occasionally underflows and actually shows more medicine than is available. The software engineer then acts in the best interest of the client and employer by asking for extra time to ensure that this bug gets resolved and the underflow is eliminated.

_Product:_ A software engineering firm gets a request to make a program that is capable of sorting large amounts of data that is getting inputted from multiple sources, while also displaying statistics on the dashboard as new data comes in. The team weighs multiple sorting algorithms to determine which sort would be most effective, while not sacrificing space or performance.

_Judgement:_ A team of software engineers decide to use a component that has had previous security vulnerabilities, although their previous uses has never had a breach. However, one software engineer objects and notes the security vulnerabilites and finds an alternative that does not have those vulnerabilities for the final product.

_Management:_ A manager of a software engineering team has been asking for a deadline extension on an important product, and their managers have been denying the extension. The deadline is in a week and multiple test cases are still failing, despite every engineer working around the clock on the issue. The manager elects to tell the upper management instead of lying on the test case outcomes.

_Profession:_ After releasing new software, users have been reporting an outcome that is unexpectedly crashing in some cases. The software engineering team that primarily worked on the program looks back through all of the reports and within a day, is able to push out a patch to users that fixes the issue.

_Colleagues:_ A newer software engineer joins the team and starts pitching ideas in a scrum meeting to determine the tasks and delegate each person's jobs for the day. The software engineers who have been working on the project for a significant period of time welcome the new perspective and listen attentively, which leads to a successful product.

_Self:_ A software engineer has been employed at a firm for 10 years. In 8 of those years, she has attended ACM conferences to watch presentations of research in the software engineering field.

1.10: The ethical implications of working on a system to track citizens of a country and their actions as they relate to the ACM Code of Ethics are as follows. First, the public interest is both supported and subverted by the development of this type of software. Naturally, the public interest would be served by preventing or at the least, curtailing, terrorism attacks in a country. However, the public interest is also subverted by privacy disruptions. One organization that is able to collect data on every citizen will be vulnerable to cyber attacks, and that data could be released to cause significant harm to those affected by the leaks, including citizens getting stalked, doxxed or even murdered. The ethical ramifications of being a part of this development could result in a significant boost in hate crimes in addition to the complete destruction of privacy. 

_**HW2**: Reflections on software engineering practices_

Some of the most severe issues facing software engineers and software engineering
as a discipline are problems that regard the primary nature of software
development as obstacles. The issues facing this comes from the fact that
software engineering as a whole is a fairly new profession, really only
catching on in the 1950s and 1960s. Giving a liberal estimate, there has
really only been 70 years to formalize the ideas that provide productivity
boosts as well as make software engineers and developers have less trouble
doing their job and doing it well. In addition to this, in the beginning,
the cost of hardware far exceeded the cost of software. This trend has reversed
immensely with software being much more expensive to develop in comparison to
hardware. As the problems changed, the formalisms that dictated the values of
preserving hardware had to shift to focus on how to develop software efficiently.
Another difficulty is the localization of software engineering and how
different companies approach the issues that face their enterprise. In Google's
first iteration of their code base, there was one repository of code that every
developer took from. Surprisingly, however, even today, they still work from a
central repository. In fact, instead of migrating to Git or a version control
system, they maintain the central repository and have developed tools to
work with the fact that they do not have separate repositories for each team
or each department. However, any other enterprise that attempts that approach
will likely result in disaster. Why then, does it work for Google. The difference,
I believe, lies in the people that work for the enterprise. Just as the famous
No Silver Bullet article mentions, there is no "one way" to develop software.
As a society, we can define processes and products that may help, but just as
some programmers prefer Vim to VSCode or any other text editor, a one-size-fits-all
approach may be impossible, in fact, there may not be one solution. How, then, do
we quantify usefulness of practices of programming and developing software? Turning
attention to online help columns reminiscient of the days of Dear Abby, there may
not be a solution that results in universally useful information. For example,
using the scientific method as a backbone for coding and developing software is
generally a good idea. It focuses the idea behind the implementation and helps
to eliminate ideas that already failed. It also serves as documentation for the
thought process that led to the solution in addition to possibly discovering
potential test cases. However, take the Google code base again. Commits to the 
repository are done pending a pass from the code directory owners, much like a 
merge request in Git. The difference relates to the nature of the code repository.
Instead of a merge request, all work is done on the cloud, where each developer
can see each other's work in real-time, and utilizes auto-commit options to 
allow for concurrent work across the globe. However, needing to utilize the 
scientific method in every "merge" case, would likely eat up more time than would
save from the code review having documentation. An enterprise running version
control on Git, on the other hand, could benefit greatly from a requirement to
use and document the scientfic method in development. Ultimately, the only
thing that can truly be defined as a "silver bullet" can only be a silver bullet
for the beasts we face in our own environment.


_**HW3**: Chapters 11 & 12_

11.4: The one thing in common that all architectures that are designed
to support software fault tolerance is that they are all geared at
redundancy with regards to operation. Any architecture that provides fault
tolerance has the ability to run the operation multiple times
and then compare the different answers to determine whether there had been any
failure at any part of the calculations. As well, some systems also have backups
so that in the event of a failure of the primary system, the secondary system
can perform the calculations necessary to aborting the program without loss of life.

11.7: N-version programming for controlling a radiation therapy machine is
arguably a very bad idea. The problem inherent in using N-version programming as
a control system. First, the idea of using N-version programming would require
much more development teams and the cost of development would go up 
disproportionately. While radiation therapy software is extremely safety-critical,
self-monitoring architecture would provide much more robust protection. In
addition, it is far more important that a radiation therapy machine is
reliable, and works under the assurance that the program is correct, as opposed
to available. Availability is far less important in terms of the operation
of radiation therapy, because radiation therapy issues can lead to serious
injury or death.

11.9: A program that requires a large amount of availability should have robust
exception handling because exceptions allow for the program to avoid error
conditions that would otherwise crash the program. Having an excess of these
inputs that cause crashing ultimately undermines the goal of availability
and without those exceptions, attackers could leverage these values to
bring down services, antithetical to availability.

12.4: Five functional requirements that would be generated from the safety
requirements would be that (1) the program will be able to determine the 
track segment light and ensure the signal is red, (2) the program must be able
to accurately determine the speed that the train is moving, (3) the program
must be able to determine the speed limit that a track has, (4) the program must
be able to ensure that the comparisons between the speed and the speed limit
are accurate, and (5) the program must be able to employ the brakes quickly
and effectively without causing harm to the train or the passengers inside.

_**HW4**: Reflections on software failures_

All forms of engineering have respective standards and provisions that
determine what actions should be taken to ensure that the final product
is correct and will work in practice. An architect has building blueprints
that are verified independently, a chemical engineer has run the calculations
to ensure that the product is correct, and so on. However, there is a
glaring inconsistency with regards to software engineering due to a significant
difference in disciplines. An architect has the responsibility of designing
a building such that the building is stable and aesthetically pleasing, while
a chemical engineer has to create compounds based on the requirements given.
In a stark contrast, software engineers are required to know about multiple
programming languages, security concerns, potential failures of software,
potential failures of hardware, potential points of weakness in both security
and efficiency, and the list continues. There is clearly much more aspects that
a software engineer is required to maintain and define, which presents a
severe problem to software engineers in general. In addition, a group of
software engineers may have different expertises and experiences that
influence where their concentrations lay. Therefore, it is extremely unlikely
that one single software engineer will have all of the proficiencies to
determine problems in the program and develop code to fix those problems.  
On the other hand of that, too many developers may end up hurting efficiency,
even if they all have different proficiencies and some joined mid-project.
Naturally, it is very hard to determine the exact needs of a project,
especially if the project manager is unable to negotiate for appropriate
deadlines and budgets. That also presents a new problem: the culture of the
company that the software engineers work at. A company that has a long-standing
culture of producing products from a physical standpoint may have significant
trouble accommodating a new software engineering department in the company.
This may cause issues for any contracts that the company may take on, especially
early in the lifecycle of the department if there was not sufficient research
done to be knowledgeable in the needs of the department. This shift in software
development may ultimately cause millions of dollars in losses for the 
company. Conversely, a company that had either done research or formed
specifically as a software engineering firm would likely have a much
more understanding culture with regards to the needs of the department. while
this does not guarantee success, these factors will likely create projects
that will finish within the deadlines and budgets.  
In its entirety, software engineering is a discipline of many different aspects.
There is no one software engineer who can successfully and efficiently manage
all of these aspects of a software development project. As such, collaboration
is a necessary part of software engineering, and provided a healthy environment
in addition to a diverse team of different backgrounds and abilities, a firm
should be able to deliver their own successful projects and avoid significant
failures that may result in loss of money, life, or property.  

_**HW5**: Chapter 4 and Reflections_

4.5  
The gas pump shall read the card that is swiped.  
The gas pump shall transmit the necessary information in a secure manner.  
The gas pump shall dispense the correct amount of gas.  
The gas pump shall debit the correct amount to the user's account.  
The gas pump shall verify that the card is valid before pumping gas.  
The gas pump shall output receipts.  

The ATM shall verify that there is enough money in the account before dispensing any money.  
The ATM shall verify that there is enough money in the ATM before dispensing money.  
The ATM shall not dispense any money that is not available for the user.  
The ATM shall be able to process withdrawals and deposits of all types.  
The ATM should be able to perform efficiently.  
The ATM shall be able to output receipts.  

The facility shall verify that both accounts are valid before transfer.  
The facility shall verify that the account that is transferring money has enough money.  
The facility shall make sure that the transaction goes through in full or is cancelled.  
The facility should make funds available as quickly as possible.  
The facility shall keep a log of all transactions made on any given day.  
The facility shall be able to retrieve past logs.  

4.6  
A good way that an engineer may keep track of the relationships between
functional and non-functional requirements effectively would be to create
a tree graph with functional requirements being the roots of the trees
while leaves connect to pertinent functional requirements from non-functional
requirements. Leaves can connect in a many-to-one fashions.  

4.7  
A user approaches the ATM and inserts their bank card. The ATM reads the card 
and the ATM asks what functionality the user wants. The user selects "Deposit" 
and the ATM prompts the user for the money or check that the user wants to 
deposit along with the amount the user wishes to deposit. Upon putting the money 
in the ATM, the ATM checks that the amount inserted and inputted are the same 
amount. If the amounts match up, the money is credited to the account. In the 
case that they are not, the ATM displays a message and the transaction is voided.

A user approaches the ATM and inserts their bank card. The ATM reads the card and
the ATM asks what functionality the user wants. The user selects "Withdrawal" and
the ATM displays the accounts eligible for withdrawal. The user selects which 
account the user wishes to withdraw from and then asks for the amount to withdraw. 
In the case where there is enough money, the ATM dispenses the correct amount 
and the account is debited the amount. In the case where there is not enough 
money, the ATM displays a message and the transaction is voided.  

Reflections:
The articles in their entirety reflect the somber truth of software engineering and 
computer science. Ultimately, the profession is driven by humans 
and software engineering is a profession that draws in some of 
the most intelligent and innovative individuals that exist in the world. 
With that brilliance comes hubris, and a remarkable amount of work goes into 
figuring out how to ensure that the productivity of software engineers do not get
overshadowed by their own personality. As such, procedures like Test Driven 
Development are implemented to ensure that the code being created does not get 
backed up by adding features that are unfeasible to test or too imposing. The 
reason this exists is that many engineers do not take into account the factors that 
affect the security and performance of the program. For example, in the case of the 
tire pressure gauge sensor, it is very difficult to determine the case where 
an attacker is able to spoof a signal from a sensor, where researchers could 
replicate this attack cheaply. This does not get helped by the extreme range in 
time that laws can be passed to ensure security and safety. For example, take the 
research paper that exploited Tire Pressure Gauge Sensors in 2010. Now, the law 
specifically outlining what must be protected by the United States Government was 
not brought forth until 2015. There is absolutely no way that a government is 
able to push forth laws that will keep up with cybersecurity requirements and as 
such, the software engineer must be aware of these potential breaches and 
determine what data must be protected. Society will continue integrating systems 
and software engineers must be able to create tests to secure programs for the 
good of society.

_**HW6**: Chapter 2_

Ex. 2.1:

In order to develop a system to control antilock braking in a car, a waterfall
approach would be the best software development process. The reasons for this is
that there was a veritable amount of safety requirements and regulations that
the software must pass in order to be integrated. As well, the waterfall
method requires a significant amount of documentation to support the development
process. As a result, in the case of failure, the company can hold those
accountable for any failures.

In order to develop a virtual reality system to support software maintenance, 
the integrate and configure approach would be the best process to develop 
the software. As virtual reality software is being developed en force these days,
it would not be unfeasible to find software that could potentially support
this endeavor.

In order to develop a university accounting system that replaces an existing system, the waterfall method would also be advantageous for this approach.
Given that there is already an existing system, it is likely that the
specifications are well-known and understood. As well, there is a large base
of knowledge that the software engineers can build on.

In order to develop an interactive travel planning system that helps users 
plan journeys with the lowest environmental impact, the incremental development
approach would work best. As the sources for lowest environmental impact shifts,
it may be a great way to ensure that the client is satisfied with the ability
to determine the lowest environmental impact. As well, it would not be infeasible
to produce a working prototype that is ready for production that may not
optimally determine the lowest environmental impact but may suggest trips that
are close to optimal.
