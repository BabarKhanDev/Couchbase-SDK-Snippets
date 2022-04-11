# couchbase-sdk-snippets README

## How to Install

Please download our extension on the visual studio code extension marketplace or download the source code and compile your own vsix file. 

## Features

This extension adds snippets that are useful when developing with supported Couchbase SDKs. These are: 
 * Java - [Link to Documentation](https://docs.couchbase.com/java-sdk/current/hello-world/overview.html), 
 * .NET - [Link to Documentation](https://docs.couchbase.com/dotnet-sdk/current/hello-world/overview.html), 
 * Node.js - [Link to Documentation](https://docs.couchbase.com/nodejs-sdk/current/hello-world/overview.html), 
 * Python - [Link to Documentation](https://docs.couchbase.com/python-sdk/current/hello-world/overview.html),
 * Go - [Link to Documentation](https://docs.couchbase.com/go-sdk/current/hello-world/overview.html).

## Snippets

| Category | Name  | Shortcut  | Description  | Java Docs  | .NET Docs  | Node Docs  | Python Docs  | Go Docs  |
| :-----: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Bootstrapping |  |  |  |  |  |  |  |  |
|  | Connect to Cluster | @cbcon | Connect to a cluster and get a refernece to it, a bucket, and a collection | [Y](https://docs.couchbase.com/java-sdk/current/hello-world/start-using-sdk.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/hello-world/start-using-sdk.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/hello-world/start-using-sdk.html) | [Y](https://docs.couchbase.com/python-sdk/current/hello-world/start-using-sdk.html) | [Y](https://docs.couchbase.com/go-sdk/current/hello-world/start-using-sdk.html) |
|  | Connect to Cluser with TLS | @cbcontls | Connect to a cluster using TLS and get a reference to it, a bucket, and a collection. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/managing-connections.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/managing-connections.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/managing-connections.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/managing-connections.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/managing-connections.html) |
|  | Connect to Cluster with DNS SRV | @cbcondns | Connect to a cluster using DNS SRV and get a reference to it, a bucket, and a collection. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/managing-connections.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/managing-connections.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/managing-connections.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/managing-connections.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/managing-connections.html) |
| Data Service |  |  |  |  |  |  |  |  |
| KV Ops | Import | @cbkvimp | Import all necessary KV namespace. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/kv-operations.html) |
|  | Example | @cbkvex | Example code that shows: inserting, upserting, getting, replacing, and removing a document. Along with all required imports. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/kv-operations.html) |
|  | Insert | @cbins | Insert a document into a collection. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/kv-operations.html) |
|  | Upsert | @cbups | Upsert a document to a collection. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/kv-operations.html) |
|  | Replace | @cbrep | Replace a document in a collection. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/kv-operations.html) |
|  | Get | @cbget | Use a key to get a document from a collection. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/kv-operations.html) |
|  | Remove | @cbrem | Use a key to remove a document from a collection. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/kv-operations.html) |
|  | Transcoder | @cbtranscoder | Example code that shows how to use a RawJSONTranscoder on an upsert operation. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/transcoders-nonjson.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/transcoders-nonjson.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/transcoders-nonjson.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/transcoders-nonjson.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/transcoders-nonjson.html) |
|  | Document Expiry | @cbsetexp | Use Document Expiration | [Y](https://docs.couchbase.com/java-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/kv-operations.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/kv-operations.html) |
| Subdocument Ops | Get Value | @cbsubget | Get or check the existence of a sub document value by providing document key and path. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/subdocument-operations.html) |
|  | Upsert Value | @cbsubups | Modify the value of an existing path or create it if it does not exist. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/subdocument-operations.html) |
|  | Insert Value | @cbsubins | Add a new value to a path that does not exist. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/subdocument-operations.html) |
|  | Remove | @cbsubrem | Remove the value of an existing path. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/subdocument-operations.html) |
|  | Array Operations | @cbsubarr | Example code showing different array operations. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/subdocument-operations.html) |
|  | Array Append | @cbsubarrapp | Append a value to an existing array in a document. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/subdocument-operations.html) |
|  | Array Prepend | @cbsubarrpre | Prepend a value to an existing array in a document. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/subdocument-operations.html) |
|  | Array Add Unique | @cbsubarradd | Treat an existing array like a unique set and add a value. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/subdocument-operations.html) |
|  | Array Insert At | @cbsubarrins | Insert a new element into an array at a specific position. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/subdocument-operations.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/subdocument-operations.html) |
| Query Service |  |  |  |  |  |  |  |  |
|  | Import | @cbqimp | Import all necessary query namespaces | [Y](https://docs.couchbase.com/java-sdk/current/howtos/n1ql-queries-with-sdk.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/n1ql-queries-with-sdk.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/n1ql-queries-with-sdk.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/n1ql-queries-with-sdk.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/n1ql-queries-with-sdk.html) |
|  | Example | @cbqex | Example code that shows connecting to a cluster and running a query on it. | [Y](https://docs.couchbase.com/java-sdk/current/hello-world/start-using-sdk.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/hello-world/start-using-sdk.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/hello-world/start-using-sdk.html) | [Y](https://docs.couchbase.com/python-sdk/current/hello-world/start-using-sdk.html) | [Y](https://docs.couchbase.com/go-sdk/current/hello-world/start-using-sdk.html) |
|  | Simple Select Query | @cbq | Use SQL++ to Query the Couchbase Cluster. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/n1ql-queries-with-sdk.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/n1ql-queries-with-sdk.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/n1ql-queries-with-sdk.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/n1ql-queries-with-sdk.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/n1ql-queries-with-sdk.html) |
|  | Parameterized Query | @cbqparam | Use parameterised SQL++ to query the Couchbase Cluster. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/n1ql-queries-with-sdk.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/n1ql-queries-with-sdk.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/n1ql-queries-with-sdk.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/n1ql-queries-with-sdk.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/n1ql-queries-with-sdk.html) |
|  | SQL++ Query With All Options | @cbqopts | Use SQL++ to Query the Couchbase Cluster, this has all options available. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/n1ql-queries-with-sdk.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/n1ql-queries-with-sdk.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/n1ql-queries-with-sdk.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/n1ql-queries-with-sdk.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/n1ql-queries-with-sdk.html) |
|  | Using FTS with Query | @cbqfts | Use SQL++ to query the Couchbase Cluster with full text search. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/n1ql-queries-with-sdk.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/n1ql-queries-with-sdk.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/n1ql-queries-with-sdk.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/n1ql-queries-with-sdk.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/n1ql-queries-with-sdk.html) |
| Analytics Service |  |  |  |  |  |  |  |  |
|  | Import | @cbanimp | Import all necessary Analytics namespaces. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/analytics-using-sdk.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/analytics-using-sdk.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/analytics-using-sdk.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/analytics-using-sdk.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/analytics-using-sdk.html) |
|  | Example | @cbanex | Example code that shows connecting to a cluster and running an analytics query on it. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/analytics-using-sdk.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/analytics-using-sdk.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/analytics-using-sdk.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/analytics-using-sdk.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/analytics-using-sdk.html) |
|  | Analytics Simple Select | @cbanq | Use SQL++ to Query the Analytics Service on the Couchbase Cluster. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/analytics-using-sdk.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/analytics-using-sdk.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/analytics-using-sdk.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/analytics-using-sdk.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/analytics-using-sdk.html) |
|  | Parameterized Query | @cbanparamq | Use SQL++ to Query the Analytics Service on the Couchbase Cluster, this uses parameters. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/analytics-using-sdk.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/analytics-using-sdk.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/analytics-using-sdk.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/analytics-using-sdk.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/analytics-using-sdk.html) |
| Search Service |  |  |  |  |  |  |  |  |
|  | Import | @cbftsimp | Import all necessary FTS namespaces | [Y](https://docs.couchbase.com/java-sdk/current/howtos/full-text-searching-with-sdk.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/full-text-searching-with-sdk.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/full-text-searching-with-sdk.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/full-text-searching-with-sdk.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/full-text-searching-with-sdk.html) |
|  | Example | @cbftsex | Example code that shows connecting to a cluster and running an FTS query on it. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/full-text-searching-with-sdk.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/full-text-searching-with-sdk.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/full-text-searching-with-sdk.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/full-text-searching-with-sdk.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/full-text-searching-with-sdk.html) |
|  | Search Query | @cbfts | Use a query string on the Full Text Search Service of your Couchbase Cluster. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/full-text-searching-with-sdk.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/full-text-searching-with-sdk.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/full-text-searching-with-sdk.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/full-text-searching-with-sdk.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/full-text-searching-with-sdk.html) |
|  | Search Query With All Options | @cbftsopts | Create a FTS query that has all options shown to you. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/full-text-searching-with-sdk.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/full-text-searching-with-sdk.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/full-text-searching-with-sdk.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/full-text-searching-with-sdk.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/full-text-searching-with-sdk.html) |
| Management API |  |  |  |  |  |  |  |  |
|  | Collection Manager | @cbcolman | Connect to a cluster, and create a collection manager. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/provisioning-cluster-resources.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/provisioning-cluster-resources.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/provisioning-cluster-resources.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/provisioning-cluster-resources.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/provisioning-cluster-resources.html) |
|  | Create a Collection | @cbcrcol | Create a new collection, this will create a new collection manager. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/provisioning-cluster-resources.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/provisioning-cluster-resources.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/provisioning-cluster-resources.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/provisioning-cluster-resources.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/provisioning-cluster-resources.html) |
|  | Create a Collection Reference | @cbcol | Create a reference to an existing collection. | [Y](https://docs.couchbase.com/java-sdk/current/hello-world/start-using-sdk.html#hello-couchbase) | [Y](https://docs.couchbase.com/dotnet-sdk/current/hello-world/start-using-sdk.html#hello-couchbase) | [Y](https://docs.couchbase.com/nodejs-sdk/current/hello-world/start-using-sdk.html#hello-couchbase) | [Y](https://docs.couchbase.com/python-sdk/current/hello-world/start-using-sdk.html#hello-couchbase) | [Y](https://docs.couchbase.com/go-sdk/current/hello-world/start-using-sdk.html#hello-couchbase) |
|  | Create a Scope | @cbcrscope | Create a new scope, this will create a new collection manager. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/provisioning-cluster-resources.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/provisioning-cluster-resources.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/provisioning-cluster-resources.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/provisioning-cluster-resources.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/provisioning-cluster-resources.html) |
|  | Create a Bucket | @cbcrbuck | Create a new bucket on an existing cluster reference. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/provisioning-cluster-resources.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/provisioning-cluster-resources.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/provisioning-cluster-resources.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/provisioning-cluster-resources.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/provisioning-cluster-resources.html) |
|  | Create a Bucket Reference | @cbbuck | Create a reference to an existing bucket. | [Y](https://docs.couchbase.com/java-sdk/current/hello-world/start-using-sdk.html#hello-couchbase) | [Y](https://docs.couchbase.com/dotnet-sdk/current/hello-world/start-using-sdk.html#hello-couchbase) | [Y](https://docs.couchbase.com/nodejs-sdk/current/hello-world/start-using-sdk.html#hello-couchbase) | [Y](https://docs.couchbase.com/python-sdk/current/hello-world/start-using-sdk.html#hello-couchbase) | [Y](https://docs.couchbase.com/go-sdk/current/hello-world/start-using-sdk.html#hello-couchbase) |
|  | Create an Index | @cbcrindex | Create a new index, this will create a new index manager. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/provisioning-cluster-resources.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/provisioning-cluster-resources.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/provisioning-cluster-resources.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/provisioning-cluster-resources.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/provisioning-cluster-resources.html) |
|  | Create a User | @cbupsuser | Add a user to your Couchbase Cluster. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/sdk-user-management-example.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/sdk-user-management-example.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/sdk-user-management-example.html) | [Y](https://docs.couchbase.com/python-sdk/current/howtos/sdk-user-management-example.html) | [Y](https://docs.couchbase.com/go-sdk/current/howtos/sdk-user-management-example.html) |
| Transactions |  |  |  |  |  |  |  |  |
|  | Example | @cbcolman | Example code that shows connecting to a cluster and running a transaction on it. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) | N | [Y](https://docs.couchbase.com/go-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) |
|  | Insert Transaction | @cbcrcol | Perform an insertion transaction | [Y](https://docs.couchbase.com/java-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) | N | [Y](https://docs.couchbase.com/go-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) |
|  | Get Transaction | @cbcol | Perform a get transaction | [Y](https://docs.couchbase.com/java-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) | N | [Y](https://docs.couchbase.com/go-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) |
|  | Replace Transaction | @cbcrscope | Perform a replace transaction | [Y](https://docs.couchbase.com/java-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) | N | [Y](https://docs.couchbase.com/go-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) |
|  | Remove Transaction | @cbcrbuck | Perform a remove transaction | [Y](https://docs.couchbase.com/java-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) | N | [Y](https://docs.couchbase.com/go-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) |
|  | Import | @cbbuck | Import all necessary transaction namespaces. | [Y](https://docs.couchbase.com/java-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) | [Y](https://docs.couchbase.com/dotnet-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) | [Y](https://docs.couchbase.com/nodejs-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) | N | [Y](https://docs.couchbase.com/go-sdk/current/howtos/distributed-acid-transactions-from-the-sdk.html) |