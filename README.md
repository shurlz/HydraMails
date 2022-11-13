# HydraMails
documentation , resourses and bugs
#
## Getting Started <img src="https://img.icons8.com/clouds/35/null/firework.png"/> <img src="https://img.icons8.com/clouds/35/null/firework.png"/>
# 
> create an account https://www.hydramails.com/auth/sign-up/
```
  - create a new collection with API support
    - copy your API key generated upon creation
    - copy your collection name
      - These details can also be found on the credentials page
```
#
### 3 major endpoints:
```
  . get all subscribed email addresses
  . subscribe to collection
  . un-subscribe from collection
```
#
### getting all subscribers
    - GET request
```
   API endpoint : https://hydramails.com/subscribe/api/< collection name >/< api key >
   
   Extra Optional Arguments : page = all or numerical value 
   Extra Optional Arguments : order = least_recent [ default ordering is by most recent ]
   
   example - https://hydramails.com/subscribe/api/< collection name >/< api key >/?page=2&order=least_recent
```
