# CMPE 281 - Team Hackathon Project

# Project Journal - Team SharkHead

## Members:
+ Sunny Udhani
+ Akshat Shah
+ Viraj Upadhyay
+ Mandipsinh Gohil
+ Manikant Prasad

### Important Links
* <a href="https://bit.ly/2JyJyBR" target="_blank">Sprint Task Sheet</a>
* <a href="https://bit.ly/2JUna6p" target="_blank">Team Kanban Board</a>


# Project idea:

## Cash App prototype

Cash App is a seamless way to send money to anyone using just their email address. There are no middlemen to slow down the transaction, which is immediate. The functionalities are as follows:
> It consists of various modules such as Sign up, Log in, Add money, Withdraw money and Send money. The users are able to choose their unique Cash App id on registration.

## Project Architecture Diagram:
<img src="https://raw.githubusercontent.com/nguyensjsu/team281-sharkhead/master/Design/Design%20Architecture.jpg?token=AiMCxOPk_DlQ4he9S2NaSvCWzqZYhAnLks5a9llXwA%3D%3D">


> The front-end is developed in React which is hosted on Heroku. The back-end developed using NodeJS is divided in two ec2 instances, to split the functionalities. The login and signup functionality runs on one node and the transaction in another. Each of the functionalities are connected to each member's GO API which allows it to interact with the redis database in each cluster. The sessions are maintained in MongoDB on mLabs. Load balancers are added to make the system scalable.
 
# Weekly progress
## Week 1:
* Decided the project idea and road-map.
* Decided what technology stack should be used.
* Went through multiple project ideas and discussed each one.
* Need to distribute tasks related to development to team members leveraging expertise knowledge.
* Discussed how each member's individual GO API would integrate into the project.
>Agenda: Road-map for Project and Task Distribution 

>Number of meeting hours this week: 2

## Week 2:
* Finally agreed on Cash App prototype.
* Finished wrapper API individually for database clusters.
* Reviewed as a team - Feasible timeline of tasks and responsibilities.
* Started coding for back-end.
>Agenda: To select the Application. Talk about API Document. Make Kanban Board to get the project done in desired timeline.

>Number of meeting hours this week: 2

## Week 3:
* Created a design architecture.
* Discussed how the functionalities will split.
* Integrated GO Data Service API.
* GO program setup and client connectivity.
* Front-end in React finished.
>Agenda: Design Architecture, Functional Split, Sharding, Replication stratgy.

>Number of meeting hours this week: 3

## Week 4:
* UI Improvements.
* Finished all the functionalities.
* Hosted the front-end on Heroku.
* Hosted the back-end on AWS.
* Connected MongoDB to maintain session.
* Added load balancers.
>Number of meeting hours this week: 5

## Week 5:
* Finished writing the Project Journal.
* Tested the performance of the Cash App prototype.
>Number of meeting hours this week: 1

# Challenges faced:
* Creating the design of the system.
* Set up the tools required for the application to work.
* Integrating front-end and back-end.
* Integrating GO APIs.
* Some conflicts in the code took significant amount of time to resolve.
* How to achieve functionality split.
* Code integration for Node and GO.
---
#### References, tools and technologies used:

##### [NodeJS](https://nodejs.org/en/) for back-end.
##### [React](https://reactjs.org/) for front-end.
##### [Video](https://www.youtube.com/watch?v=9S-mphgE5fA) referered to integrate Redis and Node.
##### [Draw.io](https://www.draw.io) to create diagrams.
##### [mLabs](https://mlab.com/) used to store sessions in MongoDB.
##### [AWS](https://aws.amazon.com/free/) for deployment.
##### [Heroku](https://www.heroku.com/) to deploy front-end.





