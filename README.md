#HumanCoin

##The Problem

Distributed digitial governance solutions have an identity problem. Specifically, it is difficult to design a system that ensures that people cannot dominate a system by controlling resources.

For example, to enable the application of digital democracy, in which each person gets one vote, how can a distributed, digital system ensure that one person isn't controlling multiple accounts in order to game the system?

This has also been referred to as the "one person, one wallet" problem in the cryptocurrency space.

##The Solution
Some solutions have been proposed. Examples include using social networks and reputation, or using the game Go as a test to prove humanity.

Fortunately, Alan Turing has already designed a test to determine humanity. The [Turing Test](https://en.wikipedia.org/wiki/Turing_test) asks a human to judge whether they are speaking with a machine or a human.

This document proposes expanding on this test as a way to positively identify humans in the following way:

- at the same time(s) every day (possibly 2), users that wish to recieve HumanCoin log into a system that will connect them randomly with some number (possibly 3) of other users via video conference. 
- They will all communicate with eachother for some amount of time (possibly 5-10 minutes). 
- At the end of their conversation they will vote on whether each of the participants is Human.
- A system reviews the votes and distributes HumanCoin accordingly.

##Risks and Mitigations

Note that this document is in an early draft stage. All contributions via Issue tracking and pull requests is most welcome. What follows is an attempt to catalogue potential weaknesses in the system, as well as potential ways to address them. 

_What makes HumanCoin valuable?_

HumanCoin is produced by humans randomly interacting briefly everyday. As such, it is not backed by anything scarce and transferrable, like rare minerals. However, there may be applications where "proof of humanity" is valuable, such as in governance systems, as well as other systems not envisioned.  

_What prevents one person from logging on with multiple accounts?_

By limiting the number of times that this global conversation happens, the system relies on the fact that:
- a) people can't be two places at once, and 
- b) the other participants should be able to tell if someone is carrying on multiple conversations

_What prevents people colluding?_

Random selection of particpants across the network should ensure collusion is not very feasible.

_What prevents an attacker from flooding the system with bots and voting itself as human?_

This is a risk similar to the risk BitCoin faces if any one actor gets more than 50% of voting power. Random selection of participants is meant to make this less feasible, but similar mitigation techniques and risk analysis from security experts is required.

_What prevents an attacker from employing very sophisticated AI and video rendering in order to fake humanity?_

Aside from the technical difficulty at this time, this document currently has no proposals for mitigating that risk.

_What voting system properly incentives correct behavior?_

A version of the [Schelling Coin](https://blog.ethereum.org/2014/03/28/schellingcoin-a-minimal-trust-universal-data-feed/) system has been proposed that would incentivize proper behavior. For example, perhaps the rules could be as follows:

- If your vote agrees with the majority, and you are voted human, then you are deemed human
- If your vote disagrees with the majority, or you are voted machine, then you are deemed machine

##Next Steps
As is clear, this is a very initial draft, with many questions to be answered. The author seeks input from all to:
- Confirm that another system isn't already attempting this
- Determine if this is a potentially viable solution to an actual problem
- Refine this solution to the point of actually being viable
