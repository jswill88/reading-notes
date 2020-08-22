# Authentication
* Emails, usernames, and addresses can be saved as text as long as they are protected by a password or behind a firewall
* Passwords should be encrypted with a hashing algorithm before being stored
* Create a second model for a profile that can be seen by users, and protect data in a separate model
* A Cryptographic Hash Algorithm takes a piece of data and makes a hash that is difficult to reverse
* A hash password is made when a user signs up, and when they return and enter their password, the same hash algorithm is used to log them in
* A Cryptographic Cypher Algorithm takes data and a key, and produces encrypted data. The data can be deciphered when the same key is presented
* With this, a a random unique sting called a tokenSeed is associated with the user account
* With Basic Authorization the username and password are sent in the HTTP request.
* This is not a form of encryption, and HTTPS must be used to protect the user
* Credentials are joined by a colon
* In browsers use `atob` and `btoa` to convert to and from "Base64 Encoding"
* With node you can `require('base-64')` to do the same thing. (`base64.encode(string)` and `base64.decode(encoded)`)
