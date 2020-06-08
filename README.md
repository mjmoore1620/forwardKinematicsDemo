# Forward Kinematics Demo
* Based on/inspired by [Coding train video][5], [Coding math kinematic series][4]

# Progress
* Started: 5/28/2020
* Milestone: Completed [Coding math part 1 demo][4]
* Milestone: Completed [Coding math part 2 demo][7]
* Milestone: Refactored [Coding math part 1 demo][4] from p5.js to generic javascript in 'wildKinematicChain' branch
* Finished: 6/8/2020, moving on to inverse kinematics

# What is the purpose of this exercise?
* Demonstrate forward kinematics
* Work towards understanding and implementing inverse kinematics
    * Understanding inverse kinematics would be useful for complex animation 

# What should I get out of doing this exercise?
* I should gain a basic understanding of forward kinematics
* I should build a foundation for learning the more complex inverse kinematics algorithms

# What have I got from doing this so far?
* Trig functions review
    * How to get the x2,y2 of line with only x1,y1 + angle
* Used new git commands: 
    * git reset HEAD filename
        * to unstage a file that I didn't want to be part of the commit
    * git stash save "save message"
        * to save uncommitted changes so I can switch to another branch
    * git commit --amend 
        * add to the last commit instead of creating a new one
        * easy way to alter last commit message
* Learned how to animate with generic javascript

# Thoughts
* The mathematical and engineering formality is way overkill in the wikipedia documentation
    * [Coding math][4] made a working demo seem very simple and straight-forward
* My useful knowledge of trig is very lacking
    * Need to practice practical application

# Keywords
* kinematic chain/linkage system/linkages: a series of rigid bodies connected by joints
    * degrees of freedom/mobility: the number of independent variables that define the configuration of a kinematic chain 
        * technical jargon, not intuitive 
* end-effector: the end of the kinematic chain that interacts with the environment
* kinematic constraints: essentially going to be angle limits I think

# Issues
* I suck at trig apparently
* Need to implement 2 canvases to reproduce [Coding math part 1][4] style demo
    * Requires instance mode if using p5.js
    * Might just use base javascript

# Specifications
* On completion of forward kinematics demo, fork repo to start inverse kinematics project

# Possible Modifications

# References
1. <https://en.wikipedia.org/wiki/Kinematic_chain> (Kinematic chain)
2. <https://en.wikipedia.org/wiki/Forward_kinematics> (Forward kinematics)
3. <https://en.wikipedia.org/wiki/Inverse_kinematics> (Inverse kinematics)
4. <https://www.youtube.com/watch?v=WHn2ouKKSfs&list=PL7wAPgl1JVvXZDYBPGfjvgeUQHJFWLPit&index=3&t=0s> (Coding math part 1)
5. <https://www.youtube.com/watch?v=xXjRlEr7AGk&feature=youtu.be> (Coding train video)
6. <https://en.wikipedia.org/wiki/Trigonometric_functions> (Trig functions)
7. <https://www.youtube.com/watch?v=4oCo1j8xGew&list=PL7wAPgl1JVvXZDYBPGfjvgeUQHJFWLPit&index=3> (Coding math part 2)

[1]: <https://en.wikipedia.org/wiki/Kinematic_chain> (Kinematic chain)
[2]: <https://en.wikipedia.org/wiki/Forward_kinematics> (Forward kinematics)
[3]: <https://en.wikipedia.org/wiki/Inverse_kinematics> (Inverse kinematics)
[4]: <https://www.youtube.com/watch?v=WHn2ouKKSfs&list=PL7wAPgl1JVvXZDYBPGfjvgeUQHJFWLPit&index=3&t=0s> (Coding math part 1)
[5]: <https://www.youtube.com/watch?v=xXjRlEr7AGk&feature=youtu.be> (Coding train video)
[6]: <https://en.wikipedia.org/wiki/Trigonometric_functions> (Trig functions)
[7]: <https://www.youtube.com/watch?v=4oCo1j8xGew&list=PL7wAPgl1JVvXZDYBPGfjvgeUQHJFWLPit&index=3> (Coding math part 2)