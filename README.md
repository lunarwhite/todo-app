# todo-app
A todo app written in Golang, MongoDB, and React.
```
.
├── LICENSE
├── README.md
├── client
│   ├── README.md
│   ├── node_modules
│   ├── package-lock.json
│   ├── package.json
│   ├── public
│   │   ├── favicon.ico
│   │   ├── index.html
│   │   ├── logo192.png
│   │   ├── logo512.png
│   │   ├── manifest.json
│   │   └── robots.txt
│   └── src
│       ├── App.css
│       ├── App.js
│       ├── App.test.js
│       ├── To-Do-List.js
│       ├── index.css
│       ├── index.js
│       ├── logo.svg
│       ├── reportWebVitals.js
│       └── setupTests.js
├── go.mod
├── go.sum
├── server
│   ├── main.go
│   ├── middleware
│   │   └── middleware.go
│   ├── models
│   │   └── models.go
│   └── router
│       └── router.go
└── tree.txt
```

## setup envs
- golang
- golang package
  ```shell
  # MongoDB Go Driver
  go get go.mongodb.org/mongo-driver

  # mux router
  go get -u github.com/gorilla/mux
  ```
- mongodb
- node.js
  ```shell
  sudo apt-get install nodejs
  sudo apt-get install npm
  ```

## how it works
- server: Golang
- client: React, semantic-ui-react
- database: Cloud MongoDB

## deploy
- Open the terminal and start the server from the server directory.
  ```shell
  go run main.go
  ```
- Open the terminal and start the react application from the client directory.
  ```shell
  npm start
  ````
- Go to `http://localhost:3000`

## reference
- [Build a Todo App in Golang, MongoDB, and React - Shubham Chadokar](https://levelup.gitconnected.com/build-a-todo-app-in-golang-mongodb-and-react-e1357b4690a6)
