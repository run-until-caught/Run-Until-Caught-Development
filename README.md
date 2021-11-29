# Run Until Caught Development Manifesto
```Run Until Caught Development is a set of principles for moving faster than large company process normally would allow through strategic positioning of your work relative to burdensome internal processes.```

#### History of the Term
"Run until caught" is a throw away phrase often used in jest. It is a way to refer to people who want to get things done, or at least further along, than is typical given the process rich environment they work within and are willing and capable of safely bending the rules a little. Here we attempt to write down what might be included in a formal defintion of "Run Until Caught" development.

#### Run Until Caught Development Users
Run Until Caught Development is more likely to be found in large organizations where processes over time proliferate, increase in complexity, get modified in the direction of the worst case scenario, and expand scope in terms of what should go through them. Why this occurs has been written about extensively elsewhere. No matter the forcing factors, the end result tends to be a high process burden on what can be developed and how it can be developed.

Users of the <i>"Run Until Caught"</i> development methodologies described in this document are often those passionate and motivated to solve problems. They often want to get things done at a faster pace than would occur if every process that might possibly apply was followed as fully as possible and as early as possible in the software development process.

When should you use Run Until Caught Developement? That's up to you, the reader. However, the authors recommend your actions should ideally always be moral, legal, and not get you fired or otherwise in trouble. Run Until Caught isn't about being a hacker or a pirate, not that there is anything wrong with being a hacker or a pirate. It is about smartly navigating the ecosystem of proccesses you find yourself potentially faced with in order to maximize your productivity and impact.

----------------------

## Other Development Philosophies
'Run Until Caught' is a type of development, similar to how <a href="https://en.wikipedia.org/wiki/Waterfall_model">waterfall</a>, <a href="https://agilemanifesto.org/">agile</a>, <a href="https://en.wikipedia.org/wiki/Extreme_programming">Extreme Programming</a> and <a href="https://en.wikipedia.org/wiki/Lean_software_development">lean</a> are approaches to developing products, services, software, etc.

Like these other methods of development, 'Run Under Caught' is based on a series of principles. The principles can be formed into patterns. If not careful, the patterns can be formed into stringent processes that then go against the principles.

----------------------

## Principles of 'Run Until Caught'
There are five higher-order concepts within Run Until Caught development. 

The first 4 concepts are part of the "run" part of "run until caught" development.
- Believable Ignorance
- Creatively Leverage Definitions
- Defer Until Tomorrow
- Piggyback Rides

The 5th concept is all about the "caught" part of "run until caught" development.
- Have a Plan for Being Caught

## Believable Ignorances
In large organizations processes proliferate. It can be hard to know what processes exist and what situations don't have a process. They can be documented in highly varied locations. Even if there is a central place for most or some processes to be documented, there might be 3, 4, or 10 processes documented in that central repository out of 100s of policies that apply to your situation. It can be difficult to know you've understood all the processes that might apply without closely reading hundreds of them. These common situations lead to believable process ignorances.

#### Did Not Know
There are times where you can honestly say you didn't know a policy. 
- The policy is written up inside the service you're trying to get access to. 
- The policy can only be seen by admins and they can't tell who else can not see the policy. 
- The policy is written a document that has sense moved and so links to it don't work anymore. 
- The policy was decided verbally in a meeting that did not include you and there is no easily discoverable written record of it. 
- etc.

#### Did Not Look Very Hard
There are also situations where you can decide ignorance is better than enlightenment. If the policy is not in an intuitive location or lost in a pile of hundreds of other policies in a central registry, you can decide you have "looked hard enough for now" or "looked a reasonable amount".

#### Partially Known
This is related to the two scenarios above, there are circumstances where it can be a good call to put in a reasonable amount of effort, become partial informed on relevant policies,and then stop under the logic that if there was more policies a reasonable person would assume they would have been in the same place as the other policies. 

## Creatively Leverage Definitions
Processes are usually built around definitions for the types of projects, workflows, situations or people that either trigger a process or need to be put through a process. Because you have control over your work, your project, and how it is described, you can influence what processes you have to complete.

