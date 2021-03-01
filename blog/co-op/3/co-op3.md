---
layout: post
title: Why interviewing in tech is broken (and the direction it is going)
permalink: /co-op3/
category: co-op
tag: co-op
date: 28/2/2021
order: 3
finished: true
---

After applying/interviewing for 4 years straight I have some opinions on tech interviews. I think it is a largely broken system that is very poorly optimized from both a technical (engineer) and non-technical (recruiter) standpoint. The fallacy is that the most qualified and most intelligent person is hired but that is rarely the case. I would like to think that I am going up against other candidates in a person against person battle of skills and who can handle pressure, but that simply isn't true. It is more subjective due to the human nature of assessing interviews, it is flawed on asking simple algorithm questions, it is based on faith that a person who can present themselves in an interview can work as a software engineer in that team. All those things are not respective of the job, but unfortunately there is no great alternative at this point. The Googles and Facebooks decidingly have technical bars so the industry copied it and followed suit.

Equating it to regular jobs, it hinges more on `WHO` you know rather than what you know. And the referrals can go a long way or straight up be duds. Sometimes job hunting and interviewing just feels like blindly throwing darts at a dartboard.

<img src="/blog/co-op/3/nv2.png">

> "Truth is...the game was rigged from the start."
> - Benny from Fallout New Vegas

### Problems of interviewing (summarized)
- resume screening is a broken process
- the most technical/best/smartest person doesn't always get hired
- memorizing coding questions is a bad practice that still works
- the level of perfection expected usually causes false negatives/positives
- hardly a fair process (quotas being met)

## The Problems

### Recruiters screening
Where do I start. Non-technical recruiters often have no idea what projects or experience mean on a resume. How do they know who to pick? (This is **AFTER** your resume has been passed through an filtering software)

Technical recruiters luckily have a little more insight. But even then how many times do you think they check if you full-stack web app posted on your github was not just a copy and paste from some other repo? Or that you didn't just put a bunch of buzzwords to pass through the resume screening software. That is an overly cynical take but it'd be easy to create false-positives on a resume for the sake of impressing recruiters.

The next "easy" cutaway is looking at companies you interned at and basing a person's worth on that. There are a multitude of issues here. How do you equate impact or actual technical competency from looking at their job/job description. An example of this is a thought process along the lines of "Billy interned at Google, they surely must be a reputable engineer. They passed their technical bar and did an internship there." We are forced to extrapolate data based on this experience but it doesn'te tell the whole story. We have very little context into how they were hired (were they asked some easy question or something they saw before?) and we have little context in their internship other than what they wrote about it (did they perform poorly? Were they unable to work in a team setting?)

This is more of a gripe with recruiters not doing their research but I had someone on LinkedIn messaged me this:
```
Hey John,
your internship at Linkedin caught my eye.
We at <COMPANY> are ex-Googlers and ex-Amazon engineers, working on AI powered search to own local shopping.We’re funded and growing.
Nike CF Sephora Ulta are our customers.
I’m looking for super smart engineers like yourself to join our team.
```

Firstly he called me "John" which isn't "Jonathan" or "Jon" but I'll overlook that. I make mistakes in people's names sometimes.

I'm not sure how much more general you can get. He only mentions my LinkedIn intership and then talks about his company. He mentions ex-Googlers and ex-Amazon employees and a fairly vague company description. It probably is a copy-and-pasted headhunt message but this shows the lack of depth into person research they sometimes do. If I asked what they liked about my internship at LinkedIn, or why they reached out to me, I'm not sure I'd get a well-thought out answer. They cannot tell my actual impact from just glancing briefly at my LinekdIn profile.

I could go on and on about recruiter and recruitment practices but it can be boiled down to a few statements. A lot of times they have no idea who to look for, who is right for the role, or what makes a good engineer. (You could make the case only software engineer managers can really do those things, but their time is usually spent managing software projects not searching for candidates)

