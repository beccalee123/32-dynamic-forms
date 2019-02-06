![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

## Dynamic Forms

### Author: Becca Lee
Paired with Brent Woodward, Hannah Ingham, and Heather Cherewaty

### Links and Resources
* [repo](https://codesandbox.io/s/r79r31p03p)
* [site](https://r79r31p03p.codesandbox.io/)


### Modules
- `index.js` renders the app, sets up the store
- `players.json` holds players data
- `schema.json` holds the form schema
- `components/app.js` contains the elements to be rendered, sets up mapping for app, and defines setState methods
- `components/conditional.js` contains conditional statement components
- `components/getPlayer.js`contains the detail view, which is displayed upon click of the details button
- `components/player.js`sets up handleSubmit method and renders the form, as well as mapping
- `store/app-actions.js` contains the CHANGE action for names
- `store/players-actions.js` contains the GET, POST, PUT and DELETE actions for players
- `store/index.js` sets the reducers
- `store/players-reducers.js` creates the players reducers

#### UML