#### The Jedi Mind Trick
<i>"This is not the new IT system you're looking for".</i>

The Jedi method is a refence to <a href="https://youtu.be/CnjaUoR15dU">this scene in Star Wars: A New Hope</a>.

Sometimes you can avoid a lot of process slowdowns by simply being smart about what label you put on your project. What rules apply are often based on labels. You, to some extend, are often the person who assigns the label that then determines what processes your project project calls under. This isn't always true. Sometimes there isn't a lot of flexibility. However when their is flexibility or when the boundaries between labels get very blury, it can be something to leverage. Maybe your project is eventually going in production but isn't quite there yet? Can you still call it development?

#### Choose Your Own Process Adventure
Closely related to The Jedi Mind Trick is the choose your own adventure method. Similarly, you're making an active choice to avoid the worst processes, but here you actually decide what to build or how to build it specifically to pick your process path.

One example is you might rewrite your code into 200 lines of bash to avoid having to ask for permission to install a specific Python library that lets you do the same task in 2 lines of Python. Sure, it might take 2 hours more to to code, but it could save you 1 month in finding the right people to give you permissions, asking them, waiting for the once a month of quarter meeting on such things, a system administrator install that python library, you not having access to run python code yet on the server, etc. etc. Maybe you finally get those two lines of Python to run 7 weeks later when you could have just rewritten it in bash and got it done that day.

#### "Rules, Where we're going, we don't yet have rules"
Section header above is a poorly executed reference to a Doc Brown quote in <a href="https://m.youtube.com/watch?v=pDX997uKTGg&pp=QAFIAQ%3D%3D">"Back to the Future"</a> movie.

In situations where process you don't want to deal with has lots of words to describe when it should be applied, you can choose to make the case that the rules do not apply. A more appealing way to phrase this might be that the "rules are not yet written" for your particular case. This is likely only the case when the definitions for when the process needs to be applied are written very narrowly in the first place. Sometimes, there can be 4 approved ways to do something for 4 different narrow situations. If you need to do something else that alls outside those 4 defined scenarios, maybe the rules haven't yet been written for your fifth scenario? Maybe you could figure things out for your situation and help suggest a process later for your new situation if asked?

## Defer Until Tomorrow
Guidelines for whether a process needs to be followed sometimes have very clear timelines associated with them. Other times they don't. Careful reading of these details can provide flexibility in when a process is started. Other times there is strict guidelines when a process should be started but not when it needs to be finished by.

Deferring process can give you time to fit in a few more iterations that help you decide whether to push forward or kill the project entirely.

Sometimes deferring a process until another one can be undertaken at the same time, or a specific party can be involved, can reduce the total process burden for all parties involed. Perhaps a key approver is only available on the same day but willing to approve two things at once? Aligning multiple processes such that they are tied together can be risky, but it can also increase assurances that meetings are not continuously postoned.


#### Non-Production Working Prototypes
Often processes are built around worst case scenarios. What's the worst that can happen with real data, real servers, real customers, real liability. Describing or otherwise keeping your project as a lab project, prototype, test, development, experiment, or some other category can be an escape hatch that excuses it from burdensome process until a later point in time. This often lets you get through more interations, failures, and learning cycles 'process time' needs to be included in to the development time & cost arithmetic. Sometimes entire teams can be labled labs, be banned from deploying anything into production, and thereby move faster than anyone else.

## Piggyback Rides
Piggybacking on established IT systems can be one of the fastest and most effective ways to get through process.

##### Existing IT Systems
If you can deploy your project on another IT system that already exists, has gone through months of process, and has a clear authority to operate, it could be a huge process savings.

##### More Birds Less Stones
Additionally, if you can join forces with multiple closely related projects and get processes done as a class, it can be a force multiplier with huge cost and time savings.

