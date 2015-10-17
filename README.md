# Voting platform

A simple voting application based on [this tutorial](http://teropa.info/blog/2015/09/10/full-stack-redux-tutorial.html).

The users can vote in a set of predefined options and the results are showed in realtime on a leaderboard.

It uses react and redux. This is the client. You need [the server](https://github.com/luisbebop/voting-server) as well.

## How to use

[The server](https://github.com/luisbebop/voting-server) needs to be running.

```
npm install
webpack-dev-server
open open http://localhost:8080
```

To check the leaderboard

```
open http://localhost:8080/#/results
```