1. Describe a case where snapshot testing would be useful, and describe another case where it would be ineffective.
  - Snapshot testing is useful for a fully developed UI page that doesn't need to be changed any more. If you change your code, then the snapshot is null and void.
  - It is ineffective if you have to continuously update and change it.
2. What is the difference between full mount and shallow mount?
  - Full mounting allows you to render the entire component as well as any children components
  - Shallow Mounting minimize the render of any imported components
3. What does npm run build do?
  - it runs your application as "live server" to see what it will look like once you deploy it