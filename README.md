tCouchbaseInput
===============

Talend component to retrieve data streams from a couchbase cluster.

Prereqs
=============

- Talend Open Studio for Data Integration (5.2.1 or above)

- tCouchbaseConnection: (https://github.com/ronniedada/tCouchbaseConnection)

    A predefined connection connects to couchbase server.

Settings
=============

- Connection: tCouchbaseConnection component which handles the connection to a couchbase cluster.

- Schema: output schema is predefined as the follows:

    **key**: the document key as stored in the couchbase cluster.
    **value**: the entire json document.

- To dump the json documents to other databases, console, etc. Please refer to tParseJson (https://github.com/ijokarumawak/tParseJSON), which takes a json document as input and produces an output according to the schema. 

