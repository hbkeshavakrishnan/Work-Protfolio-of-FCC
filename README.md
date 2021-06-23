# Farmer Customer Connect

## About the project:
The main objective of this project is to provide an online platform for connecting farmers and customers where customers can purchase goods from farmers without any intermediary.

## Description:
The tradition of buying vegetables from a farmer directly is not something we see on a regular basis. This is happening because of the intervention of intermediaries who are looting all the profits and leaving the farmer and the customer out of the box. Furthermore, in today’s pandemic driven busy world, people prefer to shop online for all their needs. So, in order to satisfy the customer and make the farmer taste the fruit of his efforts, we have developed an e-commerce website where farmers and customers are connected so that the trading can be done without an intermediary.

Farmer Customer Connect directly connects farmers and customers and provides the users with the facility to serve and be served. Thus directly eliminating the purpose of an intermediary. Also, the customer will be aware about the quality of the product based on the date the product has been set for sale. As part of our website we have also given the farmer the ability to accept or reject a customer’s request based on the quantity of stock or the transport distance or any other reasons.
Thus, Farmer Customer Connect helps the farmer and the customer trade vegetable goods and reek the benefits.



## Problems faced while doing the project:
* While implementing the Google Oauth authentication, we faced a lot of issues because of our design. we were supposed to place a radio button and fetch data from when we press login button but we were not able to do it becuase google is redirecting it to the other page and the radio buttton placed above it are not able to fetch the data. So this process took an entire week. So we moved on to traditional login process.

* For implementing Login, we wanted to implement a safe and secure method. So we took JWT authentication as one of the safest process. We implemented it in a seperate file and incorporated it in the main code. We were divided into two teams, both the teams are working on it parallelly. Fortunately we got it in three days and implemented it in the main code. 

* The next bug we faced is to redirect farmer and customer to their respective pages. We didn't have prior knowledge on how to redirect it based on the role connected from Sign up data. Therefore, we used if condition to seperate them from one another.

* While implementing Farmer's products page we wanted farmer and customer mail where we stored it in the local storage. But it is getting cleared when we logout from the farmer product page. We suffered we this issue for two days. Hence we looked about this query in Stackoverflow and they suggested us to use try and catch method. With this, we were able to handle this error.

* The last issue we encountered is to accept and reject orders for farmer when placed by a customer. The update process was not working properly but the syntax was correct. So we tested it in other laptop and it worked there. So then on we implemented the procedure in the code. 

## Technologies that we are learning:

* Frontend: React
* Backend: Node, Express and MongoDB
* Testing tool: Jest
* Code Versioning Systems: GitHub

## During Sprint 1...
* we learnt about scrum processes and agile methodology. Also, we came to know about the technologies (MERN - MongoDB, Express, React JS and Node JS) that have to be used to complete the project. 
* After that, we learnt how to create and use Git repositories and branches. During the last day of the Sprint, we started to create a database and created a sample database to know about how databases work.

## During Sprint 2...
* we were split into two teams and my team was given the task of login user using Google authentication. 
* We worked for 2 days for Google authentication and then we have split again into two teams. 
* One team worked on the general login process and the other worked on the google ones. I was in charge of google authentication. 
* The difficulty I faced is in our designing part we were asked to retrieve data from a radio which separates the user from google generated information which made us difficult task.

## During Sprint 3...
* my team started working on the farmer’s login and log out page where a user with type farmer can register their credentials and login to their respective pages.
* The login needs to be done with JWT authentication where a token is developed using an algorithm. 
* We generated the page but not able to redirect the user

## During Sprint 4...
* my team started working on redirecting the farmer’s page to the farmer page and then the customer to the customer page. 
* But we had bugs which are to be fixed. We also fixed bugs in that. So as of now, we were ready to redirect the page to the respective user.
* Now the process is to test every component of the frontend and backend.

## During Sprint 5...
* my team started working on integrating our work with other team. So in this week, we were expected to do finish testing and integrating into one file. 
* For testing, we used JEST methodogy to test each and every component. Testing process completed with all the vulnerabilitites.
* For Integrating, we pushed our files into github and started to merge files with other teams. The hardest part is to look for similar components and again merge it with our components. So it takes a lot of time to do that.

## During Sprint 6...
* I worked with the team and completed the integration part.
* Later, I worked on the images, I faced the some issues regarding the images then we formed the group and took all the suggestion from friends and completed.
* Last day I tried to implement the add to cart of the products but I didn’t finished it.

## During Sprint 7...
* I worked on the add to cart products.
* Later, I faced some bugs in the add to cart, it taken time for me to fixed the bugs.
* By end of the week I fixed the bugs and worked on place order. Solved the bugs in place order.
