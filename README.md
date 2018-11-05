# Node-refresh-token
Implement Refresh Token Authentication Using Node and JWT

Clone the repository and switch to the project directory.

Install dependencies using ```npm install``` command then run the code using following command.

```node app.js```

Give following API calls to check the working.

```/login```

post data =>

```
{
	"email": "jk@codeforgeek.com",
	"name": "jjj123"
}
```

```/secure```

in headers provide,

```x-access-token=access token from the previous API```
