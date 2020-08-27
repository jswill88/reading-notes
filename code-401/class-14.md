# Access Control (ACL)

__When is Basic Authorization used vs. Bearer Authorization?__
 Basic authorization is the simplest version of authorization and the least secure. It may be used for a read only resource, and it should only be used with HTTPS because the encryption can be easily reversed. Bearer authoriztion uses a token and is more secure for an exchange between a client and a server.  
 https://dev.to/caffiendkitten/authentication-types-3984
__What does the JSON Web Token package do?__  
It defines packages for securely transmitting information as a JSON object. It is can be signed with a secret, whcih certifies that the only owner of the secret is the party the signed the JWT.  
https://jwt.io/introduction/
__What considerations should we make when creating and storing a SECRET?__  
It is best to make a secret that is random and unguessable. It should be stored in the .env file, though there may be some better options. The goal with a secret is to make sure nobody has access to it, to keep your app secure.  
https://docs.github.com/en/actions/configuring-and-managing-workflows/creating-and-storing-encrypted-secrets

|Term | Definition |  
|---|---| 
| encryption | The method by which information is converted into a secret code that protects the data from being easily understood. https://searchsecurity.techtarget.com/definition/encryption |
| token | These are strings or JWTs that let an api know that the token bearer is authorized. https://www.oclc.org/developer/develop/authentication/access-tokens.en.html |
| bearer | The bearer is the 'owner' of the token in bearer authentication. The bearer shows the token and is granted access to the resource or URL. https://blog.restcase.com/4-most-used-rest-api-authentication-methods/|
| secret | This is often sent along with a client id to a resource to obtain a token. It is only known to the OAuth Client and the authorization server. https://developers.google.com/youtube/registering_an_application|
| JSON Web Token | A method for securely transmitting JSON objects between different parties. The tokens can be transmitted as query strings, header attributes, or in the body of a POST request. JWT is popular because of teh small size. https://auth0.com/learn/token-based-authentication-made-easy/ |
