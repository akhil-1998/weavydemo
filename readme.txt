- index.html, customer.html: 
Update the script tag with id "weavy-client-script" (in both files). Make sure it points to your Weavy installation.

- assets/js/weavy.js
Update the secretString in the generateJWT function. Must be the same secret as you entered in the Weavy setting weavy.jwt-secret. 
See: https://docs.weavy.com/tutorials/single-sign-on for more information.


