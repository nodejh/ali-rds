
{
  id: 1,
  name: 'foo',
}

=> 
id = 1 AND name = foo




$and: {
  id: 1,
  name: 'foo',
}

=> 
id = 1 AND name = foo



$or: {
  id: 1,
  name: 'foo',
}

=>
id = 1 OR name = 'foo'


$and: {
  id: 1,
  name: { $gt  }
}



$gt  >
$lt <
$elt <=

https://docs.mongodb.com/manual/reference/operator/query/lte/