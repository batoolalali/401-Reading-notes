# API Server

- Express: Router Parameters
In Express parameters in routes can be read  (GET)

- run middleware on every request
Middleware that has to run on 10 out of 15 of your routes.

- Express lets you run middleware only when certain parameters are present and expected, eliminating that choice.


## Sub Documents in Mongoose
- Mongoose is a schema driven ORM, which gives us the opportunity to provide structure to our Mongo documents.

- Mongoose gives you the ability to take that a step further and use a schema to describe a deeper part of a data model. This can be useful when a document contains potentially a list of other documents. For example, an online store likely has a collection of products.

- Sharing a schema as a sub-document doesn’t bring in or connect the data, it simply uses the schema/rules. It’ll be up to you to manage the actual data.

- Sub Documents are great for supportive data such as comments on a blog post, but they’re not “populated” unless you do this manually. 


- Joining Data/Documents in Mongo
link  two collections together but noSQL Databases don’t really join, and doing so generally is considered an anti-pattern. Ensure that you’re modeling things in the most logical way for this data store.

- populate() is a method we can use in Mongoose to connect 2 collections
Method 1: physically joining using a reference to another collection
Method 2: Virtual Population


