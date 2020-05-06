1. What is a benefit to using express.Router()?
  - The benefit of that is it allows you to have a "base" route set up so that if you have to make a change to everything with that base you just need to adjust one function/code block instead of changing multiples
2. When I say that top-down order matters in Express, what does that mean?
  - Express reads the code base from top to bottom. If you were to put your app middleware after your handler middleware it would read last. Essentially you can choose when your code runs using express.
3. Why do we use a model class (with create(), read(), etc.) instead of directly calling MongoDB operations (such as save(), find(), etc.) within our Express route handlers?
  - It allows us to place specific content within the methods themselves, it also allows us to call upon that middleware at any given moment. It helps modularize our file structures