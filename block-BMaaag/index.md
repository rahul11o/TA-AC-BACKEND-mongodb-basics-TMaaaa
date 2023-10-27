writeCode

Write code to:-

- create a database named `mountains`
  // use mountains
- a collection inside that database named `himalayas`
  //db.createCollection("himalayas")
- insert 1 document into that collection `{name: 'Dhauldhar range', height: '4000 mtrs'}`
  //db.himalayas.insertOne({name:"Dauldhar range",height:"4000 mtrs"})
- insert multiple document using insertMany command
  // db.himalayas.insertMany([{ name: "Himalayan Mountains", height: "8000 mtrs" },{ name: "Rocky Mountains", height: "3500 mtrs" },{ name: "Andes Mountains", height: "6000 mtrs" },{ name: "Alps", height: "4800 mtrs" }
  ])
- find all documents from mountains
  //There is no single command in MongoDB to get all documents from all collections in a database. However, you can achieve it by itterating over each collections and then displaying all the the documents insid it. but if you meant to find all the documents from the himalayas collections , then here is the command to achieve that-
  //db.himalayas.find();

- find a single document using name
  //db.himalays.findOne({name:"Rocky Mountains"})
