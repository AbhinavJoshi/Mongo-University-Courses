# Week 4

  - Problem 1 Answer:
    - db.product.find({'brand':"GE"}).sort({price : 1})
    - db.products.find( { $and : [ { price : { $gt : 30 } }, { price : { $lt : 50 } } ] } ).sort( { brand : 1 } )
  - Problem 2 Answer: 
    - The query uses an index to determine the order in which to return result document.
    -  The query examines 251120 documents
  - Problem 3 Answer: 893jfns29f728fn29f20f2
  - Problem 4 Answer: 15820


Code is also attached for all the given set problems. 

