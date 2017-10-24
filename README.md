
# 3. Use Case Model

## A sub-system sequence diagram for all identified scenarios in the use-cases


### Login - Substystem Sequence Diagram

* **Name** - Login
* Scope - System under design (SuD)
* Level - Goal: login to account
* Primary Actor - User
* Precondition - User is already registered
* Main success scenario 
	1 User navigates to site
    2 System shows “home” page
    3 User clicks on “login” in navigation bar
    4 System shows “login” page
    5 User enters username and password and clicks on submit
    6 System authenticates user and shows “home” page
* Success guarantees - the user is authenticated
* Extensions - none
* Special Requirements – none 


### Register - Subsystem Sequence Diagram

* Name - Register
* Scope - System under design (SuD)
* Level - Goal: register account
* Primary Actor - User
* Precondition - User is not already registered
* Main success scenario 
* User navigates to site
* System shows “home” page
* User clicks on “register” in navigation bar
* System shows “register” page
* User enters username and password and clicks on submit
* System validates entered details and shows “home” page
* Success guarantees - the user is registered 
* Extensions - none
* Special Requirements – none


### Publish a story - Subsystem Sequence Diagram

* Name - Publish a Story 
* Scope - System under design (SuD)
* Level - Goal: publish a story
* Primary Actor - User
* Precondition - User is authorized
* Main success scenario 
* User navigates to site
* System shows “home” page
* User clicks on “submit” in navigation bar
* System shows “submit” page
* User enters required fields and clicks on submit
* System validates entered details and shows “home” page
* Success guarantees - the user published a story
* Extensions - none
* Special Requirements – none


### Comment a story - Subsystem Sequence Diagram

* Name - Comment a Story 
* Scope - System under design (SuD)
* Level - Goal: comment a story
* Primary Actor - User
* Precondition - User is authorized
* Main success scenario 
* User navigates to site
* System shows “home” page
* User clicks on “comments” under a post
* System shows “post” page
* User enters required fields and clicks on add comment
* System validates entered details and shows “home” page
* Success guarantees - the user commented on a story
* Extensions - none
* Special Requirements – none


### Reply a comment - Subsystem Sequence Diagram


* Name - Reply a comment 
* Scope - System under design (SuD)
* Level - Goal: reply a comment
* Primary Actor - User
* Precondition - User is authorized
* Main success scenario 
* User navigates to site
* System shows “home” page
* User clicks on “comments” under a post
* System shows “post” page
* User clicks on “reply” under a comment
* System shows “reply” page
* User enters required fields and clicks on reply
* System validates entered details and shows “post” page
* Success guarantees - the user replied a comment
* Extensions - none
* Special Requirements – none


### Read a story - Subsystem Sequence Diagram

* Name – Read a story
* Scope - System under design (SuD)
* Level - Goal: read a story
* Primary Actor - User
* Precondition - none
* Main success scenario 
* User navigates to site
* System shows “home” page
* User clicks on a story
* System redirects to story url
* Success guarantees - the user redirected to story url
* Extensions - none
* Special Requirements – redirect requires url


### Up-vote a story - Subsystem Sequence Diagram

* Name – Up-vote a story
* Scope - System under design (SuD)
* Level - Goal: up-vote a story
* Primary Actor - User
* Precondition - user is authorized
* Main success scenario 
* User navigates to site
* System shows “home” page
* User clicks on up-vote button 
* System adds a points to the story
* Success guarantees - the user up-voted a story
* Extensions - none
* Special Requirements – none


### Down-vote a story - Subsystem Sequence Diagram

* Name – Down-vote a story
* Scope - System under design (SuD)
* Level - Goal: down-vote a story
* Primary Actor - User
* Precondition – user is authorized and story has at least 500 karma points 
* Main success scenario 
* User navigates to site
* System shows “home” page
* User clicks on down-vote button 
* System removes a point from story
* Success guarantees - the user down-voted a story
* Extensions - none
* Special Requirements – none



## Communication Sequence Diagram

