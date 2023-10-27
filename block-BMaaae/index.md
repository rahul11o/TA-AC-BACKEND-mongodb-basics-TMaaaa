writeCode

Write code to:-

- create a database named `sports`.
  // use sports
- list all databases present in local mongod server.
  // show dbs
- create 3 collections named `cricket`, `football`, `TT` in sports databse.
  // db.createCollection("cricket")
  // db.createCollection("football")
  // db.createCollection("TTa")
- add multiple players in those collections which should have fields like `name`, `age` and `email` and `bid_price`.
  //db.cricket.insertMany([{name:"virat", age:"32",email:"virat@gamil.com", bid_price: "17cr"},{name:"rohit", age:"32",email:"rohit@gamil.com", bid_price: "14cr"},{name:"kl", age:"31",email:"kl@gamil.com", bid_price: "17.5cr"}])
  //db.football.insertMany([{name:"messi", age:"35",email:"messi@gamil.com", bid_price: "178cr"},{name:"becham", age:"42",email:"becham@gamil.com", bid_price: "146cr"},{name:"mbape", age:"21",email:"mbape@gamil.com", bid_price: "47.5cr"}])
  // db.TT.insertMany([{name:"saanu", age:"20",email:"sanu@gamil.com", bid_price: "1"},{name:"navnit", age:"20",email:"navnit@gamil.com", bid_price: "1cr"},{name:"rahul", age:"21",email:"rahul@gamil.com", bid_price: "4cr"}])
- list all collections in sports database.
  // show collections
- rename `TT` collection to `tennis`.
  db.TT.renamecollection("tennis")
- create a capped collection called `khokho` which should have max 3 documents.
  //db.createCollection("khokho", {capped: true, size:1000000, max:3})
- Try inserting more than 3 and see what happens?
  db.khokho.insertMany([{key:"value1"},{key:"value2"},{key:"value3"},{key:"value4"}])
- check whether a collection is capped or not?
  //db.cricket.isCapped()
- drop all documents from `football` collection.
  //db.football.remove({})
- delete cricket collection completely.
  // db.cricket.drop();
- delete sports database.
  // db.dropDatabase()
- check which database you are connected to ?
  //db
- connect to test database
  // use test
