# A Peace Corps for Programmers

The federal government should fire me. Like the thousands of other contractors who develop software for government agencies, I am slow, overpaid, and out of touch with the needs of my customers. And I’m keeping the government from innovating.

In recent years, the government has become almost completely dependent upon contractors for information technology (IT). So deep is this dependency that the government has found itself in a position that may shock those in the tech industry: it has no programmers of its own; code is almost entirely outsourced. Government leaders clearly consider IT an ancillary function that can be offloaded for someone else to worry about.

But they should worry. Because while they were pushing the responsibility for IT into the margins, the role of IT became increasingly central to every agency’s business. Computing might have been ancillary 20 years ago, when the only computers were the mainframes in the basement. Average employees never had to worry about them. But today, a computer is on the desk of every civil servant. Those servants rely on their computers to do their jobs effectively. Every day, they encounter new problems that could be quickly solved with a bit of web savvy, were there only a programmer there to help.

And they desperately do need help. Imagine not having Google to quickly find information; no Facebook or LinkedIn to find new colleagues; no instant messaging to communicate with those colleagues once you found them. Imagine having to ask for permission every time you wanted to publish content online, instead of being able to do it quickly and easily with a wiki or weblog. This is the state of computing in the federal government.

> SIDEBAR

> On top of keeping the government from innovating, the dependence on contractors hurts the country in much more tangible ways. In February 2003, a few weeks into my job as an intelligence analyst with the Department of Defense (DoD), the Federal Republic of Yugoslavia officially changed its name to Serbia and Montenegro. My job was to maintain an enormous database of facilities in Eastern Europe, including labeling each one with a country name. But the tool we used didn’t have an option for “Serbia and Montenegro,” so on the day of the name change, I emailed the contract officer in charge of the database with a simple request: “This country changed its name. Could you please update the tool to reflect this?”

> Doing so would have taken a computer programmer less than five minutes. But instead, he used that time to respond to my email:

> “We’ll consider it for the next version.”

> In other words, his current contract—written months prior—didn’t account for changes in the geopolitical landscape, so there was no paperwork explicitly authorizing him to make this change. To do it, he would have to wait until the contract was renewed (months or years from now) and the government allotted funds for this five-minute job. It wasn’t his fault; he was no doubt aware of how easy it was to make this change. But doing it without permission from either his boss or the government would spell trouble. Yugoslavia didn’t exist anymore. Except inside our office, where we had to wait for a contract to make it so.

The government can no longer afford to outsource IT. It is core to the government’s business. If the government intends to do IT right, it should wean itself from outsiders like me and start doing the job itself.

What’s so wrong with contractors? Nothing, really; the problem is the processes they have given rise to. The pervading philosophy is that government is slow, inefficient, and incapable of quickly adapting to change, while private companies do things better, faster, and cheaper. In many cases, this is true; the government is by no means a well-oiled machine. But software is one thing that contracts do not speed up. Software developed under contract is much slower and much more expensive than any other form of software development still in practice. Here is how the typical IT contract evolves:

1. A low-level government employee complains to her boss about a problem. This could be anything from a bug in an existing piece of software to a gaping hole in her agency’s IT security. The boss has no programmers on hand to solve the problem, so he dismisses it.

2. More and more people complain about the problem until it gets attention from higher levels. But even thinking about a solution is expensive—months of paperwork must come before a contract is awarded and someone finally starts writing code—so the problem remains unsolved.

3. The problem leads to a calamity—a website is hacked, classified information is stolen, or electronic voting booths break down on Election Day—and leaders are finally motivated to solve the problem.

4. Procurement officers write a list of requirements for the ideal solution. Because they have little direct experience with the problem, they survey the workforce to get a sense of what’s needed.

5. The workforce’s version of the problem is condensed into a document called a Request for Proposals, or RFP. The RFP is then distributed to potential bidders, who will respond with a proposed solution and a bid based entirely on the contents of the RFP. Contractors cannot go directly to the users, the people who know the problem best. The RFP is therefore an indirect, highly edited communiqué from the user to the contractor, a substitute for the invaluable direct interaction between user and coder that guides any successful software product. But it’s too late: contractors are from here on out trying to solve what they believe the problem to be, not the problem that really is.