## Have a Plan for Being Caught
#### Types of Being Caught & Types of Responding to Being Caught
If you're going to move quickly and creatively within the process landscape, eventually you're going to get "caught". What caught means and how you respond to it, is worth thinking about in order to minimize negative impact to you, your career, the team, the project, your organization, etc.

### Types of Being "Caught"
We can think about the "caught" in terms of a combinaion of when it occurs, who or what is impacted, and the extent to which being "caught" is a dangerous thing.

#### Timing
- early
- mid development
- near end of development
- post project
- never caught

#### Impacts Who
- you
- team & others
- project
- organization

#### Danger Level
- never caught
- friendly caught
- soft caught
- hard caught
- in trouble caught

Not being caught can sometimes be a form of technical debt in the sense that there's always the change you'll be forced to take X amount of time to redo some proess step. Getting "caught" towards the end of a project at a more serious danger level can mean project abondonment or an extra X number of months of work. Sometimes getting caught can mean just doing X amount of process work sooner than you had planned.

Different scenarios should be considered and evaluated in terms of a cost benfit calculation that weights the benfits of the "Run" from the potential negative impacts of being "Caught".

### How To Respond To Being "Caught"
There are many possible ways to respond to being "caught". What method makes sense often depends on situation specific details regarding the process you're avoiding, who "catches" you, who else is involved, and your ability and appeatite for later steps. 

##### Defer to authority
Sometimes it can be sufficient to say, "We've been working with Vice President Jane Doe on this project". 

##### Do Not Reply
Other times it might be someone's responsiblity to inform you that a process exists, but not their job to follow up and make sure you go through it within a certain amount of time after being "caught".  

##### Stall for time
Closely related to "do not reply" is "stall for time". It could be stalling for time, so you could start the process in question. It could be stall for time to get management on your side. It could be stall for time to figure out how you could pivot your project to avoid the process in question. 

##### Capitulate
Sometimes the wisest course of action is to say "Thank you very much, I'll start that process".

###### Capitulate & Ask Them For Propper Steps
Capitulation can sometimes be even more effective if you then involve them in the process. Buying what they're selling terms of their interpretation of the proces can get them on your side for later process interpretations. 

###### Capitulate & Pivot
Sometimes it doesn't make sense to go through a process. Maybe the process is designed for very critical systems, which yours is not, so you will never get the development time required to actually push through the process. In this case, it might make more sense to look into other places to deploy your system even if it makes some aspects of the project more awkward. Getting caught can require a pivot when process costs are very high and the math doesn't work out.

###### Capitulate & Abandon Project
In rare circumstances, there are no opportunities to pivot and the best course of actino is to cut your loses and abandon the project entirely. 

###### Capitulate & Later Resurrection
Depending on who caught you, there may be a change to resurrect the project later. This might be the case if the person who "caught" you was later replaced by someone who has a different interpretation of the policy in question. Other times the policy itself changes in some way.

## Disclaimer
This was not written with any particular organization in mind. It is not the opion of any organization the author or authors have previously worked for in the past.

To anyone who got here from elsewhere. Stars, forks, and retweets are not necessarily endorsements. It could just be someone found it 'interesting', so definitely go ahead and do those.


-------------
## FAQ
Frequently Asked Questions:

- QUESTION: Will you sell certification?
- ANSWER: Unlike the purveyors of the other development philosophies, the authors of Run Until Caught Development will never sell certifications. We might sell stickers but probably not.

- QUESTION: Who wrote this?
- ANSWER: The author(s) of Run Until Caught Development might be 3 racoons in a trenchcoat, 12 people at one of those fancy developer resort things with lots of cheese, 3 racoons in a trenchcoat at one of those fancy developer resort things with lots of cheese, or 1 person procrastinating instead of doing work on their other side projects. In all cases, they are remaining anonymous for now.


- QUESTION: Can I contribute to this document?
- ANSWER: Yes, there will eventually be a "CONTRIBUTING" markdown file with instructions but there is not one yet.


- QUESTION: There is no open source license file?
- ANSWER: That's a statement not a question. In any case, it means you can reference it but not copy it and claim it as your own.

   
