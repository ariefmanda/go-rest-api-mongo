# Golang-REST-API-with-MongoDB

## You need to import following packages
* go get github.com/gin-gonic/gin
* go get gopkg.in/mgo.v2
* go get gopkg.in/mgo.v2/bson

## To run the server
* go run server.go

## Basic Routing
 Routing | HTTP | Description
 --------|------|------------
/users | GET | Get All User
/users/:id | GET | Get Single User
/users | POST | Create A User
/users/:id | PUT | Edit User
/users/:id | DELETE | Delete User