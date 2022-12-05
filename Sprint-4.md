## **Sprint Goal:**

| ID | As a… | I want to be able to… | So that… | Priority |
|----|-------|-----------------------|----------|----------|
| 3 | Personal account | accept a transaction | I can buy | Must |
| 4 | Personal account | deposit / withdraw money to my account | I can manage the money available for my future transactions | Must |
| 5 | Commercial account | to define the information of a transaction | I procede to issue a transaction | Must |
| 11 | Personal account | see my money available | I can monitor the money I can spend | Should |
| 6 | Commercial account | issue a transaction | I can sell my product  | Must |
| 17 | Personal account | see my purchases | I can monitor the money I spend | Could |
| 18 | Commercial account | see my transactions | I can monitor them | Could |

In this sprint our goal was to implement a robust Login and Sign-up page and improve some aspects of previous Sprints.

## **Sprint Planning:**

## **Done User Stories**

| ID | As a… | I want to be able to… | So that… | Priority | Status |
|----|-------|-----------------------|----------|----------|--------|
| 3 | Personal account | accept a transaction | I can buy | Must | Work in progress |
| 4 | Personal account | deposit / withdraw money to my account | I can manage the money available for my future transactions | Must | Done |
| 5 | Commercial account | to define the information of a transaction | I procede to issue a transaction | Must | Done |
|  | Commercial account | issue a transaction | I can sell my product | Must | Done |
| 11 | Personal account | see my money available | I can monitor the money I can spend | Should | Done |
| 17 | Personal account | see my purchases | I can monitor the money I spend | Could | Work in Progress |
| 18 | Commercial account | see my transactions | I can monitor them | Could | Work in Progress |

## **Sprint Retrospective:**

* **Do well**: On this sprint we added way more functionality to our software, unfortunately not every feature is 100% finished and stable, but now everything is at least sketched whish help us to implement more complex features in the future.
* **Do different**: In the following days we will focus more on smaller details, finishing each feature individually.
* **Puzzles**: 
  * When trying to implement the Test Units to our program, we faced many issues due to problems on our project configuration with Maven. After a lot of debugging, we decided to recreate our project from scratch and those issues were solved. Unfortunately, we didn´t had much time left to do the tests we wanted.
  * Passing Login information to the actual application is something that we are still struggling with.

### Sprint Review

On this sprint we had more struggles than successes, writing so much code in a short period of time leads to many typos and bugs that end up consuming precious time. But despite that we managed to be productive and overcome most of those issues while implementing many important features

#### Team Roles

* **Alexandre Mourão**: <span dir="">In this sprint, I was responsible for the back-end development of the program, having developed and created a new table in the database to save all transactions (cancelled, to be accepted and done), as well as the transference request and confirmation of a transaction on the database. I was responsible for the Unit tests done of the sign up, and state diagram</span>.
* **Pedro Duarte**: <span dir="">In this sprint, I was again responsible for the front-end design, with the design of the homepage, wallet and transactions tabs being in an advanced state of development. Moreover, I was responsible for producing the UML sequence diagram for the login feature.</span>
* **Tiago Ribeiro**: In this sprint, <span dir="">I worked on both front-end and back-end. My main role was to ensure that my colleagues' work matched each other</span>, being responsible to making our app GUI usable, handling every scene, action and event. (Basically, the same as last sprint)\
  <span dir="">Furthermore</span>, I was responsible to fix some bugs we add and work on Unit Tests, too. 