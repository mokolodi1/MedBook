# MedBook

Parent repo for MedBook project

1. `./init.sh`
2. `./startDev.sh`

## General MedBook documentation

Meteor generates string `_ids` for documents using `Random.id`. The `_id`s that mongo generates are wrapped in a function called ObjectID. `_id`s in the MedBook database must be strings and are not to be wrapped in the ObjectID funciton to facilitate easy querying. See [this page](http://api.mongodb.org/python/current/faq.html#web-application-querying-by-objectid) for more information about ObjectID and querying mongo using ObjectIDs. 
