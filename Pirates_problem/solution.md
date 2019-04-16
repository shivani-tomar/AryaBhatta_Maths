To understand the answer, we need to reduce this problem to only 2 pirates. So what happens if there are only 2 pirates. Pirate 2 can easily propose that he gets all the 100 gold coins. Since he constitutes 50% of the pirates, the proposal has to be accepted leaving Pirate 1 with nothing.

Now let’s look at 3 pirates situation, Pirate 3 knows that if his proposal does not get accepted, then pirate 2 will get all the gold and pirate 1 will get nothing. So he decides to bribe pirate 1 with one gold coin. Pirate 1 knows that one gold coin is better than nothing so he has to back pirate 3. Pirate 3 proposes {pirate 1, pirate 2, pirate 3} {1, 0, 99}. Since pirate 1 and 3 will vote for it, it will be accepted.

If there are 4 pirates, pirate 4 needs to get one more pirate to vote for his proposal. Pirate 4 realizes that if he dies, pirate 2 will get nothing (according to the proposal with 3 pirates) so he can easily bribe pirate 2 with one gold coin to get his vote. So the distribution will be {0, 1, 0, 99}.

Smart right? Now can you figure out the distribution with 5 pirates? Let’s see. Pirate 5 needs 2 votes and he knows that if he dies, pirate 1 and 3 will get nothing. He can easily bribe pirates 1 and 3 with one gold coin each to get their vote. In the end, he proposes {1, 0, 1, 0, 98}. This proposal will get accepted and provide the maximum amount of gold to pirate 5.



