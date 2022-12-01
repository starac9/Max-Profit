#MAX_PROFIT

LIVE HERE :- https://starac9.github.io/Max-Profit/

TOOLS Used:- HTML,CSS,JS

Problem Statement: -

User will give the number of days. We can construct 3 different type of buildings, i.e. Theatre (takes 5 unit of time to construct and revenue is $1500 per unit time after construction), Pub (takes 4 unit of time to construct and revenue is $1000 per unit time after construction), Commercial Park (takes 10 unit of time to construct and revenue is $3000 per unit time after construction). We have to calculate the maximum profit, user can earn and the count of all the buildings constructed to get this profit.

Approach: -

User can give input as the number of days in the input box.
I observed that we will never construct "Commercial Park", instead we can construct 2 "Theatre" to get more profit.
Now we only have 2 buildings to be constructed, and we have reduced one variable from our calculation.
Now we can greedily construct all the "Theatres" first (as much as we can) to get maximum profit.
After constructing the "Theatre", we can build "Pubs" from the remaining days if possible.
I've used Arithmetic Progression to calculate maximum profit from the number of "Theatres" and "Pubs".

Features:-

Works in constant time
Responsive
Multiple Output
Supports large input
