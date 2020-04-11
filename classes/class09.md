# Reading Questions

1. Describe a use-case where param middleware would come in handy.
  * It allows us to be able to set it to run on routes instead of being defined
2. What are the two ways to add middleware in-between Mongoose and MongoDB interactions?
  * One way is to use populate()
  * Second way is using virtual joins
3. What is the difference between a join by reference and a virtual join?
  * A join by reference gives an "id" of a record to the schema you are connecting
  * Doing a virtual join allows us to give the connection a name, it is a easier way of seeing it visually
4. What do localField and foreignField mean?
  * They are connected in a sense that localField finds data that matches what is in the foreignField