### Mongo DB Commands

#### To Filter for a specific parameter
`db.{table_name}.find({${parameter}: "value"})
.projection({})
.sort({_id:-1})
.limit(10)`

#### To insert a list of documents
`db.{table_name}.insert([{object1}, {object2}])
{
"_id" : "z0000",
"lastCaptured" : "2021-01-02",
"name" : "Invalid NODE ID TEST",
"type" : "Tag",
"created" : "2020-10-22T16:12Z",
"lastModified" : "2022-10-26T18:21:59.000Z",
"lastUpdated" : "2022-10-26T18:22:21.000Z",
"childIds" : [ ],
"ancestorIds" : [ "root" ],
"_class" : "com.tgt.marketing.morpheus.support.entity.AggregateTaxonomyNode"
}`

#### To delete one document
`db.getCollection(table_name).deleteOne({${parameter}: "value"})`

#### To delete more than one document
`db.getCollection(table_name).deleteMany({${parameter}: "value"})`