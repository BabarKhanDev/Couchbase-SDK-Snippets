# couchbase-sdk-snippets README

## Features

This extension adds snippets that are useful when developing with supported Couchbase SDKs. These are: Java, Go, .NET, Node.js, and Python

## Snippets


| Category | Name  | Shortcut  | Description  | Java Docs  | .NET Docs  | Node Docs  | Python Docs  | Go Docs  |
| :-----: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Bootstrapping |  |  |  |  |  |  |  |  |
|  | Connect to Cluster | @cbcon | Connect to a cluster and get a refernece to it, a bucket, and a collection |  |  |  |  |  |
|  | Connect to Cluser with TLS | @cbcontls | Connect to a cluster using TLS and get a reference to it, a bucket, and a collection. |  |  |  |  |  |
|  | Connect to Cluster with DNS SRV | @cbcondns | Connect to a cluster using DNS SRV and get a reference to it, a bucket, and a collection. |  |  |  |  |  |
| Data Service |  |  |  |  |  |  |  |  |
| KV Ops | Import | @cbkvimp | Import all necessary KV namespace. |  |  |  |  |  |
|  | Example | @cbkvex | Example code that shows: inserting, upserting, getting, replacing, and removing a document. Along with all required imports. |  |  |  |  |  |
|  | Upsert | @cbups | Upsert a document to a collection with durability options. |  |  |  |  |  |
|  | Insert | @cbins | Insert a document to a collection to a collection, this will fail if a document with the same key already exists. |  |  |  |  |  |
|  | Replace | @cbrep | Create a document object and replace a document in a collection, this will fail if no document with the specified key exists. |  |  |  |  |  |
|  | Get | @cbget | "Use a key to get a document object from a collection and assign it to a dictionary, this will fail if no document with the specified key exists. |  |  |  |  |  |
|  | Remove | @cbrem | Use a key to remove a document from a collection, this will fail if no document with the specified key exists. |  |  |  |  |  |
|  | Transcoder | @cbtranscoder | Example code that shows how to use a RawJSONTranscoder on an upsert operation. |  |  |  |  |  |
|  | Document Expiry | @cbsetexp | Use Document Expiration |  |  |  |  |  |
| Subdocument Ops | Get Value | @cbsubget | Get or check the existence of a sub document value by providing document key and path. |  |  |  |  |  |
|  | Upsert Value | @cbsubups | Modify the value of an existing path or create it if it does not exist. |  |  |  |  |  |
|  | Insert Value | @cbsubins | Add a new value to a path that does not exist. |  |  |  |  |  |
|  | Remove | @cbsubrem | Remove the value of an existing path. |  |  |  |  |  |
|  | Array Operations | @cbsubarr | Example code showing different array operations. |  |  |  |  |  |
|  | Array Append | @cbsubarrapp | Append a value to an existing array in a document. |  |  |  |  |  |
|  | Array Prepend | @cbsubarrpre | Prepend a value to an existing array in a document. |  |  |  |  |  |
|  | Array Add Unique | @cbsubarradd | Treat an existing array like a unique set and add a value. |  |  |  |  |  |
|  | Array Insert At | @cbsubarrins | Insert a new element into an array at a specific position. |  |  |  |  |  |
| Query Service |  |  |  |  |  |  |  |  |
|  | Import | @cbqimp | Import all necessary query namespaces |  |  |  |  |  |
|  | Example | @cbqex | Example code that shows connecting to a cluster and running a query on it. |  |  |  |  |  |
|  | Simple Select Query | @cbq | Use SQL++ to Query the Couchbase Cluster. |  |  |  |  |  |
|  | Parameterized Query | @cbqparam | Use parameterised SQL++ to query the Couchbase Cluster. |  |  |  |  |  |
|  | SQL++ Query With All Options | @cbqopts | Use SQL++ to Query the Couchbase Cluster, this has all options available. |  |  |  |  |  |
|  | Using FTS with Query | @cbqfts | Use SQL++ to query the Couchbase Cluster with full text search. |  |  |  |  |  |
| Analytics Service |  |  |  |  |  |  |  |  |
|  | Import | @cbanimp | Import all necessary Analytics namespaces. |  |  |  |  |  |
|  | Example | @cbanex | Example code that shows connecting to a cluster and running an analytics query on it. |  |  |  |  |  |
|  | Analytics Simple Select | @cbanq | Use SQL++ to Query the Analytics Service on the Couchbase Cluster. |  |  |  |  |  |
|  | Parameterized Query | @cbanparamq | Use SQL++ to Query the Analytics Service on the Couchbase Cluster, this uses parameters. |  |  |  |  |  |
| Search Service |  |  |  |  |  |  |  |  |
|  | Import | @cbftsimp | Import all necessary FTS namespaces |  |  |  |  |  |
|  | Example | @cbftsex | Example code that shows connecting to a cluster and running an FTS query on it. |  |  |  |  |  |
|  | Search Query | @cbfts | Use a query string on the Full Text Search Service of your Couchbase Cluster. |  |  |  |  |  |
|  | Search Query With All Options | @cbftsopts | Create a FTS query that has all options shown to you. |  |  |  |  |  |
| Management API |  |  |  |  |  |  |  |  |
|  | Collection Manager | @cbcolman | Connect to a cluster, and create a collection manager. |  |  |  |  |  |
|  | Create a Collection | @cbcrcol | Create a new collection, this will create a new collection manager. |  |  |  |  |  |
|  | Create a Collection Reference | @cbcol | Create a reference to an existing collection. |  |  |  |  |  |
|  | Create a Scope | @cbcrscope | Create a new scope, this will create a new collection manager. |  |  |  |  |  |
|  | Create a Bucket | @cbcrbuck | Create a new bucket on an existing cluster reference. |  |  |  |  |  |
|  | Create a Bucket Reference | @cbbuck | Create a reference to an existing bucket. |  |  |  |  |  |
|  | Create an Index | @cbcrindex | Create a new index, this will create a new index manager. |  |  |  |  |  |
|  | Create a User | @cbupsuser | Add a user to your Couchbase Cluster. |  |  |  |  |  |
| Transactions |  |  |  |  |  |  |  |  |
|  | Example | @cbcolman | Example code that shows connecting to a cluster and running a transaction on it. |  |  |  |  |  |
|  | Insert Transaction | @cbcrcol | Perform an insertion transaction |  |  |  |  |  |
|  | Get Transaction | @cbcol | Perform a get transaction |  |  |  |  |  |
|  | Replace Transaction | @cbcrscope | Perform a replace transaction |  |  |  |  |  |
|  | Remove Transaction | @cbcrbuck | Perform a remove transaction |  |  |  |  |  |
|  | Import | @cbbuck | Import all necessary transaction namespaces. |  |  |  |  |  |