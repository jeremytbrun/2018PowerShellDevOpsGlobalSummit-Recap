# PowerShell + DevOps Global Summit Recap
* Seattle, WA
* April 8-12, 2018
* Jeremy Brun

## What is PowerShell + DevOps Global Summit
PowerShell + DevOps Global Summit is the gathering of PowerShell + DevOps professionals and enthusiasts. More than just a conference, it’s a true in-person gathering of a vibrant commuity - we learn from each other, we develop practices and standards, we share challenges and solutions, and we drive our industry forward. If you’re working with PowerShell, Desired State Configuration, and related technologies, and especially if you’re moving your organization toward a DevOps footing, then this is the 400+ level event you’ve been looking for. [More here...](https://powershell.org/summit/)

## Why I chose to attend What is PowerShell + DevOps Global Summit
When I first discovered this event opportunity I was struck by the level of technical expertise and community involvement exhibited by the event participants.

Now, after attending this event on two different years (2017 and 2018), I am certain that my first impressions were absolutely correct, and I have enjoyed participating and contributing in that experience.

The non-profit organization that facilitates this event, [The DevOps Collective](https://devopscollective.org/), desires only to bring together the best in the PowerShell and automation community so that they can share knowledge and create connections. As such, most of the technical session content is presented by volunteers from the community - _by other attendees and peers_! There is also a limited number of industry leading vendors that participate in the event. Technical representatives (real developers working on the technology) are there and open to conversation and feedback. Groups that are present, like **the PowerShell product team from Microsoft**, make this event unique in that it allows the users of the tool to interact directly and unfiltered with the makers of the tool.

## Takeaways
As always one of this event's strongest points is the ability to interface and connect with fellow attendees who are doing many of the same IT activities with many of the same tools. The ability to build on these relationships both during and after the event allows for industry knowledge sharing and innovation to happen. Since my first time attending this event I've found new and exciting ways to engage with the technical community as well as fostering new ideas and training around PowerShell and automation within my work area.

In this particular summit there were a number of sessions that are still inspiring new ideas and thought processes that I can take back to my workplace.

The first day held keynote presentations by Jeffrey Snover (The Shell Father), Don Jones (The DevOps Collective), and others from the Microsoft PowerShell product team shed light on where PowerShell, as a tool, has been, and what the future plans are. PowerShell has skyrocketed in the IT space as a do-all administrative tool, beginning with the Windows OS, now extending into the *nix world. It is my go-to tool for day-to-day operations and having access to this caliber of information and industry leaders enables me to make informed decisions and recommendations.

The rest of the week consisted of technical deep dives and breakout sessions geared towards a spectrum of different IT roles and toolsets - all geared towards automation, automation, and of course, automation.

## Detailed Session Information

### [**Be the Master**](https://bethemaster.com/) with [Don Jones](https://donjones.com/)

#### Summary
Don discusses the old "Master/Apprentice" relationship that was more prevalent in the past and why it may be the secret to capable and effective technical skillsets in those who are learning behind us. He also reflected on the past individuals who may have invested their time and efforts into what the technologists we are today. It's time to _pay it forward_.

#### Takeaways
I was really challenged by this session because oftentimes I, like most, call into the "but I don't have anything to offer category", but we truly do each have unique skillsets and abilities that we bring to the table that someone else is always learning behind us. A similiar concept to the Master/Apprentice relationship is mentorship. Everyone has an opportunity to both be a mentor and be mentored.

#### Action Items
+ I'll be reading Don's book titled _Be the Master_ which takes a deepdive into this valuable concept.
+ I'd like to explore new ways of investing in my relationships with my coworkers. In the technical realm I'd specifically like to continuously foster the automation mindset and a practical application of that is to use PowerShell.
+ I'm going to continue to invest in developing training opportunites like the _PowerShell Challenge_ that I've been doing with coworkers. I'd like to explore new ways of learning the basics of PowerShell for those who have little to no experience with it.

### [**Connecting the Dots with PowerShell**](https://powershelldevopsglobalsummit2018.sched.com/event/Cpp3/connecting-the-dots-with-powershell) with [Warren Frame](http://ramblingcookiemonster.github.io/)

#### Summary
One of PowerShell's greatest strengths is its ability to glue pretty much any technologies together. We'll use that strength to pull data from a number of services, connecting the resulting dots with a graph database that could be used as a lightweight CMDB.

#### Takeaways
This session was fascinating. Not only did I learn more than I ever have about Graph database implementations like [Neo4j](https://neo4j.com/), but also how quickly something like an asset discovery solution could be stood up and seeded with data that is relevant and relational. This was by no means a fully built out solution, but it was simple POC that demonstrated a methodology and technology that was extremely capable at scale.

#### Action Items
+ I'd like to dig into the Neo4j Graph database architecture because it could serve a purpose for internal tool making due to it being lightweight and free (open source).

### [**Defending against PowerShell attacks - in theory, and in practice**](https://blogs.msdn.microsoft.com/powershell/2017/10/23/defending-against-powershell-attacks/) with [Lee Holmes](https://twitter.com/Lee_Holmes)

#### Summary
Lee Holmes is a Principal Security Architect at Microsoft. This presentation dove into the dark corners of how PowerShell not only is being used by bad actors, but also despite that how it can be one of the security technologists greatest assets.

#### Takeaways
This was a high caliber presentation! Lee is a polished speaker and knows his stuff. We saw real demonstrations of obfuscation and other ways that bad actors are increasingly using PowerShell as their post-exploitation language of choice. This is because it is so powerfull! But thankfully there is a greater power offered to those who's job is to protect assets from those bad actors. PowerShell's audit logging and transparency, paired with tools like [Revoke-Obfuscation](https://github.com/danielbohannon/Revoke-Obfuscation) (developed by Lee Holmes and Daniel Bohannon) offer the "good guys" extremely advanced script analysis and forensics tools to add to their arsenal.

#### Action Items
+ I'd will be doing some research into the PowerShell audit logging and Revoke-Obfuscation options that were discussed. I'd like to determine if it'd make sense to recommend any one of the tools discussed to be implemented in our environment to some degree.

### [**Whip Your Scripts into Shape: Optimizing PowerShell for Speed**](https://powershelldevopsglobalsummit2018.sched.com/event/Cq9V/whip-your-scripts-into-shape-optimizing-powershell-for-speed) with [Josh King](https://king.geek.nz/)

#### Summary
With a handful of techniques tucked away in your tool belt your PowerShell code will be running faster than ever. Buckle up for a demo heavy session that can’t drop below 50 mph. When every second counts, you can’t sit around waiting for your script to finish. 

#### Takeaways
Josh did a great job of demonstrating many different "gotchas" that can really make the difference in speed when running IOPS and CPU intensive PowerShell scripts. He boiled it down into easily grasped chunks of demonstration code.

This is a field of scripting that I've been fascinated with for a long time. I am always searching for ways to improve performance in the scripts that I write for large data gathering or transformation.

#### Action Items
+ I will be doing testing with some of the suggestions he made to see if I can measure increased performance when implemented in some of my existing scripts.
+ I'll also be using his demos as a reference when developing new scripts.

### [**Documentation as User Experience**](https://powershelldevopsglobalsummit2018.sched.com/event/CrVW/documentation-as-user-experience) with [Michael Lombardi](http://michaeltlombardi.gitlab.io/)

#### Summary
Mike walked us through the threefold model of documentation, the many forms of documentation, and tips and advice to help humans produce more and better documentation for their teammates, customers, and future selves.

#### Takeaways
Documentation is something just about all of us can improve on. Sometimes is can seem more intimidating to write in real english than in code for me though! Mike made it a very approachable and achievable task though, as he demonstrated the different effective ways that we can leave a story behind with our code that both others and our future selves will appreciate when reading or supporting our code.

I'm constantly evaluating the effectiveness of the documentation (or lack of in some cases) of the code that I produce for my work role. The information Mike had to share is going to help me continue to fine-tune those results.

#### Action Items
+ Mike used some intriguing technologies to produce his session content that I'd like to take a look at. He has a [Documentarian project](https://gitlab.com/documentarian/documentarian) which is a scaffolding/framework for documenting PowerShell projects.

## [Iron Scripter](http://ironscripter.us/) Games

### Summary
The Iron Scripter games is a scripting competition that saw its first event at the 2018 PowerShell + DevOps Global Summit. Participants split up into different factions that exhibit different coding practices and disciplines. The games officials then provide a series of challenges that have specific requirements for all of the factions to compete in producing scripts to meet. The games are timed and require each faction to self-organize and delegate work to be done among faction members in order for the deadline to be met.

Finally a panel of judges such as Jeffrey Snover, Richard Siddaway, and Don Jones review the faction submissions and declare a winner. The faction that rises to the top gets to claim the Iron Scripter champion title for the next year as well as receives swag and/or cash prizes.

### Takeaways
I loved participating in this event. This being the first time, I think there are a lot of lessions learned for each of the factions in what to expect and how best to organize. I look forward to following these games and participating as much as possible. I think it not only gives a fun opportunity to socialize and work with peers in the automation/PowerShell world, but also gives opportunity to hone our skillset to meet real-world needs more effectively and efficiently.

## In Closing

This summit event remains at the top of my most valued experiences in the realm of technical training and community. I am grateful to have been able to go the last 2 years and I look forward to participating in any way I can in the future. This may include volunteering to present at the summit as well as making more regular contributions to the PowerShell scripting community. Year after year this event delivers the opportunity and knowledge that can boost an automation expert's skillset and act as a spring board to the next level.