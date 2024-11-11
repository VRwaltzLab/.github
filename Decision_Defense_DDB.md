# Distributed DataBase
## Introduction 
The following problem is interesting: How do you distribute the network and memory and compute load onto the users? and avoid a central server?
Formally, some protion of this problem would be trying to build a low-trust distributed relational database or low-trust distributed dcoument store...
( more in the spirit of skyhook with data sharding, rather than the focus of data availability)
### Pros
1. More general interest than the rest of this project.
2. I (the founder) was adjacent to this research in the past.
3. Aimed in theory at the low cost goal of the project.
### Cons
1. Unclear connection or necessity for dancing.
2. Unclear Value proposition to end users ( does it deliver joy)
3. Hard to test whether it delivers lower costs.
4. likely to deliver more lag to end users. (does it deliver joy)
## Ideas that I'm putting down to move on from for now
1. Building on top of bit-torrent for large file spreading, and building moderation on top of it.
2. Arranging the file hosts in a hypercube to minimize both the amount of communication and the number of swarms that a host needs to partake in.
3. Assigning private-public keys to a document, to add a viewer and editor list, while the file storer is not on either list, and the owner role having control over that list.
4. Adding an attribute to shard mapping before storing a tuple/row in a shard, so that queries on the database can be made without contacting the entire database.
5. Using h(x,y) = (ax+b)(cy+d) hash function to avoid correllated loss of files in rendevous hashing.
## Conclusion
While I think the problem posed is interesting, I think that this problem should be near the back of the list of projects that I try to finish.
(After the tracking, drone, and lens projects at least.... if not even farther)
