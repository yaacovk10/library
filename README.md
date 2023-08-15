 # ensure node.js is installed
https://nodejs.org/en

 # install server
npm install -g json-server

 # run server
json-server --watch db.json

 # server address
http://localhost:3000/library

 # sample data
{
  "library": [
    {
      "id": 1,
      "title": "Le Petit Prince",
      "author": "Antoine de Saint-Exupéry"
    },
    {
      "id": 1,
      "title": "le comte de monte cristo",
      "author": "Alexandre Dumas"
    }
  ]
}
