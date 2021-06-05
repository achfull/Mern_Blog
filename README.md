# Blog_Mern

A MERN blog is not hosted on heroku

## Website

Not Yet

## Functionalities

- [x] Register: creating user with password encrypted with bcrypt
- [x] Login: JWT request the token with the token that is saved in local storage and redux state
- [x] Protected routes: If user is authenticated can access /login or /register
- [x] Create posts: Users loggedin can create posts
- [x] Create posts: Image upload through cloudinary
- [x] Create posts: Shows the user name of the user who created it
- [x] Posts: Users can comment posts
- [x] Error messages: When user submits recieves an alert
- [x] Comments: Comment form should only appear if loggedin
- [x] Comments: Create redux actions for this
- [x] Admin: Users / Posts / Comments + Charts + CRUD
- [ ] NavBar: Create a dropdown with user profile and logout
- [ ] Posts: Like button(A user can only like one time per post)
- [ ] Posts: Add video ...


## Before you start

Install Node_module
Change the URL of mongodb if you dont have access 💥
```.env
URL=<mongodb+srv.....>
```

### JWT authentication

- Decide a secret key that you will use to create the token to be used in JWT
- This key can be anything ex: <MY_SECRET_KEY>
- Open `.env` and insert one line, with your own info

```.env
SECRET=<MY_SECRET_KEY>
```

### Host Mongo DB

.....

### Host images

....

## How to run locally

First clone the project

```shell
git clone https://github.com/achfull/Blog_Mern.git
```

Then install the node_modules (this installs the server and the client)

```shell
npm install
```

For running frontend and backend in the same time

```shell
npm run dev
```


Now its ready to use

## How to run in production

#Not yet


## The project is ready to run  in heroku

.....

