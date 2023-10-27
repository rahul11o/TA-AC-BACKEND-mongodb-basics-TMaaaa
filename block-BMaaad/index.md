writeCode

Write command to

- List collections from a database.
  // show collections
- create a new collection in your country database which you created recently.
  //db.createCollection("rahul")

Write code to:-

- crate a database named `weather`
  //use weather
- create a capped collection named `temperature` with maximum of 3 documents and try inserting more than 3 to see the result.
  //db.createCollection("mycappedcollection",{capped:true,size:1000000, max:3})
  //if we try to insert the fourth document, the document which were inserted at the very first get removed , and the collection always have only three documents inside it.
- create a simple collection named `humidity`
- check whether `temperature` collection is capped or not ?
  //db.getCollectionInfos()
- Delete `humidity` collection and then the entire database(weather).
  //db.humidity.drop()
  //db.dropDatabase()
