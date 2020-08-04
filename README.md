# Fake API

# Use your own data

With [typicode's](https://github.com/typicode) MyJSONServer online service(https://my-json-server.typicode.com/) and a simple GitHub repo, you can have your own online fake REST server in seconds. 

https://my-json-server.typicode.com/Finoy/fake-api/users/

You can use GET, POST, PUT, PATCH and DELETE. Changes aren't persisted between calls.

## Example

Run this code in a console or from any site: 

```sh
fetch('https://my-json-server.typicode.com/Finoy/fake-api/users/1')
  .then(response => response.json())
  .then(json => console.log(json))
```

### For Random User Generator with profile image
A free, open-source API for generating random user data. Like Lorem Ipsum, but for people. 

https://randomuser.me/