### Memorizing questions
Sites like leetcode got popular by posting specific lists of questions companies would ask and people then memorizing those specific questions. This always frustrated me because questions like "reversing a linked list" is really dumb but I got asked it 3-4 times. I've been asked "coin change" 4-5 times, "kth largest number" 5-6 times, "2d-islands" or some variant 3-4 times, etc.

**I did not go out and attempt to memorize these questions**. There is a lack of creativity and actual gauging of algorithmic ability in interviews (especially at companies that aren't big N size). Making questions that test problem solving skills, data-structures and algorithms, and making it the right difficulty is hard. Imagine you make a great question, only for it to be leaked on Glassdoor, Leetcode, or any other derivative. 

A lot of companies ask textbook questions in interviews hoping to litmus test candidates on this, and feel pressured due to big tech companies following same procedures. (A few are moving away from this, but more on that later). In reality a good startup or smaller-sized company should tailor questions to their business, therefore making questions weed out people who are not interested and also get a much more focused group of people rather than people who know the "Top 100 most common interview questions".

If everyone is going out and memorizing questions on how to find cycles in linked lists, two sum, and largest contiguous subarray why should companies ask this? They are just playing a game of what do you know from leetcode and what have your studied previously. It in turn has become like studying for the SAT where it is more about knowing **how** to write the SAT than the knowledge behind the SAT.

**I have always said that people should learn the techniques of how to use various data structures and algorithms (arrays, linked lists, trees, graph traversals, sliding window, dynamic programming) and apply them to solve the problems. If you learn the fundamentals you should be able to apply them to different problems**

I used to dislike the notion of asking dynamic programming in an interview but lately I've had a change of opinion. Dynamic programming questions are hinged on implementation. You cannot implement a dynamic programming question WITHOUT understanding the recurrence relation (which often is not TOO complicated unless the interviewer picks a fiendish problem on purpose). If you memorized a recurrence relation for a question and you don't actually understand what the question is asking it is evident when you need to explain what is going on.

People memorizing questions to pass the bar creates a situation where you potentially have a "leetcoder" joining your team. Great at memorizing niche problems like "how to create a bst from preorder traversal" or "inverting a binary tree" but can they code your web app? Might be a yikes situation depending on their actual aptitude to learn, willingness to work in a team, and ability to grow as a software engineer. In the best case, they practiced and studied knowing that they need to pass the algorithms section to pass the interview.

I always felt it was weird how KMP string matching was a technical report paper in 1970, but it is now expected in some interviews to write it out. If it took extremely smart computer scientists time to create it, why would I regurgitate something I memorized purely for the sake of memorizing it. This is in the same vein of "memorized purely for sake of recall in an interview".

### Memorizing trivia
Even worse than memorizing interview questions is memorizing interview trivia. I don't have the greatest memory for things I don't use frequently so I dislike trivia. I don't know the exact number for doing a `chmod` on a file to make it read only. If I did a 4 second google search I could find it out. If I did it often enough I would know off the top of my head.

There is a lot of trivia that I do know by virtue of general use. I got asked about "difference in public, private, and protected in objects", I got asked about "eventual consistency and strict consistency", etc. Some stuff was from university classes, some was just from using it often enough. If I don't know a trivia question, like 99% of people, I'd google it and find the answer. Obviously memorizing the solution would save that time, but in all honesty I am not a huge hash-table lookup that memorizes every bit of information I receive.

### leetcode gripes
Contrived example: (showing leetcode gripes)

**leetcode profile for superdupercoder123**

**Contest Rating:** ~1500 (depends but anything below 1600 is imo roughly weak/needs practice)

**Solved:** 1000+ questions (or a lot)

**Acceptance Rate:** 75%+ (anything more than 50% is abnormal for a "everyday" coder)

On leetcode it is really easy to copy and paste solutions seen in the discuss section or straight from the solution section. You get a nice green accepted solution and you solved the question. And then if you want to bump up your acceptance rate you submit the **SAME** solution multiple times. This is only to get your acceptance rate inflated. So instead of getting 1 WA (wrong answer) and 1 AC (accepted) and having a acceptance rate of 50%, I'll submit my correct code 4 times making my acceptance rate 80%. This is dumb.

This doesn't always indicate you know how to solve the question or if you even did the question in the first place. I want to ask you, do you normally solve a question perfectly on the first run-through 75% of the time? Even AMAZING competitive programmers like:

[awice](https://leetcode.com/awice/) Ranked 3rd in the world, Acceptance Rate: `31%`

[tmwilliamlin168](https://leetcode.com/tmwilliamlin168/) Ranked 5th in the world, Acceptance Rate: `61%`

[SaveVMK](https://leetcode.com/savevmk/) Ranked 24th in the world, Acceptance Rate: `71%`

[LarryNY](https://leetcode.com/larryny/), Ranked 36th in the world, Acceptance Rate: `68%`

Even awice trying out solutions has a fairly low acceptance rate and shows that he actually tries stuff out. If you have a high acceptance rate it doesn't mean anything. For all we know you could be resubmitting your two sum solution 50+ times to normalize getting a LC medium incorrect. The top tier talent have closer to 50-80% acceptance rate. You don't become a top tier talent by having a high acceptance rate and having a high acceptance rate doesn't make you a top tier talent.

The number solved versus contest rating is also an interesting comparison. When I see 1000+ (or a fair amount) solved and a low contest ranking that raises some red flags. Just like an assignment is an indicator for the midterm. At the University of Waterloo I scored **BELOW** average on assignments in cs341 (algorithms) usually getting ~70s where class averages were high 80s to 90s. I was going to office hours every week and continuously trying to solve the assignments and learn the concepts. Then when the midterm rolled around I got 88%, but we had a class average of ~40% on that midterm. If people were really doing much better than me on assignments, where were they when they had the midterm which had similar content? Pressure and time constraints are one thing, but the class was averaging near 90% on the assignments and couldn't even do a simple DP algorithm on the midterm? That is the exact same thing here. You can do an obscenely large number of leetcode questions but if you aren't learning concepts and fundamentals you're going to do poorly in the interviews or contests. In the end when you gameify your leetcode progress to show off you are just cheating yourself.

### Expecting perfection in interviews
Perfection is expected in answers for technical interviews. I have never passed an interview where I did not code a problem (or in the case of multiple rounds, every round) to 100% perfection. Even places where I coded to 100% perfection they would still say no. It transcends perfection.

One place I got asked 2sum (trivial), 3sum (harder but still trivial), and 4sum (n^3 is trivial. Looking back ok it isn't even that hard. But interviewer didn't nudge me in that direction). Since I didn't solve all 3 questions optimally in 45 minutes I got rejected. That's tight constraints. You need perfection in all facets.

It is disappointing because in my opinion someone who gets stuck but prevails and solves it in the end, or is solving organicly (as opposed to memorizing a question and having it be perfect on the first try) is a rewarding experience for the candidate, but it is extremely devalued in the interview. If I had a candidate who solved it with struggles on their own in 20 minutes but someone who coded it perfectly in 10 minutes at face value you want the person who did it perfectly. But who is to say the circumstances of the question didn't just make it that way. (For an easy question sometimes it should be a short time frame, but I am generalizing it to the point that an novel solving experience is more valuable for an interviewer than seeing something beforehand.)

### Explaining code to interviewer
If an interviewer asks me a question I hope they understand the question. (This has unfortunately not always been the case)

I outline my algorithm to make sure the interviewer is on the same page as me. What I deem as important is the understanding that the interviewer knows what I am doing. For one, they are writing my interview notes and feedback so for them to understand is paramount.

In the off chance they don't understand what is going on, or don't understand my thought process I try to explain it to them the best I can without losing lots of time.

Due to unavoidable social barriers sometimes people just don't connect socially. You can think of concepts and code in ways that they don't think of. Some interviewers demand you solve a problem **THEIR** way. Any other way is suboptimal (when it may not be) or is not acceptable (which is also dumb). When this occurs you are stuck. You are forced to do it **THEIR** way because they are the interviewer.

### Some interviewers want you to succeed and help you...some really want you to suffer
The majority of interviewers I have interacted with were very polite, understanding, and willing to help when I got stuck.

On the off-chance, sometimes interviewers were flat-out terrible. I've had ones berate my code, ask me why I was putting comments to explain "production code" (in the interview I perceive it as "interview code" so I will put comments for extra clarity), eating loudly during the interview, make fun of my hobbies etc. If these are the people interviewing me and writing feedback on me, how am I even supposed to show them my skills and what I coded?

### Quotas
I am not going to touch on this in depth but the system is not fair and probably rigged against you. You often say "\_\_\_\_ got an interview/offer and I didn't. I'm much more qualified". Whether or not if that is actually true recruiters make mistakes in who they choose. I've had it happen both ways.

Back when I was in science and business there was a certain group that had specific avenues that increased their chances for employment opportunities. They weren't actually a minority but actually a majority if you really calculated the numbers. Despite that, people of that group would still take advantage of that nuance they were a minority because when you're all fighting for jobs you will take any advantage you can get because you're looking for yourself out there. When the cards favoured them, they took it upon themselves to deem what was fair.

### Parity

There really is no parity in job hunting so people will do what they deem as necessary. Here are some scenarios that you may come across:

- Is lying about your accomplishments on your resume (putting different companies or roles) okay since everyone else embellishes their resumes?
- Is it cheating on a code challenge if the code was posted on leetcode?
- Is memorizing all of a company's questions using leetcode premium before your interview fair? All I had to do was pay for leetcode premium to see the questions
- Can I google the coding question they asked me **DURING** the interview? They can't see me if it is virtual. (BIG yikes)

These are huge grey areas people face and there is little to no boundaries other than people's morals. When software engineer positions and internships are so coveted some people are willing to do **whatever it takes** to get those jobs. The competition is present in any profession but here so much money is at stake for many people.

## The Future of Interviewing
Where I think interviewing is going. Hopefully in a positive direction, but there is still a lot to fix in the very broken process.

### Previous landscape
A few years ago the questions being asked at Big N companies are now widely known. Questions have risen in difficulty. No longer does Google ask brainteasers. Topics like dynamic programming are more commonstay. Lesser known topics are being more common like sliding window, prefix sum, disjoint sets, monoqueues, segment trees, etc. (some of the latter ones not so much but we shall see in the future) It is hard to predict what is to come, but I think places like India where the competition is much higher, a lot more people are competiting for less positions (compared to US), and talent pool is much higher is going to cause question difficulty to skyrocket.

### More custom questions focusing on concepts
I've seen more follow-up questions focusing on understanding now. Specifically under hypothetical space constraints, dealing with distributed systems, etc.

I've had places say "ok now we can't load it all in memory, what can we do if..." or "How does this function run with a stream of data...". These are usually more nuanced statements meant to probe deeper in the fundamentals of the problem solving. Which also means if you memorized a problem's solution and nothing beyond it, that is a steep cliff that stands before you. I think these are fine in terms of learning more of a person's thoughts on a solution. They are usually more open-ended as they initiate discussion.

### System Design
I think the future of tech interviews lies in system design questions. They are less memoizable with leetcode and other dedicated problem sites. I think leetcode questions may be obsolete in a few years due to the bar being that "people just memorize questions". It has come to the point where you just read CTCI (cracking the coding interview) and hope a big name overlaps a question with one you saw in the book.

System design (which even I have areas to improve on it) encompasses object-orientated design, real-world distributed system constraints, and a lot more fluidity for thought from backend and frontend. I think the negative aspect is that it pushes more towards generalists that need to be familiar with all facets, but also means you need to understand how your API webhook fits into the giant landscape of the product. There are negatives and positives to basing cs knowledge on system design more and more. (which becomes more prevalent as your move upwards).

## Final Thoughts
These are just my thoughts after doing interviews for a few years. I could be wrong but this is what I've seen from my experiences.
