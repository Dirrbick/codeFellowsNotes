1.  When is Basic Authorization used vs. Bearer Authorization?
  * Basic Authorization is used just to verify a user. When using a Bearer Authorization it "remembers" the users info or contains information that will let the server understand which user the client represents.
2.  What does the JSON Web Token package do?
  * It securely transits information between two systems as a JSON object. This information is digitally signed.
3.  What considerations should we make when creating and storing a SECRET?
  * One should consider putting the users sensitive data like their password into the JWT. You shouldn't put a lot of data in there because it isn't extremely secure.