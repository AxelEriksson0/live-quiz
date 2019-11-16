# Live Quiz
Multiplayer quiz game built in 9 hours at Salt during hackday. https://live-quiz.netlify.com/ - Using sockets to connect multiple players with server built using NodeJS/Express and frontend in React.

- Best viewed on desktop!
- Your answer gets registered but the UI doesn't really update. Check your points if you got it right or wrong.

Update 2019-11-04:
- Used React Context and React Hooks to do state management

# Start Client
cd client && npm start

# Start Server
cd server && npm run watch

# Dev
Push subfolder to Heroku:
- git subtree push --prefix server heroku master
