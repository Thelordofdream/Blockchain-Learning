# Blockchain
####The next revolutionary technique of the Internet

##Chapter 1
###Definition
* Hash function is one kind of project rule for its inputs

###Collision-free(256bits）
* Two different input have the same hash value, these two inputs collide, and this situation is named "collision"
* 99.8% chance to find two inputs collide after trying 2^130 randomly chosen inputs, but it is impossible as a result of limited computation
* Some hash functions are easy to find collision, but no hash function is proven collision-free

#####Application(message digest)
* For some usable hash functions, which aren't found collision, one possible application is message digest, comparing two big file through comparing their hash value 

###Hiding
* For a subset of a large scale set, it's impossible to find the input(in the subset) through its hash value of limited computation
* H(r | x) can hide x, while r is high min-entropy distribution which means there is no hash value with obviously high possibility for the input x.

#####Application(commitment)
* 