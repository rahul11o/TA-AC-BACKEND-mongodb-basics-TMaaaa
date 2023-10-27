writeCode

Run these shell commands in mongo shell:

- db.version()
  // 7.0.2
- db.stats()
  // {
  db: 'test',
  collections: Long("0"),
  views: Long("0"),
  objects: Long("0"),
  avgObjSize: 0,
  dataSize: 0,
  storageSize: 0,
  indexes: Long("0"),
  indexSize: 0,
  totalSize: 0,
  scaleFactor: Long("1"),
  fsUsedSize: 0,
  fsTotalSize: 0,
  ok: 1
  }
- db.help()

Write code to

- create a database of your country name.
  // use india
- check list of databases to see newly created database.
  // In order to display the list of databases , we run command "show dbs", but the newly created database "india" wont appaer in the list ,its because show dbs command only displays those databases which has some sort of date inside them.
- check which database you are currently connected to ?
  //db
