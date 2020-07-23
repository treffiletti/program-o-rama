Node/Express Samples - Modify Data
=======================================================================
npm install

Run samples - Option 1 - Using 'nodemon'
	Copy the contents of one of the 'sample*.js' files into index.js
	npm start

Run samples - Option 2 - Using 'node'
	node sample01


Samples
----------------------------------------------------------------------
sample01 - Post data
  {
    "id": 7,
    "name": "Pumpkin",
    "wholePrice": 20.99,
    "slicePrice": 5.19,
    "sliceCalories": 70,
    "imageUrl": "images/pumpkin.jpg"
  }

sample02 - Put data
  http://localhost:5000/api/1
  Put the following in the Body
  {
    "id": 1,
    "name": "Green Apple",
    "wholePrice": 19.99,
    "slicePrice": 4.99,
    "sliceCalories": 67,
    "imageUrl": "images/apple.jpg"
  }

sample03 - Delete data
  http://localhost:5000/api/7

sample04 - Patch data
  http://localhost:5000/api/1
  Put the following in the Body
  {
    "name": "Apple-Changed",
    "wholePrice": 22.22
  }
