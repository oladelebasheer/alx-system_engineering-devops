
# Postmortem
Any software system will eventually break for a variety of reasons, such as bugs, traffic peaks, security risks, hardware issues, natural calamities, and human error. Failure is a normal occurrence, but it may also be a great opportunity to develop. Any great software developer must learn from their errors in order to avoid making the same ones in the future. Failure is OK, but repeating it for the same issue is not.
 An effective tool in the technology sector is the postmortem. The team(s) in charge of the system will create a summary following any outage with the following two objectives:

# Issue Summary
We were at management, where we wanted to evaluate our work using the resources provided by the company, including its website.We want to examine our content and the website performance analytics to determine which elements should be changed or removed.
    Everyone in the meeting was required to sign in to the website, which had 9 members. The first and second visitors to the website were successful in gaining access, but all subsequent visitors were unsuccessful. because of a traffic issue.

# Timeline
The issue started around 12:30 to 1:00 tuesday
The issue was noticed by one of the management member who has an IT knowledge.
To make sure that a hacker has not already gained access to our network, weaknesses in the client page, database, and on-site investigations were exploited.
Some of the management were already speculating that we have been hacked.
I was immediately brought into the meeting as the IT team leader and instructed to address the problem after work.
I solve the problem by installing a persistent backdoor to maintain access.
For on-site I called our host to ask them if there is any problem with them.
# Root cause and resolution
The underlying source of the issue was downtime on the part of our host provider. And our load balancing was not set up correctly.

# Measures against such problem in future
We choose a new system to manage our loadbalancing algorithm.
Always keep an eye on your servers to ensure they are running properly.
Have extra back-up servers to prevent your program from completely going offline   during an issue.



