# h1 - Should Tero wear a helmet?

# Threat modeling summary
1)  Braiterman et al 2020

i) Threat modeling is basically analysing systems and asking 4 main questions to identify if there are any security or privacy risks. 

ii) Use of threat modeling manifesto is important as it provides with guiding values and princples. Value would be something that has signficance and priciples are the facts about 
    threat modeling (there are 3 types of principles in question). 
    
iv) Things that will benefit threat modeling are; Systematic approach, Varied viewpoints, and putting theory into practise etc. These anti patterns should be avoided; Admiring the problem, and having Tendency to Overfocus etc. 

iii) Idea: New people to threat modeling could learnt he system faster if they review some past threat models. 

2) Shostack 2022

i) This is a threat modeling course by Adam Shoestack who has written a very famous book on threat modeling. According to him threat modeling should be done early on to anticipate problems like before any code has been written or chips being procured. Threat modeling is a package of methods that will help us to think about security beforehand. There are four questions and if we focus on these we are threat modeling
 
- What are we working on?
- What can go or what could possibly go wrong?
- What are we gonna do about it?
- Did we did a good job?

ii) Sketching on the other hand is the beginning part of answering the questions what are we working on as we put thoughts out of our heads and discuss it with others. Using a drawing a tool might be beneficial. This all helps to answer "what could possibly go wrong?" 

iii) Data flow diagrams are simple to draw and help us understanding "what are we working on?". Answer the questions the heart of threat modeling "What could go wrong" if one takes guidance using Stride it might be easier. Structure is important for consistency and for that we use STRIDE to answer what could go wrong. 

iv) Tracking is important as each threat could be countered by the answers of the question "What are we gonna do about it". Risk management is utilized for analysing subset of threats and helping us to decide what are we going to do about those. Last question "did we do a good job", is there so we know that work was actually done and it was worth our time. 

3) OWASP CheatSheets Series Team 2021

i) Threat modeling is strcutured, and it focuses on analsying how might a system be attacked. It should be done early in the SDLC and as a normal step in the process. 

ii) Advantages of threat modeling are Identify risks early, increase security and have a better understanding of the system. 

iii) Each of the four questions should be answered and looked in depth by using tools. Stride can be used to identify the threat, "what can go wrong". Response and migitation is the section to think and decide what to do about each threat. Last but not least Review and Validation where we check if the work is good enough. 

iv) Cloud systems might introduce new challenges. Clooud frameworks for example, "AWS’s Well-Architected Framework – Security Pillar " might help. 

Idea: Threat modeling could be used like a checklist that is revisited at every design change in a system.

# Infosec Scene (Epi 151 Chris Rock)
- This episode is about an Australian hacker who was into Black and white hat hacking since childhood.
- Chris believes that morally there is no difference between Black and White hat hacking because at the end of day its hacking which is a skill. He also says that he has particpated in big criminal offences like robbing banks, and transferring moeny and he has never been caught nd arrested.
- Chris also mentions that hackers get caught because of mistakes and not because it is hard, he says its easy onece you have the experience.
- He describes one operation against a CEO Bob where he had steps what is he gonna do, where first he was gonna go after his family then his laywers and legal matters as he uses a bottom-up approach.
- The guy also mentions about flaws in systems so technically Attackers could, declare people dead and create fake identities.
- Chris tells many things that hackers could do and governments didn't do anything against them. 
- Jack at the end also mentions a youtube channel that has mind blowing talks "Chris Rock Defcon". 

# a) Security hygiene
There are somethings that a normal person could do to stay safe. Starting by using strong and unique passwords. Secondly, enable multi-factor authentication this system will make sure multiple times that it is the owner who is trying to login. Other than this devices might be locked using fingerptints. For companies employees could keep a log and monitor if there is some weird activity. Should'nt download stuff from unknown sources. People working could avoid typing their passwords when more people are around. 

# b) Make-belief boogie-man 
The company 

Heritage Motors buys, stores, restores and sell antique cars. These could be vintage ferraris or classic mercedes from the 70s. I took inspiration from GM General Motors for the name of my company and the idea was my own. 

What are we Working on? 
- This business model depends on trust, mutual understanding, Authenticity, Availibility of parts and Financial transactions. Key assets are the Customer identity and contact information, this also include financial payments data and Customer's work place etc. Furthermore, car documentations, actual cars stored in warehouses and inventory data. Our online marketing platform helps customers to find cars for buying and selling. There is direct communication with brokers and online payment options.

What could go wrong? 
- After applying STRIDE to my company's vulnerabilities, I think some example threats could be Spoofing where someone acts to be someone else and might get away with confidential data, Tampering ehre the valuation and credibility of documents might be compromised. Leak of customer data like their wealth or location might be information disclosure and is a major threat. Forgery of documents and payment frauds are most likely common in these areas. These are things that would effect the customer and can be done as the system is online.

What are we going to do about it?
- The security strategy should include migitation so there is strong identity verification for buyers and sellers. Moreover, MFA for brokers and staff Tamper evident document storage and proper verification of these documents. We can also remove any unesscary access to ownership documents and customer's data. Employees hiring should be solely based on their skills and trustworthyness. Regular audits and security measures should be checked by someone to make sure there is no compromise in anything.

Did we do a good enough job?
- In terms of internal security yes, but there are many more things that should have been considered like wifi or unknown sources on the internet, what to do if you notice weird changes on the marketing platform. For 1 person this was enough but to make it even better we need collaboration and a team to make sure nothing is missed and question 2 is answered in more depth. Overall trust and threat modeling is the key to remain safe!  
