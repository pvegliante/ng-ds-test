1 Name and describe the two main operations of a stack (to add and remove data).

  .push() and .pop()

2 Name and describe the two main operations of a queue (to add and remove data).

  enqueue() and dequeue()

3 Draw the tree resulting from adding the following sequence of numbers to an empty tree: 30, 45, 15, 10, 50, 40, 20, 27

                                    30
                              15          45
                          10      20          50
                                     27
                                        29

4 Is this tree balanced? If not, which rotation needs to be done? (Use the following rotation as an  example: rightRotation(30), or leftRotation(10))

    the tree is balanced.

5 Now add 29. Is the tree balanced? If not, which rotation needs to be done? (Use the following rotation as an example: rightRotation(30), or leftRotation(10))

                                  30
                            15         45
                         10    20         50
                                  27
                                     29

    leftRotation(20)

Consider the following tree:
--------5
-----2-----8
---1---3
-0

6 Now add 0 to the tree. Which one is the first node to go out of balance?

    2.

7 How do you fix this node? (Use the following rotation as an example: rightRotation(30), or leftRotation(10))

    rightRotation(5)

8 What are the four main steps of mergesort?  

    1. split the array in 2
    2. mergesort left half
    3. mergesort right half
    4. join the two arrays.

9 Say you have a program which handles the login queue to a game server. The game server is able to log in one person every one second. Assume that one second must elapse after a person logs in with an empty queue before they are removed from the queue. Draw the state of the queue at 12:00:06, considering the following sequence of events:

<!-- At 12:00:00 Hades logs in -->
<!-- At 12:00:00 Ares logs in -->
<!-- At 12:00:00 Zeus logs in -->
<!-- At 12:00:00 Buzz Light Year logs in -->
<!-- At 12:00:02 Kanye West logs in -->
At 12:00:03 Taylor Swift logs in
At 12:00:03 Darkwing Duck logs in
At 12:00:04 Evil Mickey logs in.

At 12:00:06 Taylor Swift will log in.
At 12:00:08 Darkwing Duck will log in.
At 12:00:10 Evil Mickey will log in.

10 What is an angular directive?

  angular directives are an extention of html.

11 When specifying an angular directive, you write a function which must return an object called:
<!-- a. Directive Constructor -->
<!-- b. Fidel y Chavez Object -->
c. Directive Definition object
<!-- d. Directive Object -->

 12 What is the relationship between html, the $scope construct, and angular expressions? (Expressions are the ones that are written like so: {{quote}} ).

    html is what is on a page, the $scope constructor identifies what the html can use, an expression injects a part of the scope into the html.

13 In order to send ajax requests in Angular, the most accepted programming convention is to create an angular:
<!-- a. Module -->
b. Service
<!-- c. Controller -->
<!-- d. $http -->

14 In order to create a service, you must use the following angular function:
<!-- a. angularApp.controller -->
b. angularApp.module
<!-- c. angularApp.directive -->
<!-- d. angularApp.factory -->

15 Do this exercise: https://github.com/Real-Skill/angular-exercises/tree/exercise1 You will need to run git checkout exercise1 in addition to the commands listed in that readme. You do not need to run grunt karma.
