
# 3. Use Case Model

## A sub-system sequence diagram for all identified scenarios in the use-cases


### Login - Substystem Sequence Diagram

* Name - Login
* Scope - System under design (SuD)
* Level - Goal: login to account
* Primary Actor - User
* Precondition - User is already registered
* Main success scenario 
	+ 1 User navigates to site
    + 2 System shows “home” page
    + 3 User clicks on “login” in navigation bar
    + 4 System shows “login” page
    + 5 User enters username and password and clicks on submit
    + 6 System authenticates user and shows “home” page
* Success guarantees - the user is authenticated
* Extensions - none
* Special Requirements – none 

![Text](https://github.com/HakimiX/Toolbox/blob/master/Diagrams/LoginDiagram.png)


### Register - Subsystem Sequence Diagram

* Name - Register
* Scope - System under design (SuD)
* Level - Goal: register account
* Primary Actor - User
* Precondition - User is not already registered
* Main success scenario 
	+ 1 User navigates to site
	+ 2 System shows “home” page
	+ 3 User clicks on “register” in navigation bar
	+ 4 System shows “register” page
	+ 5 User enters username and password and clicks on submit
	+ 6 System validates entered details and shows “home” page
* Success guarantees - the user is registered 
* Extensions - none
* Special Requirements – none

![Text](https://github.com/HakimiX/Toolbox/blob/master/Diagrams/RegisterDiagram.png)

### Publish a story - Subsystem Sequence Diagram

* Name - Publish a Story 
* Scope - System under design (SuD)
* Level - Goal: publish a story
* Primary Actor - User
* Precondition - User is authorized
* Main success scenario 
	+ 1 User navigates to site
	+ 2 System shows “home” page
	+ 3 User clicks on “submit” in navigation bar
	+ 4 System shows “submit” page
	+ 5 User enters required fields and clicks on submit
	+ 6 System validates entered details and shows “home” page
* Success guarantees - the user published a story
* Extensions - none
* Special Requirements – none


![Text](https://github.com/HakimiX/Toolbox/blob/master/Diagrams/PublishDiagram.png)

### Comment a story - Subsystem Sequence Diagram

* Name - Comment a Story 
* Scope - System under design (SuD)
* Level - Goal: comment a story
* Primary Actor - User
* Precondition - User is authorized
* Main success scenario 
	+ 1 User navigates to site
	+ 2 System shows “home” page
	+ 3 User clicks on “comments” under a post
	+ 4 System shows “post” page
	+ 5 User enters required fields and clicks on add comment
	* System validates entered details and shows “home” page
* Success guarantees - the user commented on a story
* Extensions - none
* Special Requirements – none


![Text](https://github.com/HakimiX/Toolbox/blob/master/Diagrams/CommentDiagram.png)

### Reply a comment - Subsystem Sequence Diagram


* Name - Reply a comment 
* Scope - System under design (SuD)
* Level - Goal: reply a comment
* Primary Actor - User
* Precondition - User is authorized
* Main success scenario 
	+ 1 User navigates to site
	+ 2 System shows “home” page
	+ 3 User clicks on “comments” under a post
	+ 4 System shows “post” page
	+ 5 User clicks on “reply” under a comment
	+ 6 System shows “reply” page
	+ 7 User enters required fields and clicks on reply
	+ 8 System validates entered details and shows “post” page
* Success guarantees - the user replied a comment
* Extensions - none
* Special Requirements – none

![Text](https://github.com/HakimiX/Toolbox/blob/master/Diagrams/ReplyDiagram.png)


### Read a story - Subsystem Sequence Diagram

* Name – Read a story
* Scope - System under design (SuD)
* Level - Goal: read a story
* Primary Actor - User
* Precondition - none
* Main success scenario 
	+ 1 User navigates to site
	+ 2 System shows “home” page
	+ 3 User clicks on a story
	+ 4 System redirects to story url
* Success guarantees - the user redirected to story url
* Extensions - none
* Special Requirements – redirect requires url


![Text](https://github.com/HakimiX/Toolbox/blob/master/Diagrams/ReadDiagram.pn)


### Up-vote a story - Subsystem Sequence Diagram

* Name – Up-vote a story
* Scope - System under design (SuD)
* Level - Goal: up-vote a story
* Primary Actor - User
* Precondition - user is authorized
* Main success scenario 
	+ 1 User navigates to site
	+ 2 System shows “home” page
	+ 3 User clicks on up-vote button 
	+ 4 System adds a points to the story
* Success guarantees - the user up-voted a story
* Extensions - none
* Special Requirements – none


![Text](https://github.com/HakimiX/Toolbox/blob/master/Diagrams/UpvoteDiagram.png)

### Down-vote a story - Subsystem Sequence Diagram

* Name – Down-vote a story
* Scope - System under design (SuD)
* Level - Goal: down-vote a story
* Primary Actor - User
* Precondition – user is authorized and story has at least 500 karma points 
* Main success scenario 
	+ 1 User navigates to site
	+ 2 System shows “home” page
	+ 3 User clicks on down-vote button 
	+ 4 System removes a point from story
* Success guarantees - the user down-voted a story
* Extensions - none
* Special Requirements – none

![Text](https://github.com/HakimiX/Toolbox/blob/master/Diagrams/DownvoteDiagra.png)


## Communication Sequence Diagram

![Text](https://github.com/HakimiX/Toolbox/blob/master/Diagrams/CommunicationSequence.png)


