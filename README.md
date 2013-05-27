nedb-to-mongodb
===============

If you've outgrown <a href="https://github.com/louischatriot/nedb" target="_blank">NeDB</a>, use this utility to transfer all your data in a nedb database in a MongoDB collection.

### Installation
```javascript
git clone git@github.com:louischatriot/nedb-to-mongodb.git
npm install
```

### Usage
Usage is pretty straightforward. All the information you need is one `./transfer.js --help` away. Here is what this command tells you:  

    Usage: ./transfer.js [options]

    Options:

    -h, --help                      output usage information
    -V, --version                   output the version number
    -h --mongodb-host [host]        Host where your MongoDB is (default: localhost)
    -p --mongodb-port [port]        Port on which your MongoDB server is running (default: 27017)
    -d --mongodb-dbname [name]      Name of the Mongo database
    -c --mongodb-collection [name]  Collection to put your data into
    -n --nedb-datafile [path]       Path to the NeDB data file
    -k --keep-ids [true/false]      Whether to keep ids used by NeDB or have MongoDB generate ObjectIds
                                    (probably a good idea to use ObjectIds from now on!)
