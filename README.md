# MD File Editor

Created by following https://scotch.io/tutorials/building-a-real-time-markdown-viewer

## Overview
This project contains a mini editor of markdown files. 

This editor has two panes - the left one holds the raw md text and the right one displays the md formatted version. The database used to store the state between sessions is Redis. The app enables cooperation on the same document via a web socket connection.

## How to run

Start the Redis database using the command:

```
redis-server
```

The app is then started using:

```
node index.js
```