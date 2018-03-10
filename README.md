# Bar Battles
Each week a new song is posted that has a featured artist. Users will vote to determine who had the best bars.

**Link to project:**
Coming Soon

![alt tag](https://i.imgur.com/Z0hFKnF.png)

## How It's Made:

**Tech used:** Node.JS Express MongoDB Javascript Framework of choice
Under the Hood:
This is a simple application with the concept of CRUD in mind. Using node, express modules, MongoDB and the server localhost 3000 I was able to connect the front and back ends. Initially while running command line all updates were made with node server.js, this was tedious and I eventually installed nodemon to take advatange of its ability to auto update the server. An html.ejs file was used as a template to reduce the amount of code needed to get this app running. This method allows me to define something once and reuse it throughout my application. A back up index.html page was added for trouble shooting. The JavaScript handles event listeners, any get, post, put or delete requests. You will notice this when adding to the messages input and clicking on the thumb or trash icons.


## Optimizations
Due to the fast turn around of this project I didn't get to add all of the usability that I hoped for. A few things I would add to improve upon this project would be:
1) Tally Count For Each Artist
  a)As users added there picks for best lyrics. A number next to each name would increase or decrease at the end of the week the winner would be displayed.

2) Highest up-voted comment would populate at the top of page.

3) Allow users to create personal accounts;
  a) I would allow for users to be able to create log-ins so that they could have a more personalized experience.

4) Custom music player.

## Lessons Learned:

Learning more about how CRUD works at least seeing it first hand was pretty amazing. Actually working with Node.js and seeing how data I put into the DOM populated into the database on mLab was pretty awesome too. I believe this project help solidify my understanding of how the front-end and back-end work together. One thing that blew my mind if if you are working front end we only worry about separation of concerns, but if we are doing full stack development then we are using MVC.

## Examples:


## Installation

1. Clone repo
2. run `npm install`

## Usage

1. run `npm run bars`
2. Navigate to `localhost:3000`
