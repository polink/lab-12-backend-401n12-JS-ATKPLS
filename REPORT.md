![CF](http://i.imgur.com/7v5ASc8.png) Lab 12 - Discord - OAuth Comparative Analysis
================================================================

## OAuth Provider Name: Discord

### Research Conducted By:
* Anthony Triplett
* Karl Polintan
* Lorin Stewart

### Overall Score and Comments
#### Score (Out of 10): 7
#### General Comments
Describe the stack (front-end only? full stack?), database, efficiency, etc. Describe the general usability and learnability
It uses Oauth to handle the token handshake, for sending a ClientID and Secret. You have to create a [Discord Application] (https://discordapp.com/developers/applications/) beforehand to be able to do this.

#### Pros
* Huge Community


#### Cons
* Documentation can be unclear


### Ratings and Reviews
#### Documentation
https://discordapp.com/developers/docs/topics/oauth2


#### Systems Requirements
#####Above and beyond 'node' and 'linux', what dependencies or core requirements exist for this framework?  Can it play at AWS/Heroku?  Does it require a certain database?
It doesn't require a specific database - it shoots back out information as JSON. 

#### Ramp-Up Projections
#####How long would/should it take a team of mid-junior developers to become productive?
It'd likely take about a week - averaging out mine and Anthony's efforts in our 301 project, which includes the few days or so we were working on this lab.

#### Community Support and Adoption levels
#####How popular is this framework? What big companies are running on it? How is it "seen" in the general JS community?  Is there an active community of developers supporting and growing it?
Discord is pretty popular, with a prevalent DiscordJS chat channel. They've recently opened up chat channels for games - so there's popular chat channels for most major games, like Apex Legends and Fortnite.
"As of December 2018, there are over 200 million unique users of the software." https://en.wikipedia.org/wiki/Discord_(software)


### Links and Resources
* [docs - Discord Oauth](https://discordapp.com/developers/docs/topics/oauth2)

### Code Demos
* [live/running application](https://lab-12-401n12js-backend-atkpls.herokuapp.com/)
* [frontend repository](https://github.com/polink/lab-12-frontend-401n12-JS-ATKPLS/)
* [backend repository](https://github.com/polink/lab-12-backend-401n12-JS-ATKPLS/)

### Operating Instructions
If someone were to download your repo (above), what steps do they need to take to run the application
* Frontend `npm run start`
* Backend `npm run start`
* MongoDB `mkdir -p ./db && mongod --dbpath ./db`
* Endpoint: `/oauth/`
  * Returns a JSON object with user identity & email in it. 
