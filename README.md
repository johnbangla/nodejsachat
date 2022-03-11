
heroku login
git init
git add .
git commit -m "Chat commit first time"
git push heroku master


heroku config:set APP_NAME="Chat Application"
heroku config:set PORT=5000
heroku config:set MONGO_CONNECTION_STRING=mongodb+srv://johnbangla:johnbangla@cluster0.duyhv.mongodb.net/myFirstDatabase?retryWrites=true&w=majority
heroku config:set COOKIE_SECRET=learnwithjohnbangla
heroku config:set JWT_SECRET=testbangla
heroku config:set JWT_EXPIRY=86400000
heroku config:set COOKIE_NAME=a-simple-chat
