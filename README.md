From https://clerk.com/blog/building-a-react-login-page-template

frontend: react
npx create-react-app frontend
npm i react-router-dom

backend: auth-server
npm i express cors bcrypt jsonwebtoken lowdb
bcrypt: for hashing and comparing passwords
jsonwebtoken: for generating and verifying JSON web tokens
lowdb: for storing user details (email and hashed password)
