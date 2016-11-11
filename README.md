# Untested thoughts of things for (mostly algorithms) that have wandered through my mind
For now, just a text file where I write down crazy ideas that I have about implementing theories and stuff from Computer Science in real life. Look at the readme if you're confused.

A LOT (if not all) of these will be barely more than a "what-if" that crosses my mind at some point during the day. So please don't make fun of me if it's a stupid idea ;-;

## Thought 1
Implementing a cities layout using a Tree data structure (with weighted branches). Alright, so a specifically shaped graph that looks like a tree. Would this lead to O(logn) travel performance? Investigate / research into the data structures further.

##Thought 2
Having subgraphs in each node of a graph. This came about as I was thinking about graph theory for dependency graphs.
tldr; each macro node is a node for a certain program (feh, libreoffice, vim, etc) and is made up of micro-nodes (versions of the programs)
	ex) the feh macro-node is comprised of a micro graph of versions 1.07 - 2.3.1

Not sure how helpful this would actually be though
Will have to look into it more later.

##Thought 3
WebSnake. Basically a DFS search of the web (as opposed to a BFS). This follows the first link it sees and every first link on the new page, until it either runs out of links to follow, OR hits a link it's already visited.

I can't think of any practical applications for this at the moment, or even if it would be a good idea. Think about this when you get more sleep

##Thought 4
Shortest Path algorithm that looks at the angles of paths between s and t, and chooses the path with the closest angle to 0. Since the shortest distance between any two points is a straight line. Of course there will have to be more to this than that, and this would only work in real world scenarios (like with a map).

##Thought 5
Create new font that is derived from the overlapping form of the 10 top monospace fonts. Sort of like this web app, but with more fonts: https://tiff.herokuapp.com/

##Thought 6
Bootstrapped Artifical Intelligence. (Or whatever you would call it)  
Have two separate instances of a basic(-HUGE understatement) AI, that can improve source code. (Ie, make it more efficient, robust, add features whatever. Point them at each other. They both start out with the same source, but Machine A makes changes first, which means Machine B is now "better". Machine B then makes changes to A. Since its "better" though, it won't make the same changes that A made to B. IE, it'll make more intelligent changes / features whatever. Continue until Terminator: Judgement Day occurs.

##Thought 7
Would it be easier/more intuitive to call it Storage, Modification, Display instead of Model, View, Controller?