6. The contract is awarded. Months or years after the problem was first noticed, the first line of code is written. Over the coming months, the winning bidder will develop the solution off-site, hidden from the eventual users who could be providing valuable feedback.

7. The solution is delivered. Because the target users had such a small part in the development process, the solution falls short. It is hard to use and comes with an 80-page manual.

It should now be clear why the government is so far behind the times: it isn’t allowed to solve its own problems, relying instead on people who do not understand them. Two glaring faults doom the contracting process to failure. First, the development process is vastly different from that of today’s most popular software. Modern web applications are persistently watching their users and adjusting their code to make it faster and more user-friendly. Adventurous users can begin using these applications before they’re even finished, giving the developers invaluable insight into their users’ preferences. Without this constant feedback, the developers risk spending years on a product in private, only to reveal it to the public and find that nobody wants to use it. Such products are so common in government that they have earned their own moniker, named for their eternal home: shelfware.

Second, the paperwork required to simply start coding takes time and money. So, to even consider solutions, the problem has to be severe enough to justify months of bureaucracy. Why go through all that trouble just for a problem that would take a week to solve? The logic makes the taxpayer ill: the bureaucracy actually wants high price tags. The result is an organization full of easy problems that get no attention until they are big, expensive, and ready to boil over.

## Tipping Point: The Extinction of Pencils

One such problem that may soon boil over is the terrorist watch list. For years, the list—created to monitor suspected terrorists and keep them from flying on commercial airliners—had inconvenienced innocent travelers. The problems were evident, but they weren’t bad enough to justify asking for help.

Then a toddler was kept from boarding a flight. Then a senator. At some point, this problem crossed the threshold, and the government issued an RFP for an improved database to manage the list. The $500 million contract was awarded to Boeing and a smaller company. After months of development, a congressional investigation discovered that the soon-to-be-deployed database could not perform basic searches for names, and was missing huge stores of valuable data. The National Counterterrorism Center had spent half a billion dollars on a tool that, while certainly complex, could not do things that you and I do every day from our home computers.

Why so much money for something that seems so simple? This frame of mind—that technology projects should be big, expensive, and time-consuming—has honest beginnings. Twenty years ago, computing was a niche. The government used computers to encrypt the president’s phone calls, simulate nuclear blasts, and predict the weather. The government paid private companies lots of money to build very complex systems. That’s OK, because tasks such as these required lots of computing power, so the biggest, baddest, most expensive system was usually the best. It didn’t matter that these systems were hard to use, because the only people using them were computer scientists. The builder of the system understood the user—the builder and user may have even worked side by side—and if the user ever needed the system to do something it couldn’t, that user probably had the skills to tweak the system. Computers were left to the computer people. Everyone else still used pencils.

But computing is now everywhere. Computers long ago fit on our desktops. Now they fit in our palms. But the government still acts like computers fill basements, and if you could sit down at a government desktop, this outdated mindset would be immediately apparent: on the screen would be websites reminiscent of the mid-1990s, without any of the web-based productivity and collaboration tools that define today’s Web. Expensive supercomputers still matter. But so do cheap, light web applications. Small, unassuming tools can change the way an organization does business. Such tools are commonplace online, but they do not get a second look from a government that expects and needs its technology to be expensive. Meanwhile, independent developers are at their keyboards, proving themselves willing to help a government that, as we’ll see, is slowly opening its arms to them.

## Competition Is Critical to Any Ecosystem

One of the reasons the Web has better tools than the government is competition.

Take airfare as an example. There are countless websites that help you buy plane tickets, each of them constantly improving their tools and layouts to make you happier. And if you aren’t happy with those sites, you’re free to start your own business and compete with them. But when the government contracts new software, it gets only one product out of it. Instead of many choices, users have only two: use this tool, or use nothing.

Web developers know that the first attempt at an innovation almost never works, and that it takes many attempts before someone gets it right. For every Facebook, there are countless Friendsters. Given one chance, you’ll likely end up with one of the latter. If the government wants better software, it has to start creating and acquiring more software.

In the past year, two promising government projects have chipped away at this problem. Washington, D.C.’s Apps for Democracy competition let independent developers build web applications for a shot at prize money. The D.C. government’s $50,000 investment bought it 40 tools in 30 days. The District got to keep every contribution but only paid for the really good ones.

