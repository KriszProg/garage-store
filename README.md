## About The Garage Store Project

This is a school Team Work project to learn how to implement Microservices Architecture.

The purposes were to:

* get familiar with splitting an application into multiple services
* practice the development of a microservice
* practice using and writing HTTP APIs
* learn how to cooperate with your team members implementing a different service

### Features

_Main page:_<br>
- On the main page you will find the Stuffs that someone is selling.<br> 
- 'SOLD' indicates if the stuff has already been sold.

_Details:_<br>
- If you one more details about the cards just click on it.<br>
- On the detail page an embedded youtube video about the Stuff available as well.
- 'UPDATE' feature is available from here, and you can change the status of the Stuff
to sold, with the 'SOLD' button.
- Remarks: registration and login have not yet been implemented, but in the future, 
the 'UPDATE' and 'SOLD' features will only be available if the item belongs to the logged 
in user.

_Add New Stuff:_<br>
- This feature available directly from the Menu Bar
- Remarks for 'Copy video id' field: If you want to embed a youtube video you should
copy only the video id which you can find at the end of the youtube link (after the v=).<br>
For example if the youtube link is: 'https://www.youtube.com/watch?v=aBCDefg' the video
id you should copy is: 'aBCDefg'


### Technologies

We used the following technologies for implementing the project:<br>

* ReactJS
* Spring Boot
* Project Lombok
* Eureka server
* Netflix/Zuul API Gateway
* H2 Database
* Hibernate

<!-- GETTING STARTED -->

## How to Download and Try

1. Open a Terminal on your PC

2. Create a project folder somewhere you want:
```
mkdir <name-of-your-project-folder>
```
<br>
3. Step into the folder:

```
cd <name-of-your-project-folder>
```
<br>
4. Clone this Repo:


```
//with ssh:
git clone git@github.com:KriszProg/garage-store.git

//or with https:
git clone https://github.com/KriszProg/garage-store.git
```
<br>
5. Create <b>'jpa_databases_for_own_projects'</b> folder in the root folder:<br> 
(this is necessary for the database setup)

```
cd ~
mkdir jpa_databases_for_own_projects
```
<br>
6. Open you project folder in your IDE (IntelliJ preferred)<br>

<br>
7. Go to <b>[Services]</b> sheet (View/Tool Windows/Services) and Run all the services
with the green play icon<br>

<br>
8. Open a [Terminal] (View/Tool Window/Terminal) inside your IDE and navigate to: 

```
<name-of-your-project-folder>/garage-store-ui
```


<br>
9. Run the App by:

```
npm start
```
