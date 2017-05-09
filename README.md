<!--
Creator: SF WDI Team, Brianna Veenstra
Edited by: Brianna
Location: SF
-->

![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)

# Firebase 

### Why is this important?
<!-- framing the "why" in big-picture/real world examples -->
*This workshop is important because:*

For prototypes and simple applications, development will often be faster if we rely on stronger tools.  Firebase is a tool that makes it very fast and easy to set up a server and database. It also has features like authentication that can be complex and/or risky (insecure) to build ourselves.

### What are the objectives?
<!-- specific/measurable goal for students to achieve -->
*After this workshop, developers will be able to:*

- set up a project on firebase
- configure firebase authentication 


### Where should we be now?
<!-- call out the skills that are prerequisites -->
*Before this workshop, developers should already be able to:*

- draw a diagram of the request-response cycle 
- make an AJAX request to a third party API
- describe a login process and expectations from a user perspective


### What Is Firebase?

Firebase is a PaaS, or "Platform as a Service." That means it offers a number of cloud-based computing services, including the one that matters to us today: a realtime database. 

Not only can we access a Firebase database programmatically using code, but we can also interact with data via a graphical interface in the browser.

Firebase uses a NoSQL database. This means that information is not stored in tables. Instead, information stored in one big JSON object.

#### Why Use Firebase?

There are lots of notable apps that use Firebase, including [Shazam](https://www.shazam.com/) and [NPR One](http://one.npr.org/), and [plenty more](https://firebase.google.com/customers/).


It's fast to develop.
* Setting up Firebase should take much less time than coding a back-end from scratch.

It's realtime.
* Firebase uses Websockets to maintain a constant, open connection between the client and the database. Rather than use a traditional request-response system with HTTP, the browser and server are constantly in communication with each other and are immediately aware of changes on either end. 

It's user friendly.
* Firebase's graphical interface means we only need to load up a browser in order to explore what we have in our database.

It's secure.
* Because it's widely used and well-maintained, Firebase's authentication solutions are more secure than what we would create ourselves.

#### Why Not Use Firebase?

Limited querying.
* Firebase's JSON format isn't set up well for complex data queries and aggregation. 

Limited control.
* Users, especially free users, have very limited say in when Firebase makes updates or takes services offline for maintenance. The free version also only allows about 50 connections and 100mb of storage.

Not a one-stop solution.
* Features like mailing, image processing, repeated jobs, or server-side integration with most APIS aren't part of Firebase yet.

And remember, some simple web apps don't need a backend at all.  