Meanwhile, the U.S. Intelligence Community is becoming an unexpected leader in engaging everyday developers. To provide more analytic tools to their workforce, they have released BRIDGE, an open development platform akin to Facebook’s: now, any software developer can build a tool and provide it to intelligence analysts. If the analysts like it, the government buys it. If it’s junk, your tax dollars are saved.

This approach worked for Facebook: it gained 30,000 new tools in two years, and got other people to do all the work. Most of these new tools fall into the junk category, but many others are invaluable. The community finds the good ones and makes them more visible. It is the same principle that governs our economy: we buy the dish soap that works, and the bad ones go away. We should expect the same practice from our government, whose very job is the promotion of market economies and democracy. Apps for Democracy and BRIDGE are a welcome departure from contract-based software.

But while these projects are giving government employees more options, they haven’t filled in all the gaps. Who will maintain software that was built not by a global firm, but by an independent developer who is juggling multiple projects?

And what about user feedback? Neither of these projects addresses the fact that government software is built by people unfamiliar with government users. Apps for Democracy produced useful tools for D.C. residents, but little for D.C. employees. And applications on the Intelligence Community platform are hobbled by the world’s biggest firewall: intelligence analysts use these tools on a top-secret network that doesn’t allow them to communicate with the outside world. As long as the government keeps developers outside its walls, those developers have no hope of solving the government’s technology problems. The civil service needs an infusion of technical talent. The civil service needs intel techs.

## Creating a Developer Corps

Decades ago, the intel tech (also known as “mission support” at some agencies) was a specialist in the Intelligence Community who helped analysts with now-defunct technologies: setting up the light table to look at satellite imagery, making mimeographs, and so on. Unlike today’s tech support staff who sit in the basement or in Bombay, these experts sat among the analysts and were solely dedicated to the analysts’ mission. And because they were government employees, they were at the analysts’ disposal whenever help was needed.

But then personal computers arrived. Software made the intel techs’ tools obsolete. The light tables vanished. The intel techs soon followed. It is the opposite of what should have happened: IT’s role in intelligence analysis—and every other government function—has grown tremendously, while the government’s in-house technical talent has dwindled. Government employees’ need for technical help has never been greater, but there is nobody there to help them.

If they still existed, today’s intel techs would be developers. They would be deploying web applications for new needs the moment they arose. They would mash up data and make it easier for both civil servants and private citizens to consume. They would do the things that contractors do today, only immediately—no paperwork necessary—and with users at their side. The intel tech must be resurrected for the Internet age. The government must hire web developers and embed them in the federal bureaucracy.

The government needs to hire the people who have been fueling the web application boom for the past 10 years. They are young programmers who created revolutionary tools from their dorm rooms, and they are small firms with virtual offices who stumbled upon a new way of doing business. The trouble is, most of these people are not compatible with government culture. They like working from p.m. to a.m. They don’t like ties. They seek venture capital, not pay grade bumps. Are they supposed to move from one coast to another and indefinitely trade in their lifestyles for something completely different, not knowing when they would return to their old lives? That is asking too much.

But what if these in-house developers weren’t standard government hires on entry-level salaries? What if their time in the government wasn’t a career, but a mission akin to a term in the Peace Corps or Teach For America? A program marketed and structured as a temporary “time abroad” would let developers help their country without giving up their careers and identities.

Now is the perfect time for such a program. Silicon Valley’s interest in D.C. has never been as great as it is now. Technology icons are encouraging developers to quit creating banal tools and instead put their energy into things that matter. And it’s working: several prominent Internet entrepreneurs have become full-time civil servants. Many more have contributed software tools to programs such as Apps for Democracy and BRIDGE. Apps for America‡—a federal take on Apps for Democracy sponsored by the nonprofit Sunlight Foundation— received 34 submissions during its first iteration, and 46 more on the second. Geeks want to help government. The government just has to give them the right invitation.

Like the Peace Corps and Teach For America, terms in the Developer Corps would have a time limit. Whether this limit is six months or six years, I do not know. But a limit of some kind is important. First, it will be easier for developers to make the leap if they know they will eventually return to their current careers.

