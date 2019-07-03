# Search Result List

Congratulations! You made it to the eBay Kleinanzeigen remote Full Stack coding challenge, where we want to see how your hands-on coding skills.

## Steps

1. Check installation prerequisites: JDK version >=8, Maven (latest version), Node/NPM, your preferred IDE/editor. To see that everything basic is working, startup server and the client app (see below)
2. Read carefully through "Requirements" and "Out-of-scope" to focus on the right things
3. After finishing coding please add your comments and remarks inside this `README.md` file, see end of file
4. Send back the result as .zip file to the person who sent it originally to you. Please do within **3 hours** after you received the task. No need to be hyper-punctual (e.g. 10 minutes earlier or sooner won't make a difference)

Coding guidance: Combine "clean code" with "working software".


## Starting up server
We provided already a running application and project harness. You can start the server with:

```
cd ./server
mvn spring-boot:run
```

Your an example endpoint is now available: [http://localhost:8080/ad-list](http://localhost:8080/ad-list)

Alternatively, start the main class `hello.Application` in your preferred IDE

## Starting up react client
We provided a client-side react app. Start it with:

```
cd ./client
npm install
npm start
```

The client app should be available under [http://localhost:3000/](http://localhost:3000/) by default.

## Requirements
* Provide a styled list of search results under the following url: [http://localhost:3000/ad-list](http://localhost:3000/ad-list)
* When the user clicks on an item, a details page should be shown.
* On the details page provide a button for "contact poster".
* If the user clicks on "contact poster", open an overlay where the user can input a message and email address. A "send" button sends the message via ajax to a Java controller, that does something with the data (e.g. System.out).
* Before sending data, validate the fields. Message and email are mandatory fields. It is allowed to use simple HTML 5 validation.
* After sending the message a success message should be displayed.
* Use the preinstalled react app for the frontend and Java on the backend.
* Use some CSS to style your components and pages


## Out-of-scope
* NO Crossbrowser optimization necessary. We assume that we use a single modern browser. (e.g. latest chrome)
* NO need to be Maven expert or to adapt build, project harness and build is setup already
* NO perfect screen design necessary. But the user interface should look reasonably good and meet the basic requirements for usability. 
* NO Javadoc or big comments sections necessary. Tests and self explaining code is sufficient


## Your comments / remarks

What would you do if you had more time? Which trade-offs did you take?

* FILL-ME 1
* FILL-ME 2


Have fun!



