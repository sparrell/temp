**Key Takeaways**
-	Cybersecurity == Cybersafety == important in cyber-physical systems
-	Cybersecurity Automation is cheaper/better/faster than manual
-	Cybersecurity Vendor-agnostic standards enable automation
-	Where to go for more info

**Why people will want to attend?**

Terrestrial cybersecurity automation protocol will determine whether the new space race is the stuff of dreams or nightmares. This talk knits together abstract theories with concrete consequences in a cosmic call to action.
-	To takeaway the key takeaways
-	Because cybersecurity is no longer just for cybersecurity geeks
-	Amusement
-	To win prizes

**Structure of Talk (25 min)**
1. Background (4 min)
1. Uncle Jim’s Cosmic Quadblox Quiz (4 min)
1. Automation (8 min)
1. Blinky Demo (2 min)
1. Conclusion (2 min)
1. Q&A (3 min)
1. Announce Prize Winners (2 min)

**Detailed Outline**

1. Background
   *	Title Slide
      - My Mastodon handle is @sfractal@infosec.exchange. Please toot/post about this talk
   * Tagline (Think Evilly, Act Ethically slide)
      - My tagline is think evilly, act ethically and this talk will be about applying that tagline to space – ie
      - #Security101
   * Dreams and Nightmares  I (Moon Landing Pic)
      - What’s more aspirational than a kid saying they want to be an astronaut?
      - No greater stage of human endeavor than space flight and no more aspirational dream than taking part in it.
   * Dreams and Nightmares  II (Challenger explosion Pic)
      - FLIPSIDE: No tragedy more visible or visceral than a space tragedy
      - Challenger, Columbia, uncontrollable descents, launch pad explosions. Low orbit collisions & routine loss of signal are just a few of the many ghosts that haunt human exploration of space
   * Only Getting Harder (jfk pic)
      - On September 12, 1962 in a speech delivered at Rice University, JFK offered that we choose to go to the moon “not because it’s easy, but because it’s hard.”
      - Historically, the devil has been in the details
      - Dropped oxygen tanks, ruptured o-rings, cracked tiles, and rounding errors have meant the difference between life and death, mission success and failure
      -   RAZOR THIN MARGINS OF ERROR and they’re only getting thinner
   * We are the Space Program I (webb telescope pic)
      - I mention all of this because everyone in this room is a part of the space program
      - Gone are the days when people with crew cuts and pocket protectors in Huntsville, Houston, and Cape Canaveral were the sole administrators of space travel
      - In an age when common smart phones are many tens of thousands of times more powerful than the guidance computer on a Saturn V rocket, the boundaries between the work we do in terrestrial cyber security and the software that finds its way beyond earth’s atmosphere are few
      -   BTW, this is a pic of the James Webb Telescope. A friend of mine, Dr. Ori Fox, runs the part of the telescope that sees in the mid-infrared.
   * Space Pic from telescope
      - For decades, teams built from some of the most qualified engineers on the planet worked to deliver a platform so technically excellent that it could broadcast stunning images like this from the depths of space through a complex communication network back to its handlers on earth.
      - This is the public unveiling of this picture and you are the first people outside the telescope
      - Ori info summary here on how many computers, much software, how much open source … in telescope
      -   More on the telescope in a minute, but did you know
   * We are the Space Program II (hacked webb pic)
      - This pic, taken by the Webb telescope, was used by hackers to distribute malware.
      - Which means that decades of work executed by teams built from some of the most qualified engineers on the planet was co-opted in a matter of days by nefarious actors who saw the majesty of the galaxy as nothing more than a clever exploit
