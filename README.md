# NodeServerAuthentication

This is a boilerplate code which can be used for authentication in web apps or even mobile apps.

This authentication is making use of the following libraries and is using MongoDb.

- express
- body-parse
- bcrypt
- jwt-simple
- mongoose
- morgan
- passport
- nodemon

### Getting Started

There are two ways for getting started with this repo, useing Git or downloading it

#### Familiar with Git?
To get started with this repo using Git, clone it as follows.

```
  > get clone 
  > cd xxx
  > npm install
  > npm dev
```

#### Not Familiar with Git?
If you are not familiar with Git and prefer to download the zip file, then do the following.
Click [here]() then download the .zip file

```
  > npm install
  > npm dev
```

## Get Running

**Note** Before you run the application you need two things

1. you need to add a file to the root called **config.js**  You need to just add the folowing code to the file. This was not committed as this contains your secret key and by the name it is secret, so you would also add this to your .gitignore file if using Git to stop it being copied to a remote repo. The key can be a mix of letters, numbers and special characters, make it at least 15 characters in length.

```
// Hold application secrets and config
module.exports = {
  secret: '<ADD-YOUR-KEY-HERE>'
};
```

2. You need to have MongoDB installed and Running

Thats it you're now good to go, use Postman to test. The app will run on port 3090 as in the config.

Happy coding!