Second, being detached from an agency’s pay scale and career plan will give the participants the freedom to experiment and—more importantly—to fail. Failure is a key part of innovation. Technology firms know this, and their employees are used to working in atmospheres that encourage failure. If they don’t try new things, they’ll be killed by their competition.

Not so in government. Unlike private companies, a government—at least ours—is relatively safe from competition, and thus doesn’t feel the need to be constantly reinventing itself. Things are fine how they are. The populace views failed government projects as little more than a waste of taxpayer dollars. No career-conscious government employee wants to take on such a risk. So, to succeed, the Developer Corps’ participants must have the same freedom to fail that they did in their former jobs. The knowledge that their terms will end on a set date will quell the fear of failure that plagues the average government employee.

The greatest threat to this program is lack of permission. If red tape keeps developers from being productive, they will end up wasting their time fixing printer jams instead of writing code.

Developers work quickly. They can implement ideas within hours of conceiving them, continuously deploying, checking, modifying, and redeploying their code dozens, hundreds, thousands of times along the way. Doing this never requires anyone’s approval. But within each government agency are multiple offices that must vet code before it is deployed: system administrators, information security officers, lawyers, and so forth.

Developers will never get anything done with such thick bureaucratic walls between them and their work. Wasting their talent is the fastest way to destroy the corp’s reputation. They must be given authority to code what they please. Not all agencies will grant this authority. Such agencies must not be allowed to participate in the Developer Corps. (Participants in restrictive environments would never get anything done anyway, so there is no harm in barring uncooperative agencies.)

Finally, this program should take a page from a new organization called Code for America (http://codeforamerica.org). CFA recruits coders to work with government offices for set terms, but at the municipal level instead of federal. About to enter its inaugural iteration, CFA’s participants will work with their respective governments remotely from a shared space in California. This communal coding environment will let participants enjoy networking events, guest speakers, and the creative energy generated by each other’s ideas.

The federal program I’ve proposed in this chapter should incorporate a similar communal environment. While coders will spend their days at their respective government agencies, group housing will let them discuss their work over dinner and drinks, allowing the creative process to continue after hours. And select days could be dedicated to meetings with government leaders and tech luminaries, visits to other agencies, and networking. Such events will help ensure a D.C. term is a boost to a coder’s career instead of diversion from it.

## Conclusion

Our government agencies need the ability to develop their own software. Keeping them from doing so prevents them from providing vital services that we all pay for. No story makes the case for this capability better than that of Jim Gray.

Gray was a technology pioneer who, during a sailing trip in early 2007, disappeared off the coast of San Francisco. The Coast Guard searched for him for three days and could not find him. They called off their search.

But a group of determined people kept looking. They had imagery satellites take fresh pictures of a swatch of sea outside the San Francisco Bay. If Gray was out there, he and his boat were now on film. But they were left with hundreds of photos, each big enough to cover a wall. A handful of people could never review the images in time to save Gray. So, a team of software developers converted those large photos into lots of smaller ones, which were then posted to a website where the public could review them. Clicking on a possible sighting sent a report to a flight crew, which then searched the area in question. Noticing that the images were blurry, another team of programmers contributed code that automatically sharpened the images. The entire system was created from scratch in just a few days. And it was done without any help from the government.

This effort was coordinated entirely by private citizens with the help of publicly available technology. Though he was never found, Gray inspired the largest collaborative search party in history. Twelve thousand private citizens reviewed more than half a million images. It is an amazing story of teamwork and ingenuity. Inspiring. Soul-stirring.

But also frustrating: why didn’t our government do this the moment Gray was reported missing?

It is tempting to use this story as a case for more self-governance: if the public can do it and the government can’t, why not go with it? Instead of equipping the government to do what private citizens already can, let’s just do their jobs for them from our home computers.

The Web has made it simple to form ad hoc groups and coordinate their actions, and we will continue to see cases where such groups fill the government’s shoes. But such cases will not be the norm. Our populace cannot govern itself just yet. There are too many critical functions that we cannot yet take over. We do not have battleships. We cannot run elections. Some private citizens guard our borders, but that doesn’t mean they should.

We will need a formal government for the foreseeable future. Our government should be at least as capable as a quickly organized group of virtual volunteers. It will certainly have the budget for it.