1. Uncle Jim’s Cosmic Quadblock Quiz
Aside to reviewers. QuadBlockQuiz is a game on the web developed for Supply Chain Sandbox at RSAC 2021 and reused at BSidesLV 2021 and RSAC 2022 (https://supplychainsandbox.org/quadblocks). It is being modified for this talk and a contest will be run during the talk, with 3 prizes (2 raspberry pi’s with LED matrix, programmed with some of the automation features discussed in the talk, 1 book). The talk and contest will be preannounced on social media.
   *	QBQ falling blocks Gif
      - in the spirit of our newfound role in the space program of the future, I'd like to introduce a game I built.
      - It's called Uncle Jim's Cosmic Quadblox Quiz.
      - You'll be stacking space junk amid a storm of trojans, rootkits and errant cosmic ray bit flips that threaten to end your mission.
   * QBQ QnA gif
      - Answer questions correctly and you have a better chance of success.
      - Otherwise, the consequences could be devastating (timed so attack on gif shows up as I say that)
      - Why Uncle Jim? (run into next section introducing Uncle Jim's contribution to Apollo)
   * Houston, We have a problem (apollo 13 slide)
      - Recap my Uncle Jim’s role in bringing Apollo 13 home safe. Need to tighten up and get graphics right
      - Jim Sparrell (my uncle) role in bringing the astronauts home safe –
      - one small computer, necessary for real-time reentry calculations, used power they didn't have enough of, so they shut it off
      -   Space is cold - computer got very cold
      -   did the simulations on the tradeoff between turning computer on too early (and would run out of power/oxygen and crew would die) and waiting too late (computer would take too long to warm up and not be available for reentry and capsule would burn up on and crew would die)
v      - play short clip from movie where my uncle Jim is briefly mentioned
v      - loss of that computer imperiled lives. thousand time more true today
1. Automation
   *	Houston, We Have A Solution (Houston, We Have A Solution = automation slide)
      -   Fine-tuning standards-based interoperable cybersecurity for the inhospitably of space
      - Where human-produced technology goes, so go human problems
   * Risk (Jerry Maguire “Show me the money” slide)
      -   This is from the movie Jerry Maguire – show me the money.
      - It turns out or most business decisions, including on security – money is a good metric but only if you do the math correctly.
      - These ‘correct’ math tools actually came out of the safety industry and work equally well for money, or casualties/deaths which unfortunately is more appropriate for space travel.
   * Risk (“How to” Sieresen book slide)
      -   This book has been out a while but I still recommend it. It’s a textbook, and like most textbooks, it’s not necessarily an easy read.
      - But the concepts in it are really important. I’ll give out one of these at the end of my talk as a prize.
   * Savings (JHU 3-order slide)
      -   Here is some data from the Johns Hopkins University Applied Physics Lab. They automated their defenses using some standards I’ll  cover next.
      - Being a university and a national lab – they studied the impact of automation. They saw:
1.	3-order of magnitude increase in how well they handled events and incidents
2.	2-order of magnitude increase in how much was mitigated
3.	Most important – 2-order of magnitude decrease in how long the hacker was in.
      - That is what you plug into your risk quantification in the Green book I just mentioned – 2-order of magnitude decrease in time for hacker to do damage which results in an even greater reduction in damage.
   * Acronyms (alphabet soup slide)
      -   Cybersecurity automation has as many acronyms as the space shuttle – well maybe not the thousands NASA uses. I’ll try to not only define the acronym but explain the value.
   * PACE in Space (Pace logo slide)
      -   Security Posture - you want to know the state of your enterprise
      - More words here – analogous to telemetry in spacecraft
   * OCA (OCA/NASA Slide)
      -   PACE is part of the Open Cybersecurity Alliance or OCA.
      - OCA is a nonprofit, global collaboration of software providers, end users, government agencies, research institutes, and individuals committed to enabling the free exchange of information, insights, analytics, and response across cybersecurity tools.
      - OCA is to cybersecurity what NASA is to rockets.
   * Kestrel hunting (Hawk hunting slide)
      -   One critical security attribute (ie input to PACE) is
1.	‘are there hackers in my system? If so, where? What are they doing’
      - Kestrel is an OCA project for threat hunting ie finding the hackers.
      - For a spaceship this is analogous …
      -   Stix/threat intelligence sharing (Stix slide)
      -   Why might you be looking? Because your peers, your government intelligence agencies, or your ISAC/ISAO gave you threat intelligence.
      - STIX is an OASIS standard for sharing threat intelligence.
      - TAXII, another OASIS standard, is the typical distribution for STIX
      -   For a spaceship this is analogous …
      -   Unfortunately, many vendors put out cybersecurity tools with their own custom interfaces. Good for vendor because leads to vendor lockin. Bad for customer and bad for cybersecurity overall.
v      -   Good news is the OCA has an open-source project, stixshifter, to convert all these vendor interfaces into standard STIX output
j.	Playbooks/Courses of action (Playbook slide)
      -   Don’t just share threats, share solutions (playbooks)
      - Mission Control in Houston follows playbooks, so do cyber defenders
      - CACAO is the OASIS standard for sharing cybersecurity playbooks
      -   This is fundamental to automation
      -   What’s in playbooks
1.	Controls based on the security posture ie PACE
2.	Commands
k.	OpenC2 (OpenC2 slide)
      -   Just like rockets have command & control, or C2 in NASA speak, so does cybersecurity automation.
      - And the OASIS standard for C2 is OpenC2
l.	Back to PACE for SPACE (Space Race for PACE slide)
      -   One crucial input to your security posture is whether your software is vulnerable to exploit.
      - To know that, you need to know what your software is, and what it’s made up of, which brings us to Software Bill of materials or SBOM.
m.	SBOM/VEX (sbom slide)
      -   In a world where a tile can cause a catastrophic failure of a space shuttle, we should be just as concerned about what goes in the software.
      - Knowing the components of the software let you know whether it’s vulnerable to exploit. So you need SBOMs for any software.
      - A companion document is the VEX or vulnerability exploitability eXchange. This tells you whether vulnerabilities are actually exploitable.
      -   Having SBOMs and VEXs lets you “shift left” and fix problems upsteam before they cause problems.
      -   This is another aspect of security posture to store in PACE
n.	TAC (tac slide)
      -   Another important input in PACE, and also helps with threat hunting, is more information about the threat actor. The threat actor context (or TAC) OASIS technical committee is standardizing how to describe threat actors in STIX
o.	IOB (IOB slide)
      -   And besides knowing about the threat actors, it helps to know about how they behave and that is where Indicators of Behavior or IoB help.
      - IoB is another project in the OCA, along with PACE, kestrel, stixshifter.
      - Like TAC, IoB standardizes in STIX but in IoB it is the indicators of behavior instead of the threat actor themselves
      -   Both TAC and IOB help defenders know what to look for and to Find and fix the faults that allow them in
p.	HDL (HDL slide)
      -   Mitre has a cybersecurity automation effort and needed a way for cybersecurity tools to exchange data, so they came up with the Heimdeall Data Format to normalize data. It is now being developed as an OASIS standard.
q.	NIEM (NIEM slide)
      -   NIEM started outside of cyber as a US government effort to standardize terminology for communications among federal agencies and with state and local governments. It is now an OASIS open project and had expanded to include cyber/
      - For cybersecurity the rocket analogy to NIEM is NIEM – ie the NASA already uses NEIM 😊.
r.	VSMI (value slide)
      -   Value Stream Management or VSM means translating all this into business terms – for example the financial risk mentioned earlier in the green book
      - For a spaceship this is analogous to the Office of Management and Budget and just like rockets, cybersecurity costs a lot. But if you skimp, people die.
s.	Automation summary (rocket build slide)
      -   To get the Webb Telescope to space required a rocket, with fuel, and a gazillion piece parts.
      - The fuel for the rocket in cybersecurity is automation,
      - the gazillion piece parts are the alphabet soup I just went thru,
      -   and the rocket holding it all together is sharing among defenders
1. Blinky Demo (pi slide)
      -   Live demo of raspberry pi doing small subset of previous automation stuff
1. Conclusion
   *	Takeaway slide
      - Cybersecurity == Cybersafety == important in cyber-physical systems
      - Cybersecurity Automation is cheaper/better/faster than manual
      - Cybersecurity Vendor-agnostic standards enable automation
   * For more information (“links to resources” slide)
      - For more information, see the links on this slide or feel free to contact me via the various methods on this slide
   * Conclusion (another space pic from webb – never seen before)
      - It's a luxury to think that the work we contribute to cybersecurity in space will have a long lead time or the deliberate tempo of Devops. More likely than not, cybersecurity professionals will find themselves drawn into extraterrestrial operations in the same way my Uncle Jim found himself involved with Apollo--via a random call on an otherwise ordinary afternoon. We need to prepare for how sudden and seemingly mundane our role in the space program will be and adjust our dreams and nightmares accordingly.
   * Clock Slide
      - never enough time, thank you for yours
1. Q&A (Q&A/patch logo slide)
1. Announce Prize Winners (prizes slide)
