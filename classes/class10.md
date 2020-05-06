1. Why is authentication important?
  - You need to verify that the use is authorized to access certain data
2. Why should we be careful about storing a user’s password?
  - If we store the users actual password then hackers can use it to access sensitive content within our code base... not only that but most importantly they can use it to access our clients personal information if they so feel.
3. What is the difference between hashing and encryption?
  - Encryption is for maintaining confidentiality and requires the use of a key in order to return to plaintext
  - Hashing is a process in which as the password runs through the server out sends a completely random set of characters that can not be traced back to the original password/plaintext.
4. What is the difference between encryption and encoding?
  - Encoding is for maintaining data usability and can be reversed with the same algorithm
  - Encryption is for maintaining confidentiality and requires the use of a key in order to return to plaintext.
5. What is a token used for?
  - a token serves as a reference to the original data, it cannot be used to guess those values.