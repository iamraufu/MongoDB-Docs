| Query | Description |
| --- | --- |
| `db.collection.find()` | Retrieves documents from a collection based on specified criteria. |
| `db.collection.insertOne()` | Inserts a single document into a collection. |
| `db.collection.insertMany()` | Inserts multiple documents into a collection. |
| `db.collection.updateOne()` | Updates a single document in a collection based on specified criteria. |
| `db.collection.updateMany()` | Updates multiple documents in a collection based on specified criteria. |
| `db.collection.deleteOne()` | Deletes a single document from a collection based on specified criteria. |
| `db.collection.deleteMany()` | Deletes multiple documents from a collection based on specified criteria. |
| `db.collection.aggregate()` | Performs aggregation operations on a collection. |
| `db.collection.createIndex()` | Creates an index on a collection. |
| `db.collection.dropIndex()` | Drops an index from a collection. |
| `db.collection.distinct()` | Returns an array of distinct values for a specified field in a collection. |
| `db.collection.countDocuments()` | Returns the number of documents in a collection that match a specified query. |
| `db.collection.find().sort()` | Sorts the results of a `find` query in ascending or descending order based on one or more fields. |
| `db.collection.find().limit()` | Limits the number of results returned by a `find` query. |
| `db.collection.find().skip()` | Skips a specified number of documents in the results of a `find` query. |
| `db.collection.find().projection()` | Specifies which fields to include or exclude in the results of a `find` query. |

| Aggregation Operation | Description |
| --- | --- |
| `$project` | Reshapes the documents in a collection by specifying which fields to include or exclude, renaming fields, adding new fields, or computing expressions. |
| `$match` | Filters the documents in a collection based on specified criteria. Similar to `find` query but works within an aggregation pipeline. |
| `$group` | Groups the documents in a collection based on specified criteria and computes aggregate values for each group. |
| `$sort` | Sorts the documents in a collection based on specified criteria. |
| `$limit` | Limits the number of documents passed to the next stage in an aggregation pipeline. |
| `$skip` | Skips a specified number of documents passed to the next stage in an aggregation pipeline. |
| `$unwind` | Deconstructs an array field in a document into multiple documents, each containing a single element of the array. |
| `$lookup` | Performs a left outer join between two collections based on specified criteria. |
| `$group` | Groups the documents in a collection based on specified criteria and computes aggregate values for each group. |
| `$project` | Reshapes the documents in a collection by specifying which fields to include or exclude, renaming fields, adding new fields, or computing expressions. |
| `$match` | Filters the documents in a collection based on specified criteria. Similar to `find` query but works within an aggregation pipeline. |
| `$facet` | Enables multiple aggregation pipelines to be executed within a single aggregation stage. |
| `$out` | Writes the results of an aggregation pipeline to a specified collection. |
| `$addFields` | Adds new fields to documents in a collection based on specified criteria. |
| `$bucket` | Categorizes the documents in a collection into buckets based on specified criteria. |
| `$graphLookup` | Performs a recursive search on a collection based on specified criteria. |

| Operator | Description |
| --- | --- |
| `$eq` | Matches documents where the value of a field equals a specified value. |
| `$ne` | Matches documents where the value of a field does not equal a specified value. |
| `$gt` | Matches documents where the value of a field is greater than a specified value. |
| `$gte` | Matches documents where the value of a field is greater than or equal to a specified value. |
| `$lt` | Matches documents where the value of a field is less than a specified value. |
| `$lte` | Matches documents where the value of a field is less than or equal to a specified value. |
| `$in` | Matches documents where the value of a field equals any value in a specified array. |
| `$nin` | Matches documents where the value of a field does not equal any value in a specified array. |
| `$exists` | Matches documents where the specified field exists or does not exist. |
| `$type` | Matches documents where the specified field is of a specified BSON data type. |
| `$mod` | Matches documents where the value of a field modulo a specified divisor equals a specified remainder. |
| `$regex` | Matches documents where the value of a field matches a specified regular expression. |
| `$options` | Specifies options for a `$regex` operator. |
| `$not` | Inverts the effect of a specified operator expression. |
| `$and` | Joins query clauses with a logical AND. |
| `$or` | Joins query clauses with a logical OR. |
| `$nor` | Joins query clauses with a logical NOR. |
| `$all` | Matches documents where the value of a field contains all the specified elements in an array. |
| `$elemMatch` | Matches documents where the value of a field contains at least one element that matches all the specified criteria. |
| `$size` | Matches documents where the value of a field is an array of a specified size. |
| `$slice` | Returns a subset of an array field in a document. |
| `$elemMatch` | Matches documents where the value of a field contains at least one element that matches all the specified criteria. |
| `$text` | Performs a text search on a collection. |
| `$geoNear` | Returns documents based on proximity to a specified point. |
