# Invoice simulator - Server with Mongo

This application simulates a simplified portfolio of invoices and their generation of account receivables. Compliant with the legal and banking environment, as well as interfaces easy and familiar for the personnel usually found in the finance department of local companies.

It's the server split from the ctr-invoice-mean project, so can connect to other versions of Clients and support other databases.

As its origin, it can be used as a demo and template of a series of finance applications develipped for clients since 2010.
.
## Scope

The REST full server application controls:

* Login (suggesting a demo company)
* Users
* Invoices
* Config

## Stack

Backend

* Node
* Express
* Mongoose
* MongoDb

## Set up

* If Mongodb not installed, install it

* Download files to the working folder

* Install the application and run Node
```shell
$ npm install
$ node index
```

* Open browser and create default database
```shell
localhost:3000/api/install
```
This url will reset the original database at any time

* Still in the browser, run the application
```shell
localhost:3000
```

## Configuration
In the file config.json:

* serverPort, default: 3000
* mongooseConnectionString, default: 'mongodb://localhost/example'
* token, defult '123321'


## Contribution ##

* Any suggestion or info request to:
   plinio.prado@immaginare.com.br