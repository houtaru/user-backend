# Description

User Backend for fc5y project

# How to run

Development:

```sh
npm install
npm run dev
```

Test:

```sh
npm run test
```

# Notice

Developers can modify everything but please provide the scripts to run dev, start and test.

For example:

- Developers can change the place of test files, developers can add test config
- Developers can change the folder structure to store routes, controllers or anything else
- Developers can change the content of starting script like "ENV_ABC=xyz node abc/index.js" but please remains the script command.

# REST example

* Open your browser in `localhost:4000` and try the example REST endpoints:
	* `localhost:4000/api/users` (GET)
	* `localhost:4000/api/users/1` (GET)
	* `localhost:4000/api/users` (POST)
		* Body format: `{ username: 'john' }`
	* `localhost:4000/api/users/1` (PUT)
		* Body format: `{ username: 'john' }`
	* `localhost:4000/api/users/1` (DELETE)