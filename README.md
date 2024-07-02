# Project Name

**0x04. Files manager**

This project is a summary of this back-end trimester: authentication, NodeJS, MongoDB, Redis, pagination and background processing.

The objective is to build a simple platform to upload and view files:

- User authentication via a token
- List all files
- Upload a new file
- Change permission of a file
- View a file
- Generate thumbnails for images

You will be guided step by step for building it, but you have some freedoms of implementation, split in more files etc… (`utils` folder will be your friend)

Of course, this kind of service already exists in the real life - it’s a learning purpose to assemble each piece and build a full product.

## Resources

**Read or watch**:

- [Node JS getting started](https://nodejs.org/en/learn/getting-started/introduction-to-nodejs "Node JS getting started")
- [Process API doc](https://node.readthedocs.io/en/latest/api/process/ "Process API doc")
- [Express getting started](https://expressjs.com/en/starter/installing.html "Express getting started")
- [Mocha documentation](https://mochajs.org/ "Mocha documentation")
- [Nodemon documentation](https://github.com/remy/nodemon#nodemon "Nodemon documentation")
- [MongoDB](https://github.com/mongodb/node-mongodb-native "MongoDB")
- [Bull](https://github.com/OptimalBits/bull "Bull")
- [Image thumbnail](https://www.npmjs.com/package/image-thumbnail "Image thumbnail")
- [Mime-Types](https://www.npmjs.com/package/mime-types "Mime-Types")
- [Redis](https://github.com/redis/node-redis "Redis")

## Requirements

### JavaScript Scripts

- Allowed editors: `vi`, `vim`, `emacs`, `Visual Studio Code`.
- All your files will be interpreted on Ubuntu 20.04 LTS using `node` (version 14.x).
- All your files should end with a new line.
- The `main.js` files are used to test your functions, but you don’t have to push them to your repo.
- Your code will be analyzed using the linter [ESLint](https://eslint.org/) along with specific rules that will be provided.
- When running every test with `npm run test *.test.js`, everything should pass correctly without any warning or error.
- All of your functions must be exported.

## Project Description

Learn How to create an API with Express.
how to authenticate a user.
how to store data in MongoDB.
how to store temporary data in Redis.
how to setup and use a background worker.

## More Info

### Install Node 14

```
$ curl -sL https://deb.nodesource.com/setup_14.x | sudo -E bash -
$ sudo apt-get install -y nodejs
```

### Install Jest, Babel, and ESLint

```
$ npm install --save-dev jest
$ npm install --save-dev babel-jest @babel/core @babel/preset-env
$ npm install --save-dev eslint
```

**Find the configuration files `package.json`, `babel.config.js` and `.eslintrc.js` in the project directory. Run `npm install` when you have the `package.json`**
